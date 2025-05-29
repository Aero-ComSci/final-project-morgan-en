[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/DpCY8B3G)
1. This program is for anyone who would like to quickly calculate the cost of any of their summertime activities.
2. My program asks the tax, amount, and cost of the individual activity that the user wants and then outputs the combined total cost.
SS':
![image](https://github.com/user-attachments/assets/e473a381-f4f7-4aee-b161-566d0b76ce1d)
![image](https://github.com/user-attachments/assets/b2c430f9-db45-4f73-b15c-b254972e2e59)

```python def AskActivity():
    y = "Hello! What activity would you like to add?"
    try:
        a = input(y)
    except:
        a = input(y)
    y1 = "How many or much of this activity would you like to perform?"
    try:
        b = input(y1)
    except:
        b = input(y1)
    y2 = "What is the tax on this/these item(s)?"
    try:
        c = input(y2)
    except:
        c = input(y2)
    y3 = "What is the cost of this/these item(s)?"
    try:
        d = input(y3)
    except:
        d = input(y3)
    Activity1 = Activity(str(a), int(b), int(c), int(d))
    print(Activity1) ```
```python for i in activity_list:
    print(i) ```
```python NZLTicket = Activity("New_Zealand_Ticket(s)", 2, 25, 1000) 
AUSTicket = Activity("Australia_Ticket(s)", 3, 30, 950) ```
