			FreecellTool 2.1

Contents of this file:
=======
	What's FreecellTool?
	What's new
	System requirement 
	How to install 
	Copyright / How to Register
	Get support/Contact the author 
	FAQ


What's FreecellTool?
=======
	FreecellTool is a tool to help you solve any freecell game. It automatically catches the game you are playing, solve it and show the solution. It can operate on the freecell program automatically.


What's new
=======
			FreecellTool 2.1
	There are some game numbers seem very hard to solve in prevoius version (about 70 in first 1,000,000). In v2.1, solve algorithm has been improved to handle these games. If a puzzle ID seems hard, set "max search states" to 500,000 and set "search mode" to "random" in option dialog, then it will be solved in no more than 5 times normally.

			FreecellTool 2.01
	Improve the possibility to solve a game in "random mode".

			FreecellTool 2.0
	Enhanced solve algorithm more than 3 times faster than old version. It will not become slower while lots of states has been searched. If you set "max search states number" in option to a large number, the tool can handle any puzzle ID. For example, It proves that "puzzle No.-2" has no answer in 5 minutes on my P4 CPU.
	Now the tool can generate puzzle directly. The first 1,000,000 is the same as Microsoft's game. This can save a lot of time while doing batch solve. You can see what the puzzle looks like if its ID is out of Microsoft's game ID range.
	Now support "retry" in batch solve. This will help if you want to go through a large range of game ID.

			FreecellTool 1.21
	Now you can specify puzzle ID 1-1000000 in the "Batch solve" mode. (WindowsXP has extend the maximum puzzle ID from 32000 to 1000000.)
	Now you can read puzzle from text file and solve it. See example.txt for how to edit custom puzzle.

			FreecellTool 1.2
	Now FreecellTool supports win2000.
	Fix a bug about working under true color mode.

			FreecellTool 1.1
	Search method improved, the speed is 5 times of FreecellTool 1.0!
	Some bugs fixed. In my test it automatically solved thousands of Freecell problems in a night.


System requirement:
=======
	A PC running ENGLISH win95/98/Me/2000, and with freecell.exe installed.
	Notice: ONLY freecell game on ENGLISH version Windows is supported. If you only want to solve specified game ID (you do not want to catch current freecell game), then this limitation doesn't matter.
	The tool does not work under 16-color display mode.


How to install:
=======
	Unzip the zip file and run "FreecellTool.exe".


Copyright / How to register: 
=======
	FreecellTool is shareware. If you like it, please register. For detail information, please see file "register.txt".


Get support/Contact the author:
=======
	Author: GeYong
	Email: sweeper@ynmail.com or notabdc@hotmail.com
	Homepage: notabdc.vip.sina.com


FAQ
=======
	Q: Does FreecellTool support WindowsXP ?
	A: I developed this tool under windows95, then find it works well under win98 and win2000. It seems that Microsoft does not want to change the game. I believe (but not sure) it will work under WindowsXP. Anyway, if you find the tool does not work well under WindowsXP (or other windows version), please tell me the problem and email me the file "Freecell.exe". I promise to give free register code to the first people give me bug report.
	
	Q: Why does the tool not work at all ?
	A: The tool reads game information from the window of freecell game, so you should let the window "readable". Please read the error message carefully, then following the hints. following are some suggestion:
	Do not click any card.
	Do not move the window of freecell game outside of screen.
	Do not resize the window of freecell game.
	Do not use software that has a window "always on top".
	Be sure you are not in 16-color mode.
	FreecellTool doesn't support freecell game from windows3.x, windowsNT3.x, and windowsNT4.x. 
