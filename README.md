# knocks
## About
Knock is a lightweight communication application built with security as a core principle. It enables direct chat and file transfer through controlled connections, minimizing exposure to third-party services. By keeping the communication path simple and local.
## installation
for the installation properly, you must git clone from this repository.
```
git clone https://github.com/almuhdilkarim/knocks.git 
```
## Usage
This section explains how to use Knock for chat and file transfer. the first step is you must in knocks directory
```
cd knocks
```
### chat
for chating 
### Send Files
To send a file you must give execution permission to the file `sender ` with this command
```
chmmod +x sender 
```
for the next step, running this command for execute the script
```
./sender [file_name] [ip]
```
> change [file_name] with your file name example `test.txt`, 
> change [ip] with the ip target you want to send the files
### Receive
To Receive a file you must give execution permission to the file `receiver ` with this command
```
chmmod +x receiver
```
for the next step, running this command for execute the script
```
./receiver
```
> note the reciever must execute `receiver` file before sending the file
