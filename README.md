# JavaSE-26.One Dimension Arrays

In Java, a one-dimensional array is a collection of elements of the same data type, stored in contiguous memory locations. 

Each element in the array is accessed by its index, starting from 0.

Let me show you an example:

```java
public class OneDimensionalArrayExample {
    public static void main(String[] args) {
        // Declaring an array of integers
        int[] numbers = new int[5];

        // Initializing the array
        numbers[0] = 10;
        numbers[1] = 20;
        numbers[2] = 30;
        numbers[3] = 40;
        numbers[4] = 50;

        // Accessing elements of the array
        System.out.println("Element at index 0: " + numbers[0]);
        System.out.println("Element at index 2: " + numbers[2]);

        // Modifying an element
        numbers[1] = 25;
        System.out.println("Modified element at index 1: " + numbers[1]);

        // Iterating through the array
        System.out.println("Elements in the array:");
        for (int i = 0; i < numbers.length; i++) {
            System.out.println("Element at index " + i + ": " + numbers[i]);
        }
    }
}
```

In this example, we declare an array of integers named numbers with a size of 5.

We initialize the elements of the array and then access and modify them using their indices.

Finally, we use a loop to iterate through all elements of the array.
