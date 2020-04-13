##### PostgreSQL role ####

1. Complete variables in default directory
2. Run role using command: sudo ansible-playbook --connection=local postgres-playbook.yml
3. Try to log in into your database using your created user
psql -d "DATABASE_NAME" -U USER_NAME -W -h 127.0.0.1
