import java.util.*;
import java.util.Scanner;
class removespace {  
    public static void main(String[] args) {
        Scanner input=new Scanner(System.in);
        System.out.println("Enter the string:");  
        String str =input.nextLine();  
        String empty="";
        String noSpaceStr = str.replaceAll("\\s", "");   
        System.out.println(noSpaceStr);  
       
        char[] strArray = str.toCharArray();  
        StringBuffer stringBuffer = new StringBuffer();  
        for (int i = 0; i < strArray.length; i++) {  
            if ((strArray[i] != ' ') && (strArray[i] != '\t')) {  
                stringBuffer.append(strArray[i]);  
            }  
        }  
        String noSpaceStr2 = stringBuffer.toString();  
        System.out.println(noSpaceStr2);  
    }  
}
