#Quinthia Nishimwe
#Testing_Student_GPA's
#Description: The program decides weather the student has made Dean's list or the Honor Roll.
#Ask the user to enter student last name.
lastName = input("Enter student last name: ")
#Checking if last name was entered as 'ZZZ' or not.
while lastName != "ZZZ":
    #Asking  the user to enter student First name.
    firstName = input("Enter student First name: ")
    #Asking the user to enter student GPA.
    gpa = float(input("Enter student GPA: "))
    #Cheking if student GPA is 3.5 or greater, if so they have made the Dean's List.
    if gpa >=3.5:
        print("{} {} has made the Dean's List.".format(firstName, lastName))
    #checking if student GPA is 3.25 or greater, if so they have made Honor Roll.
    else:
        if gpa >= 3.25:
            print("{} {} has made the Honor Roll.".format(firstName, lastName))
    lastName = input("\nEnter student last name: ")
#Repeating the processing until 'ZZZ' entered.
