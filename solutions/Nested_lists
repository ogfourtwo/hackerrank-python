if __name__ == '__main__':
    stu=[]
    min=9999
    second=9999
    for _ in range(int(input())):
        name = input()
        score = float(input())
        if(score<min):
            min=score
        stu.append([score,name])
    for j in stu:
        if(j[0]>min and j[0]<second):
            second=j[0]
    names=[]
    for i in stu:
        if(i[0]==second):
            names.append(i[1])
    names.sort()
    for k in names:
        print(k)
