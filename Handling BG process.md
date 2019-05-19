##  run a node server in background 

node /srv/www/MyUserAccount/server/server.js > stdout.txt 2> stderr.txt &

Note: Specifying comsole output and log/error file is important. If you skip this, the background process will still fail if it tries to print an error or message on the console.

##  Seeing all running background processes
ps -ef|grep

## Seeing all running background node processes.
ps -ef|grep node


## Killing a process
pkill <PID>
or kill PID
