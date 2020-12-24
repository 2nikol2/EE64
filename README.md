# G21

G21 is a regular stand alone Windows application. 

G21 simulates(full animation) Match of the Century - the World Chess Championship( 1972 ).

Bobby Fischer, USA ( 12½ ) vs Boris Spassky, USSR ( 8½ ). 

Fischer's win ended Soviet domination of the World Championship.

G21 was designed with the goal to entertain you.
G21 wants to show you beautiful game, played by masters.
G21 is one of the best-looking chess simulators.
The design and graphic is very expressive, elegant and powerful.
It's just like favorite movie... you want to play it again and again...
Ok... Now... 
Sit back... Relax... and Enjoy...

G21 has many interesting features to play.

1 - Start game and play the whole match in full animation mode.
   - Enter - go to game...
   - Enter - start it...

2 - Choose specific game to play. 
   - Page Up, Down - pick game...
   - Enter - commit...
   - Esc - disregard...

3 - Go to game end or beginning.
   - End...
   - Home...   

4 - Start - Stop game. 
   - Enter...
   - Enter...

Next features require game be in STOP mode ( see #4 ).

5 - Play one-move animation. 
   - Arrow Up... 
  
6 - Jump to random move in game.
   - Arrow Left, Right - to open pick screen...
   - Arrow Left, Right - pick move...
   - Enter - commit...
   - Esc - disregard...

You still in STOP mode.
Can utilize #5, #6 in loop. 
To go back to START( full animation ) mode - push Enter( see #4 ). 
                 
Keyboard interface summary.

Enter - start game
        - ( already in game ) - switch mode ( STOP - START )   
        - ( at welcome screen ) - go first game
        - ( at FIN or G2 screen ) - go next game
        - commit any changes ( see... #2, #6 )
 
Esc - Quit app
      - disregard any changes ( see... #2, #6 )

Home ( End ) - see... #3  
Page Up ( Down ) -  see... #2
Arrow Left ( Right )  -  see... #6
Arrow Up    -  see... #5

P.S. - About implementation of G21.

G21 developed in C++ with supreme algorithm design, very professional choice of all data structures and API... etc.
All logic and moves are in single executable. 
Despite being very functional, G21 is probably the smallest chess emulator you can find on market(size G21.exe just ~ 66KB).
As the bottom line - it consumes very little computer's resource(CPU ~ 1% & RAM ~ 9MB).

# EE64(SCR)

EE64 is a regular Windows Screen Saver.  
It's simulates, animates moves of all 21th games of World Chess Championship 1972 between Fischer-Spassky, Match of the Century.

Microsoft Windows supports special applications called screensaver - a computer program that start automatically when the mouse and keyboard have been idle
for a specified period of time.  
When compiling the list of available screen savers, Windows searches the Startup directory for files with the "SCR" extension, usually C:\Windows\system32 
or C:\Windows\SysWOW64.  
Consult Windows doc how to Install New Screen Saver and activate it in Screen Saver Settings window on your computer.

User instruction

EE64 can be run in two modes.

1 - Manually - double clicking on it, screen savers are standard Windows executable.   Pay attention - because it's screensaver, it will be terminated at         once on first mouse's movement or use of keyboard.

2 - Auto mode - as regular classic screensaver on Windows.   Consult Windows doc how to Install New Screen Saver and activate it in Screen Saver Settings         window on your computer.  
      
Showtime.

Before each game begins there are the count start from 5 to 0.   After each game ends there are freeze of screen for about 10 sec, to show ending position and then next game starts.   Game 2: Fischer forfeits.

P.S.

On top all reasons to use screen savers, it can help to conceal sensitive information left( accidentally ) on the screen.
