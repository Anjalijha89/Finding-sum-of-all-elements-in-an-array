# Finding-sum-of-all-elements-in-an-array
package com.company;

public class sum_of_array {
    public static void main(String[] args){
        int arr[]={12,5,7,9,4,3,1};
        int sum=0;
        for(int i=0;i<arr.length;i++){
            sum=sum+arr[i];
        }
        System.out.println("Sum is :"+sum);
    }
}
