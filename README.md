# nosleep

A group of simple scripts to prevent your windows computer from entering sleep mode.

This is *especially* useful when performing tasks in group-policy managed environments, for example if you need to leave a simulation to run but the computer will automatically log-off after some amount of time.

I have seen many ways that people have tried to do this, from installing programs to playing a YouTube video full screen. These scripts however use built-in windows functions to run (VBScript), and hence need no extra installation or persistence on the system.

##Usage

Open `no-sleep.vbs` to prevent computer sleep or inactivity logoff.

Open `stop-no-sleep.bat` to kill `no-sleep.vbs` and return the computer to a normal state.