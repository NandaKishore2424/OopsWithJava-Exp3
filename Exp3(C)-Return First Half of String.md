# EX.NO 3(C): Return First Half of String

## DATE:
## Name: Nanda Kishore R
## Reg.no: 212222060157

## AIM:
To write a Java program that returns the first half of a string if its length is even, otherwise returns null.

## Algorithm:

1. Read the input string from the user.

2. Check if the length of the string is even.

3. If it is even, take the substring from index 0 to half of the length.

4. If the length is odd, set the output to null.

5. Print the output.



## Program:

```
import java.util.Scanner;
public class Assignment4 {
	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);  // Create a Scanner object
        String str = sc.nextLine();
		String output;
		if (str.length() % 2 == 0) {
			output = str.substring(0, str.length() / 2);
		} else {
			output = null;
		}
		System.out.println(output);
	}

}
```

## Output:
![image](https://github.com/user-attachments/assets/34d060a9-88bf-4bd9-a0ac-69ac622943a8)


## Result:
For the input "DogCat", the program prints "Dog", and for odd-length strings, it returns "null".
