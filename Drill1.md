# Practice Drill CLI

  


### Start with main directory name hello by using mkdir command and then navigate in hello folder for further creation

mountblue@mountblue-pc:~$ mkdir hello

mountblue@mountblue-pc:~$ cd hello

#### According to above chart all directory or files has been created

mountblue@mountblue-pc:~/hello$ mkdir five

mountblue@mountblue-pc:~/hello$ cd five

mountblue@mountblue-pc:~/hello/five$ mkdir six

mountblue@mountblue-pc:~/hello/five$ cd six

#### To create an empty file use touch command with the extension of file

mountblue@mountblue-pc:~/hello/five/six$ touch c.txt

mountblue@mountblue-pc:~/hello/five/six$ mkdir seven

mountblue@mountblue-pc:~/hello/five/six$ cd seven


mountblue@mountblue-pc:~/hello/five/six/seven$ touch error.log

#### To Move UP in directory use cd .. command

mountblue@mountblue-pc:~/hello/five/six/seven$ cd ..

mountblue@mountblue-pc:~/hello/five/six$ cd ..

mountblue@mountblue-pc:~/hello/five$ cd ..

#### Now create directory name one and add its sub folders

mountblue@mountblue-pc:~/hello$ mkdir one

mountblue@mountblue-pc:~/hello$ cd one

mountblue@mountblue-pc:~/hello/one$ touch a.txt b.txt

mountblue@mountblue-pc:~/hello/one$ mkdir two

mountblue@mountblue-pc:~/hello/one$ cd two

mountblue@mountblue-pc:~/hello/one/two$ touch d.txt

mountblue@mountblue-pc:~/hello/one/two$ mkdir three

mountblue@mountblue-pc:~/hello/one/two$ cd three


mountblue@mountblue-pc:~/hello/one/two/three/three$ touch e.txt

mountblue@mountblue-pc:~/hello/one/two/three/three$ mkdir four

mountblue@mountblue-pc:~/hello/one/two/three/three$ cd four

mountblue@mountblue-pc:~/hello/one/two/three/three/four$ touch access.log




## 2.Delete all the files having the .log extension

#### Find all file and Navigate to the directory where .log file is present using cd command then apply below command

rm [nameOfFile].log

mountblue@mountblue-pc:~/hello/five/six/seven$ rm error.log

mountblue@mountblue-pc:~/hello/one/two/three/three/four$ rm access.log


find . -name "*.log" -delete





## 3.Add the following content to a.txt

#### Navigate to directory where a.txt file is present then apply below command 

mountblue@mountblue-pc:~/hello/one$ echo "Unix is a family of multitasking, multiuser computer operating systems that derive from the original AT&T Unix, development starting in the 1970s at the Bell Labs research center by Ken Thompson, Dennis Ritchie, and others" >> a.txt

#### To print the content of file a.txt

mountblue@mountblue-pc:~/hello/one$ cat a.txt

Unix is a family of multitasking, multiuser computer operating systems that derive from the original AT&T Unix, development starting in the 1970s at the Bell Labs research center by Ken Thompson, Dennis Ritchie, and others

## 4.Delete the directory Name Five

mountblue@mountblue-pc:~/hello$ rm -r five

#### Above command is for directly delete all sub file and content with directory named five

#### we can also first empty that directory by deleting its sub files and folder then apply below command for empty directory

rmdir five 

## 5. Rename the 'one' directory to 'uno'

mountblue@mountblue-pc:~/hello$ mv one uno


## 5. Move a.txt to the two directory

#### Navigate to folder where a.txt file is present then write below command


mountblue@mountblue-pc:~/hello/one$ mv a.txt two




