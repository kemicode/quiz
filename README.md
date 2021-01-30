# quiz
quiz
#Name: Oluwakemi LaBadie
#Program that prompts the user to enter his/her age.
#Collaboration: none
#Pseudocode
#Write a creative quiz program, that consists of three original questions
#that make up according to the specifications given.
#
#Pseudocode
#input first question, assign Question1
#input second question, assign Question2
#input third question, assign Question3
#input if Question1 equals 30
#input if print correct else print wrong
#input if Question2 equals 98.6 print correct
#input else print wrong
#input if Question3 equals Bill Clinton, print correct
#input else print wrong
#End program

#Start Program

#Get Variables
month_question = 31
temperature_question = 98.6
politics_question = "Bill Clinton"

#Enter Question 1
print("Brain teezer quiz*\n")
print("Question 1:")
print("How many days are in January?\n")
print("Input your answer numerically")
answerCorrect = False
maxTrys = 2
while not answerCorrect and maxTrys > 0:
    print("(A): 30")
    print("(B): 31")
    print("(C): 29\n")
    month_question = int(input("Input your answer here: "))
    if month_question == 31:
        print("Correct Answer, you rock!!,".format (month_question))
        answerCorrect = True
    else:
        maxTrys -= 1
        if maxTrys == 0:
            print("Sorry, you lost...")
        else:
            print("Oop Try Again? [{} Chances Remaining]" .format(maxTrys - 1))
            
#Enter Question 2

print("Question 2:")
print("What is the average body temperature?\n")
print("Input your answer numerically")
answerCorrect = False
while not answerCorrect and maxTrys > 0:
    print("(A): 98.6")
    print("(B): 95.9")
    print("(C): 98.2\n")
    Answer = float(input("Input your answer here: "))
    if Answer == 98.6:
        print("Correct Answer, you rock!!,".format (Answer))
        answerCorrect = True
    else:
        maxTrys -= 1
        if maxTrys == 0:
            print("Sorry, you lost...")
        else:
            print("Oop Try Again? [{} Chances Remaining]" .format(maxTrys - 1))           
    
#Enter Question 3

print("Question 3:")
print("Who is the 42nd President of United States of America ?\n")
print("Write out your answer")
answerCorrect = False
while not answerCorrect and maxTrys > 0:
    print("(A): Joe Biden")
    print("(B): Goerge Bush .Jr")
    print("(C): Bill Clinton")
    Answer = str(input("Input your answer here: "))
    if Answer == "Bill Clinton":
        print("Correct Answer, you rock!!,".format (Answer))
        answerCorrect = True
    else:
        maxTrys -= 1
        if maxTrys == 0:
            print("Sorry, you lost...")
        else:
            print("Oop Try Again? [{} Chances Remaining]" .format(maxTrys - 1))
             print('End of Quiz, have a nice day!')
    

    
