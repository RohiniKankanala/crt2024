Write a program to sum of even and odd elements in an array.

Input Format

Integer corresponds to the size of the array. Read n elements line by line

Constraints

1<=n<=10^7

Output Format

Print Odd sum Print Even sum

Sample Input 0

3
31
28
13
Sample Output 0

44
28
Sample Input 1

6
12
100
28
31
22
45
Sample Output 1

76
162

#include <stdio.h>
int main() {
    int n;
    scanf("%d", &n);

    long long sum_odd = 0;
    long long sum_even = 0;

    for (int i = 0; i < n; i++) {
        int element;
        scanf("%d", &element);

        if (element % 2 == 0) {
            sum_even += element;
        } else {
            sum_odd += element;
        }
    }

    printf("%lld\n", sum_odd);
    printf("%lld\n", sum_even);

    return 0;
}
