# ACD_JAVAB2_Session_2_Assignment_3
 package com.session2.pack;

public class ACD_JAVAB2_Session_2_Assignment_3 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		int num = 3;
		char ch,c;
		
		for (int i = 1; i <= num; i++) {
           ch='a';
            for (int j = num; j >= i; j--) {
                System.out.print(" ");
            }
            for (int m = 1; m <= i; m++) {
                System.out.print(ch);
                ++ch;
            }
            ch-=2;
            for(int l=1;l<i;++l)      // FOR LOOP FOR PRINTING ALPHABETS IN ASCENDING ORDER
            {
            System.out.print(ch);
            --ch;
            }
             System.out.println(" ");
        }
	
		}
	}
