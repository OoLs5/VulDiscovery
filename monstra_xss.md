Log in and click "Edit profile"

![image-20240526212325074](C:\Users\OoLs\AppData\Roaming\Typora\typora-user-images\image-20240526212325074.png)



payload: ”><script>alert(1)</script>

Enter payload under email

![image-20240526212640712](C:\Users\OoLs\AppData\Roaming\Typora\typora-user-images\image-20240526212640712.png)

Click "Save" and click "Edit profile" again  --> xss

 ![image-20240526212947934](C:\Users\OoLs\AppData\Roaming\Typora\typora-user-images\image-20240526212947934.png)

![image-20240526213006680](C:\Users\OoLs\AppData\Roaming\Typora\typora-user-images\image-20240526213006680.png)



It has the same effect on "Twitter" and "Skype" with the same payload



Also,"About Me" has the same effect with a different payload.

payload:  </textarea><script>alert(1)</script>

![image-20240526213512179](C:\Users\OoLs\AppData\Roaming\Typora\typora-user-images\image-20240526213512179.png)



![image-20240526212947934](C:\Users\OoLs\AppData\Roaming\Typora\typora-user-images\image-20240526212947934.png)