Run backup:

docker exec -it borgmatic /usr/local/bin/borgmatic prune create -v 1 --stats 2>&1 --monitoring-verbosity 1 --syslog-verbosity 1
