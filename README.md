# substringrotation
check weather given string is present or not

public class StringRotation {
	
		
	    static boolean areRotations(String str1, String str2) 
	    { 
	       
	        return (str1.length() == str2.length()) &&  
	               ((str1 + str1).contains(str2)); 
	    } 
	  
	    
	    public static void main(String[] args) 
	    { 
	        String str1 = "waterboottle"; 
	        String str2 = "erboottlewat"; 
	  
	        if (areRotations(str1, str2)) 
	            System.out.println("Yes"); 
	        else
	            System.out.printf("No"); 
	    } 
	}
