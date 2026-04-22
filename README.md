a=int(input("enter the first digit\n"))
c=input('enter the first operator\n')
b=int(input("enter the second digit\n"))
d=input('enter the second operator\n')
e=int(input("enter the third digit\n"))

if c=="*" and d=="-":
    print("your answer is",(a*b)-e)
elif c=="*" and d=="+":
    print("your answer is",(a*b)+e)
elif c=="*" and d=="/":
    print("your answer is",(a*b)/e)
elif c=="*" and d=="*":
    print("your answer is",(a*b)*e)

elif c=="/" and d=="*":
    print("your answer is",(a/b)*e)
elif c=="/" and d=="/":
    print("your answer is",(a/b)/e)
elif c=="/" and d=="+":
    print("your answer is",(a/b)+e)
elif c=="/" and d=="-":
    print("your answer is",(a/b)-e)

elif c=="+" and d=="*":
    print("your answer is",(a+b)*e)
elif c=="+" and d=="/":
    print("your answer is",(a+b)/e)
elif c=="+" and d=="+":
    print("your answer is",(a+b)+e)
elif c=="+" and d=="-":
    print("your answer is",(a+b)-e)

elif c=="-" and d=="*":
    print("your answer is",(a-b)*e)
elif c=="-" and d=="/":
    print("your answer is",(a-b)/e)
elif c=="-" and d=="+":
    print("your answer is",(a-b)+e)
elif c=="-" and d=="-":
    print("your answer is",(a-b)-e)

else:
    print("please enter +, -, * or /")
