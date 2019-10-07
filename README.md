# 1Repo
menu with some exercise


import os
while True:
    os.system('cls')
    print("Aby wyświetlić informacje o autorze wciśnij -'A'")
    print("Zadanie 1, wciśnij - '1'")
    print("Zadanie 2, wciśnij - '2'")
    print("Zadanie 3, wciśnij - '3'")
    print("Aby wyjść wciśnij - '0'")
    decyzja=input()
    if decyzja=='A':
        print("Autorem jest Agnieszka Iwańczuk:)")
    elif decyzja=='1':
        for i in range(0,71):
            if i%7==0:
                print(i)
    elif decyzja=='2':
        liczby=50
        while liczby !=150:
            if liczby%3==0 and liczby%5!=0:
                print(liczby)
            liczby=liczby+1
    elif decyzja=='3':
        tabliczka=0
        while tabliczka !=51:
            if tabliczka%5==0:
                print(tabliczka)
            tabliczka=tabliczka+1
    elif decyzja=='0':
        break
    else:
        print("Źle wpisałeś")
    input()
