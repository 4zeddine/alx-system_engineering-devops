0 pwd : Print working directory
1 ls: list content of the current directory
2 cd ~ : change back to Home 
3 ls -lA : Display current directory contents in a long format
4 ls -la : Display current directory contents, including hidden files (starting with .) in long format
5 ls -na : Display current directory contents in long format with user and group IDs displayed numerically and hidden files (starting with .)
6 mkdir /tmp/my_first_directory : creates a directory named my_first_directory in the /tmp/ directory
7 mv /tmp/betty /tmp/my_first_directory : Move the file betty from /tmp/ to /tmp/my_first_directory
8 rm /tmp/my_first_directory/betty : Delete the file betty
9 rmdir /tmp/my_first_directory : Delete the directory my_first_directory that is in the /tmp directory
10 cd - : changes the working directory to the previous one
11 ls -la . ..  /boot : lists all files  in the current directory and the parent of the working directory and the /boot directory (in this order), in long format
12 file /tmp/iamafile : prints the type of the file named iamafile
13 ln -s /bin/ls __ls__ : Create a symbolic link to /bin/ls, named __ls__ 
14 cp *.html ../ : copies all the HTML files from the current working directory to the parent of the working directory
