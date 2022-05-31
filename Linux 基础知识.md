# Linux 基础知识

## 权限知识

1. 文件权限

   Linux 系统中采用三位十进制数表示权限，如0755， 0644.
   ABCD
   A- 0， 表示十进制
   B－用户
   C－组用户
   D－其他用户

   ---  -> 0  (no excute , no write ,no read)
   --x  -> 1  excute, (no write, no read)
   -w-  -> 2  write 
   -wx  -> 3  write, excute
   r--  -> 4  read
   r-x  -> 5  read, excute
   rw-  -> 6  read, write , 
   rwx  -> 7  read, write , excute

