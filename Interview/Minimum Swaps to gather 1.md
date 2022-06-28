Given a list of values containing only 0s and 1s, what are the minium no of swaping in the position required to gather all the numbers together.

Assume, input = [1,0,0,0,1,1,0]
Output can be = [0,0,0,1,1,1,0] or [0,0,0,0,1,1,1]. Here, Only swap is required to gather all 1s together.

**Solution:** This problem uses concept of sliding window. With sliding window, we try to obtain result within given window size. 
One step at a time is considered. Here, window size is the no of 1s i.e. 3

![image](https://user-images.githubusercontent.com/22523309/176149851-380fe073-1ba3-4415-b4e0-134ba2bc14d1.png)

