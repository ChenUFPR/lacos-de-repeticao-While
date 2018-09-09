n = int(input("Tabuada de:"))
print("\n") 
while n!=int:
    x = 1 
    while x <= 10:
        print("{}*{}={}".format(n, x, n*x)) 
        x = x + 1
    print("\n")
    n = int(input("Tabuada de:"))
    print("\n")
