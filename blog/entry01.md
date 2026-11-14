# Entry 1
##### 11/13/2026

Node.js is hard like really hard it makes my skin crawl any time i see code written in it. But you can do lots with it and it is what i will be using my freedom project. The reason its so hard and why i am using it for my freedom project is because that that it can do async computing which is a way for javascript to do 2 operations at once, and that it deals with networking so i can make my server fast.

First let us in depth talk about async computing in js. As said in the last paragraph async computing is a way for js it do multiple things at once. For you more techy people it doesn't use multiple cores it just doesn't stop whatever it was doing because of one operation. Basically the program says ok do this thing i will check back on you to see if it is complete and if it is, it will take out that value and do whatever it needs to do with it.

Some basic code for async and await is 

```
async function hi(){
  return 20
}
function print(text){
  console.log(text)
}


hi().then(function(value){      /*calls hi then says "once your done with that move one to calling"
  print(value);                 and after this statement we can still call new statements that */
});
```
![alt text](image.png)

As you can see the task that was called without async got done before the one with async. That's because when the browser or in node.js case runtime is done with a task it waits until js is done with the operation it's doing.

Also i forgot to say that operations that await or async are run on the browser.

Async and await are useful for this project because there are gonna be task that my code has to do that take a long time like reading and looking for files.


[Next](entry02.md)

[Home](../README.md)