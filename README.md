# Test
This is my first Repository
<br>
Author - Anamul Haque



#include <stdio.h>

int main() {

    int marks[5];
    int total = 0;
    float average;
    printf("Enter marks of 5 students:\n");

    for(int i = 0; i < 5; i++) {
        printf("Student %d: ", i + 1);
        scanf("%d", &marks[i]);
        total += marks[i];
    }
    average = total / 5.0;
    printf("\n--- Student Report ---\n");
    for(int i = 0; i < 5; i++) {
        printf("Student %d Marks = %d\n", i + 1, marks[i]);
    }
    printf("\nTotal Marks = %d\n", total);
    printf("Average Marks = %.2f\n", average);
    return 0;
}
