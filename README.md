# project1
celsius to fahrenheit
#include<stdio.h>
float conv(int c);
int main(){
    float c;
    printf("Enter temperature in celsius ");
    scanf("%f",&c);
    printf("Fahrenheit equivalent is %f", conv(c));
    return 0;
}
float conv(int c){
    float f=(1.8*c)+32;
    return f;
}
