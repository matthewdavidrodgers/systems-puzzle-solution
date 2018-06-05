# My Solution for the Insight DevOps Engineering Systems Puzzle

Please see https://github.com/InsightDataScience/systems-puzzle for more details

# Installing and Running

While the original system requires you to run these installation commands:

    docker-compose up -d db
    docker-compose run --rm flaskapp /bin/bash -c "cd /opt/services/flaskapp/src && python -c  'import database; database.init_db()'"

before starting the system with

    docker-compose up -d

My solution does not require the installation commands. After cloning the repo, the only command needed is

    docker-compose up -d