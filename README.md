// c++ project to show the use of range in the switch case statement
//code prototype for switch and temperature readings
//sample to help us gain a deeper understanding of this
#include<stdio.h>
int main()
{
	int x;//creating an int var to store the temperature reading
	printf("Please type the temperature reading");
	printf("\n temp in centigrades\n");
	scanf("%d",&x);//storing typed value in our int container
	switch(x)
	{
		//start of switch
	case -100 ... -1:
		printf("The weather is literally freezing\n");
		break;

	case  0 ... 19:
		printf("The weather is really cold\n");
		break;
	case  20 ... 29 :
	    printf("The weather today reads normal temperature");
	break;
	case 30 ... 100:
		printf("Today is extremely hot!");
		break;
	default:
		printf("error no output response has been programmed for your input");
	}
	return 0;
}//end of main function

