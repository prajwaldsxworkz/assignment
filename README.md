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





Assignment 15


package com.newmethod;

public class discount {
	public static void Discount (double value ,double discount) {
		double total=value-(value*discount);
		if(value==1000) {
			System.out.println("the discount is 10% and the discounted price is"+total);
		}
		else if(value==2000) {
			System.out.println("the discount is 20% and the discounted price is"+total);
		}
		else if(value==3000) {
			System.out.println("the discount is 25% and the discounted price is"+total);
		}
		else if(value>=3000) {
			System.out.println("the discount is 30% and the discounted price is"+total);
		}
		
		
	}

	public static void main(String[] args) {
		System.out.println("Welcome to the shop");
		discount.Discount(3500, 0.35);
		System.out.println("Thank you for  shopping with us ");
		
	}

}


Assignment 16



package com.newmethod;

public class vtu {
	public static double VtuResults() {
		return 75;
	}

	public static void main(String[] args) {
		System.out.println("Welcome to the VTU Official Website");
		double Results=VtuResults();
		System.out.println("Vtu reults"+Results);
		

	}


}



Asiignment 16



package com.newmethod;

public class temperature {
	public static double GetTemperature() {
		return 25.0;
	}

	public static void main(String[] args) {
		System.out.println("Welcome to the temperature forecast of today");
		double temp=GetTemperature();
		System.out.println("temperature"+temp);
		

	}

}



Asiignment 17


package com.newmethod;

public class billgenerator {
	
	
	public static void Billgenerator(int price , int quantity) {
		int total=price*quantity;{
			System.out.println("total is "+total)	;}
	}

	public static void main(String[] args) {
		
	System.out.println("Welcome");
	billgenerator.Billgenerator(15, 12);

	}

}



Assignment18

package com.newmethod;

public class Bank {
	String bankname;
String branch ;
String type;
String timings;
int staffcapacity ;
int noofaccounts;



public void Issuecheque() {
	System.out.println("Check issued");
}

public void Debitcard() {
	System.out.println("Debit card has been issued");
}
public void Creditcard() {
	System.out.println("Credit card has been issued");
}
public void withdraw() {
	System.out.println("Money withdraw has been succesfull");
}
public void accountcreate() {
	System.out.println("Account has been created");
}
}




Assignment 19


package com.newmethod;

public class ac {
	String model;
	String colour;
	String mounttype;
	int price;
	int toncapacity;
	int weight;
	

	
	public void turnon() {
		System.out.println("AC turned on");
	}
	
	public void Increase() {
		System.out.println("AC temperature incresed");
	}
	public void Recirculation() {
		System.out.println("AC Recirculation started ");
	}
	public void Decrease() {
		System.out.println("AC speed decreased");
	}
	public void turnoff() {
		System.out.println("AC speed turned off");
	}
}


Assignment 20


package com.newmethod;

public class Laptop {
	String model;
	String colour;
	String displaytype;
	String Os;
	int Ram;
	int Rom;
	int displaysize;
	int bittype;

	
	public void Start() {
		System.out.println("Laptop is showing start screen");
	}
	
	public void chrome() {
		System.out.println("Chrome browser is opened");
	}
	public void wifi() {
		System.out.println("Wifi turned on");
	}
	public void search() {
		System.out.println("Search bar opened");
	}
	public void shutdown() {
		System.out.println("Laptop turned off");
	}
}





Assignment 21




package com.newmethod;

public class car {
	String model;
	String colour;
	String door;
	int price;
	int displacement;
	int fueltankcapacity;
	int mileage;

	
	public void Dooropen() {
		System.out.println("Door opened");
	}
	
	public void enginestart() {
		System.out.println("engine has been started");
	}
	public void Gearshift() {
		System.out.println("Gear has been shifted");
	}
	public void Headlight() {
		System.out.println("Headlight turned on");
	}
	public void brake() {
		System.out.println("Break has been applied");
	}
}

