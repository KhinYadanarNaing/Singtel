# Singtel

1.class Bird extends Animal {
 
boolean fly() {
 
System.out.println("I am flying");
return true;
 
}
boolean sing()
{
System.out.println("I am singing");
return true;
}
1a. I am going to use JUnit Test Case by using Eclipse IDE to do unit test.



2a,b. calss Duck extends Bird{
boolean sound()
{
System.out.println("“Quack, quack");
return true;
}
boolean swim()
{
System.out.println("I am swimming");
return true;

}
}

2c,d. class Chicken extends Bird
{
boolean sound()
{
System.out.println("Cluck, cluck");
return true;;
}
boolean fly()
{
System.out.println("I cannot fly");
return false;
}

}


3a
class Rooster extends Chicken
{
boolean sound()
{
System.out.println("Cock-a-doodle-doo");
return true;
}

}

3b. Chicken is parent class and Rooster is child class.
3c.Yes. Rooster class can stand without inheriting chicken class.

4a. public interface AnimaTestl()
{
public void sound();

}
class Parrot extends Bird implements AnimaTestl()
{
public boolean sound()
{
System.out.println("Woof, woof");
return true;

}

}

4b class Parrot extends Bird  implements AnimaTestl()
{
public boolean sound()
{
System.out.println("Meow");
return true;

}

}

4c.class Parrot extends Bird  implements AnimaTestl()
{
public boolean sound()
{
System.out.println("“Cock-a-doodle-doo");
return true;

}

}

4d. Answer is the same as 4a,4b,4c.

B 1. class Fish extends Animal
{
boolean sing()
{
System.out.println("I cannot sing");
return false;
}
boolean walk()
{
System.out.println("I cannot walk");
return false;

}
boolean swim()
{
System.out.println("I can swim");
return true;

}
}


B.2  class Shark extends Fish
{
String size="large";
String color="grey";
boolean eat()
{
System.out.println("Eat other fish");
return true;
}
}

  class Clownfish extends Fish
{
String size="small";
String color="colorful";
boolean joke()
{
System.out.println("Make jokes");
return true;
}
}


B.3 .a   class Dolphin
{
boolean swim(){
System.out.println("I am good swimmer");
return true;
}

B.3.b  I will use the common interface to avoid duplicating code.


D.1  class Butterfly extends Animal
{
boolean fly()
{
System.out.println("I can fly");
return true;
}
boolean sound()
{
System.out.println("I cannot make sound");
return false;
}
}

D.2.  class Caterpillar extends Animal
{
boolean fly()
{
System.out.println("I cannot fly");
return false;
}
boolean walk()
{
System.out.println("I can walk");
return true;
}
}

E  public class AnimalCount
{
int countFly=0;
int countSwim=0;
int countWalk=0;
int countSing=0;
Animal[] animals = new Animal[]{
 
new Bird(),
 
new Duck(),
 
new Chicken(),
 
new Rooster(),
 
new Parrot(),
 
new Fish(),
 
new Shark(),
 
new Clownfish(),
 
new Dolhpin(),
 
new Frog(),
 
new Dog(),
 
new Butterfly(),
 
new Cat()
};

public count()
{
 for(int i=0;i<animal.length;i++)
{
boolean a=animal[i].fly();
boolean b=animal[i].walk();
boolean c=animal[i].sing();
boolean d=animal[i].swim();
if(a){
countFly+=1;

}
if(b){
countWalk+=1;

}
if(c){
countSing+=1;

}
if(d){
countSwim+=1;

}



}
}
}
