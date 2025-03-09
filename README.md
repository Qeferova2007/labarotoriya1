import math as m
k1=(8.15*((14.36)**(1/3)*m.log(2)))/(24.38*(8.734)**(1/2)*(m.exp(2)-m.exp(-2)))
k2=m.sin(m.sin(1/2)+m.cos(1/3))
if min(k1,k2)<1:
    r=(abs(2*k1-7*k2))**(1/2)
elif min(k1,k2)>=1:
    r=(abs(2*k1+7*k2))**(1/2)
print(r)
   
