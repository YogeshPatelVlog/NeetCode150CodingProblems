import java.util.HashSet;

public class containsDuplicate {
    public static boolean containsDuplicates(int [] nums){


        // 1. Brute Force approach tc: o(n2)
    //     for(int i = 0; i<nums.length; i++){
    //         for(int j = i+1; j<nums.length; j++){
    //             if (nums[i] == nums[j]) {
    //                 return true;
    //             }
    //         }
    //     }
    //     return false;
    // }

// Best Appproach 
        HashSet<Integer> values = new HashSet<>();
        for(int num : nums){
            if(values.contains(num)){
                return true;
            }
            values.add(num);
        }
        return false;
    }
    public static void main(String[] args) {
        int [] nums = {1,2,3,4};
        System.out.println(containsDuplicates(nums));
    }
}
