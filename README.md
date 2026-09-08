# sshDump

this is a bash script specifically written for one reason, to dump hashes form Linux server's shadow file by only providing ssh credentials, it achieves this by downloading sshpass if not installed and giving it the corresponding arguments credentials you gave, once the connection is established and the "script" is inside it executes "cat /etc/shadow && exit" command.
