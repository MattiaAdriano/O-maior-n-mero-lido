# O-maior-n-mero-lido

#include <stdio.h>
#include <stdlib.h>
int main ()
{
	int cont, num, maior;
	maior=0;
	for (cont=1;cont<=10;cont++)
	{
		printf ("digite um numero: ");
		scanf("%d" ,&num);
		if (num > maior)
		{
			maior=num;
		}
	}
	printf ("O maior dos numeros lidos = %d\n" ,maior); 
	return 0;
	
}
