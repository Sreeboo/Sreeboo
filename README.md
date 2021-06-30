-import random
ans1='8 Ball:"Most certainly!! XD"' #NOICE!!  =UwU= 
ans2='8 Ball:"Probably. :)"'
ans3='8 Ball:"Maybe not.."'
ans4='8 Ball:"Absolutely not..."'
ans5='8 Ball:"Do not even think about it!"' # ;_;
ans6='8 Ball:"Concentrate and try again..."'
ans7='8 Ball:"Hell no!!!"' #NOT NOICE -_-
name= input('What is your name? ')
print(name,', I am the CoreBot...')
lifequest= input(  'Type your question and I shall forsee your luck....  ')
print('Your question is:' , lifequest)

randinteger=random.randint(1,7)
if randinteger==1:
    answer= ans1
if randinteger==2:
    answer= ans2
if randinteger==3:
    answer=ans3
if randinteger==4:
    answer= ans4
if randinteger==5:
    answer= ans5
if randinteger==6:
    answer= ans6
if randinteger==7:
    answer= ans7


print(answer)









