This is an example docker compose approach that automatically creates database, schema, and insert data into mysql container 

that will be utilized by php and phpmyadmin services, respectively.

Create a directory with the following structure:
├── docker-compose.yml
├── Dockerfile
├── dump
│   └── 1_create_db.sql
│   └── 2_create_schema.sql
│   └── 3_insert_data.sql
└── src
    └── index.php
└── log
