# EX.NO 3(A): Convert Char Array to String

## DATE:
## Name: Nanda Kishore R
## Reg.no: 212222060157

## AIM:
To write a Java program that reads characters stored in arrays and displays them as strings.

## Algorithm:

1. Declare character arrays with given characters.

2. Convert each character array to a String using the String constructor.

3. Print the converted strings.

## Program:

```
class prog{
    public static void main(String[] args)
    {
        char a[]={'j','a','v','a'};
        char b[]={'s','t','r','i','n','g','s'};
        char c[]={'e','x','a','m','p','l','e'};
        String a1=new String(a);
        String b1=new String(b);
        String c1=new String(c);
        System.out.println(a1);
        System.out.println(b1);
        System.out.println(c1);
    }
}
```

## Output:
![image](https://github.com/user-attachments/assets/f706f220-cba3-4df8-90bb-72e6601f0ffd)


## Result:
The program successfully converts the character arrays into strings and displays them as "java", "strings", and "example" respectively.
