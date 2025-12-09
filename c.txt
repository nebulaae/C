   1) Looking at the question:

**The French language is an example of:**

- [ ] a programming language  
- [ ] a machine language  
- [x] a natural language  

French is a human language spoken by people, so it is a **natural language**, not a programming or machine language.   2) The correct way to make comments in C is:

a) */ my comment /*
b) /* my comment */
c) # my comment #
d) <!— my comment —>
 Answer =  `/* ... */` for multi-line comments

 3) int var;

var = 3;
var = var * var;
/* var = var + var; */
/*
var = var / var;
var = var % var;
*/
var = var - 1;

Answer = 8
  4) #include <stdio.h>

int main(void)
{
    int a, b, c;

    a = -1;
    b = 2;

    if(a)
          a--;
    if(b)
           b++;

    c = a * b;
    
    printf("%d", c);
    return 0;
}

Answer = -6 
 5) #include <stdio.h>

int main(void)
{
    int i, j;
    i = 1; j = 1;

    while(i > 16) {
          i += 4;
           j++;
    }
    printf("%d", j);
    return 0;
}

Answer = 1   6) #include <stdio.h>

int main(void)
{

    k = !i | j;
    k = !k;

    printf("%d", k);
    return 0;
}

Answer = 0   7) #include <stdio.h>

int main(void)
{

    int i = 1, j = -1;

    for(;;) {
          i *= 2;
           j++;

           if(i >= 16)
            break;
    }

        printf("%d",j);
    return 0;
} 

Answer = 3   8) #include <stdio.h>

int main(void)
{

    int i = 2, j = 0;

    switch(i + 5) {
    case 1: j++;
    case 2: j++;
    default:j = 5;
    case 0: j++; break;
    }

    printf("%d",j);
    return 0;
}
 Answer = 6  8) #include <stdio.h>

int main(void)
{
    int i, t[4];

    t[3] = 0;

    for(i = 1; i >= 0; i--)
          t[i] = t[3] * i;

    printf("%d",t[1]);
    return 0;
}
 Answer = 0


9) Which of the following examples are legal ways of initializing arr array?

a) int arr[3] = {1, 2, 3};
b) int arr{3} = [1, 2, 3];
c) int arr{3} = {1, 2,  3};
d) int arr[] = {1, 2, 3};
 Answer = int area [] = {1, 2, 3};  
int area [3] = {1, 2, 3}; 

10) #include <stdio.h>

int main()
{
	int arr[5] = {1, 2, 3, 4, 5};
	arr[1] = 0;
	arr[3] = 0;

for(i = 1; i >= 0; i--)
	t[i] = t[3] * i;

for(int i = 0; i < 5; ++i) {
	printf("%d ", arr[i]);
}
return 0;

return 0;
} 
Answer = 1 0 3 0 5 
 11) #include <stdio.h>

void fun(int a, int b)
{
    printf("%d", b);
    printf("%d", a);
}
int main()
{
    int arr[] = {1, 2, 3, 4};
    fun(arr[1], arr[3]);
      return 0;
}

Answer = 42   12) #include <stdio.h>
#include <string.h>

int main(void)
{
    char s[5] = "ABC";

    strcat(s + 1, "ABC");

        printf("%d", s[0] - s[1]);
      return 0;
}

Answer = -1  
13) #include <stdio.h>

int main ()
{
    int* a, b;
    b = 1;
    a = &b;
    b = 2;

    printf("%d\n", b);
    printf("%d", *a);

      return 0;
}

Answer = 2  2


14) #include <stdio.h>

int fun(int a) {
    return a + 1;
}

int main()
{
    int a = 0;

    fun(1);
    printf("%d", *a);
}

Answer = compile error 
 15) What is the value of the following integer literal? \013
 Answer = 11 
 16) 0x22 in hexadecimal:  Answer = 34

 17) #include <stdio.h>

int main(void)
{
    int i = 4, j = 1;

    while(j > 0) {
          i /= 2;
           printf("%d", i);
    }

    printf("%d", i + j);
    return 0;
}

Answer = 21000… Alternative answer = 22222…  18) #include <stdio.h>

int main(void)
{

    int i = -1, j = 3;

    for(j > 0; j; j--)
           i *= 2;

    printf("%d", i + j);
    return 0;
}

Answer = -8 

19) #include <stdio.h>

int main(void)
{
    int i = -3, j = 0;

    for(i++; i++; i++)
          j--;

    printf("%d", i - j);
    return 0;
}

Answer = 2 Alternative Answer = 1 
 20) #include <stdio.h>

int main(void)
{
    int i = 2, j = 1, k;

    k = i >> j;
    k <<= i;

    printf("%d", k);
    return 0;
}

Answer = 4


21) #include <stdio.h>

int main(void)
{
    int i = 3;
    int j = i - 1 / i;

           switch(i - j) {
    case  1: j--;
           case  2: j++;
           case  0: j++; break;
           default: j = -1;

    printf("%d", --j);
    return 0;
}

Answer = 3 
 22) #include <stdio.h>

int fun() {
    int a;
    return ++a;
}

int main()
{
    printf("%d", fun());
    return 0;
}

Answer = Undefined behavior 

23) #include <stdio.h>

int fun(int a=1) {
    return a;
}

int main() {
    printf("%d", fun(2));
}

Answer = Compile Error 

24) Which of the following are legal variable name in the C language?

a) 01myvariable
b) MyV@riable
c) My_Variable
d) _myVariable
E) MyVariableIsTheLongestvariable

Answer = My_Variable, MyVariableIsTheLongestvariable, _myVariable 
 25) #include <stdio.h>

int fun(int a) {
    int b = 1;
    return a << b;
}
int main()
{
    int x;

    scanf("%d", &x);

    printf ("%d", fun(x));

    return 0;
}  Answer = Input 5 --> Output 10;   Input 3 --> Output 6 
 26) Which of the following are valid floating-point literals? 
Select two answers.
a) .1
b) 1
c) -1
d) -0.1

Answer = .1 ; -0.1 
 27) What is the value of the var variable after the execution of the following snippet of code:
int var;
var = -1;
var = var + 1;
var = var + var;  Answer = 0 
 28) int var;

var = 9;
var = var / 2; 
Answer = 4   29) #include <stdio.h>

int main(void)
{
    int i, j, k;

    i = 1;
    j = 3;

    int x;

    if(j)
           j--;
    else
           i++;
    if(i) 0;
           i--;
    else
           j++;
       k = i + j;

    printf("%d", k);
    return 0;
}

Answer = 2 
30)  int area[] = {1, 2, 3}
int area[3] = {1, 2, 3}
