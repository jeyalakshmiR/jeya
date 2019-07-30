Package train;
import java.util.*;
import java.util.arrays;
import java.util.list;
Public class train
{
  Public Static void main(string[]args){
  Scanner sc=new scanner(system.in);
  String[] dep={"Monday 6.04", "Monday 9.04","Monday 12.04","Monday 15.04","Monday 19.04","Tuesday 6.04","Tuesday 9.04","Tuesday 12.04","Tuesday 15.04","Tuesday 19.04","Wednesday 6.04","Wednesday 9.04","Wednesday 12.04","Wednesday 15.04","Wednesday 19.04"}
  int[] pas={22,119,64,177,21,22,111,87,193,107,93,162,42};
  List1=Arrays.asList(dep);
  int quit=0,choice;
  while(quit!=1)
  {
   System.out.print("1.Display day,time and passengers number\n2.Display the most popular train\n3.Display the least popular train\n4.Popular train between 6.04 train and 9.04 train\n5.Popular train between Monday 6.04 and Tuesday 6.04);
   System.out.print("Enter the number from choice:");
   Choice= sc.nextInt();
   Switch (choice)
   {
    Case1: System.out.print("Day  Departuretime  Passengers number");
    for(int i=0;i<=15;i++)
   {
    System.out.print(dep[i]+"\t\t\t\t"+pas[i];
    break;
   }
   Case2: for(int i=0;i<=15;i++)
   {
    if(pas[i]>190)
   {
    System.out.print(dep[i]);
    break;
    }
  }
   Case3: for(int i=0;i<=15;i++)
   {
    if(pas[i]<15)
   {
    System.out.print(dep[i]);
    break;
   }
  }
   Case4: if(pas[10]<pas[1]&&pas[5]<pas[6]&&pas[10]<pas[11])
   {
    System.out.print("9.04 train is popular than 6.04 train");
   }
  else
  System.out.print("6.04 train is popular than 9.04 train");
  break;
  } 
   Case5: if(pas[0]<pas[5])
   {
    System.out.print("6.04 train on Monday is popular than 6.04 train on Tuesday");
   }
   else if(pas[0]>pas[5])
    System.out.print("6.04 train on Tuesday is popular than 6.04 train on Monday");
   else
    System.out.print("Both 6.04 trains on Monday and Tuesday have same popularity");
    break;
  }
   Case6: string A1,A2;
     System.out.print("Enter day and time of 2 trains as (Monday 6.04)");
     A1=Sc.nextLine();
     A2=Sc nextLine();
     int b,c;
     b=l.indexOf(A1);
     c=l.indexOf(A2);
     System.out.print(" Passenger number in train1:"+ pas[b]+"\n passenger number in train2:"+ pas[c]);
     if(pas[b]>pas[c])
     {
      System.out.print(A1+"train is more popular than"+A2+" train");
     }
    else if(pas[b]<pas[c])
     {
       System.out.print(A2+" train is more popular than"+A1+" train");
     }
   else
    {
      System.out.print("Both trains have the same popularity");
      break;
    }
    Case7:for(int i=0;i<=15;i++)
    {
     if(pas[b]<50)
    {
      System.out.print(dep[b]+"\n");
      break;
    }
   }
    Case8: int sum;
    sum=(pas[2]+pas[7]+pas[12]);
    System.out.print("Average number of passengers traveling in 12.04 in 3 days: "+(sum/3));
    break;
    
    Case9: System.out.print("Enter the day and time of train to display the average no.of.passengers(day and time as:Monday 6.04)");
    String S=Sc.nextLine();
    int i=l.indexOf(S);
    System.out.print("Average no.of.passengers traveling in"+s+" train is"+pas[b]);
    break;
  }
 }
}

  

  
