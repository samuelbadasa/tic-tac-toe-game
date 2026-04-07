p1="-"
p2="-"
p3="-"
p4="-"
p5="-"
p6="-"
p7="-"
p8="-"
p9="-"

while 'true':
    print("Player 1, enter the number representing the location to place your X (1-9): ")
    a=input()

    print("Here is the state of the board:")

    if a=="p1" or a== "1":
        p1="X"
    if a=="p2" or a =="2":
        p2="X"
    if a=="p3" or a=="3":
        p3="X"
    if a=="p4" or a=="4":
        p4="X"
    if a=="p5" or a=="5":
        p5="X"
    if a=="p6" or a=="6":
        p6="X"
    if a=="p7" or a=="7":
        p7="X"
    if a=="p8" or a=="8":
        p8="X"
    if a=="p9" or a=="9":
        p9="X"
    print(p1,p2,p3)
    print(p4,p5,p6)
    print(p7,p8,p9)
    
    if(p1==p2 and p1==p3 and p2==p3):
        if(p1=="X"):
            print("Player 1 wins!")
            break
        if(p1=="O"):
            print("Player 2 wins!")
            break
    if(p1==p4 and p1==p7 and p4==p7):
        if(p1=="X"):
            print("Player 1 wins!")
            break
        if(p1=="O"):
            print("Player 2 wins!")
            break
    if(p1==5 and p1==9 and p5==p9):
        if(p1=="X"):
            print("Player 1 wins!")
            break
        if(p1=="O"):
            print("Player 2 wins!")
            break


    if(p5==p1 and p5==p9 and p1==p9):
        if(p5=="X"):
            print("Player 1 wins!")
            break
        if(p5=="O"):
            print("Player 2 wins!")
            break
    if(p5==p3 and p5==p7 and p3==p7):
        if(p5=="X"):
            print("Player 1 wins!")
            break
        if(p5=="O"):
            print("Player 2 wins!")
            break
    if(p5==p2 and p5==p8 and p2==p8):
        if(p5=="X"):
            print("Player 1 wins")
            break
        if(p5=="O"):
            print("Player 2 wins!")
            break
    if(p5==p4 and p5==p6 and p4==p6):
        if(p5=="X"):
            print("Player 1 wins!")
            break
        if(p5=="O"):
            print("Player 2 wins!")
            break
    

    if(p9==p8 and p9==p7 and p8==p7):
        if(p9=="X"):
            print("Player 1 wins!")
            break
        if(p9=="O"):
            print("Player 2 wins!")
            break
    if(p9==p6 and p9==p3 and p6==p3):
        if(p9=="X"):
            print("Player 1 wins!")
            break
        if(p9=="O"):
            print("Player 2 wins!")
            break
    if(p9==p5 and p9==p1 and p5==p1):
        if(p9=="X"):
            print("Player 1 wins!")
            break
        if(p9=="O"):
            print("Player 2 wins!")
            break
    if(p1!="-" and p2!="-" and p3!="-" and p4!="-" and p5!="-" and p6!="-" and p7!="-" and p8!="-" and p9!="-"):
        print()
        print("Tied game!")
        break
    
    print()

    a=input("Player 2, enter the number representing the location to place your O (1-9): ")

    print("\nHere is the state of the board:")

    if a=="p1" or a=="1":
        p1="O"
    if a=="p2" or a=="2":
        p2="O"
    if a=="p3" or a=="3":
        p3="O"
    if a=="p4" or a=="4":
        p4="O"
    if a=="p5" or a=="5":
        p5="O"
    if a=="p6" or a=="6":
        p6="O"
    if a=="p7" or a=="7":
        p7="O"
    if a=="p8" or a=="8":
        p8="O"
    if a=="p9" or a=="9":
        p9="O"
    print(p1,p2,p3)
    print(p4,p5,p6)
    print(p7,p8,p9)
   

    if(p1==p2 and p1==p3 and p2==p3):
        if(p1=="X"):
            print("Player 1 wins!")
            break
        if(p1=="O"):
            print("Player 2 wins!")
            break
    if(p1==p4 and p1==p7 and p4==p7):
        if(p1=="X"):
            print("Player 1 wins!")
            break
        if(p1=="O"):
            print("Player 2 wins!")
            break
    if(p1==5 and p1==9 and p5==p9):
        if(p1=="X"):
            print("Player 1 wins!")
            break
        if(p1=="O"):
            print("Player 2 wins!")
            break
    

    if(p5==p1 and p5==p9 and p1==p9):
        if(p5=="X"):
            print("Player 1 wins!")
            break
        if(p5=="O"):
            print("Player 2 wins!")
            break
    if(p5==p3 and p5==p7 and p3==p7):
        if(p5=="X"):
            print("Player 1 wins!")
            break
        if(p5=="O"):
            print("Player 2 wins!")
            break
    if(p5==p2 and p5==p8 and p2==p8):
        if(p5=="X"):
            print("Player 1 wins!")
            break
        if(p5=="O"):
            print("Player 2 wins!")
            break
    if(p5==p4 and p5==p6 and p4==p6):
        if(p5=="X"):
            print("Player 1 wins!")
            break
        if(p5=="O"):
            print("Player 2 wins!")
            break
    

    if(p9==p8 and p9==p7 and p8==p7):
        if(p9=="X"):
            print("Player 1 wins!")
            break
        if(p9=="O"):
            print("Player 2 wins!")
            break
    if(p9==p6 and p9==p3 and p6==p3):
        if(p9=="X"):
            print("Player 1 wins!")
            break
        if(p9=="O"):
            print("Player 2 wins!")
            break
    if(p9==p5 and p9==p1 and p5==p1):
        if(p9=="X"):
            print("Player 1 wins!")
            break
        if(p9=="O"):
            print("Player 2 wins!")
            break
    print()
