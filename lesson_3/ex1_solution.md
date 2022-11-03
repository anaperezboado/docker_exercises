
Image Size:377MB

Container Name:custom-postgres

Container ID:d620d1c0c40e

Exposed port:map[5432/tcp:{}]

Postgres version:"PG_VERSION=15.0-1.pgdg110+1"

Data Volume (aka PGDATA):/var/lib/postgresql/data

default entrypoint: [docker-entrypoint.sh]

default command: "Cmd": [
                "-e",
                "POSTGRES_PASSWORD=mysecretpassword",
                "-d",
                "postgres"
            ]
baseline consumption : CPU ___% MEM ___MB
root@IMATIA22016:/home/anaperez# docker stats --no-stream custom-postgres
CONTAINER ID   NAME              CPU %     MEM USAGE / LIMIT   MEM %     NET I/O   BLOCK I/O   PIDS
d620d1c0c40e   custom-postgres   0.00%     0B / 0B             0.00%     0B / 0B   0B / 0B     0

OS: Distro Version Codename (Ubuntu 22.04 jammy)
