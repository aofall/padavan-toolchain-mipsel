# Padavan toolchain for mipsel

This repository already build from the source code

The firmware with the kernel 3.4.x

## Build

You can build it from the source code by yourself:

Install all the required packages first

    sudo apt-get install autoconf automake bison build-essential flex gawk gettext gperf libtool pkg-config zlib1g-dev libgmp3-dev libmpc-dev libmpfr-dev texinfo python-docutils mc

Starting bulid

    git clone clone https://bitbucket.org/padavan/rt-n56u.git

    cd ./rt-n56u/toolchain-mipsel

    sudo ./clean_sources

If you plan to build the firmware with the kernel 3.4.x

    sudo ./build_toolchain

If you plan to build the firmware with the kernel 3.0

    sudo ./build_toolchain_3.0.x
