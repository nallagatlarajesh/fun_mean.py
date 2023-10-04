# fun_mean.py
#function to calculate mean
#requirements
#total as combine all
#count 
#mylist

def myMean(mylist):
    count=0
    total=0
    for i in mylist:
        total=total+i
        count=count+1
    mean=total/count
    print("the calculated mean is :",mean)
    #function ends here
mylist=[1.3,2.4,3.5,6.9]
myMean(mylist)
