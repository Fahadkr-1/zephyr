The Zephyr Software Development Kit (SDK) contains toolchains for each of Zephyr’s supported architectures, which include a compiler, assembler, linker and other programs required to build Zephyr applications.

Steps to flow to install the SDK

$$Download the Zephyr sdk bundle

cd ~
wget https://github.com/zephyrproject-rtos/sdk-ng/releases/download/v0.16.8/zephyr-sdk-0.16.8_linux-x86_64.tar.xz
wget -O - https://github.com/zephyrproject-rtos/sdk-ng/releases/download/v0.16.8/sha256.sum | shasum --check --ignore-missing

$$Extract the Zephyr SDK bundle archive:

tar xvf zephyr-sdk-0.16.8_linux-x86_64.tar.xz
