name=input("please enter your name: ")
date=int(input("please enter current year: "))
date1=int(input("please enter current moth: "))
date2=int(input("please enter current day: "))
year=int(input("please enter your year of birth: "))
month=int(input("please enter your month of birth: ")) 
day=int(input("please enter your day of birth: "))
leap_year=[1304 ,1309 ,1313 , 1317,1321 , 1325 ,1329 ,1333 ,1337 , 1342 ,1346 ,1350, 1354 ,1358 , 1362 , 1366 ,1370 , 1375 , 1379 ,1383 ,1387 ,1391 ,1395 ,1399 ,1403 ,1407 ] 
if month>=1 and month<=6:
    h=31
  
elif month>=7 and month<=11:
    h=30
elif month==12:
    h=29
elif year in leap_year:
    h=30
m=date2-day
if m<0:
    month-=(-1)
    m=h-(-m)
x=date-year
n=date1-month
if n<0:
    x-=(-1)  
    n+=12 
print(f"hello {name} , you are {x} years , {n} month and {m} days old.")
