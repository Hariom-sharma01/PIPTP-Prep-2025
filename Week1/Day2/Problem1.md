Integer a,b,c
set a=2,b=6,c=8;
a=(10+9)+c
if((c+b)>(a-c))
      a=b+c
      b=b+b
end if
print a+b+c

Output:- 41

reason:- intitially the value of a,b,c are 2,6,8 respectively
but after this line a=(10+9)+c
a=(19)+8=27
and after this line if((c+b)>(a-c))
(c+b)=(8+6)=14
(a-c)=(27-8)=19
so (c+b)>(a-c) is false
so the value of a,b,c remains 27,6,8 respectively
and it will print 27+6+8=41
