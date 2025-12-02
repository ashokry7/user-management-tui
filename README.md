## Description
The program consists of a number of scripts each has a specific job, and the main script that displays the management window and calles the appropriate script according to the user input.
We can add, remove, list, or modify users and groups. Modifications include changing user login name, password, or group membership. System and ordinary users can be separately listed 
and can also be together. When a user is created, a new password is set for him (you are prompted to enter it), you can then select either to keep this password or force the user to 
change it at the first login.

It's recommended to use the main script (`user-manager-tui`) and it will invoke other scripts based on your input and let you do more than one operation, unlike using the other 
scripts manually. Needless to say, this promgram needs root privileges to run.
