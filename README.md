************************************************************How to install zephyr SDK and build project ************************************************************

Steps to flow to install the SDK

$$Download the Zephyr sdk bundle

cd ~
wget https://github.com/zephyrproject-rtos/sdk-ng/releases/download/v0.16.8/zephyr-sdk-0.16.8_linux-x86_64.tar.xz
wget -O - https://github.com/zephyrproject-rtos/sdk-ng/releases/download/v0.16.8/sha256.sum | shasum --check --ignore-missing

$$Extract the Zephyr SDK bundle archive:

tar xvf zephyr-sdk-0.16.8_linux-x86_64.tar.xz

********************************************************* Build process **************************************************************************
Open your terminal and navigate to the blinky sample application directory: zephyr/samples/basic/blinky

Use the west tool to build the application for the kore_microvisor board: west build -b kore_microvisor



