# Format: FROM    repository[:version]
FROM       ubuntu:latest

RUN apt-get update
RUN apt-get install -y gcc
COPY . .

RUN gcc main.c


CMD ["./a.out"]
