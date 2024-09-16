# Python-2
(1) #conditional statements</br>
    age =int(input("enter your age:"))</br>
    print("your age is:",age)</br>
    
    #conditional operators</br>
    print(age>18)</br>
    print(age>=18)</br>
    print(age<=18)</br>
    print(age==18)</br>
    print(age!=18)</br>
    
    if(age>18):</br>
      print("you can drive")</br>
    else:</br>
      print("you cannot drive")</br>

output:-enter your age:34</br>
your age is: 34</br>
True</br>
True</br>
False</br>
False</br>
True</br>
you can drive</br>
      
(2) x=10</br>
    y=2</br>
    if (x-y>5):</br>
      print("yes")</br>
    elif(x-y<5):</br>
      print("maybe")</br>
    else:</br>
      print("noo")</br>

output:- yes</br>

(3) #nested if-else</br>
    num=int(input("enter"))</br>
    if(num<0):</br>
      print("negative")</br>
    elif(num>0):</br>
      if(num<=10):</br>
        print("yes")</br>
      elif(num>10 and num<+20):</br>
        print("ok")</br>
      else:</br>
        print("not")</br>
     else:</br>
       print("okk")</br>

output:- enter3</br>
yes</br>


(4) #match case statement</br>
    x=int(input("enter number"))</br>
    match x:</br>
     case 0:</br>
      print("x is zero")</br>
     case 4:</br>
      print("x is four")</br>
     case _ if x!=90:</br>
      print("x is not equal to 90")</br>
     case _ if x!=80:</br>
      print("x is not ezual to 80")</br>
     case _ :</br>
      print(x)</br>

output:-enter number0</br>
x is zero</br>

(5) #for Loop</br>
    for x in range(5):</br>
     print(x)</br>

    #example</br>
    (1) name8 = "rashi"</br>
        for i in name8:</br>
          print(i)</br>

    (2) colors = ["red","green"]</br>
        for color in colors:</br>
          print(color)</br>
        for i in color:</br>
          print(i)</br>

 (6) #while loop</br>
     i=0</br>
     while(i<3):</br>
       print(i)</br>
       i=i+1</br>
       
     #example</br>
     count=5</br>
     while(count>0):</br>
      print(count)</br>
      count=count-1</br>

(7) # break statements</br>
    for i in range(10):</br>
     if(i==8):</br>
       break  #breaks the loop</br>
     print("8 x",i+1,"=",8*(i+1))</br>

(8) # continue statements</br>
    for i in range(10):</br>
     if(i==8):</br>
      continue #skips the iteration</br>
     print("8 x",i+1,"=",8*(i+1))</br>


(9)#function</br>
   def isgrater(a,b):</br>
   if(a>b):</br>
    print("first num")</br>
   else:</br>
    print("second num")</br>
    
  #leaving a function without any body</br>
  def isless(a,b):</br>
  pass</br>

  #calling of a function</br>
  a=2</br>
  b=3</br>
  isgrater(a,b)</br>

output:- second num</br>

(10) #lists</br>
    marks = [3,4,5,6,7,4,5,5]</br>
    print(marks)</br>
    print(marks[0])</br>
    print(marks[1])</br>
    print(marks[2])</br>
    print(marks[3])</br>
    print(marks[-3])</br>
    print(marks[1:6])</br>
    print(marks[1:6:2])# jump index</br>

output:- [3, 4, 5, 6, 7, 4, 5, 5]</br>
3</br>
4</br>
5</br>
6</br>
4</br>
[4, 5, 6, 7, 4]</br>
[4, 6, 4] </br>

    #list methods</br>
    l=[1,3,2,4,5,6,7]</br>
    print(l)</br>
    l.append(8) #adds a value in list</br>
    l.sort()#sorts a list</br>
    l.sort(reverse=True)</br>
    l.reverse</br>
    print(l.index(1))</br>
    print(l.count(1))</br>
    m=[1,2,3]</br>
    l.extend(m)# elements of m are added in l</br>
    print(l)</br>

output:- [1, 3, 2, 4, 5, 6, 7]</br>
7</br>
1</br>
[8, 7, 6, 5, 4, 3, 2, 1, 1, 2, 3]</br>


(11) #tuples can never be changes (immutable)</br>
     tup=(1,2,3,4)</br>
     print(tup)</br>
     ref=tup.count(1)</br>
     ref=tup.index(2)</br>
     ref=len(tup)</br>
     print(ref)</br>

output:- (1, 2, 3, 4)</br>
4</br>
 

