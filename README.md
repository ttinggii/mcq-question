# mcq-question
print("Title of program: MCQ revision program")
print()

counter = 0
score = 0
total_num_of_qn = 1


counter +=1
tracker = 0

while tracker !=1:
  
  print("Q"+str(counter)+") "+ "What is 20 + 2?")
  print("   a) 2")
  print("   b) 22")
  print("   c) 222")
  print("   d) 2222")
  answer = input("Your answer: ")
  answer = answer.lower()
  if answer == "a":
    output = "Wrong."
    score -=1
  elif answer == "b":
    output = "correct."
    score -=1
  elif answer == "c":
    output = "wrong."
    tracker =1
    score +=1
  elif answer == "d":
    output = "Wrong."
    score -=1
  else:
    output = "Please choose a, b, c or d only."
  
  print()
  print(output)
  print()
  print("Your current score: " + str(round((score/total_num_of_qn*100),1)) + "%"  )
  print()
  print()
  



