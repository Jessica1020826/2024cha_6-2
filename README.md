# 2024cha_6-2
/******************************************************************************

Welcome to GDB Online.
  GDB online is an online compiler and debugger tool for C, C++, Python, PHP, Ruby, 
  C#, OCaml, VB, Perl, Swift, Prolog, Javascript, Pascal, COBOL, HTML, CSS, JS
  Code, Compile, Run and Debug online from anywhere in world.

*******************************************************************************/
#include <stdio.h>

int sum(int k);
int main() {
    int result = sum(10);
    printf("%d", result);
    return 0;
 }

int sum(int k) {
    if (k > 0) {
    return k +sum(k - 1);
    } else {
    return 0;
  }
}
