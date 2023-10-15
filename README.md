# REVERSE WORD
public class Reverseword {

	public static void main(String[] args) {
    
		String s ="MY name is Thanishka";
		String rev=" ";
		for(int i=s.length()-1;i>=0;i--) {
	 
			char ch=s.charAt(i);
			rev=rev+ch;
			
		}
		System.out.print("Reverse" + "of String is: "+rev);
	}

}
