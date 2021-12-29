# Structure

#include <stdio.h>

typedef struct books{
        
        char BookName[15];
        char AuthorName[15];
        int BookPrice;
        int number_of_books;
}B;
int main()
{
    B book1 , book2;
    
    printf("Enter Name of Book1 : ");
    scanf("%s",book1.BookName);
     printf("Enter Name of Author of Book1 : ");
    scanf("%s",book1.AuthorName);
     printf("Enter price of Book1 : ");
    scanf("%d",&book1.BookPrice);
     printf("Enter Numbers of Books1 required : ");
    scanf("%d",&book1.number_of_books);
    
    printf("Enter Name of Book2 : ");
    scanf("%s",book2.BookName);
    printf("Enter Name of Author of Book2 : ");
    scanf("%s",book2.AuthorName);
    printf("Enter price of Book2 : ");
    scanf("%d",&book2.BookPrice);
    printf("Enter Numbers of Books1 required : ");
    scanf("%d",&book2.number_of_books);
    
    printf("Name of Book1 : %s",book1.BookName);
    printf("Name of Author of Book1 : %s",book1.AuthorName);
    printf("Price of Book1 : %d",book1.BookPrice);
    
    return 0;
}


#include <stdio.h>

typedef struct books{
        
        char BookName[15];
        char AuthorName[15];
        int BookPrice;
        int number_of_books;
}B;
int main()
{
    B book[2];
    
    for(int i=1;i<3;i++)
   {
            
    printf("Enter Name of Book%d : ",i);
    scanf("%s",book[i].BookName);
     printf("Enter Name of Author of Book%d : ",i);
    scanf("%s",book[i].AuthorName);
     printf("Enter price of Book%d : ",i);
    scanf("%d",&book[i].BookPrice);
     printf("Enter Numbers of Books required%d : ",i);
    scanf("%d",&book[i].number_of_books);
    
}

