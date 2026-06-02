# Certification-course-of-Code-2-Career



#include <stdio.h>
 void main()
 {
     int Phy, Chem, Math, Eng,  Guj,tota,perc,pen,a,b,c;
    printf("Enter marks of Phy:");
    scanf("%d",&Phy);
    printf("Enter marks of Chem:");
    scanf("%d",&Chem);
    printf("Enter marks of Math:");
    scanf("%d",&Math);
    printf("Enter marks of Eng:");
    scanf("%d",&Eng);
    printf("Enter marks of Guj:");
    scanf("%d",&Guj);
    tota= Phy+Chem+Math+Eng+Guj;
    printf("total=%d",tota);
    
     perc = tota/500*100;
     pen=0;
    
if(a<18 || b<18 || c<18)
{
    printf("Fail");
} else{
    if(perc>80 && perc<100){
        printf("A Grade");
    }
    else if(perc>60 && perc<80){
        printf("BGrade");
    }
    else if(perc>40 && perc<60){
        printf("C Grade");
    }
    else if(perc>20 && perc<40){
        printf("D Grade");
    }
    }
  }

