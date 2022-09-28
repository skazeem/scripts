#!/bin/bash
#Read in two numbers from the keyboard and print their sum
clear
echo -e "Enter First Number : \c"
read first
echo -e "Enter Second Number : \c"
read second
expr $first + $second
read sum
echo $sum
