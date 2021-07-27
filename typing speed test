# Intern-academy-projects-typing-speed



import time
import random

String = ['Generating Number in a Range', 'My name is prajwal','I am an engineer','This is my python project', "my task one"]


while True:
    n=random.randint(0,len(String)-1)
    word=String[n]
    print("\n")
    print("Type the sentence : ",word)
    
    t0 = time.time()
    inputtext = str(input('Enter : '))
    t1 = time.time()
    test_string=word.split()
    input_string=inputtext.split()



    count=0
    if len(test_string)<len(input_string):
        a=len(test_string)
    elif len(test_string)>len(input_string): 
        a=len(input_string) 
    else:
        a=len(input_string)       
    for i in range(0,a):
        if test_string[i]==input_string[i]:
            count+=1

    timetaken = t1-t0
    
    wpm = count/timetaken
    print("correct words are: ",count)
    print("WPM: ", wpm)
    print("Timetaken: ", timetaken)
