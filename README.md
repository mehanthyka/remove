Aim:

To write a Java program to add , remove, retrieve an element in an Array.

Algorithm

Step 1 : Open Intelli J application or any other code editor.

Step 2 : Create an array with a name of your choice.

Step 3 : Using Scanner, Input a number or a element from the user.

Step 4 : Using for loop insert,remove,retrieve the input element at the end of the array.

Step 5 : Display the appended array in the terminal.

Program
```
import java.util.*;
class Main
{
    public static void main(String[] args) {
        ArrayList<String> al = new ArrayList<String>();
        System.out.println("Size of ArrayList: " + al.size());
        al.add("Jawa");
        al.add("KTM");
        System.out.println("Elements of first ArrayList: " + al);
        ArrayList<String> al2 = new ArrayList<String>();
        al2.add("R15");
        al2.add("RoyalEnfiled");
        al2.addAll(al);
        System.out.println("Elements of second ArrayList: " + al2);
        al2.remove("R15");
        System.out.println("Elements of ArrayList after deletion: " + al2);
        System.out.println("Size of ArrayList: " + al2.size());
        System.out.println("The element at 2nd index is: " + al2.get(2));
    }
}
```
Output:
  
<img width="505" alt="remove" src="https://github.com/mehanthyka/remove/assets/127507580/f6b7d05d-3fbf-4744-9751-fb2342a014e5">


Result
  
We have successfully created a Java program to add , remove, retrieve an element in an Array.
