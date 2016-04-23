---
layout: page
title:  "Quick Reference"
permalink: /ref_card/
categories: reference
mathjax: true
---

### printf

`printf(STRING, VARIABLES)`

Prints the string.  

```c
int foo = 0;
int bar = 10;

printf("The value of foo is %d, the value of bar is %d\n", foo, bar);
```

<br>

### scanf

`scanf(VAR TYPE, ADDRESS OF VARIABLE)`

Awaits user input and puts it into a specific address.

```c
int user_input;

scanf("%d", &user_input);
```

<br>


### if else ...

```c
if(condition) {
  EXECUTE CODE
} else if(condition) {
  EXECUTE CODE
} else {
  EXECUTE CODE
}
```

If a condition is true (condition != 0), then execute the code.  If the condition is not true, then move to the next else or if statement.  

```c
int foo = 20;
int bar = 10;

if((foo - bar) > 10) {
  printf("first condition");
} else {
  printf("second condition");
}
```

Because `foo - bar` is equal to 10.  The first condition is not true.  Thus we print `second condition`.


### variable types
TODO




### pointers

`VARTYPE *VARNAME;`

Pointers are a special type of variable in c that hold a value of a memory address.  It is possible to deference pointers using the dereference operator `*`.  This returns the value of the memory address pointed to by the pointer.  It is also possible to obtain the address of the pointer itself using the reference operator `&`.

```c
int n;
int *p;

n = 10;
p = &n;

printf("The value of n is %d", n);
printf("The value of n is %d", * p);

printf("The address of n is %p", &n);
printf("The address of n is %p", p);

printf("The address of p is %p", &p);
```
