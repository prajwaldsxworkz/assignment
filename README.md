# assignment1
public class sum {

	public static void main(String[] args) {
		int sum=0;
		for(int i=0;i<30;i++) {
			sum=sum+i;
			System.out.println(sum);
		}
		

	}

}


assignment 2
package com.evenno;

public class even {

	public static void main(String[] args) {
		int number=50;
				for (int i=1;i<=number;i++) {
					if (i % 2 == 0) {
						System.out.println(i+"");
					}
				}
	}
}	

assignment 3

package com.odd;

public class odd {

	public static void main(String[] args) {
		int number=50;
		for (int i=1;i<=number;i++) {
			if (i % 2 != 0) {
				System.out.println(i+"");
			}
		}
}
}	




assignment 4
package com.div;

public class divby3 {

	public static void main(String[] args) {
		int number=50;
		for (int i=1;i<=number;i++) {
			if (i % 3== 0) {
				System.out.println(i+"");
			}
		}
}
}	

assignment 6
package com.sumno;

public class sumno {

	public static void main(String[] args) {
		 int number[]= {3,6,9,12,15,18};
int sumamt=0;
for(int i=0;i<=number.length;i++) {
	sumamt=sumamt+number[i];
	System.out.println(sumamt);
}
	}

}

assignment 7
package com.even;

public class even {

	public static void main(String[] args) {
		 int number[]= {3,6,9,12,15,18};
		 int sumamt=0;
		 for(int i=0;i<=number.length;i++) 
		 	if(i%2==0) {
			 sumamt=sumamt+number[i];
		 	System.out.println(sumamt);
		 }

	}

}


assignment 8

ackage com.odd;

public class odd {

	public static void main(String[] args) {
		int number[]= {3,6,9,12,15,18};
		 int sumamt=0;
		 for(int i=0;i<=number.length;i++) 
		 	if(i%2!=0) {
			 sumamt=sumamt+number[i];
		 	System.out.println(sumamt);
		 }


	}

}



assignment 9

package div3;

public class div3 {

	public static void main(String[] args) {
		int number[]= {3,6,9,12,15,18};
		 int sumamt=0;
		 for(int i=0;i<=number.length;i++) 
		 	if(i%3==0) {
			 sumamt=sumamt+number[i];
		 	System.out.println(sumamt);
		 }

	}

}


assignment 10

public class fan {


		public static void TurnonFan() {
			System.out.println("fan switched on");
		}
		public static void Increase() {
			System.out.println("fan speed increased");
		}
		public static void Decrease() {
			System.out.println("fan speed decreased");
		}
		public static void TurnoffFan() {
			System.out.println("fan switched off");
		}
		public static void main(String[]args) {
			System.out.println("Enter near switch in the Room");
			fan.TurnonFan();
			fan.Increase();
			fan.Decrease();
			fan.TurnoffFan();
			System.out.println("get away from  room");
			
		}
	}




Assignment 11

package com.accontrolstatement;

public class ac {
	public static void TurnonAC() {
		System.out.println("AC switched on");
	}
	public static void Increasetemp() {
		System.out.println("AC temperature increased");
	}
	public static void Decreasetemp() {
		System.out.println("AC temperature decreased");
	}
	public static void TurnoffAC() {
		System.out.println("AC switched off");
	}
	public static void main(String[]args) {
		System.out.println("Enter near switch in the Room");
		ac.TurnonAC();
		ac.Increasetemp();
		ac.Decreasetemp();
		ac.TurnoffAC();
		System.out.println("get away from  room");


		
	}

}



Assignment 12
public class amazon
	package com.amazoncontrolstatement;



public class amazon {
		public static void veiwproduct() {
			System.out.println("Your product is veiwed!!");
		}
		public static void Addtocart() {
			System.out.println("Added to thee cart successfully!!!");
		}
		public static void Orderstatus() {
			System.out.println("order status veiwed!!!");
		}
		public static void Payment() {
			System.out.println("Payment done and order placed");
		}
		public static void main(String[]args) {
			System.out.println("Login to the Amazon");
			
			


			amazon.veiwproduct();
			amazon.Addtocart();
			amazon.Orderstatus();
			amazon.Payment();
			System.out.println("Logout to the Amazon");
		}

	}


}










Assignment 13



package com.phonepecs;

public class Phonepe {
	public static void login(String UserName, String Password);{
		System.out.println("Logged in successfully with matched username and password");	}
	
	
public static void MobileRec(String Operater, String Phoneno, int Amount ) {
	String OP= "BSNL";
	String PN="9456388907";
	int AT=50;
	if(OP==Operater && PN==Phoneno && AT==Amount) {
		System.out.println("Mobile recharged Succesfully"+Phoneno);
	}
	else {
		System.out.println("Mobile recharge Failed");
	}
	public static void Electricity(String Board, String CustomerID, int Amount ) {
		String BD= "MESCOM";
		String CD="9456388987";
		int AT=500;
		if(BD==Board && CD==CustomerID && AT==Amount) {
			System.out.println("Electricity bill recharged Succesfully"+CustomerID);
		}
		else {
			System.out.println("Electricity bill recharge Failed");
		}
		
		public static void Water(String Board, String CustomerID, int Amount ) {
			String BD= "CAUVERY";
			String CD="9456688987";
			int AT=800;
			if(BD==Board && CD==CustomerID && AT==Amount) {
				System.out.println("Water bill recharged Succesfully"+CustomerID);
			}
			else {
				System.out.println("Water bill recharge Failed");
			}
			public static void DTH(String Operater, String CustomerID, int Amount ) {
				String OR= "D2H";
				String CD="9556688987";
				int AT=560;
				if(OR==Operater && CD==CustomerID && AT==Amount) {
					System.out.println("DTH bill recharged Succesfully"+CustomerID);
				}
				else {
					System.out.println("DTH bill recharge Failed");
				}
				
				
				public static void MoneyTransfer(String Name, String AccNo, int Amount ) {
					String NA= "CAUVERY";
					String AN="9456688987";
					int AT=1800;
					if(NA==Name && AN==AccNo && AT==Amount) {
						System.out.println("Money transferred Succesfully"+AccNo);
					}
					else {
						System.out.println("Money transfer  Failed!!");
					}
		
	public static void main(String []args) {
		System.out.println("Enter to Phonepe application");
		Phonepe.login(null, null);
		Phonepe.MobileRec(null, null, 0);
		Phonepe.Electricity(null, null, 0);
		Phonepe.Water(null, null, 0);
		Phonepe.DTH(null, null, 0);
		Phonepe.MoneyTransfer(null, null, 0);
		System.out.println("Logout from Phonepe");
		}
		
	}
}







Assignment 14 




package com.phonepecs;

public class ATM {
	public static void Insert() {
		System.out.println("Insert the card correctly");
	
	}
	public static void CheckBal(String password, int amount) {
		String PW="1234";
		int AT=500;
		if(PW==password && AT==amount) {
			System.out.println("Display balence"+amount);
		}
		else {
			System.out.println("Wrong password!!");
		}
		
		public static void Withdrawl(String password, int amount,int withamt) {
			String PW="1234";
			int AT=999;
			int WA=500;
			if(PW==password && AT==amount && AT>WA) {
				System.out.println("Withdrawn the amount successfully"+withamt);
				
			}
			else {
				System.out.println("Withdrawing the amount not possible ");
			}
			public static void main(String[]args) {
				System.out.println("Enter the ATM room");
				ATM.CheckBal(1234, 500);
				ATM.Withdrawl(1234, 999, 500);
				System.out.println("Exit from the room ");
			}
				
			
	}

}

