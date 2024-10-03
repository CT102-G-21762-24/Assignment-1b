#include<stdio.h>
int main(){
    int age;
    float income;
    
    //The user to input their age
    printf("Enter your age:");
    scanf("%d",&age);
    
    //The user to input their income
    printf("Enter your income:");
    scanf("%f",&income);
    
    //To determine if the user will qualify for a loan
    if(age>=21 &income>=2100){printf("congratulations you qualify for a loan:\n");
    }
    else{printf("unfortunately we are unable to offer you a loan at this time:\n");
    } 
    
    return 0;
    }# Assignment-1b
