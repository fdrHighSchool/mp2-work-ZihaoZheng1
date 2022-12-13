# Div By 3
#### Respond to the following:

1. A number is considered *prime* if its only factors are 1 and itself. For example, 7 is prime (1 and 7 are the only factors) and 9 is not (1, 3 and 9 are factors).  
Outline an algorithm to determine whether or not a number is prime.  
Think of the following method header:
`public static boolean isPrime(int num)`
```
  * Divide the given number by each number from 2 to half of the given number to check if there is an integer or the remainder is zero
  for example:
  
    public static boolean isPrime(int num){
    boolean check=true;
    int div=2;
    do{
    if (num%div==0){
     check=false;
    }// end if
    else{
     check=true;
    }// end else
    }while(check!=false || div<=div/2); // end do while
     return check;
    }//end isPrime method
```
