Run project with:

cd ~/Documents/Code/super-tic-tac-toe/super-tic-tac-toe/
DEBUG=myapp:* npm start

Features to be worked on:
Setup Server
Undo
Artificial Intelligence - lvl1 (random)



Model:
- Child Grid
-- private isValidMove( x, y)
-- play(x,y): error enum
-- private isWon
-- private winner enum
-- getWinner(): enum open, x, o
- Parent Grid
-- play ( parentX, parentY, childX, childY)
-- ChildGrid[3][3]
- Game Board
-- 
- Visualization tiles

Functions:
- isValidMove

Control Flow:
- setBoard
> loop
- getMove
- attemptPlay
-- if valid
--- update board with move & possible next moves
--- check game end
-- if not valid, update with error & tip
> end loop

Notes for server access:
Getting access: ssh root@107.170.66.217 // skills

MEAN is a boilerplate that provides a nice starting point for MongoDB, Node.js, Express, and AngularJS based applications.
It is designed to give you quick and organized way to start developing of MEAN based web apps with useful modules like
mongoose and passport pre-bundled and configured. We mainly try to take care of the connection points between existing
popular frameworks and solve common integration problems.

You can find your mean application in /opt/mean and can run it by typing "grunt" from /opt/mean.
You can then view the sample app at http://107.170.66.217:3000

You can read more about MEAN at http://meanjs.org/
You can read more about Node.js at https://www.digitalocean.com/community/community_tags/node-js

