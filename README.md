# CarChoice
# cook your dish here
t=int(input())
while t:
    x1,x2,y1,y2=map(int,input().split())
    if((x1*y1)<(x2*y2)):
        print("-1")
    elif((x1*y1)>(x2*y2)):
        print("1")
    else:
        print("0")
    t-=1
