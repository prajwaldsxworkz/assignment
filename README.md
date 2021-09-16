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

