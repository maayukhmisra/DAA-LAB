#include<stdio.h>

int main() {
    int arr[10] = {1,2,3,4,5,6,7,8,9,10};
    int rotate;
    int n = sizeof(arr)/sizeof(arr[0]);

    printf("\nEnter rotation count: ");
    scanf("%d", &rotate);

    rotate = rotate % n; 

    int temp[n];

    for(int i = 0; i < rotate; i++) {
        temp[i] = arr[n - rotate + i];
    }

    for(int i = rotate; i < n; i++) {
        temp[i] = arr[i - rotate];
    }

    for(int i = 0; i < n; i++) {
        arr[i] = temp[i];
    }

    for(int i = 0; i < n; i++) {
        printf("%d ", arr[i]);
    }

    return 0;
}
