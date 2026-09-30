# some-random-batch-stuff
cmd /V:ON /C "cls & set /P subnet=Enter primary IP address (e.g. 192.168.1.):  & for /L %i in (1,1,254) do @ping -n 1 -w 100 !subnet!%i >nul && echo !subnet!%i: online & pause"
