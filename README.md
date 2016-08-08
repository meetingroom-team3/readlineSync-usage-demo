readlineSync usage
========================
```
npm install readline-sync
```

question
------------------------
```
line = readlineSync.question([query[,option]])
```
Displays the ```query``` to user,and then returns the user's response after it has been typed.
```query``` may be string or may not be(e.g.number,data,object,etc).This is converted to string(i.e. toString method is called) before it is displayed.
If ```{noEchoBack:true} ```is specified to ```options```,echo back is avoided.It is used to hide the secret text(e.g.password) which is typed by user on screen.
------------------------

```
node readlineSync-question-demo.js
```
Then you will see
------------------------
What is your favorite food?
------------------------
If you input
```
What is your favorite food? :rice
```
You will get
------------------------
```
My favorite food is rice
```