# Sharing files

In this practical work, you will :

 - Deploy a NFS server
 - Use a NFS client
 - Deploy a Samba server
 - Use a Samba client

## Question 1 Warmup

Use three virtual machine. Configure them to use a private network.

## Question 2 NFS with /etc/exports

Deploy a NFS server on machine 1.

Create a share threw /etc/exports . Machine 2 should be able to mount it (using mnt). Machine 3 should not be able to mount it. Demonstrate that the changes made by machine 2 on the share are visible by machine 1. Have a look at nfsstat on machine 1 and machine 2. 

Reboot machine 2. Is your share NFS mounted after reboot ? Do the changes so that it is mounted after reboot.

Shutdown your NFS share.

## Question 3 NFS threw exportfs

Same thing than question 2 but using exportfs without /etc/exports

## Question 4 Samba server

Install a samba server on machine 1

Create a user for Samba on machine 1

Machine 2 should be able to access a directory from machine 1 using samba. Perform this configuration. Mount the samba volume on machine 2.

## Tips session

// todo


