#!/bin/bash
#print hello world
echo "Hello, World"
#print confused_smiley
echo "(Ôo)'
#view passwd file
cat /etc/passwd
#view 2 files
cat /etc/passwd /etc/hosts
#view last 10 lines
tail /etc/passwd
#view first 10 lines
head /etc/passwd
#view 3rd line
head -n 3 | tail -n +3
