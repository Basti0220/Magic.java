# Magic.java
Magic Math CodeAcademy

public class Magic {
      /*Magic Math this code will take any integer number and do some math giving always the same ouput without!! Magic!!*/ 
	public static void main(String[] args) {
      // myNumber is the Original Number!!!
      int myNumber = 8;
      int magicNumber = myNumber * myNumber;
      magicNumber += myNumber;
      magicNumber /= myNumber;
      magicNumber += 17;
      magicNumber -= myNumber;
      magicNumber /= 6;
      System.out.println(magicNumber);
	}
}
