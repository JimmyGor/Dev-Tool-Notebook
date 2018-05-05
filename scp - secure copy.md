# scp - transfer file/directory between linux/mac
* Syntax : scp [options] file_source file_target  
  * option  
  `-C` - Compress  
  `-p` - Keep modify time, access time and access privilege  
  `-P` - port number, require if remote server setup dedicate port number  
  `-r` - copy the whold folder  
  `...`
  
* Sample </br>
  * **Copy from local to remote**  
  
    `scp local_file remote_username@remote_ip:remote_folder` or  
    `scp local_file remote_username@remote_ip:remote_file`  
    
    `scp /home/hub/file1.txt root@192.168.1.1:/home/hub` or  
    `scp /home/hub/file1.txt root@192.168.1.1:/home/hub/file1.txt` 
    
    \** will prompt to input user name if without in above command
    
  * **Copy from remote to local**  
  
    `switch the remote name with local name from above sample`
