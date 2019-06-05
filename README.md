# Fileos
 a simple file system is based on ext and using c++.It is comfortable for linux.

*filesystem-1.0.tar.gz* is the better version of all.I write a simple makefile in it just for compiling easily.

## Fn directory filesytem

 the architecture of this file system is like the following picture. But it lack group descriptors and Reserved GDT block.

 ![](/picture/architecture.png)

 the tree of filesystem.

 ![](/picture/tree.png)

 if you want to run the whole project 'compile and create file',just input **make**.

 ![](/picture/make.png)

 if you want to run file simply,just input **make run**.

 ![](/picture/run.png)

 if you want to delete file,just input **make clean**.

 ![](/picture/clean.png)

 if you want to find back the usename and password of your file system,just input **make accountback**

 ![](/picture/accountback.png)

 ## The function of file system

   <br> help    ---  show help menu </br>
   <br> clear   ---  clear the screen </br>
   <br> ls      ---  list the digest of the directory's children </br>
   <br> ls -l   ---  list the detail of the directory's children </br>
   <br> cd      ---  change directory </br>
   <br> mkdir   ---  make directory </br>  
   <br> touch   ---  create a new file </br>
   <br> cat     ---  read a file </br>
   <br> write   ---  write something to a file </br>
   <br> rm      ---  delete a directory or a file </br>
   <br> mv      ---  rename a file or directory </br>
   <br> chmod   ---  change the authorizatinon of a directory or a file </br>
   <br> exit </br>