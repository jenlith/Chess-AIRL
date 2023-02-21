**Title:** Expert | **Priority:** Could | **Estimate:** IDK
(Priority "could" because we are not expecting an expert to use this, but they are nice features for everyone. Can update this at a later date for a new project iteration)

As an expert chess player,
I want to play chess against other players of my level
So that I may play games which are not one-sided

**Acceptance Criteria:**
Given that someone has a chess rating
When they start a game
Then the matchmaker will sufficiently provide them with a suitable opponent

___

**Title:** Bullet | **Priority:** Shouldn't | **Estimate:** IDK
(Priority "shouldn't" because this technology is intended for regular games and Bullet chess invites a host of new problems associated with the real-time component. It could be an interesting dive into RTOS programming with similarly real-time constrained physical components as a later phase of this project, but it will be inherently unbalanced between those playing on digital boards and those playing on physical ones)

As a bullet chess player,
I want to have no delay between when I make a move and when it is recognised
So that my limited time available over the course of a single game is not wasted

**Acceptance Criteria:**
Given that a bullet game has been started
When a move is played by either physical or digital players
Then the system will near-instantly send/receive the move and perform appropriate actions

___

**Title:** Novice | **Priority:** Should | **Estimate:** IDK
(Priority "should" because we expect novice players to engage with the chess board, but this is not exactly the intended audience)

As a novice chess player,
I want to have a learning mode/game analysis where moves are suggested during the game after a move is made and I would like to be able to take back my moves. I also want the bot to provide encouragement
So that learning from a robot is engaging
Note: the interviewee novice player does not imagine herself engaging with PvP until she is confident
Note: the interviewee novice player likes the idea of picking up a piece and being shown where it may go
I want to have puzzles designed to help learn certain concepts
So that I can understand the core tactics and strategies and feel more at ease in the otherwise beginner-unfriendly space that chess occupies

**Acceptance Criteria:**
Given that the player is playing against a bot
When they make a move
Then they will be able to receive direct and immediate feedback to help improve their game knowledge
Given that the player wants to learn
When they opt to learn specific concepts
Then they will be able to be told tactics, strategies, and more and have the ability to practice these same items.

___

**Title:** Puzzle | **Priority:** Could | **Estimate:** IDK
(Priority "should" because it is unnecessary but a cool feature for solo play, and the need that this project addresses is both remote play and solo play)

As a puzzle chess player,
I want to play puzzles intended for a variety of skill levels
So that I may improve my skill by practising play from specific setups

**Acceptance Criteria:**
Given that the player chooses to play puzzles
When they choose the difficulty
Then appropriate puzzles will be available, the device will set them up quickly, will highlight incorrect moves, and maybe even show why moves are incorrect

___

**Title:** Offline | **Priority:** Must | **Estimate:** IDK
(Priority "must" because bot play is the express purpose of the project)

As an offline chess player,
I want to pick between bots of different ratings and preferred strategies
So that I may learn strategies by repetition or face appropriately difficult bots, and so that there is long-term variety

**Acceptance Criteria:**
Given that the player is choosing to play an offline game
When they choose to play a bot
Then a variety of bots will be available for such an endeavour