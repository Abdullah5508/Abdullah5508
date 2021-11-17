#include <stdio.h>

int main() {
float marks;
printf("please inter your marks:");
scanf("%f",&marks);
    
if(100>= marks && marks >=80){printf("gread:A+");}

else if(79>= marks && marks >=70){printf("gread:A");}

else if(69>= marks && marks >=60){printf("gread:B");}

else if(59>= marks && marks >=50){printf("gread:B-");}

else if(49>= marks && marks >=40){printf("gread:C");}

else if(39>= marks && marks >=33){printf("gread:D");}

else if(32>= marks ){printf("gread:F");}

else{printf("incorrect marks!!");}

    return 0;
}
