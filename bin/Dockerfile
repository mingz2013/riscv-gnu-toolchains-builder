# tool-chains
# FROM alpine
FROM centos:7
RUN yum install libmpc-devel -y

COPY ./riscv /riscv
# RUN mkdir /lib64 && ln -s /lib/libc.musl-x86_64.so.1 /lib64/ld-linux-x86-64.so.2

# RUN echo 'export PATH=$PATH:/riscv/bin' > /root/.bashrc
