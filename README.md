1. Student Structure

#include <stdio.h>

struct Student {
    char name[50];
    int roll_no;
    float marks;
};

int main() {
    struct Student s;

    printf("Enter student name: ");
    scanf("%s", s.name);

    printf("Enter roll number: ");
    scanf("%d", &s.roll_no);

    printf("Enter marks: ");
    scanf("%f", &s.marks);

    printf("\nStudent Details\n");
    printf("Name: %s\n", s.name);
    printf("Roll Number: %d\n", s.roll_no);
    printf("Marks: %.2f\n", s.marks);

    return 0;
}
Output:
Enter student name: Ravi
Enter roll number: 101
Enter marks: 85.5

Student Details
Name: Ravi
Roll Number: 101
Marks: 85.50
2. Employee Structure

#include <stdio.h>

struct Employee {
    int id;
    char name[50];
    float salary;
};

int main() {
    struct Employee e;

    printf("Enter employee ID: ");
    scanf("%d", &e.id);

    printf("Enter employee name: ");
    scanf("%s", e.name);

    printf("Enter salary: ");
    scanf("%f", &e.salary);

    printf("\nEmployee Details\n");
    printf("ID: %d\n", e.id);
    printf("Name: %s\n", e.name);
    printf("Salary: %.2f\n", e.salary);

    return 0;
}
Output:
Enter employee ID: 201
Enter employee name: Kumar
Enter salary: 25000

Employee Details
ID: 201
Name: Kumar
Salary: 25000.00


3. Book Structure
#include <stdio.h>

struct Book {
    char title[50];
    char author[50];
    float price;
};

int main() {
    struct Book b;

    printf("Enter book title: ");
    scanf("%s", b.title);

    printf("Enter author name: ");
    scanf("%s", b.author);

    printf("Enter book price: ");
    scanf("%f", &b.price);

    printf("\nBook Details\n");
    printf("Title: %s\n", b.title);
    printf("Author: %s\n", b.author);
    printf("Price: %.2f\n", b.price);

    return 0;
}
Output:
Enter book title: CProgramming
Enter author name: Dennis
Enter book price: 450

Book Details
Title: CProgramming
Author: Dennis
Price: 450.00
