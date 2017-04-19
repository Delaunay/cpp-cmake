FROM ubuntu:xenial
MAINTAINER Pierre Delaunay <pierre.delaunay@hec.ca>

# deb http://apt.llvm.org/xenial/ llvm-toolchain-xenial-4.0 main
# deb-src http://apt.llvm.org/xenial/ llvm-toolchain-xenial-4.0 main

RUN wget -O - http://apt.llvm.org/llvm-snapshot.gpg.key|sudo apt-key add - \
    apt-get update && apt-get install clang-4.0


