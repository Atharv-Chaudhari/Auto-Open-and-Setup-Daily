# Auto Open Daily Required Applications with Windows Task Scheduler and Set Up them

This Repo have Simulation of chrome we can do the same process for other applications also...

### Instead of Task Scheduler we can Alsouse a bat file to make job done but it makes we have run bat file to run all tasks...!!

```bat
"DRIVE NAME HERE IF YOU HAVE SCRIPT IN DIFFERENT FOLDER FOR EXAMPLE :- 'G:'"
chcp 65001>nul
cd "PATH_TO_SCRIPT_FOLDER"
@echo off
py -u "start.py"
timeout /t 10 >nul
```
