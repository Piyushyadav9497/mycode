# mycode
this is my first Git Repository 
<br>
my name is piyush yadav ji 
 //INCOME TAX CALCULATOR CODE
    import java.util.*;
class Demo 
{
    public static void main(String arg[])
    {
           Scanner sc = new Scanner (System.in);
           int income = sc.nextInt();
           int tax;
           if(income < 500000){
            tax = 0;
           }
           else if ( income >=500000 && income < 1000000){
            tax = (int) (income * 0.2);

           }
          else {
            tax = (int) ( income * 0.3);
          }
          System.out.println("your tax is : " + tax);
          }
    }

num is prime or not 

import java.util.*;
class Demo 
{
    public static  boolean isprime(int n )
    {
           if (n ==2){
            return true;
           }
          for (int i = 2  ; i<= Math.sqrt(n); i ++ ){
            if (n % i == 0 ){ 
            return false;
          }
    }
    return true; }
    public static void main(String arg[])
    {
        System.out.println(isprime ( 11));
         }
        }

        print prime number range 2 to n 
        

        binaary to decumal 
        import java.util.*;
class Demo 
{
    public static  void bitodec(int binum){
      int mynum = binum;
      int pow =0 ;
      int decnum = 0 ;
      while(binum >0){
        int lastdigit = binum % 10  ;
        decnum = decnum + (lastdigit *(int) Math.pow(2,pow));
        pow++;
        binum= binum/10;
      }
      System.out.println("dec of " + mynum + " =" +decnum);
    }

  public static void main(String[] args) {
    bitodec(101);
  }
  
        }

        print hollow rectangle 
        
        import java.util.*;
class Demo 
{
    public static  void  hollowrec( int tor, int toc){
      for ( int i=1; i<=tor; i++)
      {
        for(int j=1; j<=toc; j++){
if( i == 1 || i == tor|| j==1 || j==toc){
  System.out.print("*");
}else{
  System.out.print("  n");
}
        }
        System.out.println();
      }
      }
      public static void main( String args[]){
        hollowrec( 4 ,5);
      
    }
            
         }.

         linear search in array 

         import java.util.*;
class  Demo 
{
             public static  int ls(int num[], int key){
             for(int i = 0 ; i<num.length; i++){
              if(num[i] == key ){
                return i;
              }
             } 
          return -1;
             }
             public static void main(String arg[]){
              int num[] = {3, 4, 25 , 25,56,};
              int key = 6; 
              int index = ls( num , key);
              if (index == -1 ){
                System.out.println("not foound");
              }
              else{
                System.out.println("key ai "+ index);
              }
              System.out.println();
             }
}
        


