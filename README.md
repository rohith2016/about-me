#ABOUT-ME

![profile pic](https://dyn.web.whatsapp.com/pp?e=https%3A%2F%2Fpps.whatsapp.net%2Fv%2Ft61.11540-24%2F30819199_367709447069551_8968344532450017280_n.jpg%3Foe%3D5AF83FFB%26oh%3Dc8cb306f628ecb32addabe91c198f493&t=l&u=919962824394%40c.us&i=1524683566)  
+Sometimes it is hard to introduce yourself because you know yourself so well that you do not know where to start with. Let me give a try to see what kind of image you have about me through my self-description. I hope that my impression about myself and your impression about me are not so different. Here it goes.  
+I'm the kind of guy who has been called as both an introvert and an extrovert. I love to sit in my room and just have some time with myself. But i also like to roam around with my gang. I read a lot of books, always ready for a game of fifa but i like my late night walks with my bestie. BasicaLly, I don't belong to particular category. I am a bit of this and bit of that.    
+I doubt you will find anything interesting in my timeline since I'm not really into facebook or other social networks but you can check it out here: [my timeline](https://www.facebook.com/profile.php?id=100010478928366)  

<!--ROHITH 106117041-->
<!--KANCHI 106117041-->
# Sorting.cpp
def partition(A, p, r):  
   q = j = p  
   while j < r:  
     if A[j] <= A[r]:  
       A[q], A[j] = A[j], A[q]  
         q += 1  
     j += 1  
   A[q], A[r] = A[r], A[q]  
   return q  
     
   def quicksort(A, p, r):  
   if r <= p:  
     return  
   q = partition(A, p, r)  
   quicksort(A, p, q-1)  
   quicksort(A, q+1, r)  
   return A  
