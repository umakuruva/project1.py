# project1.py
#python program to built rock-paper-scissor game
# rock=0
#paper=1
#scissor=2
' ' ' rock wins against scissor
      scissor wins against paper
     paper wins against rock '''
c=random.randint(0,2)
h=int(input())
if(0<=c<=2 and 0<=h<=2):
       if(c==h):
          print("tie")
       elif(c==0 and h==2):
          print("c win")
       elif (c==2 and h==0):
           print("h win")\
        elif(c>h):
           print("c win")
        else:
           print("h win")
else:
   print("invalid choice")
