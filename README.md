# square-patten-
it is used for makings square pattern 
a= int (input("enter"))
for i in range(a):

    if i==0 or i==(a-1):
        print("x "*a)
    
    elif a>6:
      print("x "," "*(a+(a-6)),"x")
    else:
        print("x "," "*(a-1),"x")
