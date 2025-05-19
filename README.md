# IF YOU NOT ACCESS TO TASK MANAGER IN WINDOWS YOU MAY "TASK SLEEP FOREVER" ANY PROCESS

REM BATCH FILE

FOR EXAMPLE:

> @echo off
> 
> chcp 65001
> color B
> 
> :loop
> ECHO ИМЯ ПРОЦЕССА
> set /p ffindpath=
> 
> taskkill /IM "%ddisk%%ffindpath%" /F
> 
> pause
> 
> goto loop

COMBINATION ON KEYBOARD, FOR EXIT THIS SCRIPT: 
CTRL + C OR CTRL + Z OR CLOSE WINDOW 
                      * + === AND


