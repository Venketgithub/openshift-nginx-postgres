Sequence for Openshift:
create PVC
create secret
create deployment
create service

postgres-service.team1-tenant1.svc.cluster.local

 kubectl exec -it postgres-84f959b445-mlm9g -- psql -h localhost -U postgres --password -p 5432 postgres

 curl postgres-service.team1-tenant1.svc.cluster.local:5432
 