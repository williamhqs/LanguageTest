1. Will the program compile successfully?


```
#include<stdio.h>
#define X (4+Y)
#define Y (X+3)

int main()
{
    printf("%d\n", 4*X+2);
    return 0;
}
```
	A.	Yes
	B.	No
    
Can't compile. X undeclared.

2. What will be the output of the program?	

	```
	#include<stdio.h>
	int main()
	{
	    int i=2;
	    printf("%d, %d\n", ++i, ++i);
	    return 0;
	}
	```
GCC：4，4
Windows: 3, 4
3. Is this okay? What happens?
	
	```
	#include<stdio.h>
	int main()
	{
	    printf("%p\n", main());
	    return 0;
	}
    ```
    
    Answer: ```segmentation fault```
