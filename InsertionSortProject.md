## Insertion Sort Project

### Example Array -> [22,27,16,2,18,6]

*1) The stages of the array according to the sort type <br/>*

1st Step: [**22**,27,16,**2**,18,6] -> [2,27,16,22,18,6] <br/>
2nd Step: [2,**27**,16,22,18,**6**] -> [2,6,16,22,18,27] <br/>
3rd Step: [2,6,**16**,22,**18**,27] -> [2,6,16,18,22,27] <br/>
4th Step: [2,6,16,**18**,22,27] -> [2,6,16,18,22,27] <br/>
5th Step: [2,6,16,18,**22**,27] -> [2,6,16,18,22,27] <br/>

*2) Big-O notation <br/>*

O(n^2)

*3) Time Complexity <br/>*

Worst Case: EXACTLY INVERTED ARRAY O(n^2) <br/>
Average Case: O(n^2) <br/>
Best Case: FULLY SORTED ARRAY O(n) <br/>


*4) What case does the number 18 fall into after the array is sorted?*

Average Case

### *First 4 steps of [7,3,5,8,2,9,4,15,6] according to Insertion Sort*


1st Step: [**7**,3,5,8,**2**,9,4,15,6] -> [2,3,5,8,7,9,4,15,6] <br/>
2nd Step: [2,**3**,5,8,7,9,4,15,6] -> [2,3,5,8,7,9,4,15,6] <br/>
3rd Step: [2,3,**5**,8,7,9,**4**,15,6] -> [2,3,4,8,7,9,5,15,6] <br/>
4th Step: [2,3,4,**8**,7,9,**5**,15,6] -> [2,3,4,5,7,9,8,15,6] <br/>
