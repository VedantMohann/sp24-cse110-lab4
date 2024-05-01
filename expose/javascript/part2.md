Question 1:
it will print 3 since i = 3 after the last iteration of the for loop

Question 2:
it will print 150 since 300*(1-0.5)=150

Question 3:
It will print 150 since finalPrice is set to discountedPrice rounded to 2 decimals

Question 4:
It will return [50, 100, 150] as it discounts every item by 50%

Question 5:
It will return an error because i is only defined within the scope of the for loop

Question 6:
It will return an error because discountedPrice is only defined within the scope of the for loop

Question 7:
It will print 150 because that is the final discounted price. There is no error because finalPrice is declared in the same scope, which is of the entire function

Question 8:
It will return [50, 100, 150] as it discounts every item by 50%

Question 9:
It will return an error because i is only defined within the scope of the for loop.

Question 10:
It will print 3 because that is the length of the argument array. There won't be an error because we never change the length variable. 

Question 11:
It will return [50, 100, 150] as it discounts every item by 50%

Question 12:
A: student.name
B: student['Grad Year']
C: student.greeting()
D: student['Favorite Teacher'].name
E: student.courseLoad[0]

Question 13:
A: 32 due to string concatenation
B: 1 as everything is converted to numbers
C: 3 since null is seen as 0
D: 3null due to string concatenation
E: 4 since true is seen as 1
F: 0 since both false and null are seen as 0
G: 3undefined due to string concatenation
H: NaN since undefined can't be converted to a number

Question 14:
A: true since '2' is converted to 2
B: false since string comparison happens character by character
C: true since '2' is seen as 2
D: false since they are different types
E: false since true is seen as 1, and 1 does not equal 2
F: true since 2 as a boolean is true

Question 15:
The '==' attempts to make objects on either side have the same type before comparison, while '===' performs a strict comparison

Question 17:
The result will be that every number will be multiplied by 2 and the new array will be returned. Therefore, we get [2, 4, 6]. doSomething is used as the callback function to multiply every element of our argument array by 2. 

Question 19:
It will print
1
4
3
2
This happens because 1 is printed immediately, and a timer is set on 2 and 3, even if the timer for 3 is 0 ms. Then 4 is printed, then 3 is printed immediately after, then 2 is printed a second later. 