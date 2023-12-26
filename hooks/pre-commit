#!/bin/bash

format_regex="^[A-Z][a-zA-Z0-9_]*(\.[a-z]+)?$" #имя файла должно начинаться с большой буквы и может содержать только буквы, цифры и знак подчеркивания. 

for file in $(find . -name "*.txt"); do
    filename=$(basename "$file")
    if ! [[ $filename =~ $format_regex ]]; then
        echo "Файл $filename не соответствует заданному формату."
        exit 1
    fi
done

exit 0
