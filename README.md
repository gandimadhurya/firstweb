# firstweb

Initial requirements:
1. python 2.7 2. postgres postgres setup steps: installation 
2.  sudo apt-get install libpq-dev python-dev
3.  sudo apt-get install postgresql postgresql-contrib
4. sudo su - postgres
            a. createdb db1
            b. createuser db1 --pwprompt
        (Please add "db1" as password)
5. sudo su postgres -c "psql db1 -c 'CREATE EXTENSION hstore;'"
