#include <stdio.h>
#define rangee 3
#define colonne 3
#define carre 3
void AdditionMat(int a[rangee][colonne],int b[rangee][colonne]);
int main(int argc, char **argv)
{
	int a[carre][carre]={{1,1,1},{1,1,1},{1,1,1}};
	int b[carre][carre]={{2,2,2},{2,2,2},{2,2,2}};
	AdditionMat(a,b);
	return 0;
}
void AdditionMat(int a[rangee][colonne],int b[rangee][colonne]){
	int c [rangee][colonne];
	for(int i=0;i<carre;i++){
		for(int j=0;j<carre;j++){
			c[i][j]=a[i][j]+b[i][j];
		}
	}
	for(int i=0;i<carre;i++){
		printf("|");
		for(int j=0;j<carre;j++){
			printf(" %d",c[i][j]);
		}
		printf("|\n");
	}
}