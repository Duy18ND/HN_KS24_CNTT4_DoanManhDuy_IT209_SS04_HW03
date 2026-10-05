Microsoft Windows [Version 10.0.26200.9278]
(c) Microsoft Corporation. All rights reserved.

D:\BAITAP\IT209_DEVOPS\SESSION04\SESSION04_03>ssh-keygen -t ed25519 -C "duy18namdinh@gmail.com"
Generating public/private ed25519 key pair.
Enter file in which to save the key (C:\Users\duy18/.ssh/id_ed25519):
C:\Users\duy18/.ssh/id_ed25519 already exists.
Overwrite (y/n)?

D:\BAITAP\IT209_DEVOPS\SESSION04\SESSION04_03>ssh-keygen -t ed25519 -C "duy18namdinh@gmail.com"
Generating public/private ed25519 key pair.
Enter file in which to save the key (C:\Users\duy18/.ssh/id_ed25519):
C:\Users\duy18/.ssh/id_ed25519 already exists.
Overwrite (y/n)? y
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in C:\Users\duy18/.ssh/id_ed25519
Your public key has been saved in C:\Users\duy18/.ssh/id_ed25519.pub
The key fingerprint is:
SHA256:lsQvgIGtoW+nPwavwW4izJlKveY3uWiAWOv/5cAwI2M duy18namdinh@gmail.com
The key's randomart image is:
+--[ED25519 256]--+
|   o.            |
|  o .o .         |
| . o. . o        |
|. o    o o       |
|ooE.+   S .      |
|o+*o.= . .       |
|o+**  + .        |
|+*++*+ +         |
|+o*O+++ .        |
+----[SHA256]-----+

D:\BAITAP\IT209_DEVOPS\SESSION04\SESSION04_03>type %userprofile%\.ssh\id_ed25519.pub
ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAILDYyFIL0da38yHjwM9T2S/OIIlU8xRh9T6K9+HAXYL5 duy18namdinh@gmail.com

D:\BAITAP\IT209_DEVOPS\SESSION04\SESSION04_03>ssh -T duy18namdinh@gmail.com

D:\BAITAP\IT209_DEVOPS\SESSION04\SESSION04_03>
D:\BAITAP\IT209_DEVOPS\SESSION04\SESSION04_03>ssh -T git@github.com
The authenticity of host 'github.com (20.205.243.166)' can't be established.
ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.
This key is not known by any other names.
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'github.com' (ED25519) to the list of known hosts.
Hi Duy18ND! You've successfully authenticated, but GitHub does not provide shell access.

D:\BAITAP\IT209_DEVOPS\SESSION04\SESSION04_03>git remote -v
fatal: not a git repository (or any of the parent directories): .git

D:\BAITAP\IT209_DEVOPS\SESSION04\SESSION04_03>git remote add origin git@github.com:Duy18ND/HN_KS24_CNTT4_DoanManhDuy_IT209_SS04_HW03.git
fatal: not a git repository (or any of the parent directories): .git

D:\BAITAP\IT209_DEVOPS\SESSION04\SESSION04_03>git init
Initialized empty Git repository in D:/BAITAP/IT209_DEVOPS/SESSION04/SESSION04_03/.git/

D:\BAITAP\IT209_DEVOPS\SESSION04\SESSION04_03>git remote add origin git@github.com:Duy18ND/HN_KS24_CNTT4_DoanManhDuy_IT209_SS04_HW03.git

D:\BAITAP\IT209_DEVOPS\SESSION04\SESSION04_03>