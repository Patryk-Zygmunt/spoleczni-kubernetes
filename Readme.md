helm install postgres   --set postgresqlPassword=secretpassword,postgresqlDatabase=multimedia-db   stable/postgresql