#!/bin/bash
echo "Checking the users home directories in the server"
cat /etc/passwd | awk {'print $1'}
