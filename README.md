# MLP_practical
 {"Name":"VAIDANGI GADHIYA", "Enrollment_No": 202400819010017}
import numpy as np
#create array
a=np.array([1,2,3,4,5,6,7,8,9])
b=np.array([[4,15,5],[87,9,95]])
print(a)
print(b)
vnew=np.vsplit(b,2)
print(vnew)
#return shape of a array
print(format(a.shape))
print(format(b.shape))
#return dimension of array 
print(a.ndim)
print(b.ndim)
#return size of array
print(format(a.size))
#return data type of array
print(a.dtype)
#return item size of array
print(a.itemsize)
#return data of mamaory location array
print(a.data)
#return slice of array
slicearra=a[4:7]
slicearrb=b[1:,2:]
print(slicearra)
print(slicearrb)
#return sum of array
print(a.sum())
print(b.sum())
#opration of matrix create a new array 
m1=np.array([[1,2],[3,4]])
m2=np.array([[6,7],[8,9]])
print(m1)
print(m2)

# cross multiply of matrix  
mul = np.dot(m1,m2)
print(mul)
# row column multipication
mulM=np.multiply(m1,m2)
print(mulM)
#add of matrix
addM= np.add(m1,m2)
print(addM)
#sub of matrix
subM= np.subtract(m1,m2)
print(subM)
#convert array to matrex
M3=np.array([1,2,3,4,5,6,7,8,9])
m3=M3.reshape(3,3)
print(m3)
# find minimum value of matrix
print(m3.min())
# find maximum value of matrix
print(m3.max())
# find minimum value of each row 
print(m3.min(axis=1))

# find minimum value of each column 
print(m3.min(axis=0))

# find maxmum value of each row 
print(m3.max(axis=1))

# find maxmum value of each column 
print(m3.max(axis=0))

m4=np.array([[121,4,9],[16,49,81]])

# find a squre root of matrix
print(np.sqrt(m4))
#print standard deviation ofn matrix 
print(np.std(a))
#create vertical stack
v=np.vstack((m1,m2))
print(v)
#create vertical stack
h=np.hstack((m1,m2))
print(h)
# provide a range between the number
rang=np.arange(0,20,2)
print(rang)
# provide a range between the number
rang=np.arange(0,20,2,float)
print(rang,rang.dtype)
# divide number of this range in given part
divide=np.linspace(0,50,5)
print(divide)

#convert horizontal to vertical
ht=h.T
print(ht)
#convert vertical to horizontal
vt=v.T
print(vt)

# print each element of array
for i in np.nditer(a):
    print(i)
ab=np.array([[4,5,2],[17,8,9],[6,54,52],[47,95,10]])

#split the array horizontal
h_split=np.hsplit(ab,3)
print(h_split)

#split the array vertically
v_split=np.vsplit(ab,2)
print(v_split)
abc=np.array([54,89,32,54])
#return the square root of each element
print(np.sqrt(abc))

#return the exponentials of each element
print(np.exp(abc))

#return the sin of each element
print(np.sin(abc))

#return the cos of each element
print(np.cos(abc))

#return the log of each element
print(np.log(abc))

#return the sum of total element of array
print(np.sum(abc))

#return the standard deviation of in the array
print(np.std(abc))
# random number genrator in floats
anw=np.random.random(5);
print(anw)
# random number genrator in given range
ran=np.random.rand(3,4)
print(ran)

# random in integer by range 
inte=np.random.randint(0,50,5)
print(inte)
# random permutation of number
per= np.random.permutation(np.arange(5))
print(per)

