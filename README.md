#include <stdio.h>
int main() {
    int n, i, a = 0, b = 1, c;
    printf("Enter the number of terms: ");
    scanf("%d", &n);
    printf("Fibonacci Series: ");
    for (i = 1; i <= n; i++) {
        printf("%d ", a);
        c = a + b;
        a = b; // Move 'b' to 'a'
        b = c; // Move 'c' to 'b'
    }
    return 0;
}
