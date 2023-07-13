# JoiningDate
# cook your dish here
import math
for t in range(int(input())):
    n,k = map(int,input().split())
    N = math.ceil(n/5)
    m = math.ceil(k/5)
    print(N-m)
