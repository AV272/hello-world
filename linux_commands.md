Basic Linux commands.

1. `ls [-l -a]` -- list of files in directory (-l -- with additional information; -a -- with hidden files).
2. `cat` -- show file content directly in terminal (-n -- fix number of lines)
3. `cd` -- goes to directory
4. `pwd` -- show catalog way
5. `mkdir [-p]` -- create new catalog (-p -- allows create few catalogs even they not exist)
6. `file 'filename'` -- show file type
7. `cp [-r] 'source' 'directory'` -- copy source to directory
8. `mv 'source' 'destination'` -- move or rename file
9. `rm [-r -d]` -- delete files or catalogs (-r --recursive; -d -- remove empty directories)
10. `ln 'target' 'link_name or directory'` -- create link (yarlyk) to target whith link_name or in dirctory
11. `chmod [-R] 'mode' 'file'` -- change access right of file to mode
12. `chown` -- change owner of file, only for sudo


13. `find` -- search files and directories in curent cataloge
14. `locate` -- search files and directory in data base, not full
15. `du [-h -s -d]` -- show size of file or cataloge (-h --simple format, -s --minimum data, -d --depth of recursion)
16. `df [-h]` -- show disk division and file systems
17. `mount/umount` -- connect/unconnect file systems, for example USB and ISO-image
18. `grep [] pattern files` -- search pattern text in files (`grep -i 'hello world' menu.h main.c`)
19. `diff` -- show differents between two files in linewise comparison


20. `kill/xkill/pkill/killall` -- end process (kill on PID, xkill --click on window, pkill - name of process)
21. `ps/pgrep -e process_name` -- show PID of process
22. `htop` -- task manager in terminal
23. `date` -- show current time
24. `time [arguments] command` -- show time of command work
25. `alias` -- create synonym of some command
26. `uname -a` -- show computer name, arhitect of processor


27. `passwd` -- change password
28. `man/whatis` -- show user manual/show which manuals has this command
29. `whereis` -- show path to file

30. `ip address` -- show network configuration
31. `ping ip_adress` -- diagnostic of network



