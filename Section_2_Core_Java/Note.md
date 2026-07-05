# Notes for Section 2


1. Java is a **Strongly Typed Language** (Whatever variables you create, needs a data type which denotes the memory that the variable can occupy)
2. Int - (Integer) - Which can store positive 
   and negative whole number (-1, 0, 1, 2 ,3)

3. DataTypes
   1. Primitive
      1. Integer -> Byte, Short, Int, Long
      2. Float -> (1.5, 3.2)
      3. Character -> (a,b)
      4. Boolean -> True/False

4. This **Integer** Datatype will have 4 diff 
   sizes 
      1. Byte -> 1 Byte (-123 to 127)
      1. Short -> 2 Bytes
      2. Int -> 4 Bytes
      3. Long -> 8 Bytes

5. Float -> 4 Bytes, Double -> 8 Bytes (Float 
   will have a limited precision set here 
   whereas double will have a maximum precision)
```java
package Section_2_Core_Java;

public class DataTypes {
   public static void main(String[] args) {
      // If you didn't assign it as 3.2f then
      // it will be considered as double,
      // asking you to change the variable to
      // double
      float marks = 3.2f;
      System.out.println(marks);
   }
}
```