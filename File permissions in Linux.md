# File permissions in Linux

## Project description

This project aim to showcase the ability of managing file permissions in Linux.

## Check file and directory details

First `ls -la` is used to list all directories (including hidden ones) and their permissions status.

## Describe the permissions string

The output would show permissions strings of each file inside the directories. Stating whether user, group or others can or can not read, write and execute the file.

## Change file permissions

In order to change file permissions, chmod is used. For example, to stop everyone from reading test.txt, following command is needed. `chmod ugo-r test.txt`

## Change file permissions on a hidden file

In order to change permissions on hidden file, `.` should be added in front of the file name. For example `.chmod ugo-r test.txt`

## Change directory permissions

To change directory permissions, it is same with doing on files. Just to changes the name of files into directory. For example, to remove everyone permission on reading directory “test”, the following command can help. `chmod ugo-r test` 

## Summary

Managing permission is important on maintaining cybersecurity, Using Linux to manage permission is the basic of that.  
