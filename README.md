# ENCAPSULATION_SMART_DOOR_SYSTEM
ADOMAKO VICENTIA-EL1A
class Staff:
def __init__(self,s_name,access_code):
self.s_name=s_name
self.__access_code=access_code

@property
def access_code(self):
return self.__access_code

@access_code.setter
def access_code(self,new__code):
if len(new_code)>=6
self.__access_code=new_code
print("Access code updated successfully.")
else:
print("Access code must be at least 6 characters long.")
def display_info(self):
print("\n----Staff Information----)
print("Staff Name:",self.s_name)
print("Access Code:",self.___access_code)

name=input("Enter staff name:")
code=input("Enter access code:")

staff1=Staff(name,code)

print("\nCurrent Access Code:",staff1.access_code)
new_code=input("Enter new access code:")
staff1.access_code=new_code
staff1.display_info()



