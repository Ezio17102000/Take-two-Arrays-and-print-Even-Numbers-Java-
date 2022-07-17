# Take-two-Arrays-and-print-Even-Numbers-Java-

import java.util.*;

class Main

{

public static void main(String args[])

{

Scanner sc = new Scanner(System.in);

System.out.println("Enter the size of the array 1 ");

int n = sc.nextInt();

System.out.println("Enter the size of the array 2");

int m = sc.nextInt();

int[] A = new int[n];

int[] B = new int[m];

System.out.println("Enter the elements of the array");

for(int i=0;i<n;i++)

{

A[i]=sc.nextInt();

}

System.out.println("Enter the elements of the array");

for(int j=0;j<m;j++)

{

B[j]=sc.nextInt();

}

for(int i=0;i<n;i++)

{

for(int j=0;j<m;j++)

{

if (A[i]==B[j])

{

if(A[i]%2==0)

System.out.println("Same even elements are:" +A[i]);

}

}

}

}

}
