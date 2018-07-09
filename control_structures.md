## Control Structures....

* Scala Control structures are similar to Java plus a lot more additional to Java.
* Java ternary operator equivalent in Scala is: ```val result = if (condition) statement1 else statement2```

* Scala for loop basic use is similar to Java, but with addition of guards and other conveniences.
* Scala for loop

```
for( line <- src.getLines){
  for(char <- line){
    //Do something here....
  }
}

for{
  line <- src.getLines
  char <- line
} //Do Something here....
```
