# apcsa-pixlab
AP Computer Science A : Picture Lab: November 15 - December 11, 2019 

Work through the 9 Picture Lab Activities by 
1. Clone the repository: git clone 

2. Create a new branch so that you can make changes and it won't affect your master: 
             git checkout -b myownbranch
             
3.Push your new branch to GitHub (the remote)
             git push -u origin myownbranch
             
4.  Compile all the class files in the classes folder using your IDE Of choice or terminal/command prompt. (If you are interested in using cloud9 IDE, let me know.) You can edit your .java files using the editor or IDE of your choice.You should keep the images folder and the classes folder together in the pixLab folder or else the program won't work. Work through the activities in the Student Guide: Record your answers to the questions in the MyAnswers.txt file. 
    a) For activity 1: For more information and practice on converting decimal characters to binary, please visit. 
                        https://www.rapidtables.com/convert/number/decimal-to-binary.html
    b) For activity 2: Visit https://www.wired.com/2010/02/color_charts/ to see the hexadecimal code for many different colors.
    c) For activities 3-9: Although the guide is written  using the beach.jpg picture already provided for in the images directory, feel free to use an image of your choice by copying them to the pixLab/images folder and updated the code to refer to your personal picture instead of beach.jpg: 
   method scale(double xPercent, double yPercent). For example, a picture can be scaled to one-fourth size using:
    Picture p = new Picture("myPicture.jpg"); // create a picture called your own personal picture 
                                              // replace MyPicture.jpg with the name of your own.
    Picture smallP = p.scale(0.25,0.25); // creates a new picture a quarter as big usingscale(double xPercent, double yPercent). 
    smallP.write("smallMyPicture.jpg"); // writes it to the images folder
    
5. Each time you complete a programming component in an activity, I suggest you use git bash to 
        update your local repository (git commit -a -m "comments about the update") 
        and update the remote repository on Github (git push)


Note: If you ever want to access the original repository, you can checkout that branch using 
  - git checkout master
  
