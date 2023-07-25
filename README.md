# practice2


# define _ CRT_SECURE_NO_WARNINGS
#include<stdio.h>


struct book
{
	char name[20];// c语言
	short price;//价格55



};
   int  main()
{
	struct book b1={"c语言",55 };
	//printf("书名%s\n",b1.name);
	//printf("价格%d\n", b1.price);
	struct book* pb = &b1;
	printf("%s\n", (*pb).name);
	printf("%d\n", (*pb).price);
	printf("%s\n", pb->name);
	printf("%d\n", pb->price);

	return 0;
}
