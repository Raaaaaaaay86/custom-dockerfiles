FROM ubuntu:20.04

RUN apt -y update
RUN apt -y upgrade
RUN apt -y install netcat-traditional
RUN apt -y install wget
RUN apt -y install mysql-server-8.0
RUN wget https://downloads.percona.com/downloads/Percona-XtraBackup-LATEST/Percona-XtraBackup-8.0.26-18/binary/debian/focal/x86_64/percona-xtrabackup-80_8.0.26-18-1.focal_amd64.deb
RUN dpkg -i  ./percona-xtrabackup-80_8.0.26-18-1.focal_amd64.deb || apt -f -y install || dpkg -i  ./percona-xtrabackup-80_8.0.26-18-1.focal_amd64.deb