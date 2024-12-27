# Daily-DSA-Q

// In this quetion sort kth element and after kth element array sort by decreasing order 

import java.util.*;

public class Main
{
    public static void solve(int [] arr, int n , int k){
         if (n < k) {
        System.out.println("k greater than array size");
         
        }
        Arrays.sort(arr,0,k);
        Arrays.sort(arr,k,n);
        int i = k; 
        int j = n-1;
              while(i<j){
                int temp = arr[i];
                arr[i] = arr[j];
                arr[j] = temp;
                i++;
                j--;
             }

    }
	public static void main(String[] args) {
	   Scanner sc = new Scanner(System.in);
	   System.out.println("Enter array size");
	   int n = sc.nextInt();
	   int [] arr = new int [n];
	   for(int i=0; i<n; i++){
	       arr[i]= sc.nextInt();
	   }
	   System.out.println("Enter the size of k ");
	   int k = sc.nextInt();
	    solve(arr,n,k);
	    for(int i =0 ; i<n; i++){
	        System.out.print(arr[i]+" ");
	    }
	  
	}
}
