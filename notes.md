#<center>output redirection</center>

cat >new.txt
/*cretes a new file if new.txt is not present else overwrites new.txt*/
">" overwrites
">>" appends

for example 

cat >>apex.txt
sdsgbjfgbjnjgndjsgnbksmdbfd
dfgfdsbfonjomgmodfmgdfkg
sdfogajofdgjfdjgodgiofdjg

cat apex.txt  //displays the content of apex.txt in the terminal

sdsgbjfgbjnjgndjsgnbksmdbfd
dfgfdsbfonjomgmodfmgdfkg
sdfogajofdgjfdjgodgiofdjg


command >> filename // appends the output of the command to the file

#input redirection
-taking input from the file 
operator "<"

command < filename

wc < apex.txt
  5  17 174// lines words characters

grep "nitish" <apex.txt
nitish of yeahhhh   //nitish highlighted in terminal
<center>#Discard the output</center>>