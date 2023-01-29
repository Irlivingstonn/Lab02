## Lab 02

- Name: Isabella Livingston
- Email: livingston.70@wright.edu

## Part 1 Answers

The answers for this section are to help you record what steps  
are needed to create a file locally (in your cloned repo)  
and push them (sync) with GitHub

1. Add a file for tracking:
2. Commit changes:
3. Sync local commits with GitHub:
4. Sync commits on GitHub to `clone`d repository:

## Part 2 Answers

For each, write the command used or answer the question posed.

1. sudo adduser bob
2. bob@ip-10-0-0-25:/home/ubuntu
3. I can't add files on this user because the user does not have permissions to add files
4. sudo su bob
5. bob@ip-10-0-0-25:~
6. Bob can add fiels to bob's home directory because bob has permission to add files
7. exit
8. cd ~

## Part 3 Answers

For each, write the command used or answer the question posed.

1. sudo addgroup crew
2. sudo usermod -a -G crew bob
3. sudo chown :crew DirA
4. su bob
5. touch file.txt
6. This is successful since bob is apart of the crew group that has permission over the DirA directo>

## Part 4 Answers

For each, write the command used or answer the question posed.

1. sudo touch sudowho.txt
2. -rw-r--r--
3. I used the command "nano sudowho.txt" and typed in "adding some text". A message popped up that r>

## Part 5 Answers

1. `ssh` command before configuring `config` file: sudo ssh -i labsuser.pem ubuntu@34.228.33.69
2. HostName: 34.228.33.69
3. User: ubuntu
4. IdentityFile: /home/amnesia/Downloads/labsuser.pem
5. `~/.ssh/config` contents: ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQDEeNK1T1U8y7t5ajNMGK38fFFiN6hIjYr>

```
Paste your config file entry here
```

6. `ssh` command after configuring `config` file: sudo ssh -i labsuser.pem ubuntu@34.228.33.69
