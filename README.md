# python-codes

############## find the numeric value in the input ##############


# s="ISTS123@gmail.com"
# b=""
# for i in s:                                              #o/p=123
#     if i .isdigit():
#         b+=i
# print(b)

############or ###

# def val():
#     s="ISTS123@gmail.com"
#     b=""
#     for i in s:                                              #o/p=123
#         if i .isdigit():
#           b+=i
#     print(b)
# val()

####0r ####


# def val():  
#     b=""
#     for i in s:                                              #o/p=123
#         if i .isdigit():
#           b+=i
#     print(b)
# s="ISTS123@gmail.com" 
# val()

########or3###########

# def val():
#     s="ISTS123@gmail.com" 
#     b="".join([i for i in s if i.isdigit()])                              #o/p=123
#     print(b)
# val()


# def val():
#     s="ISTS123@gmail.com"
#     b=""
#     for i in s:                                              #o/p=123
#         if i .isdigit():
#           b+=i
#     return b
# res=val()
# print(res)




############# find the alpha value in the input ##############


# def val():
#     s="ISTS123@gmail.com"
#     b=""
#     for i in s:                                              #o/p=ISTSgmailcom
#         if i .isalpha():
#           b+=i
#     return b
# res=val()
# print(res)




############# find the special character in the input ##############


# def val():
#     s="ISTS123@gmail.com"
#     b=""
#     for i in s:                                              #o/p=@.
#         if not i.isalnum():
#           b+=i
#     return b
# res=val()
# print(res)



################################################


# def fun(a,b,c,d):
#     for i in a:
#         if i.isalpha():
#             b+=i                         #o/p=pavists22@gmail.com
#         elif i.isdigit():                 #   pavistsgmailcom
#             c+=i                          #   22
#         else:                             #   @.
#             d+=i
#     result = [b,c,d]
#     return "\n".join(result)
# b=" "
# c=" "
# d=" "
# a=input()
# print(fun(a,b,c,d))



##############################  convert upper to lower (or) lower to upper ############

# def fun():
#     a=input()                         #engineering
#     print(a.upper())                  #ENGINEERING
# fun()


##############



# def fun():
#     a=input()                         #ENGINEERING
#     print(a.lower())                  #engineering
# fun()


############ 

# def  fun():                                                #o/p=engineering
#     return a.upper()                                        #ENGINEERING
# a=input()
# res=fun()
# print(res)

#########

# a=input()
# b=""
# c=""
# for i in a:
#     if i.isupper():
#         b+=i
#     else:
#         c+=i
# if len(b)>len(c):                                         #O/P=jjuohJ0IJ             #o/p=BOok
#     print(a.upper())                                     #     jjuohj0ij             #    BOok
# elif len(b)<len(c): 
#     print(a.lower())
# else:
#     print(a)


#########################################

# a=input()
# b=""
# c=""
# for i in a:
#     if i.isupper():
#         b+=i
#     else:
#         c+=i
# if len(b)>len(c):                                         #O/P=BOok
#     print(a.upper())                                     #     boOK
# elif len(b)<len(c): 
#     print(a.lower())
# elif len(b)==len(c) :
#     print(a.swapcase())
# else:
#     print(a)



####################################

# def fun():
#     b=""
#     c=""
#     for i in a:
#         if i.isupper():
#             b+=i
#         else:
#             c+=i
#     if len(b)>len(c):                                         #O/P=BOok
#         return a.upper()                                #          boOK
#     elif len(b)<len(c): 
#         return a.lower()
#     elif len(b)==len(c) :
#         return a.swapcase()
#     else:
#         return a

# a=input()
# res=fun()
# print(res)


#####################reverse of a number without slicing########################

# def rev(num):
#     b=0
#     while num>0:
#         b=b*10+num%10                           #o/p=321
#         num=num//10                            #     123
#     return b
# num=int(input())
# res=rev(num)
# print(res)


###0r#########

# def rev(num):
#     b=0
#     while num!=0:
#         b=b*10+num%10
#         num=num//10                                     #o/p=12344
#     return b                                            #     44321
# num=int(input())
# res=rev(num)
# print(res)



########index values #########


# array=[10,20,30,40,50]
# for index,ele in enumerate(array):
#     print(f"{index}")


###########################

# a=10
# while a:
#     print("i am working")


# a=0
# while a<=5:
#     print("i am working")a=10

# a=0
# while a<=5:
#     print("i am working")
#     a=a+1


# def reverse(num):
#     rev=0
#     while num:
#         rev=rev*10+(num%10)
#         num=num//10
#     return rev

# num=8464
# print(reverse(num))



##########count no.of digits #############


# def count(num):
#     count=0
#     while num:
#         count+=1
#         num=num//10
#     return count
# num=1234560
# print(count(num))

#######################

# def count(num):
#     count=0
#     while num!=0:
#         count+=1
#         num=num//10
#     return count
# num=1234560
# print(count(num))

################## 


# def count(num):
#     count=0
#     while num>0:
#         count+=1
#         num=num//10
#     return count
# num=1234560
# print(count(num))


###################### find odd digit in the number############\


# def odd(num):
#     odd1=0
#     while num:
#         digit =num %10
#         if digit % 2!= 0:
#             odd1+=1
#         num=num//10
#     return odd1
# num=12345667899
# print(odd(num))



#############


# def odd(num):
#     odd1=0
#     while num!=0:
#         digit =num %10
#         if digit % 2!= 0:
#             odd1+=1
#         num=num//10
#     return odd1
# num=12345667899
# print(odd(num))

#################################

#input:Localisation
#o/p:L10n

# def short(word):
#     if len (word) > 10:
#         return word[0] + str(len(word) -2) + word[-1]
#     else:
#         return word
# word="Localisation"
# print(short(word))


################333input:1246378
#################3###o/p=5##############missing number #######

# def fun(n):
#     arr=list(map(int,input().split()))
#     for i in range(1,n+1):
#         if i not in arr:
#             return i
#     return None
# n=int(input())
# res=fun(n)
# print(res)


# def fun(n):
#     arr=list(map(int,input().split()))
#     for i in range(1,n+1):
#         if i in arr:
#             continue
#         else:
#             return i
# n=int(input())
# res=fun(n)
# print(res)


#####count the number of even  elements in the given list collection ############

# def fun():
#     arr=list(map(int,input().split()))
#     b=0
#     for i in arr:
#         if i%2==0:
#             b+=1
#     return b
# res=fun()
# print(res)




# def even(num):
#     even1=0
#     while num!=0:
#         digit =num %10
#         if digit % 2== 0:
#             even1+=1
#         num=num//10
#     return even1
# num=12345667899
# print(even(num))

####################subarrys are follows sequential order #################

# listt = [10,25,39,46,53,60]                       #o/p=[10, 25, 39]
# print(listt[0:3])



# listt = [10,25,39,46,53,60]
# for i in range(0, len(listt)):
#     print(listt[i: i+3])

#####o/p=[10, 25, 39]
       # [25, 39, 46]
       # [39, 46, 53]
       # [46, 53, 60]
       # [53, 60]
       # [60]


# n=int(input("enter the value of n:"))                    #enter the value of n:5
# listt = [10,25,39,46,53,60]                              #[10, 25, 39, 46, 53]
# for i in range(0, len(listt)-(n-1)):                     #[25, 39, 46, 53, 60]
#     print(listt[i: i+n])


# n=int(input("enter the value of n:"))                    #enter the value of n:5
# listt = [10,25,39,46,53,60]                              #[10, 25, 39, 46, 53]
# for i in range(0, len(listt)):                           #[25, 39, 46, 53, 60]
#     print(listt[i: i+n])                                 #[39, 46, 53, 60]
                                                           #[46, 53, 60]
                                                           #[53, 60]
                                                           #53, 60]
                                                        


# def language (string):
#     first = string[0]
#     last=string[-1]
#     middle= string[1:len(string)]
#     print(middle)

# string =input()
# print(language(string))


######### cutting the cake problem############
# The problem is to find the number of pices of cake that can be made with a given number of cuts.

'''Problem statement
It is Edward's birthday today. His friends have bought him a huge circular cake.
Edward wants to find out the maximum number of pieces he can get by making exactly N straight
verticalcuts on the cake.
Your task is to write a function that returns the maximum number of pieces that can be obtained by
makingN number of cuts.
Note: Since the answer can be quite large, modulo it by 1000000007
Input Specification:
input1: An integer N denoting the number of cuts
Output Specification:
Return the maximum number of pieces that can be obtained by making N cuts on the cake
Example:
Input Output Explanation
1 2
Given the above scenario, if we
make 1 cut on the cake, the
maximum number of pieces of cake
we obtain is 2 and
2%1000000007=2. Hence, 2 is
returned as output.
5 16
Given the above scenario, if we
make 5 cuts on the cake, the
maximum number of pieces of cake
we obtain is 16 and 16%
1000000007=16. Hence, 16 is
returned as output'''




# def cake():
#     n=int(input())
#     num=(n*(n+1)//2)+1                 #o/p=4
#     return num                          #   11
# res=cake()
# print(res)


# def cuts(n):
#     return (((n*(n+1))//2)+1 ) % 1000000007             #o/p=7
# n=int(input())                                           #   29
# print(cuts(n))       



# ####################################################


# n=int(input())
# m=int(input())
# divisible=[]
# notdivisible=[]
# for i in range(1,m+1):
#     if i%n==0:
#         divisible.append(i)
#     else:
#         notdivisible.append(i)
# sum1=sum(divisible)
# sum2=sum(notdivisible)
# print(abs(sum1-sum2))


'''Coding Question 1
The function def differenceofSum(n. m) accepts two integers n, m as arguments Find the sum of all numbers in range from 1 to m(both inclusive) that are not divisible by n. Return difference between sum of integers not divisible by n with sum of numbers divisible by n.
Assumption:
•	n>0 and m>0
•	Sum lies between integral range
Example
Input
n:4
m:20
Output
90
Explanation
•	Sum of numbers divisible by 4 are 4 + 8 + 12 + 16 + 20 = 60
•	Sum of numbers not divisible by 4 are 1 +2 + 3 + 5 + 6 + 7 + 9 + 10 + 11 + 13 + 14 + 15 + 17 + 18 + 19 = 150
•	Difference 150 – 60 = 90
Sample Input
n:3
m:10
Sample Output
19       '''
 



# def fun(n,m):
#     divisible=[]
#     notdivisible=[]
#     for i in range(1,m+1):
#         if i%n==0:
#             divisible.append(i)
#         else:
#             notdivisible.append(i)
#     sum1=sum(divisible)
#     sum2=sum(notdivisible)
#     return abs(sum1-sum2)

# n=int(input())
# m=int(input())
# res=fun(n,m)
# print(res)




###########print gcd of numBE#####################3
'''05. Arjun has two types of Arrows. He wants to measure the length of them using a single measuring tape.
What will be the greatest possible length that can be used to measure exactly the length of two arrows? Write
a program to calculate this and help Arjun.
Example:
Input: 8 10
Output: The HCF of 8 and 10 is: 2
Input: 25 30
Output: The HCF of 25 and 30 is: 5'''




# def HCF (a,b):
#     while b:
#         a,b =b ,a%b
#     return a
# a,b=map (int,input().split())
# print(HCF(a,b))


# def fun(a,b):
#     c=min(a,b)
#     gcd=1
#     for i in range(1,c+1):
#         if a%i==0 and b%i==0:             #o/p=6
#             gcd=i                             #8
#     return gcd                                #2
# a=int(input())
# b=int(input())
# print(fun(a,b))


# def fun(a,b):
#     c=max(a,b)
#     gcd=1
#     for i in range(1,c+1):
#         if a%i==0 and b%i==0:             #o/p=6
#             gcd=i                             #8
#     return gcd                                #2
# a=int(input())
# b=int(input())
# print(fun(a,b))



###################find LCM###########



# def HCF (a,b):
#     while b:
#         a,b =b ,a%b
#     return a
# def LCM(a,b):
#     return(int((a*b)/HCF(a,b)))

# a,b=map(int, input().split())

# print(LCM(a,b))



#####################

'''You are required to implement the following Function def LargeSmallSum(arr). 
The function accepts an integers arr of size ’length’ as its arguments you are required to return the sum of second largest largest element from the even positions and second largest from the odd position of given ‘arr’.
Assumption:
•	All array elements are unique
•	Treat the 0th position as even
NOTE
•	Return 0 if array is empty
•	Return 0, if array length is 3 or less than 3
Example:-
Input
arr:3 2 1 7 5 4
Output
7
Explanation
•	Second largest among even position elements(1 3 5) is 3
•	Second largest among odd position element is 4
•	Thus output is 3+4 = 7
Sample Input
arr:1 8 0 2 3 5 6
Sample Output
8
'''


# array = [1, 2, 3, 4, 5, 6, 7]
# even_pos = array[::2]  # Elements at even indices
# odd_pos = array[1::2]  # Elements at odd indices

# def second_largest(arr):
#     if len(arr) < 2:
#         return 0  # Or handle as per your requirement
#     first = second = float('-inf')
#     for num in arr:
#         if num > first:                                  #o/p=9
#             second = first
#             first = num
#         elif first > num > second:
#             second = num
#     return second if second != float('-inf') else 0

# even_result = second_largest(even_pos)
# odd_result = second_largest(odd_pos)
# print(even_result + odd_result)

########0r##########


# def maximum(array):
#     maxi=float("-inf")
#     s_maxi=float("-inf")
#     for i in array:
#         if i> maxi:
#             s_maxi=maxi
#             maxi=i                             
#         elif maxi >i >s_maxi:
#             s_maxi=i
#     if s_maxi !=float("-inf"):
#         return s_maxi
#     return f"second maxi doesnot exist"
# def largesmallsum(array):
#     if len(array)<=3:
#         return 0
#     even=array[::2]
#     odd=array[1::2]
#     return maximum(even)+ maximum(odd)        ##o/p=11

# array=[3,2,1,5,6,8,9]
# print(largesmallsum(array))




# array =[11,2,5,7,9,8,6,4]
# even=array[::2]
# odd=array[1::2]                           #o/p=[11, 5, 9, 6]
# print(even)                                    [2, 7, 8, 4]
# print(odd)



# def maximum(array):
#     maxi=float("-inf")
#     s_maxi=float("-inf")
#     for i in array:
#         if i> maxi:
#             s_maxi=maxi
#             maxi=i                              #o/p=5
#         elif maxi >i >s_maxi:
#             s_maxi=i
#     if s_maxi !=float("-inf"):
#         return s_maxi
#     return f"second maxi doesnot exist"
# array=[4,3,2,1,5,7]
# print(maximum(array))




# def maximum(array):
#     maxi=max(array)
#     while maxi in array:
#         array.remove(maxi)
#     maxi = max(array)
#     return maxi
# array=[20,22,35,12,11,35]
# print(maximum(array))

'''Problem Description :
The function accepts two positive integers ‘r’ and ‘unit’ and a positive integer array ‘arr’ of size ‘n’ as its argument ‘r’ represents the number of rats present in an area, ‘unit’ is the amount of food each rat consumes and each ith element of array ‘arr’ represents the amount of food present in ‘i+1’ house number, where 0 <= i
Note:
•	Return -1 if the array is null
•	Return 0 if the total amount of food from all houses is not sufficient for all the rats.
•	Computed values lie within the integer range.
Example:
Input:
•	r: 7
•	unit: 2 (each rat need 2 units)
•	n: 8
•	arr: 2 8 3 5 7 4 1 2 (each element is number of food the house has)
Output:
4
Explanation:
Total amount of food required for all rats = r * unit
= 7 * 2 = 14. (requried food)
The amount of food in 1st houses = 2+8+3+5 = 18. Since, amount of food in 1st 4 houses is sufficient for all the rats. Thus, output is 4.
(4 because, you can have excess food but not least food that required after 2,8,3 count is 3 where as food requried is 2 + 8 + 3 = 13 still I need on more 1 unit so I consider next so that I can have extra food but not less that needed that is 14)

'''


# rats=int(input())
# unit=int(input())
# n=int(input())
# arr=list(map(int,input().split()))
# if not arr:
#      print(-1)
# elif sum(arr)<rats*unit:
#      print(0)
# else:
#     total_food=0
#     for i in range(n):                   #o/p=7
#         total_food+=arr[i]               #    2
#         if total_food>=rats*unit:        #    8
#             print(i+1)                   #    2 8 3 5 7 4 1 2
#             break                        #ans=4

###or in functions #########


# def fun(rats,unit,n,arr):
#     if not arr:
#        print(-1)
#     elif sum(arr)<rats*unit:
#        print(0)                       #o/p=7
#     else:                             #o/p=2
#        total_food=0                   #o/p=8
#        total_food=0                    #o/p=2 8 3 5 7 4 1 2
#     for i in range(n):                 #o/p=4
#         total_food+=arr[i]               
#         if total_food>=rats*unit:       
#             return (i+1)
#             break
        
# rats=int(input())
# unit=int(input())
# n=int(input())
# arr=list(map(int,input().split()))  
# res=fun(rats,unit,arr)
# print(res) 

    
###############0r##########

# def rat_food(r,u,n,array):
#     ate=0
#     total_food=r*u
#     for i,value in enumerate(array):
#         ate+=value                                    #o/p=4
#         if ate >= total_food:
#             return i+1
        
# r=7
# u=2
# n=8
# array=[2, 8, 3, 5, 7, 4, 1, 2]
# result=rat_food(r,u,n,array)
# print(result)

    



'''Coding Question 4

Problem Description :
The Binary number system only uses two digits, 0 and 1 and number system can be called binary string. You are required to implement the following function:
int OperationsBinaryString(char* str);
The function accepts a string str as its argument. The string str consists of binary digits eparated with an alphabet as follows:
•	– A denotes AND operation
•	– B denotes OR operation
•	– C denotes XOR Operation
You are required to calculate the result of the string str, scanning the string to right taking one opearation at a time, and return the same.
Note:
•	No order of priorities of operations is required
•	Length of str is odd
•	If str is NULL or None (in case of Python), return -1
Input:
str: 1C0C1C1A0B1
Output:
1
Explanation:
The alphabets in str when expanded becomes “1 XOR 0 XOR 1 XOR 1 AND 0 OR 1”, result of the expression becomes 1, hence 1 is returned.
Sample Input:
0C1A1B1C1C1B0A0
Output:
0
'''



# def binary_code(binary):
#        a=int(binary[0])
#        for i in range(1,len(binary)-1,2):
#               if binary[i] =="A":
#                      a= a & int(binary[i+1])
#               elif binary[i] =="B":                                 #o/p=0
#                      a= a | int(binary[i+1])
#               else :
#                      a= a ^ int(binary[i+1])
#        return a
# binary = "0C1A1B1C1C1B0A0"
# print(binary_code(binary))




'''Question 5: Password Checker
You are given a function.
int CheckPassword(char str[], int n);
The function accepts string str of size n as an argument. Implement the function which returns 1 if given string str is valid password else 0.
str is a valid password if it satisfies the below conditions.
•	– At least 4 characters
•	– At least one numeric digit
•	– At Least one Capital Letter
•	– Must not have space or slash (/)
•	– Starting character must not be a number
Assumption:
Input string will not be empty.
Example:
Input 1:				Output 1:
aA1_67				1
Input 2:				Output 2:
a987 abC012			0
'''


# def password(string):
#     if len(string) < 4 or string[0].isdigit():
#         return 0
#     d=0
#     uc=0
#     spec=0
#     for i in string:
#         if i.isdigit():
#             d+=1
#         elif i.isdigit():
#             uc+=1
#         elif i ==" " or i== " / ":
#             spec += 1
#     if spec >= 1:
#         return 0                                       #o/p=0
#     if d>= 1 and uc >=1:
#         return 1
#     return 0

# string ="a987 abC012"
# print(password(string))
    



'''You are given a function,
int findCount(int arr[], int length, int num, int diff);
The function accepts an integer array ‘arr’, its length and two integer variables ‘num’ and ‘diff’. Implement this function to find and return the number of elements of ‘arr’ having an absolute difference of less than or equal to ‘diff’ with ‘num’.
Note: In case there is no element in ‘arr’ whose absolute difference with ‘num’ is less than or equal to ‘diff’, return -1.
Example:
Input:
•	arr: 12 3 14 56 77 13
•	num: 13
•	diff: 2
Output:
3
Explanation:
Elements of ‘arr’ having absolute difference of less than or equal to ‘diff’ i.e. 2 with ‘num’ i.e. 13 are 12, 13 and 14.

'''



# arr=list(map(int,input().split())) 
# num=int(input())
# diff=int(input())
# count=0 
#                                                        #o/p==12 3 14 56 77 13
# for i in arr:                                          #     13
#     a=abs(num-i)                                       #     2
#     if  a<=diff:                                       #     3
#         count+=1
#     else:
#         pass
# if count==0:
#     print(-1)
# print(count)


#########in functions ##########

# def fun(arr,num,diff):
#     count=0                                                # o/p=12 3 14 56 77 13
#     for i in arr:                                          #     13
#         a=abs(num-i)                                       #     2
#         if  a<=diff:                                       #     3
#           count+=1
#         else:
#           pass
#     if count==0:
#        return(-1)
#     return(count)

# arr=list(map(int,input().split())) 
# num=int(input())
# diff=int(input())

# res=fun(arr,num,diff)
# print(res)



#########################################no.otf even digits and no.of odd digits########################
###input:1234567
####ouput:even:3
########  odd:4


# s=int(input())
# c=str(s)
# even=0
# odd=0                                       
# for i in c:
#     if int(i)%2==0:
#         even+=1
#     else:
#         odd+=1
# print("even:" ,even)
# print("odd:" ,odd)


###########in functions ##########


# def fun(s):
#   c=str(s)
#   even=0
#   odd=0                                       
#   for i in c:
#       if int(i)%2==0:
#         even+=1                            #o/p:1234567
#       else:                                #    3
#         odd+=1                              #   4
#   print(even)
#   print(odd)
#   return 
# s=int(input())
# res=fun(s)

#####or##############

# def count(n):
#     ec=0
#     oc=0
#     while n:
#         last = n%10
#         if last%2 ==0:
#             ec+=1
#         else:                                #o/p=1234567 
#             oc+=1                            # Even digits: 3
#         n=n//10                              # odd digits: 4
#     return f"""Even digits: {ec}
# odd digits: {oc}
# """
# n=int(input())
# print(count(n))





# t=int(input())
# notaccess=0
# access=1
# count=0
# for i in range(t):
#     t=int(input())
#     k=bin(t)[2:]
#     if k==1:
#         count+=1
        
# if k==0:
#         print("0 False")
# print(count+"True")


######replace the most repeated value with "t" if two values have most repeated then find the least ascii value and replace#####
####input:pavani
#        :t
#output: {'p': 1, 'a': 2, 'v': 1, 'n': 1, 'i': 1}
#        ['a']
#        ptvtni


# s=input()
# t=input()
# d={}
# for i in s:
#     if i not in d:
#         d[i]=1
#     else:
#         d[i]+=1
# print(d)
# m=max(d.values())
# l=[]
# for i,j in d.items():
#     if(j==m):
#         l.append(i)
# l.sort()
# print(l)
# r=s.replace(l[0],t)
# print(r)



######input=cat batman latt matter cat matter cat cat latt latt
###3output= ["cat", "latt"]










