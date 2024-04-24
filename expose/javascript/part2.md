1. The number 3 will be logged to the console because the variable i has the scope of the entire function. Since the array provided to the function has a length of three, once i becomes 3, the for loop will terminate and then the console.log(i) line will be called using that information
2. The number 150 will be logged to the console because the variable discountedPrice has the scope of the entire function. The last time it will be updated is for the last item in the provided array due to the set up of the for loop, and 300 * (1-0.5) is 150, so that is what will be logged when called upon.
3. Once again, the number 150 will be logged to the console since the variable finalPrice is still in scope. The last time it will be updated, it will take the last instance of discountedPrice (150), multiply it by 100 and round (15000), then divide it by 100, which results in 150 which will then be logged when called upon
4. The function will return an array with length 3: [50,100,150]. This is because the array is returned from the function and each final discounted price is appended to the array when its final price is calculated, and that is the order in which the prices were calculated given that the input was [100,200,300] and the discount was 0.5.
5. Line 12 will now throw an error since i is no longer in scope. By using let, i's scope was only within the for block and the location of the console log call is not within that same block
6. Line 13 will now throw an error since discountedPrice is no longer in scope. By using let, discountedPrice's scope was only within the for block and the location of the console log call is not within that same block
7. The number 150 will be logged to the console since the variable finalPrice is still in scope. The last time it will be updated, it will take the last instance of discountedPrice (150), multiply it by 100 and round (15000), then divide it by 100, which results in 150 which will then be logged when called upon. The issue of scope is not an issue since the console log call is in the same scope of which finalPrice was declared
8. The function will return an array with length 3: [50,100,150]. This is because the array is returned from the function and each final discounted price is appended to the array when its final price is calculated, and that is the order in which the prices were calculated given that the input was [100,200,300] and the discount was 0.5. There is no issue of scope since all uses of discounted are within the same block or a nested block of which discounted was declared in.
9. Line 11 will throw an error since i is no longer in scope. By using let, i's scope was only within the for block and the location of the console log call is not within that same block
10. The number 3 will be logged to the console since that is the length of the inputted array. There is no reassignment of a const variable and the scope matches for when length was declared, so there is no issues.
11. The function will return an array with length 3: [50,100,150]. This is because the array is returned from the function and each final discounted price is appended to the array when its final price is calculated, and that is the order in which the prices were calculated given that the input was [100,200,300] and the discount was 0.5. There is no issue of scope since all uses of discounted are within the same block or a nested block of which discounted was declared in. There is also no issue with the variable being const since there is no reassignment to the variable, only altering the contents within the current assignment.
12. A: student.name, 
    
    B: student["Grad Year"]

    C: student.greeting()

    D: student["Favorite Teacher"].name

    E: student.courseLoad[0]
13. A: '32' since 2 is converted to a string and concatenated
    
    B: 1 since '3' is converted to a number and done math

    C: 3 since null is converted to 0

    D: '3null' since null is converted to a string

    E: 4 since true is converted to 1

    F: 0 since both false and null are converted to 0

    G: '3undefined' since undefined was converted to a string

    H: NaN since undefined is converted to NaN and any arithmetic with NaN is NaN

14. A: true since '2' is converted to 2 and 2 > 1

    B: false since a string comparison is done and '2' is lexicographically larger than '12'

    C: true since when converted, they represent the same value

    D: false since there is no conversion and they are not the same since the types are different

    E: false since true is converted to 1 and 1 != 2

    F: true since Boolean(2) is true and true === true

15. == allows for type conversions to happen to test for equality to see if they represent the same value. === differs from that in that the two things being compared has to be of the same type and value in order to come out to true. Essentially, == will convert types to check equality while === will not convert types in any situation.
16. See code
17. The result will be [2,4,6] since the method modifyArray goes through the elements of the original array, applies the callback function to it, and appends it to the new array. Since the callback function is just multiplying the input by two, [1,2,3], when multiplying each element by two, will result in [2,4,6]
18. See code
19. It outputs, in the following order:

1

4

3

2