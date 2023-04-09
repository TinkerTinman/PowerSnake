# PowerSnake


This game was originally created by Kurt Jaegers and is on his website http://www.twentysidedblog.com/a-powershell-snake-game/. 

This game additionally was Imported from my gist, forked from GitHub user dlwyatt who added modifications and improvments after original author.  Namely performace improvments, as stated:
"The reason for the performance drag were the many loops over your $tail array inside the main event loop. As the size of the tail goes up, these operations take longer and longer. I decided to fiddle with this to improve the performance; the new version can be seen at https://gist.github.com/dlwyatt/be5a20ee80880c9f597a .

In this version, the script maintains a 2-dimensional array to track which positions are walls, snake body, apple, or empty. Every one of the “check the body” loops has been replaced with a simple lookup into that matrix, which makes each time through the main event loop take pretty much constant time, regardless of the length of the snake."


This game is written entirely in PowerShell and is a take on the classic "Snake".


The Purpose of this is teaching myself PowerShell and using games as a motivation factor.
