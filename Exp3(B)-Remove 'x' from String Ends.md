# EX.NO 3(B): Remove 'x' from String Ends

## DATE:
## Name: Nanda Kishore R
## Reg.no: 212222060157

## AIM:
To write a Java program that removes the character 'x' from the start and end of a given string if present, and returns the modified string.

## Algorithm:

1. Read the input string from the user.

2. Check if the first character is 'x'. If yes, remove it by taking a substring from index 1 to end.

3. Check if the last character is 'x'. If yes, remove it by taking a substring from start to length-1.

4. Print the resulting string.



## Program:

```
import java.util.*;
public class Hiall {
	public static void main(String[] args) {
	    Scanner sc=new Scanner(System.in);
		String str =sc.nextLine();
		if (str.charAt(0) == 'x')
			str = str.substring(1, str.length());
		if (str.charAt(str.length() - 1) == 'x')
			str = str.substring(0, str.length() - 1);
		System.out.println(str);

	}
}
```

## Output:
![image](https://github.com/user-attachments/assets/fbf5d321-92e0-4dd0-aee4-e0d3860c56a4)


## Result:
The program removes 'x' characters from the beginning and end of the string if they exist, so for the input "xHix", it outputs "Hi" as expected.
