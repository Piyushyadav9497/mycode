import java.util.*;
class Demo 
{
    public static void main(String arg[])
    {
         Scanner sc = new  Scanner (System.in);
         int number = sc.nextInt();
         if( number % 2 == 0) { 
            System.out.println("even");

         }
         else {
            System.out.println("odd");
         }
    }}

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


    CALCULATOR

    import java.util.*;
class Demo 
{
    public static void main(String arg[])
    {
           Scanner sc = new Scanner(System.in);
           System.out.println("enter a :");
           int a = sc.nextInt();
            System.out.println("enter b :");
           int b = sc.nextInt();
           System.out.println("enter operator : ");
           char operator = sc.next().charAt(0);
           switch(operator) {
            case '+' : System.out.println(a+b);
            break;
             case '-' : System.out.println(a-b);
            break;
             case '*' : System.out.println(a*b);
            break;
             case '/' : System.out.println(a/b);
            break;
             case '%' : System.out.println(a%b);
            break;
default :   System.out.println("chal nikal" );
         
            

           }
            }
           }
          
    sum of n number


    import java.util.*;
class Demo 
{
    public static void main(String arg[])
    {
         
       Scanner sc = new Scanner(System.in);
       int n = sc.nextInt();
       
       int sum = 0;
int i=1; 
while(i <= n) 
{
    sum += i;
    i++;
    
}
System.out.println("sum is : " + sum);
        }
 
           }
            
           // print star 
           import java.util.*;
class Demo 
{
    public static void main(String arg[])
    {
          for(int line = 1 ; line <=5; line++)
             {
            for(int star =1; star<=line; star++){   
                System.out.print("*");
            } 
            System.out.println();
          }
    }
         }
          
    import java.util.*;
class Demo 
{
    public static  boolean isprime(int n )
    {
           if (n ==3){
            return true;
           }
          for (int i = 2  ; i<= Math.sqrt(n); i ++ ){
            if (n % i == 0 ){ 
            return false;
          }
    }
    return true; }
    public static void primerange( int n){
      for (int i=2; i<=n; i++){
        if (isprime(i)){
          System.out.print(i+" ");
        }
      }
      System.out.println();
    }
    public static void main(String arg[])
    {
         primerange(30);
         }
        }



        print subarrays
        import java.util.*;
class  Demo 
{ // print pair
             public static  void  ps(int num[] ){
              int ts = 0;
               for(int i=0; i<num.length; i++){
                int start= i;
                for(int j=i; j<num.length; j++){
                int end = j;
                for(int k=start; k<=end; k++){
                  System.out.print(num[k]+" ");
                }
                ts++;
                System.out.println();
                   
                }
                 System.out.println();   
               }  
               System.out.println("total ps"+ ts);
             }
             public static void main(String arg[]){
               int num[] = { 2, 4 , 6, 8, 10 ,12 };    
             ps(num);
            }}

            public class OOPs {
    public static void main(String args[]){
        Student s1 = new Student();
        s1.name  = "piyush";
        s1.roll = 476;
        s1.password = "asdf";
        s1.marks[0] =100;
        s1.marks[1] = 30;
        s1.marks[2] = 45;

        Student s2 = new Student(s1);
        s2.password = "xyz";
        for(int i=0; i<3; i++){
            System.out.println(s2.marks[i]);
        }
    }
}
class Student{
    String name;
    int roll;
     String password;
     int marks[];
   //shallow copy constructor
   /* 
    Student(Student s1) {
        marks  = new int[3];
     this.name =  s1.name;
     this.roll   = s1.roll;
     this.marks = s1.marks;
    }
*/
    //deep copy constructor
    Student(Student s1){
         marks  = new int[3];
     this.name =  s1.name;
     this.roll   = s1.roll;
     for( int i=0; i<marks.length; i++){
        this.marks[i] = s1.marks[i];
     }
    }
     Student(){
         marks = new int[3];
     System.out.println("it's me");
     }
     Student(String name){
        marks = new int[3];
        this.name = name ;
     }
     Student (int roll){
        marks = new int[3];
        this.roll =  roll;
     }
    }
    

**BACK TRACKING**
            import java.util.*;
           class demo{
            public static void changearr( int arr[], int i , int val){

            if ( i == arr.length){
              printarr(arr);
              return;
            }

             arr[i] =val;
                 changearr( arr , i+1 , val+1);
                 arr[i] = arr[i] + 2;
            }

            public static void printarr(int arr[]){
              for ( int i=0; i<arr.length; i++){
                System.out.print(arr[i]+" ");
              }
              System.out.println();
            }
       public static void main( String arg[]){
        int arr[] = new int[5];
        changearr( arr , 0 , 1 );
        printarr(arr);
        }}
