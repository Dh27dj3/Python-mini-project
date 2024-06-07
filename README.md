# Python-mini-project
# This is a mini project in python for student 

print("HI,WE ARE SAVE YOUR INFORMATION")
print()
class Person_info:
    def __init__(self,name,age,gender,address,phone_number,email,user_id,pass_id):
        self.name = name
        self.age = age
        self.gender = gender
        self.address =address
        self.phone_number = phone_number
        self.email = email
        self.user_id = user_id
        self.password_id = pass_id
    def per_info(self):
        input_id = input("enter your username :-") 
        if input_id == self.user_id:
            print("right")
        else:
            print("invalid username")
            exit()
        input_pass = int(input("enter your password :-"))
        if input_pass == self.password_id:
            print()
            print("name :",self.name)
            print("age :",self.age)
            print("gender :",self.gender)
            print("address :",self.address)
            print("phone number :",self.phone_number)
            print("email :",self.email)
        else:
            print("invalid password ")
            exit()
            
             

s1 = Person_info("siddharth",18,"male","ahmednagar",7720888035,"dsiddharth550@gmail.com","s",12345)
s1.per_info()
s1 = Person_info("karan",18,"male","ahmednagar",7720887035,"karan@gamil.com","karan_d",98765)
s1.per_info()
        
        
