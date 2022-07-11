# plp_hackathon-python
our first hackathon

#bus_fare_quiz
from datetime import date
today = date.today()
print("date:", today)
#day as day of week
from datetime import date
import calendar
day_of_week=date.today()
print("day:", calendar.day_abbr[day_of_week.weekday()])
#using if statements to get bus fare
day_of_week=calendar.day_name[day_of_week.weekday()]
fare = [60,80,100]
if day_of_week==[6]:
    print("fare:",str(60))
elif day_of_week==[0]:
    print("fare:",str(80))
else:
    print("fare:", str(100))


#painter job/tax 
#enter input in float()to calculate
wall_as_int=int(float())
price_as_int=int(float())
print(galons:=(wall_as_int)/115)
print(hrs:=(wall_as_int/115)*8)
print(price_as_int*(wall_as_int)/115)
print(labour:=(wall_as_int/125)*8*20)
print(total:=(wall_as_int/115)*8*20+(wall_as_int/115)*price_as_int)


#bookshop
books_as_int=int(float())
points_as_int=int(float())
if books_as_int==0:
    print("points="+str(0))
elif books_as_int==1:
    print("points="+str(6))
elif books_as_int==2:
    print("points="+str(16))
elif books_as_int==3:
    print("points="+str(32))
else:
    print("max-points="+str(60))


#careers guide
#takes user inputs
#we have put input for tests
careers=["a","b","c"]
careers_advises=["-a","-b","+c"]
careers_quiz=["qa","qb","qc"]
lists=[careers+careers_advises+careers_quiz]
print(lists)
for i in lists:
    print(i)
    if i not in lists:
        print("err: wrong input")
if lists[0]==0:
    print(careers_advises)
    print(careers[2]+"is best fit career as per advise")
    print("program terminated:end of advise")


#door lock system
psword=input()
commands=["open","close","quit"]
def unlock(commands):
    for psword in commands:
     if(psword!=commands[0]):
        print("error:"+"enter psword again")
     elif(psword==commands[0]):
        print("The door is now open")  
     elif(psword==commands[0]+commands[0]):
        print("the door is already open")
     elif(psword==commands[1]):
        print("The door is now locked")
     elif(psword==commands[1]+commands[0]+commands[0]):
        print("the door is already locked")
     elif(psword==commands[2]):
        print("process terminated")
     elif(psword!=psword):
        print("invalid input")
from datetime import date
if(psword=="open"):
        print("Door last open at:=date.strftime()")
elif(psword=="close"):
        print("Door last closed at:=date.strftime()")
unlock(commands)


#nutrion diet manager  calory calc
fat_as_int=int(float())
carb_as_int=int(float())
print(cal_fat:=fat_as_int*9)
print(cal_carb:=carb_as_int*4)







