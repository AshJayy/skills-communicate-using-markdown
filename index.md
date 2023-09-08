# This is H1
## This is H2
###### This is H6
This is normal text

![Image of Github Listocat](https://octodex.github.com/images/orderedlistocat.png)

```C
#include <stdio.h>
#define MAX 7

void bubbleSort(int arr[MAX], int size){
    for(int i=0; i<size; i++){
        for(int j=0; j<size; j++){
            if(arr[j] > arr[j+1]){
                int temp = arr[j+1];
                arr[j+1] = arr[j];
                arr[j] = temp;
            }
        }
    }
}

int main(){
    int arr[MAX] = {250, 150, 350, 200, 300};
    bubbleSort(arr, 5);
    printf("Sorted list of fruits:\n");
    printArray(arr, 5);
    return 0;
}
```
