1. At line 12, the console prints out the value of i, which is 3, because the for loop ends when i is equal to the length of the prices (3) and i can be accessed outside of the for loop since it is a var
2. The console prints out 150. When the for loop ends, discountedPrice is assigned to the discounted price of the last item in prices. Since the last price is 300 and the discount is 0.5, discountedPrice is 150. Since discountedPrice is a var, it can be accessed outside of the for loop by console.log
3. The console prints out 150, the value of finalPrice, because finalPrice's value at the end of the for loop is the final discounted price of the last item in the prices list
4. The function returns the list of discounted prices [50, 100, 150] because we were given the prices [100, 200, 300] and the discount 0.5 and the function applies the discount to the prices and returns the result
5. The code causes an error because i cannot be accessed outside of the for loop
6. The code results in an error because discountedPrice cannot be accessed outside of the for loop
7. The console prints out 150 because finalPrice can be accessed within the function block 
8. The list of discounted prices [50, 100, 150] will be returned since discounted was defined at the beginning of the function and can be accessed anywhere within the function
9. The code causes an error because i cannot be accessed outside of the for loop
10. The console prints out the value of length, 3, because length was defined at the beginning of the function and can be accessed anywhere within the function
11. The function returns [50, 100, 150] since discounted is the list of discounted prices and can be accessed and updated (not reassigned) anywhere within the function
12. Data types
    1.  student.name
    2.  student['Grad Year']
    3.  student.greeting()
    4.  student['Favorite Teacher'].name
    5.  student.courseLoad[0]
13. Arithmetic
    1.  '32' because 2 would map to '2' so '3' + 2 = '3' + '2' = '32'
    2.  1 because '3' - 2 = 3 - 2 = 1
    3.  3 because null maps to 0 so 3 + null = 3 + 0 = 3
    4.  '3null'because null maps to 'null' so '3' + 'null' = '3null'
    5.  4 because true maps to 1 so true + 3 = 1 + 3 = 4
    6.  3 because false maps to 0 so false + 3 = 0 + 3 = 3
    7.  0 because false maps to 0 and null maps to 0 so false + null = 0 + 0 = 0
    8.  '3undefined' because undefined maps to 'undefined' and gets concatenated to '3'
    9.  NaN because undefined maps to NaN
14. Comparison
    1.  true because '2' maps to 2 and 2 is greater than 1
    2.  false because the first character in '2' is greater than the first character in '12' ('1')
    3.  true because '2' becomes the number 2
    4.  false because 2 and '2' are different types
    5.  false because true maps to 1 and does not equal 2
    6.  true because Boolean(2) returns true
15. The === operator is a strict equality operator, so the two operands must be of the same type in order to be equal. On the other hand, the == operator will perform a type conversion and then check equality

17. The modifyArray function will return the array [2, 4, 6] because it takes in the doSomething function as an argument to the callback parameter. The modifyArray function calls the callback function, in this case doSomething, on each item in the array. doSomething takes a number and doubles it. Thus, modifyArray([1, 2, 3], doSomething) doubles each number in the array and returns [2, 4, 6]

19. 1 4 3 2
