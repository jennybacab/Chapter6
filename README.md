## Chapter6

# First Exercise

 #include <stdio.h>
 
#include<math.h>


int main(void) {

 double x1;
 
 double x2;
 
 double y1;
 
 double y2;

 printf("Please insert, in this order, coordenates x1, x2, y1 and y2\n");
 
 scanf("%lf %lf %lf %lf", &x1, &x2, &y1, &y2);
 
 double firstdiff = (x1-x2);
 
 double firstsquare = pow(firstdiff, 2);
 
 double seconddiff = (y1-y2);
 
 double secondsquare = pow(seconddiff, 2);
 
 double sum = firstsquare + secondsquare;
 
 double distance = sqrt(sum);
 
 printf("The distance between those points is %lf", distance); 
 

  return 0;
  
}

# Second Exercise

#include <stdio.h>

#include<math.h>


int main(void) {

  int numgrade;
  
 printf("This program converts numeric grades to letter grades. Please insert a numeric grade\n");
 
 scanf("%int", &numgrade);
 
 if (numgrade <=60){


    printf("Letter grade is F\n");
    
} else if (numgrade>=61 && numgrade<=70){

    printf("Letter grade is D\n");
    
} else if (numgrade>=70 && numgrade<=80){

    printf("Letter grade is C\n");
    
} else if (numgrade>=81 && numgrade<=90){

    printf("Letter grade is B\n");
    
} else if (numgrade>=90 && numgrade<=100){

    printf("Letter grade is A\n");
    
}

return 0;

}

# Third Exercise

#include <stdio.h>

int main(void){

float numgrade;

printf("This program converts numeric grades to letter grades. Please insert a numeric grade\n");

scanf("%f",&numgrade);


if (numgrade <=60){


    printf("Letter grade is F\n");
    
} else if (numgrade>=61 && numgrade<=63){

    printf("Letter grade is D-\n");
    
} else if (numgrade>=64 && numgrade<=67){

    printf("Letter grade is D\n");
    
} else if (numgrade>=68 && numgrade<=70){

    printf("Letter grade is D+\n");
    
} else if (numgrade>=71 && numgrade<=73){

    printf("Letter grade is C-\n");
    
} else if (numgrade>=74 && numgrade<=77){

    printf("Letter grade  is C\n");
    
} else if (numgrade>=78 && numgrade<=80){

    printf("Letter grade is C+\n");
    
} else if (numgrade>=81 && numgrade<=83){

    printf("Leter grade is B-\n");
    
} else if (numgrade>=84 && numgrade<=87){

    printf("Letter grade is B\n");
    
} else if (numgrade>=88 && numgrade<=90){

    printf("Letter grade is B+\n");
    
} else if (numgrade>=91 && numgrade<=93){

    printf("Letter grade is A-\n");
    
} else if (numgrade>=94 && numgrade<=97){

    printf("Letter grade is A\n");
    
} else if (numgrade>=98 && numgrade<=100){

    printf("Letter grade is A+\n");
    
}

return 0;

}
