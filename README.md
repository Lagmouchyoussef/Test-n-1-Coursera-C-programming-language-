#include <stdio.h>
#include <stdlib.h>

int sum(int A, int B) {
    int S;
    S = A + B;

    return S;
}

int minimum(int A, int B) {
    if (A > B)
        return B;
    else
        return A;
}

int main() {
    int A, B;
    printf("Enter A: \n");
    scanf("%d", &A);
    printf("Enter B: \n");
    scanf("%d", &B);
    
    printf("The sum of %d and %d is: %d\n", A, B, sum(A, B));
    printf("The minimum of %d and %d is: %d", A, B, minimum(A, B));

    return 0;
}
