#include <stdio.h>
#include <stdlib.h>
#include <string.h>
/* run this program using the console pauser or add your own getch, system("pause") or input loop */

void swap(char *a, char *b)
{
	*a = *a^*b;
	*b = *a^*b;
	*a = *a^*b;
}

char *reverse_iterative(char *s)
{
	int len = strlen(s);
	int i ;
	for(i = 0; i < len/2; i++)
	{
		swap(s+i, s+(len-1-i));
	}
    
	return s;
}

int main(int argc, char *argv[]) {
	char str[10] = "hello";
	
	printf("%s\n", reverse_iterative(str));
	return 0;
}
