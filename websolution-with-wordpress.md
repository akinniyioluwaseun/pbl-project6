# WEB SOLUTION WITH WORDPRESS

## STEP 1 - PREPARE A WEB SERVER

### Volumes Created
![](volumes-created.png)
---
### Physical Volumes Created
![](physical-volumes-created.png)
---
### Webdata Volume Group Created
![](webdata-volume-group-created.png)
---
### Logical Volumes Created
![](logical-volumes-created.png)
---
### Verifying The Entire Setup
![](verifying-entire-setup.png)
---
### Formatting Logical Volumes With Ext4 Filesystem
![](formatting-lvs-with-ext4-fs.png)
---

### Creating var/www/html && home/recovery/logs Directory
![](html-logs-directory.png)
---
### Mounting Logical Volumes on var/www/html and /var/log
![](mounting-logical-volume1.png)
---
![](mounting-logical-volume2.png)
---
### Update /etc/fstab File So That The Mount Configuration Will Persist After Restart Of The Server
![](Updating-etc-fstab.png)
---
### Test Configuration And Reload Daemon
![](testing-config-reload-daemon.png)
---
### Verifying Mount Setup
![](verifying-mount-setup.png)
---


## STEP 2 - PREPARE THE DATABASE SERVER (DB SERVER)

### DB Server Volumes Created
![](db-volumes-created.png)
---
### DB Physical volumes Created
![](db-physical-volumes-created.png)
---
### DB Volume Groups Created
![](db-volume-group-created.png)
---
### DB Logical Volume Created
![](db-logical-volume-created.png)
---
### Formatting DB Logical Volumes With Ext4 Filesystem
![](formatting-db-logical-volume-with-ext4.png)
---
### Creating /db Mount Point Directory
![](Creating-db-directory.png)
---
### Mounting DB Logical Volume to /db
![](mounting-logical-volume.png)
---
### Verifying DB Mount Setup
![](verifying-mount-point.png)
---
### Update DB /etc/fstab File So That The Mount Configuration Will Persist After Restart Of The Server
![](updating-etc-fstab.png)
---
### ### Test Configuration And Reload Daemon
![](testing-config-reload-daemon.png)
---




## STEP 3 - INSTALL WORDPRESS ON YOUR WEBSERVER EC2

## STEP 4 - INSTALL MYSQL ON YOUR DB SERVER EC2

## STEP 5 -  CONFIGURE DB TO WORK WITH WORDPRESS

## STEP 6 - CONFIGURE WORDPRESS TO CONNECT TO REMOTE DATABASE