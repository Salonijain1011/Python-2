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

