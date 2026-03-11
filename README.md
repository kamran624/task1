#include <stdio.h>
int main (){
	int eded, cem, yuz, on, tek;
	printf("eded daxil edin");
	scanf("%d/n",&eded);
	yuz=eded/100;
	on=(eded/10)%10;
	tek=eded%10;
	cem=yuz+on+tek;
	printf("reqemlerin cemi:%d",cem);
}
