# Count Quarters
#### Respond to the following:

1. How do you isolate the ones digit of a number?
```
  * change the int to the string and use substring() method to get one(or over) digit of number, for example:
  int a = 88;
  String b = ""+a;
  b = b.substring(0,1);
  a = Integer.parseInt(b);//if convert back to integer needed
``` 
