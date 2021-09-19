# Print

    printf("Hello World");

# Variable and Data type

1. Syntax

    - type variable = value;

2. Example

    - Data type: char, int, float, double, bool...
      int myNum = 5;
      double myFloatNum = 5.99;  
       char myLetter = 'D';

        printf("%d\n", myNum);
        printf("%lf\n", myFloatNum);
        printf("%c\n", myLetter);

# Operators

1.  Syntax
    ( + - _ / %
    += -= _= /=
    ++ --
    == >= <= !=
    ...

        logical
            && || !

    )

2.  Example

    -   int x = 100 + 50;
        printf("%d\n", x);
        x += 10;
        printf("%d\n", x);

    -   int a = 7;
        int b = a % 5;
        printf("%d", b);

    -   int a = 1;
        a++;
        printf("%d", a);

# User input

1. example
   int a;
   printf("nhap a: ");
   scanf("%d", &a);
   printf("%d", a);

# If else

1. Syntax
   if(...) {
   //my code
   }else {
   //my code
   }

2. example
   int a = 9;
   if( a == 2) {
   printf("a == 2");
   }else {
   printf("a != 2");
   }

3. exercise

    - Cho 2 số nguyên a và b, so sánh 2 số

        int a, b;
        printf("nhap a: ");
        scanf("%d", &a);
        printf("nhap b: ");
        scanf("%d", &b);

        if(...){
        printf(...);
        } else if (...) {
        printf(...);
        }else {
        printf(...);
        }

    - Cho số nguyên a, kiểm tra a là số chẵn hoặc lẽ

        int a;
        printf("nhap a: ");
        scanf("%d", &a);

        if(...){
        printf(...);
        }else {
        printf(...)
        }

    - Giải phương trình bậc nhất: ax + b = 0

        int a, b;
        printf("nhap a: ");
        scanf("%d", &a);
        printf("nhap b: ");
        scanf("%d", &b);

        ....

# Loop

1. Syntax

    - for (...; ...; ...){

        }

    - while(...) {

        }

    - do {

        }
        while(....)

2. Example:

    - for

        for (int i = 0; i < 5; i++) {
        printf("%d\n", i);
        }

    - while

        int i = 0;
        while (i < 5) {
        printf("%d\n", i);
        i++;
        }

    - do while

        int i = 0;
        do {
        printf("%d\n", i);
        i++;
        }
        while (i < 5);

    - break
      for (int i = 0; i < 5; i++) {
      if(i == 2) {
      break;
      }
      printf("%d\n", i);
      }

3. Exercise

    - In ra các số nguyên dương chẵn nhỏ hơn n

        int n;
        printf("nhap n: ");
        scanf("%d", &n);
        for(... ;... ; ...){
        ...
        }

    - Tính trung bình cộng các số nguyên dương trong khoảng
      0 < x < n

        int n;
        printf("nhap n: ");
        scanf("%d", &n);

        while(...) {
        ...
        }
        printf(...);

    - In bảng cửu chương rút gọn

        2 4 6 8 10 12 14 16 18 20  
         3 6 9 12 15 18 21 24 27 30
        4 8 12 16 20 24 28 32 36 40
        5 10 15 20 25 30 35 40 45 50
        6 12 18 24 30 36 42 48 54 60
        7 14 21 28 35 42 49 56 63 70
        8 16 24 32 40 48 56 64 72 80
        9 18 27 36 45 54 63 72 81 90

        for( ...; ...; ...){
        for (...; ...; ...){
        printf(...);
        }
        printf(...);
        }

# Scope

1. Example
   int a = 2;
   printf("%d", a);
   {
   int b = 0;
   }
   printf("%d", b);

# Array

1. Example  
   int myArr[5] = {1, 3, 5, 7, 9};

    printf("%d", myArr[0]);

2. Exercise

    - Khai báo một mảng số nguyên có n phần tử, nhập giá trị cho phần tử của mảng và in mảng ra.

        int n;
        printf("nhap n: ");
        scanf(...);
        int A[...];

        for(...; ....; ....) {
        printf("nhap phan tu thu %d: ", ....);
        scanf("%d", &A[...]);
        }

        for(...; ...; ...) {
        printf("%d \t ", A[...]);
        }

    - Cho một mảng số nguyên A có n phần tử, tính tổng các số nguyên âm có trong mảng

        int n;
        printf("nhap n: ");
        scanf(...);
        int A[...];

        for(...; ...; ....) {
        printf("nhap phan tu thu %d: ", ....);
        scanf("%d", &A[...]);
        }

        for(...; ...; ...) {
        ...
        }

        printf("%d", ...);

    - Cho một mảng số nguyên A có n phần tử, tìm giá trị lớn nhất có trong mảng.

        int n;
        printf("nhap n: ");
        scanf(...);
        int A[...];

        for(...; ...; ....) {
        printf("nhap phan tu thu %d: ", ....);
        scanf("%d", &A[...]);
        }

        for(...; ...; ....) {
        ...
        }
        printf("%d", ...);
