##  run a node server in background 

node /srv/www/MyUserAccount/server/server.js > stdout.txt 2> stderr.txt &


##  Seeing all running background processes
ps -ef|grep

## Seeing all running background node processes.
ps -ef|grep node


## Killing a process
pkill <PID>
or kill PID
