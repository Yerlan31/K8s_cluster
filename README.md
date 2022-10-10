# K8s_cluster
Learning kubernetes and applying some practiceis

Steps of creating db:
 - creating sc, pv, pvc, they should be empty fot psql from folders <b>storage and storage-replica</b>
 - creating configmaps from folder <b>db</b>
 - creating master psql pod (psql-master.yaml)
 - creating temp-psql.yaml, for configuring backup of master
 - creating psql-slave.yaml, for slave psql pod
