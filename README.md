#include <stdio.h>
#include<stdlib.h>

struct node{
int i;
char c;
struct node *ptr;
};

int main(){
struct node var1;
struct node var2;

var1.i=65;
var1.c='A';
var1.ptr=NULL;

var2.i=66;
var2.c='B';
var2.ptr=NULL;

var1.ptr=&var2;
printf("%d %c,var1.ptr->i,var1.ptr->c);
}
