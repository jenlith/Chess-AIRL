[The Doc - for live writing during meetings](https://docs.google.com/document/d/10uYAXTEk28SbAr04uaPNPAYEJiAXg6bZaV-KybHBkks/edit)

# Meeting 1
Feb 4, 2023

1.  What is the project?
	The project is a chess board which behaves like a chess interface
	1. Why are we doing it?
			Funsies & flex our skills
			Funsies:
		- brother is interested in chess, mr hyperfixation
		- Playing without someone else present
			Flexes:
		-   Embedded development for sensing and moving(?) pieces
		-   Hardware and firmware for sensing pieces
		-   Hardware and firmware for moving pieces
		-   Learning how hardware & software (“from scratch”) connects to each other
			-   Jen wants to learn some low-level!!
		-   Network interfacing to play using the Internet or with someone else remotely
		-   Working with/implementing a chess engine
			-   Figuring out offline chess engine (if possible/available)
		-   Potentially working with API (multiplayer/AI implementation options)
	2.  What are our specific goals?
		- Practising scalability: designing as if we were to reproduce & sell; this allows us to create multiple units and share with friends (is also best practice to be scalable)
		- Ryan: appreciation for software development
		- Networking/remote connectivity - hardware AND software
		- Jen: learning more about the various layers to developing a physical piece of tech
		- Jen: working on a project from scratch without a guideline on how a program or system should work

2.  What are expected challenges?
	- Offline chess engine/AI - more or less complex than online API?
	- Actuation[^1] messing with sensor system
	- How will the solution communicate with the Internet?
		- Is app development required/feasible?
	- Connecting between two separate boards, whether real or virtual

3.  Lay out specifications
	1. User story ([[#Appendix]] Figure 1)
	    - Users:
		    - Expert chess player
		    - Average chess player
		    - Novice chess player
		    - Bullet chess player - time constraint/requirement 
		    - Puzzle chess player 
		    - Offline player
	2. Constraints, criteria, specific and measurable, functional[^2] vs non-functional[^3]
		- Develop individually for next meeting

4.  Break the project down into its constituent elements
	- Actuation/sensing system
	- Network communications
	- Chess engine/API/how the machine will think (whether AI or vs another player)
	- AI play
		- Offline play
	- Vs play
	- Puzzle play
	- Arduino -> better microcontroller
	1. Revisit criteria, break them up into project parts we’ll do in some order
		- Next meeting

5.  Individual work before our next meeting
	1. Both Research similar projects/solutions and identify how they accomplish the constituent project elements; how is our project different? Track work; develop items for next meeting Coming up with users Coming up with specifications Which project parts would we like to prioritise, which are later developments
	2.  Ryan User stories: Expert, Bullet, Novice, Puzzle, Offline Add research links to Links doc
	3.  Jen Migrate minutes to Obsidian and GitHub Research offline chess engines Write stories for users: Average, Puzzle, Offline

6.  Next meeting (Feb 11th else Reading Week)
	1. Merge user stories
	2. Merge specifications
	3. Review notes & discuss any confusion or disagreements

[^1]: Actuation: put into mechanical motion
[^2]: Functional requirements: Expected or desired behaviour of the system (including what the system shouldn’t do)
[^3]: Non-functional requirements: Measurements of the quality/quantity of a technology’s work, but not its ability to work in the first place. (Physical properties, capacity, reliability, etc.)



# Appendix

**Figure 1:** Template for writing User Stories (which can then be used to create system specifications)

**Title:** User X.Y: Name | **Priority:** Must/Should/Could/Shouldn’t/Won’t | **Estimate:** Time to implement
-|-|-
. | **Justification:** Why it’s a certain priority level |
As a | user | ,
I want to | task | ,
So that | why is task necessary | .
. | **Acceptance Criteria**: |
Given that | conditions to be met | ,
When | action | , 
Then | what system will do | . 
