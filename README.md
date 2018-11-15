## mysql-operator

mysql-operator implement by kubernetes custom resource define. it can deploy mysql cluster easyly.
you can deploy a single instance, one master mutil slave, mutil master and mutil slave mysql cluster.
if you deploy a one master mutil slave cluster. when master is down, it't will auto change one slave
to master. you can create mysql cluster data backup or cron backup. alse you can restore the cluster 
by using the backup any data.