# PrusaSlicer Arbitrary Code Execution 
Simple .3mf file to execute commands as current user.

#Linux 
1.Download the files.
2.Make sure to have exploit.sh on /tmp directory.
3.Execute the following command > ./slicer -s evil.3mf 
4.Exploit.sh will execute as current user (run the command as sudo to get root shell)
