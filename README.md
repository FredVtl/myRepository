class Dog {
  
  
	public Dog(int age) {
    
  }
  
  public void bark() {
  
    System.out.print("Woof");
  }
  
  public void wagTail() {
   
    System.out.print("Spike is happy");
  }
  
  public String dogName(){
    return "Spike";
  }
  
 
  public static void main(String[] args) {
    
    Dog spike = new Dog(6);
    
    spike.dogName();
    spike.bark();
    System.out.print(' ');
    Boolean goodDog = true;
      if (goodDog = true){
        spike.wagTail();
       }
	}

}
