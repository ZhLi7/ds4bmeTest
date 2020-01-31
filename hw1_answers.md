

### question 2 

<img width="1057" alt="HW1_question 2" src="https://user-images.githubusercontent.com/60142425/73567067-8a262d00-4433-11ea-9e43-86980f6a9c87.png">


### question 3 

<img width="1063" alt="HW1_question 3" src="https://user-images.githubusercontent.com/60142425/73567050-7aa6e400-4433-11ea-8bab-33a1c7145841.png">

### question 4 

<img width="1017" alt="HW1_question 4" src="https://user-images.githubusercontent.com/60142425/73567019-6c58c800-4433-11ea-8bca-41593bc5ae11.png">


### question 5 
<img width="1074" alt="HW1_question 5(1)" src="https://user-images.githubusercontent.com/60142425/73566873-fbb1ab80-4432-11ea-9552-4bec86ddd096.png">

<img width="1072" alt="HW1_ question 5(2)" src="https://user-images.githubusercontent.com/60142425/73566999-606d0600-4433-11ea-8800-a0eaefb2f1d8.png">

### for question 7 

here is the bash script in the finddcm.sh file 
    find . -name "*.dcm" > dcmfile  $1 

chmod +x finddcm.sh (to make it executable)
    path/finddcm.sh directory (to execute the script)
    
    
### for question 8 
UINX>wget https://en.wikipedia.org/wiki/Alexander_the_Great | wc
--2020-01-31 12:18:06--  https://en.wikipedia.org/wiki/Alexander_the_Great
Resolving en.wikipedia.org (en.wikipedia.org)... 208.80.154.224
Connecting to en.wikipedia.org (en.wikipedia.org)|208.80.154.224|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 840064 (820K) [text/html]
Saving to: ‘Alexander_the_Great’

Alexander_the_Gre 100%[============>] 820.38K  2.27MB/s    in 0.4s

2020-01-31 12:18:07 (2.27 MB/s) - ‘Alexander_the_Great’ saved [840064/840064]

       0       0       0
UINX>ls

Alexander_the_Great     outfile.txt

hw1page.html            readme.md

lsfile.sh

UINX>wc Alexander_the_Great

    3680   46163  840064 Alexander_the_Great

UINX>wc -l Alexander_the_Great

    3680 Alexander_the_Great

UINX>
