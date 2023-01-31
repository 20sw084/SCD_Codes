#!/bin/bash
my_var=0
while [ $my_var -le 10 ]
do
echo "my_var is "$my_var
sleep 1
my_var=$(($my_var+1))
done
echo "Out of Loop now"
