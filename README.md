#!/bin/bash
echo "Enter any number:"
read abc
for ((i=1; i<=$abc; i++))
do
        if [ $(($i %2)) -eq 0 ]
        then
                echo "$i"
        fi

done
