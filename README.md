# LINUX-and-OS-Programming

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/7a73feada6e2427d8ce278d4645c0eb9)](https://app.codacy.com/manual/99002581/LINUX-and-OS-Programming?utm_source=github.com&utm_medium=referral&utm_content=99002581/LINUX-and-OS-Programming&utm_campaign=Badge_Grade_Settings)
![cppcheck-action](https://github.com/99002581/LINUX-and-OS-Programming/workflows/cppcheck-action/badge.svg?branch=master)
![C/C++ CI](https://github.com/99002581/LINUX-and-OS-Programming/workflows/C/C++%20CI/badge.svg?branch=master)


## Mini-Project
Shopkeeper and Customer

## Problem Statement
The problem describes two processes, the Shopkeeper and the customer, has a fixed-size buffer used as a queue. The Shopkeeper's job is to generate data, put it into the buffer, and start again. At the same time, the customer is consuming the data (i.e., removing it from the buffer), one piece at a time. It will also make sure that the Shopkeeper won't try to add data into the buffer if it's full and that the customer won't try to remove data from an empty buffer.

## To compile the program
Compile pract1.c using the following command on Ubuntu 18.04 or later version:

-gcc pract1.c -pthread

## To run the program
./a.out


