#!/bin/bash

for file in *.txt; do
	if grep "123" $file; then
		echo "$file имеет правильный формат"
	else
		echo "$file имеет неправильный формат"
		exit 1
	fi
done
