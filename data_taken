# database_for_attendence
student={}
def input_add():
    n = int(input("enter the strength of your class"))
    for i in range(n):
        enroll = int(input("enter the enrollno:"))
        name=input("enter the name of student")
        student.setdefault(enroll,[]).append(name)
    print(student)
    return student

def add_val():
   student1={}
   student1=input_add()
   student.update(student1)
   return student

def view_data():
    print(student)
def remove_data():
    d=int(input("enter the enroll no. you wnt to remove"))
    del student[d]
    return student
crdentials=("Admin","@python")
for i in range(3):
    user_name = input("enter your username")
    user_password = input("enter your password")
    if user_name==crdentials[0]and user_password==crdentials[1]:
        print("welcome to attendence management ")
        print("insert the data of your class")
        input_add()
        x = input("did you want editing yes or no")
        while(x=="yes"):
            ch=int(input("enter 1 to add\n2 to view\n3 to delete"))
            if ch==2:
                view_data()
                x = input("did you all editing or something left yes or no")
            elif ch==1:
                add_val()
                x = input("did you all editing or something left yes or no")
            elif ch==3:
                remove_data()
                x = input("did you all editing or something left yes or no")
            else:
                print("enter a valid option")
    else:
        print("try again")
        print("you have no attempt left")

