# python-program-7
#class setitem()
class numbers:
    def __init__(self,mylist):
        self.mylist=mylist
    def __setitem__(self,index,value):
        return self.mylist[index]
numlist=([1,2,3,4,5,6,7,8])
numlist[5]=10
print(numlist)
