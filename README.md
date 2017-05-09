# executeEBatonce
---
This script lets you run a command on all instances in a beanstalk environment.


Dependencies: awscli, awsebcli

Prerequisites: You should initialize a folder for the eb environment first and run this script from within that folder.

How to use: cd into the folder where you have initialized your elastic beanstalk environment, copy this script there and run

`$ ./executeEBatonce <yourcommand>`


Example: 
`$ ./executeEBatonce whoami`

