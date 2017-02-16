# panda-
#include <stdio.h> 
 
main() { 
    int a, b; 
    char d; 
    scanf("%d %c %d", &a, &d, &b); 
    switch (d) { 
        case '+': printf("%d", a + b); break; 
        case '-': printf("%d", a - b); break;
        case '/': printf("%d", a / b); break;
        case '*': printf("%d", a * b); break; 
    } 
}
