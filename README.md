public class palindrome 
{
    public static void main(String args[])
    {
        int num =333;
        int original=num;
        int reverse=0;
        while(num!=0)
        {
            int digit= num % 10;
            reverse=reverse*10+digit;         //after one itertion value of new reverse 3,33,333
            num=num/10;         // after one iteration value of num is 33,3
        }
        if(original==reverse)
         {    
            System.out.println("yes we got palindromic number ");
         }
        else
        {
            System.out.println("try another way to get to a palindromic number");
        }
  }
}  
  
  
