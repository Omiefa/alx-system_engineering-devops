0x05. Processes and signals

Write a Bash script that displays its own PID.
Write a Bash script that displays a list of currently running processes. Must show all processes, for all users, including those which might not have a TTY, Display in a user-oriented format, Show process hierarchy.
Using your previous exercise command, write a Bash script that displays lines containing the bash word, thus allowing you to easily get the PID of your Bash process. You cannot use pgrep, The third line of your script must be # shellcheck disable=SC2009.
Write a Bash script that displays the PID, along with the process name, of processes whose name contain the word bash.You cannot use ps
Write a Bash script that displays To infinity and beyond indefinitely; In between each iteration of the loop, add a sleep 2
We stopped our 4-to_infinity_and_beyond process using ctrl+c in the previous task, there is actually another way to do this., Write a Bash script that stops 4-to_infinity_and_beyond process; You must use kill
Write a Bash script that stops 4-to_infinity_and_beyond process.You cannot use kill or killall
Write a Bash script that displays:To infinity and beyond indefinitely, With a sleep 2 in between each iteration, I am invincible!!! when receiving a SIGTERM signal.Make a copy of your 6-stop_me_if_you_can script, name it 67-stop_me_if_you_can, that kills the 7-highlander process instead of the 4-to_infinity_and_beyond one.
Write a Bash script that kills the process 7-highlander.
Write a Bash script that:Creates the file /var/run/myscript.pid containing its PID, Displays To infinity and beyond indefinitely, Displays I hate the kill command when receiving a SIGTERM signal, Displays Y U no love me?! when receiving a SIGINT signal, Deletes the file /var/run/myscript.pid and terminates itself when receiving a SIGQUIT or SIGTERM signal
Write a manage_my_process Bash script that:Indefinitely writes I am alive! to the file /tmp/my_process, In between every I am alive! message, the program should pause for 2 seconds. Write Bash (init) script 101-manage_my_process that manages manage_my_process. (both files need to be pushed to git)
Write a C program that creates 5 zombie processes: For every zombie process created, it displays Zombie process created, PID: ZOMBIE_PID, Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl, When your code is done creating the parent process and the zombies, use the function bellow
