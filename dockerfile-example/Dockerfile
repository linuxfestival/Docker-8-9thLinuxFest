# Format: FROM    repository[:version]
FROM       ubuntu:latest

RUN apt-get update
RUN apt-get install gcc
COPY . .

RUN gcc main.c


ENTRYPOINT ["a.out"]
