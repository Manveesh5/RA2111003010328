	
#include<stdio.h>

int main()

{

    int amount_given,bill_amount;
    
    int quotient,remainder;
    printf("Enter amount:\n");
    scanf("%d",&amount_given);
    
    printf("Enter bill amount:\n");
    scanf("%d",&bill_amount);
    
    quotient= amount_given/bill_amount;
    remainder= amount_given%bill_amount;
    printf("Quotient=%d\nRemainder=%d",quotient,remainder);
    return 0;
}
