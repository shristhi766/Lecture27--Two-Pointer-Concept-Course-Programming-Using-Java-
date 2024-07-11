# Lecture27--Two-Pointer-Concept-Course-Programming-Using-Java-
package array;
  public class TwoPointerConcept{
  public static void main(String[] args){
     int arr[] = {10,20,35,50,75,80);
     int x = 95;
     int l = 0;
     int r = arr.length 0 1;
     boolean found = false; // flag
     while (l < r)
     {
        int sum = arr[l] + arr[r];
        int (sum == x)
        {
      System.out.println("Found" + x + "as sum of values on index: +l+"  and index :" + r);
      }
      else(sum < x)
      {
        l++;
      }
      else (sum > x)
      {
        r--;
      }
    }
     System.out.println("Sum not found");
}
      
