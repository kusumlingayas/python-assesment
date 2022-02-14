# python-assesment2
print("enter the string")
str = input()
str = str.replace(" ",  "")
print(str)
strRev = str[::-1]
if (str == strRev):
        print("pass")
else:
        print("fail")
    
