# py-3
class student:
    def __init__(self,roll_no,name,address,course):
        self.roll_no = roll_no
        self.name = name
        self.address = address
        self.course = course
    def print_details(self):
        print(f"roll no :{self.roll_no}")
        print(f"name:{self.name}")
        print(f"address:{self.address}")
        print(f"course:{self.course}")
student1= student(458,"moulini","sriharipuram","ece")
student1.print_details()
        
