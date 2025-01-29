# Month-study-calender
this code will help you to keep in track with your weekly study routines or any goals in a month you wanna acieve this code will break the goal into smaller weekly goals 
for i in range(4):
    d={}
    x=1
    while x<=7 :
         y=int(input("Enter the date: "))
         s=input("Enter the subject to grind on: ")
         d[y]=s
         x+=1
    print(d)
print ("month is over ")
