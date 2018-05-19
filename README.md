# I.Q-Test
#include <stdio.h>
#include<string.h>
int main()
{

     printf("\n\t\t WELCOME TO GAME\n\n") ;
     puts("\n\t\t-------------------------------");
     puts("\n\t\t Enter '1' to start game       ");
     puts("\n\t\t Enter '2' for help            ");
     puts("\n\t\t Enter '3' to quit             ");
     printf("\n\t\t------------------------------\n\n\t\t  ");

    int x=0,key,n,i=1,count=0,key1;
    printf("ENTER A KEY\n");
    scanf("%d",&key);
    
     if(key==2)
    {
    printf("\n\n\n\tThis game is very easy to play. You'll be asked some general");
    printf("\n\n\tknowledge questions and the right answer is to be chosen among");
    printf("\n\n\tthe four options provided.");
    printf("\n\n\tYour score will be calculated and displayed");
    printf("\n\n\tBEST OF LUCK.");
    
    printf("\n\nPress 1 to continue playing\n\n");
    scanf("%d",&key1);
    }
    if((key1==1)||(key==1))
    {
    switch(1)
    {
case 1:
         printf("\n\nWhich day is observed on 1st March 2015?");
         printf("\n\n1.Zero Discrimination Day\t2.World Pneumonia Day \n\n3.World Radio Day\t4.Independence Day\n\n");
        scanf("%d",&n);
        if(n==1)
        {
        printf("You have entered the correct answer Now you have won Rs.10000 \n Your Next Question is ");
        count++;
        }
        else
        {
        printf(" You have entered the wrong answer Better Luck Next Time You have earned Rs.0000");
        break;
        }
               
case 2:
        printf("\n\n\nWhich country is hosting the Fifa World Cup 2010?");
        printf("\n\n1.South Africa\t2.Italy\n\n3.Argentina\t4.Spain\n\n");
        scanf("%d",&n);
        if(n==1)
        {
        printf("You have entered the correct answer Now you have won Rs.10000 \nYour Next Question is ");
        count++;
        }
        else
        {
        printf(" You have entered the wrong answer Better Luck Next Time You have earned Rs.0000");
        break;
        }
        
case 3:
        printf("\n\nThe medulla oblongata is a part of human?");
        printf("\n\n1.Heart\t2.Liver \n\n3.Brain\t4.Sex Organ\n\n");
        scanf("%d",&n);
        if(n==3)
        {
        printf("You have entered the correct answer Now you have won Rs.10000 \n Your Next Question is ");
        count++;
        }
        else
        {
        printf(" You have entered the wrong answer Better Luck Next Time You have earned Rs.0000");
        break;
        }
case 4:
        printf("\n\nWho is the author of recently published book Final Test:Exit Sachin Tendulkar?");
        printf("\n\n1.Sachin Tendulkar\t2.Dilip D'Souza\n\n3.Kapil Dev\t4.None of these\n\n");
        scanf("%d",&n);
        if(n==3)
        {
        printf("You have entered the correct answer Now you have won Rs.10000 Your Next Question is ");
        count++;
        }
        else
        {
        printf(" You have entered the wrong answer Better Luck Next Time You have earned Rs.0000");
        break;
        }
case 5:
        printf("\n\nThe capital of Russia is?");
        printf("\n\n1.St.Petersburg\t2.Moscow\n\n3.Kiev\t4.Abaza\n\n");
        scanf("%d",&n);
        if(n==2)
        {
        printf("You have entered the correct answer Now you have won Rs.10000 Your Next Question is ");
        count++;
        }
        else
        {
        printf(" You have entered the wrong answer Better Luck Next Time You have earned Rs.0000");
        break;
        }
case 6:
        printf("\n\nThe number of seats reserved for scheduled caste in the Lok Sabha is?");
        printf("\n\n1.59\t2.79\n\n3.89\t4.99\n\n");
        scanf("%d",&n);
        if(n==3)
        {
        printf("You have entered the correct answer Now you have won Rs.10000 Your Next Question is ");
        count++;
        }
        else
        {
        printf(" You have entered the wrong answer Better Luck Next Time You have earned Rs.0000");
        break;
        }
case 7:
        printf("\n\nAspirin comes from which of the following");
        printf("\n\n1.Willow bark\t2.Acacia\n\n3.Oak tree\t4.Eucalyptus\n\n");
        scanf("%d",&n);
        if(n==1)
        {
        printf("You have entered the correct answer Now you have won Rs.10000 Your Next Question is ");
        count++;
        }
        else
        {
        printf(" You have entered the wrong answer Better Luck Next Time You have earned Rs.0000");
        break;
        }
case 8:
        printf("\n\nSatya Nadella,the latest receiver of Pravasi Bhartiya Samman,is the CEO of which of the following companies?");
        printf("\n\n1.Oracle\t2.IBM\n\n3.Symantec\t4.Microsoft\n\n");
        scanf("%d",&n);
        if(n==4)
        {
        printf("You have entered the correct answer Now you have won Rs.10000 Your Next Question is ");
        count++;
        }
        else
        {
        printf(" You have entered the wrong answer Better Luck Next Time You have earned Rs.0000");
        break;
        }
case 9:
        printf("\n\nWhich one is the largest among the following deserts?");
        printf("\n\n1.Kalahari\t2.Gobi\n\n3.Australian\t4.Atacama\n\n");
        scanf("%d",&n);
        if(n==3)
        {
        printf("You have entered the correct answer Now you have won Rs.10000 Your Next Question is ");
        count++;
        }
        else
        {
        printf(" You have entered the wrong answer Better Luck Next Time You have earned Rs.0000");
        break;
        }
case 10:
        printf("\n\nHow many times did Mahatma Gandhi nominates for Nobel Peace Prize?");
        printf("\n\n1.3 times\t2.5 times\n\n3.2 times\t4.Never\n\n");
        scanf("%d",&n);
        if(n==2)
        {
        printf("You have entered the correct answer Now you have won Rs.10000 Your Next Question is ");
        count++;
        }
        else
        {
        printf(" You have entered the wrong answer Better Luck Next Time You have earned Rs.0000");
        break;
        }
case 11:
        printf("\n\nWho won the 2014 ATP tennis Championship in Abu Dhabi?");
        printf("\n\n1.Andy Murray\t2.Rafael Nadal\n\n3.Novak Djokovic\t4.Roger Federer\n\n");
        scanf("%d",&n);
        if(n==1)
        {
        printf("You have entered the correct answer Now you have won Rs.10000 Your Next Question is ");
        count++;
        }
        else
        {
        printf(" You have entered the wrong answer Better Luck Next Time You have earned Rs.0000");
        break;
        }
case 12:
        printf("\n\nWho limits the number of Election Commissioners?");
        printf("\n\n1.Prime Minister\t2.Parliament\n\n3.None\t4.President\n\n");
        scanf("%d",&n);
        if(n==4)
        {
        printf("You have entered the correct answer Now you have won Rs.10000 Your Next Question is ");
        count++;
        }
        else
        {
        printf(" You have entered the wrong answer Better Luck Next Time You have earned Rs.0000");
        break;
        }
        
case 13:
        printf("\n\nWhich of the following date is observed as World Cancer Day?");
        printf("\n\n1.4 Feb\t2.20 Feb\n\n3.5 Feb\t4.10 Feb\n\n");
        scanf("%d",&n);
        if(n==1)
        {
        printf("You have entered the correct answer Now you have won Rs.10000 Your Next Question is ");
        count++;
        }
        else
        {
        printf(" You have entered the wrong answer Better Luck Next Time You have earned Rs.0000");
        break;
        }
case 14:
        printf("\n\nChoose the nation which is the largest supplier of arms to India in 2009-2013?");
        printf("\n\n1.Japan\t2.Israel\n\n3.Russia\t4.USA\n\n");
        scanf("%d",&n);
        if(n==3)
        {
        printf("You have entered the correct answer Now you have won Rs.10000 Your Next Question is ");
        count++;
        }
        else
        {
        printf(" You have entered the wrong answer Better Luck Next Time You have earned Rs.0000");
        break;
        }
case 15:
        printf("\n\nWhich company teams up with Pricewaterhouse Coopers to target DigitalIndia projects in 2015?");
        printf("\n\n1.Google\t2.Rediff\n\n3.Bing\t4.Yahoo!\n\n");
        scanf("%d",&n);
        if(n==1)
        {
        printf("You have entered the correct answer Now you have won Rs.10000 Your Next Question is ");
        count++;
        }
        else
        {
        printf(" You have entered the wrong answer Better Luck Next Time You have earned Rs.0000");
        break;
        }
}
int ans=count*10000;
printf("\n\n\n your total score is  ");
printf("%d\n\n",ans);
if(count>=6)
{
    printf("Good Score!! Keep it up\n");
}
else
{
    printf("\n\nTry to improve\n\n");
}
printf("\n\nTHANK YOU FOR PLAYING :-)\n\n");
}
}
