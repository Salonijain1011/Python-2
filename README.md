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
