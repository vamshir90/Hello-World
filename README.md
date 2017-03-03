// Header Files
#include<stdio.h>
#include<conio.h>

//Main Function
int main()
{
     // Variable Declaration
     char ch;

     //Get Input Value
     printf("Enter the Vowel (In Capital Letter):");
     scanf("%c",&ch);

     //Switch Case Check
     switch( ch )
     {
        case 'A' : printf( "Your Character Is A\n" );
                   break;

        case 'E' : printf( "Your Character Is E\n" );
                   break;

        case 'I' : printf( "Your Character Is I\n" );
                   break;

        case 'O' : printf( "Your Character Is O\n" );
                   break;

        case 'U' : printf( "Your Character Is U\n" );
                   break;

        default  : printf( "Your Character is Not Vowel.Otherwise Not a Capital Letter\n" );
                   break;
     }
     // Wait For Output Screen
     getch();

     //Main Function return Statement
     return 0;
}
