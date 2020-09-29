createdb redash
./bin/run python manage.py database create_tables

Create an admin user
./bin/run python manage.py users create --admin --password admin "Admin" "admin"
