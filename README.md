object Hello{
    def main(args: Array[String]){
        val sen=scala.io.StdIn.readLine()
        var n=sen.length()
        if(n<4)
        println("in upper case "+sen.toUpperCase())
        else
        println("in upper case "+sen.takeRight(4).toUpperCase())
    }
}



Que 9: -
importscala.collection.immutable.ListMap
objecthello {
println("Kushagra Trivedi\nDS\n2015079");
defmain(args: Array[String]): Unit = {
valmapIm = Map("Bill"->56,"Jonny"->87, "Tommy"->11, "Cheena"->14);
valres = ListMap(mapIm.toSeq.sortWith(_._1> _._1):_*);
print(res);
  }

}
Output:-
Kushagra Trivedi
DS
2015079
ListMap(Tommy -> 11, Jonny -> 87, Cheena -> 14, Bill -> 56)


Que 8: -
objecthello {
println("Kushagra Trivedi\nDS\n2015079");
defmain(args: Array[String]) {
varage = scala.io.StdIn.readInt();
varcheckeligible =(age:Int)=>age>=18
if(checkeligible(age))
    {
println("Eligible to vote");
    }
else
    {
println("Not eligible to vote");
    }
  }

}
Output:-
Kushagra Trivedi
DS
2015079
45
Eligible to vote





Que 7: -
objecthello {
println("Kushagra Trivedi\nDS\n2015079");
defmain(args: Array[String]) {
vara = List(99.5,100.0,50.0,55.0,70.0,100,-1.0);
varb = List(10.0,20.0,30.0,40.0,50.0);
varc = a:::b;
println(c.min);
println(c.max);
  }
}
Output:-
Kushagra Trivedi
DS
2015079
-1.0
100.0





Que 6: -
objecthello{
println("Kushagra Trivedi\nDS\n2015079");
defmain(args: Array[String]){
vall:List[Int]= List(10,20,30,30,30,60,50)
vall1=l.distinct
println("Orginal List: "+l)
println("(i) "+l1)
valfirst=l.indexOf(30)
println("(ii) First Occurence of 30: "+first)
println("(iii) Length :"+l.length)
vall2=l.sorted
println("(iv) Sorted List: "+l2)
println("(v) Sum of List: "+l.sum)
vals=l.toString()
println("(vi) String of List: "+s)
println("(vii) Min of List: "+l.min)
println("(vii) Max of List: "+l.max)
vallast=l.lastIndexOf(30)
println("(ix) last Occurence of 30: "+last)
valm=l.zipWithIndex.map{ case (v,i) => (i,v)}.toMap
println("(x) Map: "+m)
  }
}
Output:-
Kushagra Trivedi
DS
2015079
Orginal List: List(10, 20, 30, 30, 30, 60, 50)
(i) List(10, 20, 30, 60, 50)
(ii) First Occurence of 30: 2
(iii) Length :7
(iv) Sorted List: List(10, 20, 30, 30, 30, 50, 60)
(v) Sum of List: 230
(vi) String of List: List(10, 20, 30, 30, 30, 60, 50)
(vii) Min of List: 10
(vii) Max of List: 60
(ix) last Occurence of 30: 4
(x) Map: Map(0 -> 10, 5 -> 60, 1 -> 20, 6 -> 50, 2 -> 30, 3 -> 30, 4 -> 30)




Que 5: -
objecthello{
println("Kushagra Trivedi\nDS\n2015079");
defmain(args: Array[String]){
vall1: List[String]=List("Name","Section","Roll")
println("head: "+l1.head)
println("Tail: "+l1.tail)
println("isEmpty: "+l1.isEmpty)
println("reverse: "+l1.reverse)
  }
}
Output:-
Kushagra Trivedi
DS
2015079
head: Name
Tail: List(Section, Roll)
isEmpty: false
reverse: List(Roll, Section, Name)




Que 4: -
importscala.annotation.tailrec;
objecthello {
println("Kushagra Trivedi\nDS\n2015079");
defGCD(n: Int, m: Int): Int =
  {
// tail recursion function defined
    @tailrecdefgcd(x:Int, y:Int): Int=
    {
if (y==0) x
elsegcd(y, x%y)
    }
gcd(n, m)
  }
deffactorial(n: Int): Int =
  {
// Using tail recursion
    @tailrecdeffactorialAcc(acc: Int, n: Int): Int =
    {
if (n<=1)
acc
else
factorialAcc(n*acc, n-1)
    }
factorialAcc(1, n)
  }
defmain(args: Array[String]) {
println(GCD(12, 18));
println(factorial(5));
  }
}

Output: - 
Kushagra Trivedi
DS
2015079
6
120




Que 3: -
traitCar{
defhorn()
defbreak()
defgo()
}
traitTruck{
defsize()
}
classBigCarextendsCar{
defhorn(){
println("horned")
  }
defbreak(){
println("breaked");
  }
defgo(){
println("going");
  }
}
classCyberTruckextendsCarwithTruck{
defhorn(){
println("peeeeep")
  }
defbreak(){
println("stopped");
  }
defgo(){
println("brrrr");
  }
defsize(){
println("big size");
  }
}
objecthello {
println("Kushagra Trivedi\nDS\n2015079");
defmain(args: Array[String]) {
varx = newCyberTruck();
vary = newBigCar();
x.horn();
x.break();
x.go();
x.size();
y.horn();
y.break();
y.go();
  }
}


Output: -
Kushagra Trivedi
DS
2015079
peeeeep
stopped
brrrr
big size
horned
breaked
going







Que 2: - 
objecthello {
defmain (args: Array[String])
  {
println("Kushagra Trivedi\nDS\n2015079");
valdiv = (_:Int)/(_:Int);
valmul = (_:Int)*(_:Int);
valadd = (a:Int,b:Int)=>a+b;
valsub = (a:Int,b:Int)=>a-b;

varchoice:Int=0;
println("Select Choice:-\n");
println("1.Addition\n2.Subtraction\n3.Multiplication\n4.Devision");
choice=scala.io.StdIn.readInt();
println("enter two variables");
vara :Int = scala.io.StdIn.readInt();
varb :Int = scala.io.StdIn.readInt();

if(choice==1)
println(add(a,b));
elseif(choice==2)
println(sub(a,b));
elseif(choice==3)
println(mul(a,b));
elseif(choice==4)
println(div(a,b));
else
println("wrong choice entered please try again");

  }
}
Output :-
Kushagra Trivedi
DS
2015079
Select Choice:-

1.Addition
2.Subtraction
3.Multiplication
4.Devision
3
enter two variables
4
5
20









Que 1:- 
objecthello {

deffahrenheittoCelsius(temp:Float):Float= {
return (temp-32)*5/9;
  }

definchestometers(size:Float):Double= {
returnsize*0.254;
  }

defyeartodays(years:Int):Int= {
returnyears*365;
  }

defmain (args: Array[String])
  {
println("Kushagra Trivedi\nDS\n2015079");
println("Enter Temprature in Fahrenheit :- ")
vartemp: Float =scala.io.StdIn.readFloat();
println("Temprature in Celsius is :- ");
println(fahrenheittoCelsius(temp));

println("Enter Size in Inches :- ");
varsize :Float =scala.io.StdIn.readFloat();
println("Size in Meters is :- ");
println(inchestometers(size));

println("Enter No of Years :- ");
varyears :Int =scala.io.StdIn.readInt();
println("No. of Days are :- ");
println(yeartodays(years));
  }
}
Output :-
Kushagra Trivedi
DS
2015079
Enter Temprature in Fahrenheit :- 
98
Temprature in Celsius is :- 
36.666668
Enter Size in Inches :- 
5.10
Size in Meters is :- 
1.2953999757766723
Enter No of Years :- 
2
No. of Days are :- 
730
