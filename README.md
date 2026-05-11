# Sentencia
Ejercicio 1
#include <iostream>  
int main() 
{     
    int 1 = 2;     
    if (1 > 0 )     
   {
             printf("1 es positivo");  
   }   
   else if (1< 0)
   {         printf("1 es negativo");     
   }     
   else if (1 == 0)     
   {         
              printf("1 es cero");     
    }   
}   


Ejercicio 2
int 1 = 9; 
int 2 = 13; 
if (1 < 2) 
{
     printf(" 2 es mayor que 1");  
} 
else if (2 > 1) 
{
     printf("1 es mayor que 2"); 
} 
else if (1 == 2) 
{ 
    printf("1 es igual a 2"); 
}


Ejercicio 3
int 1 =16;     
int 2 = 27;     
int 3 =45;     
if (1>2 && 1>3)     
{
         printf("%d",1);     
}     
else if (2>1 && 2>3)     
{ 
        printf("%d",2);     
}    
 else if (3>1 && 3>2)    
 { 
        printf("%d"3);     
} 


Ejercicio 4
int 1=28; 
if (1%2==0) 
{
     printf("1 es par"); 
} 
else 
{ 
    printf("1 es impar"); 
}


Ejercicio 5
int 1 = 19;       
if (20 >= 1 && 1 >= 18)  
{ 
         printf("A");  
}      
  else if (17>=1 && 1>=14)      
  { 
         printf("B");      
  }      
  else if(13>=1 && 1>=12)     
  { 
         printf("C");      
  }      
  else if (12 > 1)     
  { 
         printf("D");     
  }


Ejercicio 6
int 1 = 67; 
if (1 < 60) 
{
     printf("Ok"); 
} 
else if (1 >= 60 && x <= 65) 
{ 
    printf("Advertencia"); 
} 
else if (1 >= 66 && x <= 75) 
{
     printf("Multa media"); 
}
 else if (1 > 75) 
{ 
    printf("Multa alta"); 
}


Ejercicio 7
int 1 = 9;  
int 2 = 4;      
char op = '*';       
if (op == '+')  
{
      printf("1+2=%d\n", 1 + 2);  
}  
else if (op == '-')  
{ 
     printf("1-2=%d\n", 1 - 2);   
}  
else if (op == '*')  
{
      printf("1*2=%d\n",1 * 2);   
}  
else if (op == '/' && 2 !=0)  
{ 
     printf("1/2=%d\n", 1 / 2);  
}  
else  
{ 
     printf("ERROR")


Ejercicio 8
int dias = 10; 
int km = 20; 
int costo; 
char tipo = 'M'; 
if (tipo == 'G') 
{  
costo = 30 * dias + 40 * km;    
} 
else if (tipo == 'M') 
{  
costo = 20 * dias + 30 * km;  
} 
else if (tipo == 'C')
{  
costo = 15 * dias + 20 * km;  
}  
else {  printf("tipo de auto no válido");  
} 
printf("costo=%d\n", costo);
