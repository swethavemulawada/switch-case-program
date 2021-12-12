//# switch-case-program
//developed be v swetha,using c programming language.
#include<stdio.h>
main()
{
	printf("Enter your choice what do you Eat:\n1.sandwich\n2. french fries\n3. pasta\n4. burger\n5. pizza");
	int choice=0;
	scanf("%d",&choice);
	switch(choice)
	{
		case 1:
			printf("food item-sandwich.\nprice-Rs 149");
			break;
		case 2:
			printf("food item-french fries.\n price-Rs 99");
			break;
		case 3:
			printf("food item-pasta.price-Rs179");
		    break;
		case 4:
			printf("food item-burger.price-Rs129");
			break;
		case 5:
			printf("food item.price-Rs239");
			break;
		default:
			printf("item is not available.");
			
		
	}
	return 0;
}
