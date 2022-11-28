# 24.-odev

//say�y� 2 ile �arpan fonksiyon

#include<stdio.h>
int carp(int);

int main(void)
{
	int x;
	printf("sayi gir:");
	scanf("%d" , &x);
	
	printf("sonuc: %d" , carp(x));
	
	return 0;
}

int carp(int x)
{
	return 2*x;
}
