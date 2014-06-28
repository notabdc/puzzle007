			FreecellTool 2.3

Contents of this file:
=======
	What's FreecellTool?
	What's new
	System requirement 
	How to install 
	How to Register
	Get support/Contact the author 
	FAQ


What's FreecellTool?
=======
	FreecellTool is a tool to help you solve any freecell game. It automatically catches the game you are playing, solve it and show the solution. It can operate on the freecell program automatically.


What's new
=======
			FreecellTool 2.3 (2013.10)
	Now work correctly on win7. No longer support new freecell game come with Win7 &later, use attached freecell game from WinXP instead(Press F3).

			FreecellTool 2.2 (2008.4)
	Support export game solution to text file.

			FreecellTool 2.1 (2003.2)
	There are some game numbers seem very hard to solve in prevoius version (about 70 in first 1,000,000). In v2.1, solve algorithm has been improved to handle these games. If a puzzle ID seems hard, set "max search states" to 500,000 and set "search mode" to "random" in option dialog, then it will be solved in no more than 5 times normally.

			FreecellTool 2.01
	Improve the possibility to solve a game in "random mode".

			FreecellTool 2.0
	Enhanced solve algorithm more than 3 times faster than old version. It will not become slower while lots of states has been searched. If you set "max search states number" in option to a large number, the tool can handle any puzzle ID. For example, It proves that "puzzle No.-2" has no answer in 5 minutes on my P4 CPU.
	Now the tool can generate puzzle directly. The first 1,000,000 is the same as Microsoft's game. This can save a lot of time while doing batch solve. You can see what the puzzle looks like if its ID is out of Microsoft's game ID range.
	Now support "retry" in batch solve. This will help if you want to go through a large range of game ID.

			FreecellTool 1.21 (2001.8)
	Now you can specify puzzle ID 1-1000000 in the "Batch solve" mode. (WindowsXP has extend the maximum puzzle ID from 32000 to 1000000.)
	Now you can read puzzle from text file and solve it. See example.txt for how to edit custom puzzle.

			FreecellTool 1.2
	Now FreecellTool supports win2000.
	Fix a bug about working under true color mode.

			FreecellTool 1.1 (2000.2)
	Search method improved, the speed is 5 times of FreecellTool 1.0!
	Some bugs fixed. In my test it automatically solved thousands of Freecell problems in a night.


System requirement:
=======
	A PC running ENGLISH win95/98/Me/2000, and with freecell installed. On win7 & later, use attached freecell.exe(from WinXP) instead.
	Notice: ONLY freecell game on ENGLISH version Windows is supported. If you only want to solve specified game ID (you do not want to catch current freecell game), then this limitation doesn't matter.
	The tool does not work under 16-color display mode.


How to install:
=======
	Unzip the zip file and run "FreecellTool.exe".


How to register: 
=======
	Write a Email to the author (see next section for email address), with your register name. Then you will get register code.


Get support/Contact the author:
=======
	Author: Ge yong
	Email: notabdc@gmail.com or notabdc@hotmail.com
	Homepage: notabdc.vip.sina.com


FAQ
=======
	Q: Why does the tool not work at all ?
	A: The tool reads game information from the window of freecell game, so you should let the window "readable". Please read the error message carefully, then following the hints. following are some suggestion:
	Do not click any card.
	Do not move the window of freecell game outside of screen.
	Do not resize the window of freecell game.
	Do not use software that has a window "always on top".
	Be sure you are not in 16-color mode.
	FreecellTool doesn't support freecell game from windows3.x, windowsNT3.x, windowsNT4.x. On win7 & later, use attached freecell.exe(from WinXP) instead.
