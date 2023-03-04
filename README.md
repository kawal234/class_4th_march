# class_4th_march
#include<stdio.h>
//Class of 4th March
//Calling by reference(by pointers)

//int add();
void swap(int*,int*);

int main(){
//	printf("The Answer is : %d",add());

	int a=10,b=2;
	swap(&a,&b);
//	printf("%d%d\n",a,b);
	return 0;
}

void swap(int *p,int *q){
	int temp;
	temp=*p;
	*p=*q;
	*q=temp;
	printf("%d 9+%d\n",*p,*q);
}


//int add(){
//	int x,y;
//	printf("Enter the Value of X and Y : ");
//	scanf("%d%d",&x,&y);
//	return x+y;
//}
