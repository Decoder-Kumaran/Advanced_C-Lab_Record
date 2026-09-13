# 19AI305 - Advanced C Programming - ODD - 2026

# IAPR - Module 7

# EXP.01 : C PROGRAM FOR ARRAY OF STRUCTURE TO CHECK ELIGIBILITY FOR THE VACCINE

## Aim:

To write a C program for array of structure to check eligibility for the vaccine person age above 6 years of age.

## Algorithm:

1.	Declare structure eligible with age (integer) and n (character array)
2.	Declare variable e of type eligible
3.	Input age and name using scanf, store in e
4. Conditions:
- If e.age > 6 { Print "Vaccine Eligibility: Yes" }
- Else { Print "Vaccine Eligibility: No" }
5.	Print details (e.age, e.n)
6.	Return 0
 
## Program:

```c

#include <stdio.h>

struct Person {
    int age;
    char name[50];
};

int main() {
    struct Person p[1];
    printf("Enter Your Age: ");
    if (scanf("%d", &p[0].age) == 1) {
        printf("\nEnter Your Name: ");
        scanf("%s", p[0].name);

        printf("Age:%d\n", p[0].age);
        printf("Name:%s\nvaccine:%d\n", p[0].name, p[0].age);

        if (p[0].age > 6) {
            printf("eligibility:yes\n");
        } else {
            printf("eligibility:no\n");
        }
    }

    return 0;
}

```


## Output:

<img width="687" height="250" alt="image" src="https://github.com/user-attachments/assets/6920024c-de5a-432d-8f2a-2505f2bcdba9" />

<img width="640" height="182" alt="image" src="https://github.com/user-attachments/assets/b4625d98-5ce4-4d69-aade-6d9edb895dc6" />


## Result:

Thus, the C program for array of structure to check eligibility for the vaccine person age above 6 years of age is verified successfully. 

*** 
