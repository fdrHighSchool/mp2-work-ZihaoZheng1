# Div By 3
#### Respond to the following:

1. A number is considered *prime* if its only factors are 1 and itself. For example, 7 is prime (1 and 7 are the only factors) and 9 is not (1, 3 and 9 are factors).  
Outline an algorithm to determine whether or not a number is prime.  
Think of the following method header:
`public static boolean isPrime(int num)`

  * 1.public static boolean isPrime(int num){
    2. boolean check=true;
    3.int div=2;
    4.do{
    5.if (num%div==0){
    6.check=false;
    7.}// end if
    8.else{
    9.check=true;
     10.}// end else
  11.}while(check!=false || div<=div/2); // end do while
     12.return check;
  13.}//end isPrime method
  
