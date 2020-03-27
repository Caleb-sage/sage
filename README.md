#sage
'''
    *--------------------------------------------------------------------*
    * This programs qualitatively and quantitatively calculates          *
    * Mean of a group of variables                                       *
    * Variance of a group of variable                                    *
    * Standard deviation of the variance                                 *
    * Co-variance of a group of variables                                *
    * Correlation Co-efficient between two variables                     *
    * Calculate your matrix determinant                                  *
    * Multiplies two different set of matrix                             *
    * Add two set of matrixs                                             *
    *  inverses your matrix                                              *
    *--------------------------------------------------------------------*
'''
'''
*****This Makes Use Of Basic Python Mathimatical Computations****
'''
import math #importing the maths function
def welcome():
    print("Welcome to this simple geostatistical application")
    print("Below are the full list of calculations this program can handle")
    print("Type 1: to calculate mean")
    print("Type 2: for your variance")
    print("Type 3: for your standard deviation")
    print("Type 4: for your co-variance")
    print("Type 5: for your correlation co-efficient")
    print("Type 6: for your matrix determinant")
    print("Type 7: for your matrix multiplication")
    print("Type 8: for your matrix addition")
    print("Type 9: for your matrix inverse")
    response = int(input())
    if (response == 1):
        mean()
    elif (response == 2):
        variance()
    elif (response == 4):
        co_variance()
    elif (response == 5):
        cr_variance()
    elif (response == 6):
        det()
    elif(response == 7):
        detmul()
    elif (response == 8):
        add_mat()
    elif(response == 9):
        inverse_matix()
'''---***This Program Takes a Maximuin Of Ten Variables***---'''
'''---***This Function Querries The User For How Many Variables The User Needs To Work With***---'''
def mean():
    print("This program calculates the mean of a set of varibles and can only take a maximuin of 10 variables")
    print("How many variables do you have")
    variables = int(input('variables'))
    if (variables == 2):
        variable_2()
    elif(variables == 3):
        variable_3()
    elif(variables == 4):
        variable_4()
    elif(variables == 5):
        variable_5()
    elif(variables == 6):
        variable_6()
    elif(variables == 7):
        variable_7()
    elif(variables == 8):
        variable_8()
    elif(variables == 9):
        variable_9()
    elif(variables == 10):
        variable_10()
    print("Thank you for using sage cal")



'''---***This Part Of The Program Calculates For The Mean***---'''

def variable_2():
    var_one = float(input())
    var_two = float(input())
    total = var_one + var_two
    ans = total/2
    print("The mean of the varible is ",  round(ans, 2))

def variable_3():
    var_one = float(input())
    var_two = float(input())
    var_three = float(input())
    total = var_one + var_two + var_three
    ans = total / 3
    print("The mean of the varible is ",  round(ans, 2))
def variable_4():
    var_one = float(input())
    var_two = float(input())
    var_three = float(input())
    var_four = float(input())
    total = var_one + var_two + var_three + var_four
    ans = total / 4
    print("The mean of the varible is ",  round(ans, 2))
def variable_5():
    var_one = float(input())
    var_two = float(input())
    var_three = float(input())
    var_four = float(input())
    var_five = float(input())
    total = var_one + var_two + var_three + var_four + var_five
    ans = total / 5
    print("The mean of the varible is ",  round(ans, 2))

def variable_6():
    var_one = float(input())
    var_two = float(input())
    var_three = float(input())
    var_four = float(input())
    var_five = float(input())
    var_six = float(input())
    total = var_one + var_two + var_three + var_four + var_five + var_six
    ans = total / 6
    print("The mean of the varible is ",  round(ans, 2))
def variable_7():
    var_one = float(input())
    var_two = float(input())
    var_three = float(input())
    var_four = float(input())
    var_five = float(input())
    var_six = float(input())
    var_seven = float(input())
    total = var_one + var_two + var_three + var_four + var_five + var_six +var_seven
    ans = total / 7
    print("The mean of the varible is ",  round(ans, 2))

def variable_8():
    var_one = float(input())
    var_two = float(input())
    var_three = float(input())
    var_four = float(input())
    var_five = float(input())
    var_six = float(input())
    var_seven = float(input())
    var_eight = float(input())
    total = var_one + var_two + var_three + var_four + var_five + var_six + var_seven + var_eight
    ans = total / 8
    print("The mean of the varible is ",  round(ans, 2))
def variable_9():
    var_one = float(input())
    var_two = float(input())
    var_three = float(input())
    var_four = float(input())
    var_five = float(input())
    var_six = float(input())
    var_seven = float(input())
    var_eight = float(input())
    var_nine = float(input())
    total = var_one + var_two + var_three + var_four + var_five + var_six + var_seven + var_eight + var_nine
    ans = total / 9
    print("The mean of the varible is ",  round(ans, 2))
def variable_10():
    var_one = float(input())
    var_two = float(input())
    var_three = float(input())
    var_four = float(input())
    var_five = float(input())
    var_six = float(input())
    var_seven = float(input())
    var_eight = float(input())
    var_nine = float(input())
    var_ten = float(input())
    total = var_one + var_two + var_three + var_four + var_five + var_six + var_seven + var_eight + var_nine + var_ten
    ans = total / 10
    print("The mean of the varible is ",  round(ans, 2))

'''---      ****************************************************************************
        ----*Here End The Part Of The Program That Calculates The Mean Of The Variable *--------
            ****************************************************************************
        ---'''


'''---      ************************************************************************************
        ----*This Part Of The Program Calculate The Sum Of Square and Variance Of The Variable *--------
            ************************************************************************************
        ---'''
def variance():
    print("This program calculates the sum of square and the variance of a set of varibles and can only take a maximuin of 10 variables")
    print("How many variables do you have")
    variables = int(input())
    if (variables == 2):
        variance_2()
    elif (variables == 3):
        variance_3()
    elif (variables == 4):
        variance_4()
    elif (variables == 5):
        variance_5()
    elif (variables == 6):
        variance_6()
    elif (variables == 7):
        variance_7()
    elif (variables == 8):
        variance_8()
    elif (variables == 9):
        variance_9()
    elif (variables == 10):
        variance_10()
    print("Thank you for using sage cal")

def variance_2():
    print("Now Enter Values")
    var_one = float(input())
    vr_one = var_one**2
    var_two = float(input())
    vr_two = var_two**2
    total = var_one + var_two
    total = total ** 2
    vr_total = vr_one + vr_two
    ans = vr_total - (total / 2)
    v_ans = vr_total - ans
    vr_ans = ans / 1
    print("The sum of square of the varible is ", round(ans, 2), " while the variance is :", round(vr_ans, 2))
    print("The Standard Deviation Of The Variance is ", round(math.sqrt(vr_ans), 2))

def variance_3():
    print("Now Enter Values")
    var_one = float(input())
    vr_one = var_one ** 2
    var_two = float(input())
    vr_two = var_two ** 2
    var_three = float(input())
    vr_three = var_three ** 2
    total = var_one + var_two + var_three
    total = total ** 2
    vr_total = vr_one + vr_two + vr_three
    ans = vr_total - (total / 3)
    v_ans = vr_total - ans
    vr_ans = ans / 2
    print("The sum of square of the varible is ", round(ans, 2), " while the variance is :", round(vr_ans, 2))
    print("The Standard Deviation Of The Variance is ", round(math.sqrt(vr_ans), 2))

def variance_4():
    print("Now Enter Values")
    var_one = float(input())
    vr_one = var_one ** 2
    var_two = float(input())
    vr_two = var_two ** 2
    var_three = float(input())
    vr_three = var_three ** 2
    var_four = float(input())
    vr_four = var_four ** 2
    total = var_one + var_two + var_three + var_four
    total = total ** 2
    vr_total = vr_one + vr_two + vr_three + vr_four
    ans =vr_total - (total / 4)
    v_ans = vr_total - ans
    vr_ans = ans / 3
    print("The sum of square of the varible is ", round(ans, 2), " while the variance is :", round(vr_ans, 2))
    print("The standard Deviation Of The variance is ", round(math.sqrt(vr_ans), 2))

def variance_5():
    print("Now Enter Values")
    var_one = float(input())
    vr_one = var_one ** 2
    var_two = float(input())
    vr_two = var_two ** 2
    var_three = float(input())
    vr_three = var_three ** 2
    var_four = float(input())
    vr_four = var_four ** 2
    var_five = float(input())
    vr_five = var_five ** 2
    total = var_one + var_two + var_three + var_four + var_five
    total = total ** 2
    vr_total = vr_one + vr_two + vr_three + vr_four + vr_five
    ans = vr_total - (total / 5)
    v_ans = vr_total - ans
    vr_ans = ans / 4
    print("The sum of square of the varible is ", round(ans, 2), " while the variance is :", round(vr_ans, 2))
    print("The Standard Deviation Of The Variance is ", round(math.sqrt(vr_ans), 2))

def variance_6():
    print("Now Enter Values")
    var_one = float(input())
    vr_one = var_one ** 2
    var_two = float(input())
    vr_two = var_two ** 2
    var_three = float(input())
    vr_three = var_three ** 2
    var_four = float(input())
    vr_four = var_four ** 2
    var_five = float(input())
    vr_five = var_five ** 2
    var_six = float(input())
    vr_six = var_six ** 2
    total = var_one + var_two + var_three + var_four + var_five + var_six
    total = total ** 2
    vr_total = vr_one + vr_two + vr_three + vr_four + vr_five + vr_six
    ans = vr_total - (total / 6)
    v_ans = vr_total - ans
    vr_ans = ans / 5
    print("The sum of square of the varible is ", round(ans, 2), " while the variance is :", round(vr_ans, 2))
    print("The Standard Deviation Of The variance is ", round(math.sqrt(vr_ans), 2))

def variance_7():
    print("Now Enter Values")
    var_one = float(input())
    vr_one = var_one ** 2
    var_two = float(input())
    vr_two = var_two ** 2
    var_three = float(input())
    vr_three = var_three ** 2
    var_four = float(input())
    vr_four = var_four ** 2
    var_five = float(input())
    vr_five = var_five ** 2
    var_six = float(input())
    vr_six = var_six ** 2
    var_seven = float(input())
    vr_seven = var_seven ** 2

    total = var_one + var_two + var_three + var_four + var_five + var_six + var_seven
    total = total ** 2
    vr_total = vr_one + vr_two + vr_three + vr_four + vr_five + vr_six + vr_seven
    ans = vr_total - (total / 7)
    v_ans = vr_total - ans
    vr_ans = ans / 6
    print("The sum of square of the varible is ", round(ans, 2), " while the variance is :", round(vr_ans, 2))
    print("The Standard Deviation Of The Variance is ", round(math.sqrt(vr_ans), 2))

def variance_8():
    print("Now Enter Values")
    var_one = float(input())
    vr_one = var_one ** 2
    var_two = float(input())
    vr_two = var_two ** 2
    var_three = float(input())
    vr_three = var_three ** 2
    var_four = float(input())
    vr_four = var_four ** 2
    var_five = float(input())
    vr_five = var_five ** 2
    var_six = float(input())
    vr_six = var_six ** 2
    var_seven = float(input())
    vr_seven = var_seven ** 2
    var_eight = float(input())
    vr_eight = var_eight ** 2
    total = var_one + var_two + var_three + var_four + var_five + var_six + var_seven + var_eight
    total = total ** 2
    vr_total = vr_one + vr_two + vr_three + vr_four + vr_five + vr_six + vr_seven + vr_eight
    ans = vr_total - (total / 8)
    v_ans = vr_total - ans
    vr_ans = ans / 7
    print("The sum of square of the varible is ", round(ans, 2), " while the variance is :", round(vr_ans, 2))
    print("The Standard Deviation Of The Variance is ", round(math.sqrt(vr_ans), 2))

def variance_9():
    print("Now Enter Values")
    var_one = float(input())#floating input to be be able to accept decimals as input
    vr_one = var_one ** 2
    var_two = float(input())
    vr_two = var_two ** 2
    var_three = float(input())
    vr_three = var_three ** 2
    var_four = float(input())
    vr_four = var_four ** 2
    var_five = float(input())
    vr_five = var_five ** 2
    var_six = float(input())
    vr_six = var_six ** 2
    var_seven = float(input())
    vr_seven = var_seven ** 2
    var_eight = float(input())
    vr_eight = var_eight ** 2
    var_nine = float(input())
    vr_nine = var_nine ** 2
    total = var_one + var_two + var_three + var_four + var_five + var_six + var_seven + var_eight + var_nine
    total = total ** 2
    vr_total = vr_one + vr_two + vr_three + vr_four + vr_five + vr_six + vr_seven + vr_eight + vr_nine
    ans = vr_total - (total / 9)
    v_ans = vr_total - ans
    vr_ans = ans / 8
    print("The sum of square of the varible is ", round(ans, 2), " while the variance is :", round(vr_ans, 2))
    print("The Standard Deviation Of The Variance is ", round(math.sqrt(vr_ans), 2))

def variance_10():
    print("Now Enter Values")
    var_one = float(input())
    vr_one = var_one ** 2
    var_two = float(input())
    vr_two = var_two ** 2
    var_three = float(input())
    vr_three = var_three ** 2
    var_four = float(input())
    vr_four = var_four ** 2
    var_five = float(input())
    vr_five = var_five ** 2
    var_six = float(input())
    vr_six = var_six ** 2
    var_seven = float(input())
    vr_seven = var_seven ** 2
    var_eight = float(input())
    vr_eight = var_eight ** 2
    var_nine = float(input())
    vr_nine = var_nine ** 2
    var_ten = float(input())
    vr_ten = var_ten ** 2

    total = var_one + var_two + var_three + var_four + var_five + var_six + var_seven + var_eight + var_nine + var_ten
    total = total**2
    vr_total = vr_one + vr_two + vr_three + vr_four + vr_five + vr_six + vr_seven + vr_eight + vr_nine + vr_ten
    ans = vr_total - (total / 10)
    v_ans = vr_total - ans
    vr_ans = ans / 9
    print("The sum of square of the varible is ", round(ans, 2), " while the variance is :", round(vr_ans, 2))
    print("The Standard Deviation Of The Variance is ", round(math.sqrt(vr_ans), 2))

'''---
            *********************************************************
        ----*This Function Calculates the co-variance of the varible*--------
            *********************************************************
        ---'''

def co_variance():
    print("This program calculates the covariance between two set of varibles and can only take a maximuin of 10 variables")
    print("How many variables do you have")
    variables = int(input('variables'))
    if (variables == 2):
        co_variance_2()
    elif (variables == 3):
        co_variance_3()
    elif (variables == 4):
        co_variance_4()
    elif (variables == 5):
        co_variance_5()
    elif (variables == 6):
        co_variance_6()
    elif (variables == 7):
        co_variance_7()
    elif (variables == 8):
        co_variance_8()
    elif (variables == 9):
        co_variance_9()
    elif (variables == 10):
        co_variance_10()
    else:
        print("you have entered a wrong variable")
    print("Thank you for using sage cal")


def co_variance_2():
    print("Enter the values for you 'X' variable")
    v_one = float(input())
    v_two = float(input())
    v_total = v_one + v_two
#For the y set of variables
    print("Now input values for 'y' variables")
    var_one = float(input())
    var_two = float(input())
    var_total = var_one + var_two
    var_product = (var_total * v_total)/2
    v1 = v_one * var_one
    v2 = v_two * var_two
    s_c = v1 + v2
    E = s_c - var_product
    E = E/1
    #Now summing the product of the two variables

    print("The co-variance of the variable is ", round(E, 2),)


def co_variance_3():
    print("Enter the values for you 'X' variable")
    v_one = float(input())
    v_two = float(input())
    v_three = float(input())
    v_total = v_one + v_two + v_three
    # For the y set of variables
    print("Now input values for 'y' variables")
    var_one = float(input())
    var_two = float(input())
    var_three = float(input())
    var_total = var_one + var_two + var_three
    var_product = (var_total * v_total) / 3
    v1 = v_one * var_one
    v2 = v_two * var_two
    v3 = v_three * var_three
    s_c = v1 + v2 + v3
    E = s_c - var_product
    E = E / 2
    print("The co-variance of the variable : ", round(E, 2),)


def co_variance_4():
    print("Enter the values for you 'X' variable")
    v_one = float(input())
    v_two = float(input())
    v_three = float(input())
    v_four = float(input())
    v_total = v_one + v_two + v_three + v_four
    # For the y set of variables
    print("Now input values for 'y' variables")
    var_one = float(input())
    var_two = float(input())
    var_three = float(input())
    var_four = float(input())
    var_total = var_one + var_two + var_three + var_four
    var_product = (var_total * v_total) / 4
    v1 = v_one * var_one
    v2 = v_two * var_two
    v3 = v_three * var_three
    v4 = v_four * var_four
    s_c = v1 + v2 + v3 + v4
    E = s_c - var_product
    E = E / 3
    print("The co-variance of the variable : ", round(E, 2), )

def co_variance_5():
    print("Enter the values for you 'X' variable")
    v_one = float(input())
    v_two = float(input())
    v_three = float(input())
    v_four = float(input())
    v_five = float(input())
    v_total = v_one + v_two + v_three + v_four + v_five
    # For the y set of variables
    print("Now input values for 'y' variables")
    var_one = float(input())
    var_two = float(input())
    var_three = float(input())
    var_four = float(input())
    var_five = float(input())
    var_total = var_one + var_two + var_three + var_four + var_five
    var_product = (var_total * v_total) / 5
    v1 = v_one * var_one
    v2 = v_two * var_two
    v3 = v_three * var_three
    v4 = v_four * var_four
    v5 = v_five * var_five

    s_c = v1+v2+v3+v4+v5
    E = s_c - var_product
    E = E / 4
    print("The co-variance of the variable : ", round(E, 2), )

def co_variance_6():
    print("Enter the values for you 'X' variable")
    v_one = float(input())
    v_two = float(input())
    v_three = float(input())
    v_four = float(input())
    v_five = float(input())
    v_six = float(input())
    v_total = v_one + v_two + v_three + v_four + v_five + v_six
    # For the y set of variables
    print("Now input values for 'y' variables")
    var_one = float(input())
    var_two = float(input())
    var_three = float(input())
    var_four = float(input())
    var_five = float(input())
    var_six = float(input())
    var_total = var_one + var_two + var_three + var_four + var_five + var_six
    var_product = (var_total * v_total) / 6
    v1 = v_one * var_one
    v2 = v_two * var_two
    v3 = v_three * var_three
    v4 = v_four * var_four
    v5 = v_five * var_five
    v6 = v_six * var_six

    s_c = v1 + v2 + v3 + v4 + v5+v6
    E = s_c - var_product
    E = E / 5
    print("The co-variance of the variable : ", round(E, 2), )


def co_variance_7():
    print("Enter the values for you 'X' variable")
    v_one = float(input())
    v_two = float(input())
    v_three = float(input())
    v_four = float(input())
    v_five = float(input())
    v_six = float(input())
    v_seven = float(input())
    v_total = v_one + v_two + v_three + v_four + v_five + v_six + v_seven
    # For the y set of variables
    print("Now input values for 'y' variables")
    var_one = float(input())
    var_two = float(input())
    var_three = float(input())
    var_four = float(input())
    var_five = float(input())
    var_six = float(input())
    var_seven = float(input())
    var_total = var_one + var_two + var_three + var_four + var_five + var_six + var_seven
    var_product = (var_total * v_total) / 7
    v1 = v_one * var_one
    v2 = v_two * var_two
    v3 = v_three * var_three
    v4 = v_four * var_four
    v5 = v_five * var_five
    v6 = v_six * var_six
    v7 = v_seven * var_seven

    s_c = v1 + v2 + v3 + v4 + v5 + v6 + v7
    E = s_c - var_product
    E = E / 6
    print("The co-variance of the variable : ", round(E, 2), )
def co_variance_8():
    print("Enter the values for you 'X' variable")
    v_one = float(input())
    v_two = float(input())
    v_three = float(input())
    v_four = float(input())
    v_five = float(input())
    v_six = float(input())
    v_seven = float(input())
    v_eight = float(input())
    v_total = v_one + v_two + v_three + v_four + v_five + v_six + v_seven + v_eight
    # For the y set of variables
    print("Now input values for 'y' variables")
    var_one = float(input())
    var_two = float(input())
    var_three = float(input())
    var_four = float(input())
    var_five = float(input())
    var_six = float(input())
    var_seven = float(input())
    var_eight = float(input())
    var_total = var_one + var_two + var_three + var_four + var_five + var_six + var_seven + var_eight
    var_product = (var_total * v_total) / 8
    v1 = v_one * var_one
    v2 = v_two * var_two
    v3 = v_three * var_three
    v4 = v_four * var_four
    v5 = v_five * var_five
    v6 = v_six * var_six
    v7 = v_seven * var_seven
    v8 = v_eight * var_eight

    s_c = v1 + v2 + v3 + v4 + v5 + v6 + v7 + v8
    E = s_c - var_product
    E = E / 7
    print("The co-variance of the variable : ", round(E, 2), )

def co_variance_9():
    print("Enter the values for you 'X' variable")
    v_one = float(input())
    v_two = float(input())
    v_three = float(input())
    v_four = float(input())
    v_five = float(input())
    v_six = float(input())
    v_seven = float(input())
    v_eight = float(input())
    v_nine = float(input())
    v_total = v_one + v_two + v_three + v_four + v_five + v_six + v_seven + v_eight + v_nine
    # For the y set of variables
    print("Now input values for 'y' variables")
    var_one = float(input())
    var_two = float(input())
    var_three = float(input())
    var_four = float(input())
    var_five = float(input())
    var_six = float(input())
    var_seven = float(input())
    var_eight = float(input())
    var_nine = float(input())
    var_total = var_one + var_two + var_three + var_four + var_five + var_six + var_seven + var_eight + var_nine
    var_product = (var_total * v_total) / 9
    v1 = v_one * var_one
    v2 = v_two * var_two
    v3 = v_three * var_three
    v4 = v_four * var_four
    v5 = v_five * var_five
    v6 = v_six * var_six
    v7 = v_seven * var_seven
    v8 = v_eight * var_eight
    v9 = v_nine * var_nine
    s_c = v1 + v2 + v3 + v4 + v5 + v6 + v7 + v8 + v9
    E = s_c - var_product
    E = E / 8
    print("The co-variance of the variable : ", round(E, 2), )

def co_variance_10():
    print("Enter the values for you 'X' variable")
    v_one = float(input())
    v_two = float(input())
    v_three = float(input())
    v_four = float(input())
    v_five = float(input())
    v_six = float(input())
    v_seven = float(input())
    v_eight = float(input())
    v_nine = float(input())
    v_ten = float(input())
    v_total = v_one + v_two + v_three + v_four + v_five + v_six + v_seven + v_eight + v_nine + v_ten
    # For the y set of variables
    print("Now input values for 'y' variables")
    var_one = float(input())
    var_two = float(input())
    var_three = float(input())
    var_four = float(input())
    var_five = float(input())
    var_six = float(input())
    var_seven = float(input())
    var_eight = float(input())
    var_nine = float(input())
    var_ten = float(input())
    var_total = var_one + var_two + var_three + var_four + var_five + var_six + var_seven + var_eight + var_nine + var_ten
    var_product = (var_total * v_total) / 10
    v1 = v_one * var_one
    v2 = v_two * var_two
    v3 = v_three * var_three
    v4 = v_four * var_four
    v5 = v_five * var_five
    v6 = v_six * var_six
    v7 = v_seven * var_seven
    v8 = v_eight * var_eight
    v9 = v_nine * var_nine
    v10 = v_ten * var_ten

    s_c = v1 + v2 + v3 + v4 + v5 + v6 + v7 + v8 + v9 + v10
    E = s_c - var_product
    E = E / 9
    print("The co-variance of the variable : ", round(E, 2), )


'''---
            *********************************************************
        ----*This Function calculate For The Correlation Co-variance*--------
            *********************************************************
        ---'''
def cr_variance():
    print("This program calculates the mean of a set of varibles and can only take a maximuin of 10 variables")
    print("How many variables do you have")
    variables = int(input('variables'))
    if (variables == 2):
        cr_variance_2()
    elif(variables == 3):
        cr_variance_3()
    elif(variables == 4):
        cr_variance_4()
    elif(variables == 5):
        cr_variance_5()
    elif(variables == 6):
        cr_variance_6()
    elif(variables == 7):
        cr_variance_7()
    elif(variables == 8):
        cr_variance_8()
    elif(variables == 9):
        cr_variance_9()
    elif(variables == 10):
        cr_variance_10()
    print("Thank you for using sage cal")
def cr_variance_2():
    print("Enter the values for you 'X' variable")
    v_one = float(input())
    cr_one = v_one ** 2
    v_two = float(input())
    cr_two = v_two ** 2

    # For the y set of variables
    print("Now input values for 'y' variables")
    var_one = float(input())
    cr_1 = var_one ** 2
    var_two = float(input())
    cr_2 = var_two ** 2

    v_one_1 = v_one * var_one  # product of X and Y
    v_two_2 = v_two * var_two

    v_1 = cr_one * cr_1  # product of square of X and square of Y
    v_2 = cr_two * cr_2


    v_one_s = v_one_1 + v_two_2   # sum of the product of X and Y
    v_1_s = v_1 + v_2   # sum of the product of the square of X and square of Y
    v_one_T = v_one + v_two    # sum of X
    v_one_T_2 = cr_one + cr_two   # sum of X squared
    var_one_1_y = var_one + var_two   # sum of Y
    var_one_y = cr_1 + cr_2    # sum of the square of y
    v_one_s_T = ((v_one_s - ((var_one_1_y * v_one_T) / 2)) / 1)  # sum of product
    v_one_root = ((v_one_T_2 - ((v_one_T ** 2) / 2)) /1 )  # um of square of X
    v_one_root_1 = ((var_one_y - ((var_one_1_y ** 2) / 2)) / 1)  # sum of square of Y
    v_one_root_t = math.sqrt(v_one_root) * math.sqrt(v_one_root_1)  # product of the sum of square of X and the sum of square of Y
    ans = (v_one_s_T) / (v_one_root_t)
    # Now summing the product of the two variables
    print("The correlation co-variance of the variable is ", round(ans, 4), )


def cr_variance_3():
    print("Enter the values for you 'X' variable")

    v_one = float(input())
    cr_one = v_one ** 2
    v_two = float(input())
    cr_two = v_two ** 2
    v_three = float(input())
    cr_three = v_three ** 2

    # For the y set of variables
    print("Now input values for 'y' variables")
    var_one = float(input())
    cr_1 = var_one ** 2
    var_two = float(input())
    cr_2 = var_two ** 2
    var_three = float(input())
    cr_3 = var_three ** 2

    v_one_1 = v_one * var_one  # product of X and Y
    v_two_2 = v_two * var_two
    v_three_3 = v_three * var_three

    v_1 = cr_one * cr_1  # product of square of X and square of Y
    v_2 = cr_two * cr_2
    v_3 = cr_three * cr_3

    v_one_s = v_one_1 + v_two_2 + v_three_3  # sum of the product of X and Y
    v_1_s = v_1 + v_2 + v_3   # sum of the product of the square of X and square of Y
    v_one_T = v_one + v_two + v_three   # sum of X
    v_one_T_2 = cr_one + cr_two + cr_three   # sum of X squared
    var_one_1_y = var_one + var_two + var_three  # sum of Y
    var_one_y = cr_1 + cr_2 + cr_3   # sum of the square of y
    v_one_s_T = ((v_one_s - ((var_one_1_y * v_one_T) / 3)) / 2)  # sum of product
    v_one_root = ((v_one_T_2 - ((v_one_T ** 2) / 3)) /2 )  # um of square of X
    v_one_root_1 = ((var_one_y - ((var_one_1_y ** 2) / 3)) / 2)  # sum of square of Y
    v_one_root_t = math.sqrt(v_one_root) * math.sqrt(v_one_root_1)  # product of the sum of square of X and the sum of square of Y
    ans = (v_one_s_T) / (v_one_root_t)
    # Now summing the product of the two variables
    print("The correlation co-variance of the variable is ", round(ans, 4), )

    print("The correlation co-variance of the variable is ", round(ans, 4), )

def cr_variance_4():
    print("Enter the values for you 'X' variable")
    v_one = float(input())
    cr_one = v_one ** 2
    v_two = float(input())
    cr_two = v_two ** 2
    v_three = float(input())
    cr_three = v_three ** 2
    v_four = float(input())
    cr_four = v_four ** 2

    # For the y set of variables
    print("Now input values for 'y' variables")
    var_one = float(input())
    cr_1 = var_one ** 2
    var_two = float(input())
    cr_2 = var_two ** 2
    var_three = float(input())
    cr_3 = var_three ** 2
    var_four = float(input())
    cr_4 = var_four ** 2

    v_one_1 = v_one * var_one  # product of X and Y
    v_two_2 = v_two * var_two
    v_three_3 = v_three * var_three
    v_four_4 = v_four * var_four

    v_1 = cr_one * cr_1  # product of square of X and square of Y
    v_2 = cr_two * cr_2
    v_3 = cr_three * cr_3
    v_4 = cr_four * cr_4
    v_one_s = v_one_1 + v_two_2 + v_three_3 + v_four_4  # sum of the product of X and Y
    v_1_s = v_1 + v_2 + v_3 + v_4 # sum of the product of the square of X and square of Y
    v_one_T = v_one + v_two + v_three + v_four   # sum of X
    v_one_T_2 = cr_one + cr_two + cr_three + cr_four # sum of X squared
    var_one_1_y = var_one + var_two + var_three + var_four   # sum of Y
    var_one_y = cr_1 + cr_2 + cr_3 + cr_4   # sum of the square of y
    v_one_s_T = ((v_one_s - ((var_one_1_y * v_one_T) / 4)) / 3)  # sum of product
    v_one_root = ((v_one_T_2 - ((v_one_T ** 2) / 4)) / 3)  # sum of square of X
    v_one_root_1 = ((var_one_y - ((var_one_1_y ** 2) / 4)) / 3)  # sum of square of Y
    v_one_root_t = math.sqrt(v_one_root) * math.sqrt(v_one_root_1)  # product of the sum of square of X and the sum of square of Y
    ans = (v_one_s_T) / (v_one_root_t)
    # Now summing the product of the two variables
    print("The correlation co-variance of the variable is ", round(ans, 4), )

    print("The correlation co-variance of the variable is ", round(ans, 4), )


def cr_variance_5():
    print("Enter the values for you 'X' variable")

    v_one = float(input())
    cr_one = v_one ** 2
    v_two = float(input())
    cr_two = v_two ** 2
    v_three = float(input())
    cr_three = v_three ** 2
    v_four = float(input())
    cr_four = v_four ** 2
    v_five = float(input())
    cr_five = v_five ** 2
    # For the y set of variables
    print("Now input values for 'y' variables")
    var_one = float(input())
    cr_1 = var_one ** 2
    var_two = float(input())
    cr_2 = var_two ** 2
    var_three = float(input())
    cr_3 = var_three ** 2
    var_four = float(input())
    cr_4 = var_four ** 2
    var_five = float(input())
    cr_5 = var_five ** 2
    v_one_1 = v_one * var_one  # product of X and Y
    v_two_2 = v_two * var_two
    v_three_3 = v_three * var_three
    v_four_4 = v_four * var_four
    v_five_5 = v_five * var_five
    v_1 = cr_one * cr_1  # product of square of X and square of Y
    v_2 = cr_two * cr_2
    v_3 = cr_three * cr_3
    v_4 = cr_four * cr_4
    v_5 = cr_five * cr_5
    v_one_s = v_one_1 + v_two_2 + v_three_3 + v_four_4 + v_five_5   # sum of the product of X and Y
    v_1_s = v_1 + v_2 + v_3 + v_4 + v_5   # sum of the product of the square of X and square of Y
    v_one_T = v_one + v_two + v_three + v_four + v_five   # sum of X
    v_one_T_2 = cr_one + cr_two + cr_three + cr_four + cr_five   # sum of X squared
    var_one_1_y = var_one + var_two + var_three + var_four + var_five  # sum of Y
    var_one_y = cr_1 + cr_2 + cr_3 + cr_4 + cr_5   # sum of the square of y
    v_one_s_T = ((v_one_s - ((var_one_1_y * v_one_T) / 5)) / 4)  # sum of product
    v_one_root = ((v_one_T_2 - ((v_one_T ** 2) / 5)) / 4)  # sum of square of X
    v_one_root_1 = ((var_one_y - ((var_one_1_y ** 2) / 5)) / 4)  # sum of square of Y
    v_one_root_t = math.sqrt(v_one_root) * math.sqrt(v_one_root_1)  # product of the sum of square of X and the sum of square of Y
    ans = (v_one_s_T) / (v_one_root_t)
    # Now summing the product of the two variables
    print("The correlation co-variance of the variable is ", round(ans, 4), )


def cr_variance_6():
    print("Enter the values for you 'X' variable")
    v_one = float(input())
    cr_one = v_one ** 2
    v_two = float(input())
    cr_two = v_two ** 2
    v_three = float(input())
    cr_three = v_three ** 2
    v_four = float(input())
    cr_four = v_four ** 2
    v_five = float(input())
    cr_five = v_five ** 2
    v_six = float(input())
    cr_six = v_six **2
    # For the y set of variables
    print("Now input values for 'y' variables")
    var_one = float(input())
    cr_1 = var_one ** 2
    var_two = float(input())
    cr_2 = var_two ** 2
    var_three = float(input())
    cr_3 = var_three ** 2
    var_four = float(input())
    cr_4 = var_four ** 2
    var_five = float(input())
    cr_5 = var_five ** 2
    var_six = float(input())
    cr_6 = var_six ** 2
    v_one_1 = v_one * var_one  # product of X and Y
    v_two_2 = v_two * var_two
    v_three_3 = v_three * var_three
    v_four_4 = v_four * var_four
    v_five_5 = v_five * var_five
    v_six_6 = v_six * var_six
    v_1 = cr_one * cr_1 # product of square of X and square of Y
    v_2 = cr_two * cr_2
    v_3 = cr_three * cr_3
    v_4 = cr_four * cr_4
    v_5 = cr_five * cr_5
    v_6 = cr_six * cr_6
    v_one_s = v_one_1 + v_two_2 + v_three_3 + v_four_4 + v_five_5 + v_six_6 # sum of the product of X and Y
    v_1_s = v_1 + v_2 + v_3 + v_4 + v_5 + v_6 # sum of the product of the square of X and square of Y
    v_one_T = v_one + v_two + v_three + v_four + v_five + v_six # sum of X
    v_one_T_2 = cr_one + cr_two + cr_three + cr_four + cr_five + cr_six # sum of X squared
    var_one_1_y = var_one + var_two + var_three + var_four + var_five + var_six # sum of Y
    var_one_y = cr_1 + cr_2 + cr_3 + cr_4 + cr_5 + cr_6 # sum of the square of y
    v_one_s_T = ((v_one_s - ((var_one_1_y * v_one_T) / 6 )) / 5) # sum of product
    v_one_root = ((v_one_T_2 - ((v_one_T ** 2) / 6 )) / 5) # sum of square of X
    v_one_root_1 = ((var_one_y - ((var_one_1_y ** 2) / 6)) / 5)  # sum of square of Y
    v_one_root_t = math.sqrt(v_one_root) * math.sqrt(v_one_root_1)  # product of the sum of square of X and the sum of square of Y
    ans = (v_one_s_T) / (v_one_root_t)
    # Now summing the product of the two variables
    print("The correlation co-variance of the variable is ", round(ans, 4), )


def cr_variance_7():
    print("Enter the values for you 'X' variable")

    v_one = float(input())
    cr_one = v_one ** 2
    v_two = float(input())
    cr_two = v_two ** 2
    v_three = float(input())
    cr_three = v_three ** 2
    v_four = float(input())
    cr_four = v_four ** 2
    v_five = float(input())
    cr_five = v_five ** 2
    v_six = float(input())
    cr_six = v_six ** 2
    v_seven = float(input())
    cr_seven = v_seven ** 2
    # For the y set of variables
    print("Now input values for 'y' variables")
    var_one = float(input())
    cr_1 = var_one ** 2
    var_two = float(input())
    cr_2 = var_two ** 2
    var_three = float(input())
    cr_3 = var_three ** 2
    var_four = float(input())
    cr_4 = var_four ** 2
    var_five = float(input())
    cr_5 = var_five ** 2
    var_six = float(input())
    cr_6 = var_six ** 2
    var_seven = float(input())
    cr_7 = var_seven ** 2
    v_one_1 = v_one * var_one  # product of X and Y
    v_two_2 = v_two * var_two
    v_three_3 = v_three * var_three
    v_four_4 = v_four * var_four
    v_five_5 = v_five * var_five
    v_six_6 = v_six * var_six
    v_seven_7 = v_seven * var_seven
    v_1 = cr_one * cr_1  # product of square of X and square of Y
    v_2 = cr_two * cr_2
    v_3 = cr_three * cr_3
    v_4 = cr_four * cr_4
    v_5 = cr_five * cr_5
    v_6 = cr_six * cr_6
    v_7 = cr_seven * cr_7

    v_one_s = v_one_1 + v_two_2 + v_three_3 + v_four_4 + v_five_5 + v_six_6 + v_seven_7 # sum of the product of X and Y
    v_1_s = v_1 + v_2 + v_3 + v_4 + v_5 + v_6 + v_7 # sum of the product of the square of X and square of Y
    v_one_T = v_one + v_two + v_three + v_four + v_five + v_six + v_seven # sum of X
    v_one_T_2 = cr_one + cr_two + cr_three + cr_four + cr_five + cr_six + cr_seven # sum of X squared
    var_one_1_y = var_one + var_two + var_three + var_four + var_five + var_six + var_seven # sum of Y
    var_one_y = cr_1 + cr_2 + cr_3 + cr_4 + cr_5 + cr_6 + cr_7 # sum of the square of y
    v_one_s_T = ((v_one_s - ((var_one_1_y * v_one_T) / 7)) / 6)  # sum of product
    v_one_root = ((v_one_T_2 - ((v_one_T ** 2) / 7)) / 6)  # sum of square of X
    v_one_root_1 = ((var_one_y - ((var_one_1_y ** 2) / 7)) / 6)  # sum of square of Y
    v_one_root_t = math.sqrt(v_one_root) * math.sqrt(v_one_root_1)  # product of the sum of square of X and the sum of square of Y
    ans = (v_one_s_T) / (v_one_root_t)
    # Now summing the product of the two variables
    print("The correlation co-variance of the variable is ", round(ans, 4), )

def cr_variance_8():
    print("Enter the values for you 'X' variable")

    v_one = float(input())
    cr_one = v_one ** 2
    v_two = float(input())
    cr_two = v_two ** 2
    v_three = float(input())
    cr_three = v_three ** 2
    v_four = float(input())
    cr_four = v_four ** 2
    v_five = float(input())
    cr_five = v_five ** 2
    v_six = float(input())
    cr_six = v_six ** 2
    v_seven = float(input())
    cr_seven = v_seven ** 2
    v_eight = float(input())
    cr_eight = v_eight ** 2
    # For the y set of variables
    print("Now input values for 'y' variables")
    var_one = float(input())
    cr_1 = var_one ** 2
    var_two = float(input())
    cr_2 = var_two ** 2
    var_three = float(input())
    cr_3 = var_three ** 2
    var_four = float(input())
    cr_4 = var_four ** 2
    var_five = float(input())
    cr_5 = var_five ** 2
    var_six = float(input())
    cr_6 = var_six ** 2
    var_seven = float(input())
    cr_7 = var_seven ** 2
    var_eight = float(input())
    cr_8 = var_eight ** 2
    v_one_1 = v_one * var_one  # product of X and Y
    v_two_2 = v_two * var_two
    v_three_3 = v_three * var_three
    v_four_4 = v_four * var_four
    v_five_5 = v_five * var_five
    v_six_6 = v_six * var_six
    v_seven_7 = v_seven * var_seven
    v_eight_8 = v_eight * var_eight
    v_1 = cr_one * cr_1  # product of square of X and square of Y
    v_2 = cr_two * cr_2
    v_3 = cr_three * cr_3
    v_4 = cr_four * cr_4
    v_5 = cr_five * cr_5
    v_6 = cr_six * cr_6
    v_7 = cr_seven * cr_7
    v_8 = cr_eight * cr_8

    v_one_s = v_one_1 + v_two_2 + v_three_3 + v_four_4 + v_five_5 + v_six_6 + v_seven_7 + v_eight_8 # sum of the product of X and Y
    v_1_s = v_1 + v_2 + v_3 + v_4 + v_5 + v_6 + v_7 + v_8 # sum of the product of the square of X and square of Y
    v_one_T = v_one + v_two + v_three + v_four + v_five + v_six + v_seven + v_eight # sum of X
    v_one_T_2 = cr_one + cr_two + cr_three + cr_four + cr_five + cr_six + cr_seven + cr_eight # sum of X squared
    var_one_1_y = var_one + var_two + var_three + var_four + var_five + var_six + var_seven + var_eight # sum of Y
    var_one_y = cr_1 + cr_2 + cr_3 + cr_4 + cr_5 + cr_6 + cr_7 + cr_8 # sum of the square of y
    v_one_s_T = ((v_one_s - ((var_one_1_y * v_one_T) / 8)) / 7)  # sum of product
    v_one_root = ((v_one_T_2 - ((v_one_T ** 2) / 8)) / 7)  # sum of square of X
    v_one_root_1 = ((var_one_y - ((var_one_1_y ** 2) / 8)) / 7)  # sum of square of Y
    v_one_root_t = math.sqrt(v_one_root) * math.sqrt(v_one_root_1)  # product of the sum of square of X and the sum of square of Y
    ans = (v_one_s_T) / (v_one_root_t)
    # Now summing the product of the two variables
    print("The correlation co-variance of the variable is ", round(ans, 4), )

def cr_variance_9():
    print("Enter the values for you 'X' variable")

    v_one = float(input())
    cr_one = v_one ** 2
    v_two = float(input())
    cr_two = v_two ** 2
    v_three = float(input())
    cr_three = v_three ** 2
    v_four = float(input())
    cr_four = v_four ** 2
    v_five = float(input())
    cr_five = v_five ** 2
    v_six = float(input())
    cr_six = v_six ** 2
    v_seven = float(input())
    cr_seven = v_seven ** 2
    v_eight = float(input())
    cr_eight = v_eight ** 2
    v_nine = float(input())
    cr_nine = v_nine ** 2
    # For the y set of variables
    print("Now input values for 'y' variables")
    var_one = float(input())
    cr_1 = var_one ** 2
    var_two = float(input())
    cr_2 = var_two ** 2
    var_three = float(input())
    cr_3 = var_three ** 2
    var_four = float(input())
    cr_4 = var_four ** 2
    var_five = float(input())
    cr_5 = var_five ** 2
    var_six = float(input())
    cr_6 = var_six ** 2
    var_seven = float(input())
    cr_7 = var_seven ** 2
    var_eight = float(input())
    cr_8 = var_eight ** 2
    var_nine = float(input())
    cr_9 = var_nine ** 2
    v_one_1 = v_one * var_one  # product of X and Y
    v_two_2 = v_two * var_two
    v_three_3 = v_three * var_three
    v_four_4 = v_four * var_four
    v_five_5 = v_five * var_five
    v_six_6 = v_six * var_six
    v_seven_7 = v_seven * var_seven
    v_eight_8 = v_eight * var_eight
    v_nine_9 = v_nine * var_nine
    v_1 = cr_one * cr_1  # product of square of X and square of Y
    v_2 = cr_two * cr_2
    v_3 = cr_three * cr_3
    v_4 = cr_four * cr_4
    v_5 = cr_five * cr_5
    v_6 = cr_six * cr_6
    v_7 = cr_seven * cr_7
    v_8 = cr_eight * cr_8
    v_9 = cr_nine * cr_9

    v_one_s = v_one_1 + v_two_2 + v_three_3 + v_four_4 + v_five_5 + v_six_6 + v_seven_7 + v_eight_8 + v_nine_9 # sum of the product of X and Y
    v_1_s = v_1 + v_2 + v_3 + v_4 + v_5 + v_6 + v_7 + v_8 + v_9 # sum of the product of the square of X and square of Y
    v_one_T = v_one + v_two + v_three + v_four + v_five + v_six + v_seven + v_eight + v_nine# sum of X
    v_one_T_2 = cr_one + cr_two + cr_three + cr_four + cr_five + cr_six + cr_seven + cr_eight + cr_nine# sum of X squared
    var_one_1_y = var_one + var_two + var_three + var_four + var_five + var_six + var_seven + var_eight + var_nine# sum of Y
    var_one_y = cr_1 + cr_2 + cr_3 + cr_4 + cr_5 + cr_6 + cr_7 + cr_8 + cr_9# sum of the square of y
    v_one_s_T = ((v_one_s - ((var_one_1_y * v_one_T) / 9)) / 8)  # sum of product
    v_one_root = ((v_one_T_2 - ((v_one_T ** 2) / 9)) / 8)  # sum of square of X
    v_one_root_1 = ((var_one_y - ((var_one_1_y ** 2) / 9)) / 8)  # sum of square of Y
    v_one_root_t = math.sqrt(v_one_root) * math.sqrt(v_one_root_1)  # product of the sum of square of X and the sum of square of Y
    ans = (v_one_s_T) / (v_one_root_t)
    print("The correlation co-variance of the variable is ", round(ans, 4), )

def cr_variance_10():
    print("Enter the values for you 'X' variable")

    v_one = float(input())
    cr_one = v_one ** 2
    v_two = float(input())
    cr_two = v_two ** 2
    v_three = float(input())
    cr_three = v_three ** 2
    v_four = float(input())
    cr_four = v_four ** 2
    v_five = float(input())
    cr_five = v_five ** 2
    v_six = float(input())
    cr_six = v_six ** 2
    v_seven = float(input())
    cr_seven = v_seven ** 2
    v_eight = float(input())
    cr_eight = v_eight ** 2
    v_nine = float(input())
    cr_nine = v_nine ** 2
    v_ten = float(input())
    cr_ten = v_ten ** 2

    # For the y set of variables
    print("Now input values for 'y' variables")
    var_one = float(input())
    cr_1 = var_one ** 2
    var_two = float(input())
    cr_2 = var_two ** 2
    var_three = float(input())
    cr_3 = var_three ** 2
    var_four = float(input())
    cr_4 = var_four ** 2
    var_five = float(input())
    cr_5 = var_five ** 2
    var_six = float(input())
    cr_6 = var_six ** 2
    var_seven = float(input())
    cr_7 = var_seven ** 2
    var_eight = float(input())
    cr_8 = var_eight ** 2
    var_nine = float(input())
    cr_9 = var_nine ** 2
    var_ten = float(input())
    cr_10 = var_ten ** 2

    v_one_1 = v_one * var_one  # product of X and Y
    v_two_2 = v_two * var_two
    v_three_3 = v_three * var_three
    v_four_4 = v_four * var_four
    v_five_5 = v_five * var_five
    v_six_6 = v_six * var_six
    v_seven_7 = v_seven * var_seven
    v_eight_8 = v_eight * var_eight
    v_nine_9 = v_nine * var_nine
    v_ten_10 = v_ten * var_ten
    v_1 = cr_one * cr_1  # product of square of X and square of Y
    v_2 = cr_two * cr_2
    v_3 = cr_three * cr_3
    v_4 = cr_four * cr_4
    v_5 = cr_five * cr_5
    v_6 = cr_six * cr_6
    v_7 = cr_seven * cr_7
    v_8 = cr_eight * cr_8
    v_9 = cr_nine * cr_9
    v_10 = cr_nine * cr_10

    v_one_s = v_one_1 + v_two_2 + v_three_3 + v_four_4 + v_five_5 + v_six_6 + v_seven_7 + v_eight_8 + v_nine_9 + v_ten_10  # sum of the product of X and Y
    v_1_s = v_1 + v_2 + v_3 + v_4 + v_5 + v_6 + v_7 + v_8 + v_9 + v_10  # sum of the product of the square of X and square of Y
    v_one_T = v_one + v_two + v_three + v_four + v_five + v_six + v_seven + v_eight + v_nine + v_ten # sum of X
    v_one_T_2 = cr_one + cr_two + cr_three + cr_four + cr_five + cr_six + cr_seven + cr_eight + cr_nine + cr_ten # sum of X squared
    var_one_1_y = var_one + var_two + var_three + var_four + var_five + var_six + var_seven + var_eight + var_nine + var_ten # sum of Y
    var_one_y = cr_1 + cr_2 + cr_3 + cr_4 + cr_5 + cr_6 + cr_7 + cr_8 + cr_9 + cr_10 # sum of the square of y
    v_one_s_T = ((v_one_s - ((var_one_1_y * v_one_T) / 10)) / 9)  # sum of product
    v_one_root = ((v_one_T_2 - ((v_one_T ** 2) / 10)) / 9)  # sum of square of X
    v_one_root_1 = ((var_one_y - ((var_one_1_y ** 2) / 10)) / 9)  # sum of square of Y
    v_one_root_t = math.sqrt(v_one_root) * math.sqrt(v_one_root_1)  # product of the sum of square of X and the sum of square of Y
    ans = (v_one_s_T) / (v_one_root_t)
    print("The correlation co-variance of the variable is ", round(ans, 4), )

'''---
            ************************************************************
        ----*This Function Calculate For The Determinant Of The Matrix *--------
            ************************************************************
        ---'''

def det():
    print("input the matrix you wish to find it's determinant")
    print("[a1", "a2", "a3]")
    print("[b1", "b2", "b3]")
    print("[c1", "c2", "c3]")
    a1 = int(input('a1'))
    a2 = int(input('a2'))
    a3 = int(input('a3'))
    b1 = int(input('b1'))
    b2 = int(input('b2'))
    b3 = int(input('b3'))
    c1 = int(input('c1'))
    c2 = int(input('c2'))
    c3 = int(input('c3'))
    print("Det|a1| = ",a1,"(", "(", c3,"*", b2 ,")", "-","(", c2 ,"*", b3, ")",")")
    dec_a = a1*((c3*b2)-(c2 * b3))
    print("Det|a2| = ", a2, "(","(", c3 ,"*", b1 ,")", " - ", "(", c1, " * ", b3, ")",")")
    dec_b = a2 * ((c3 * b1) - (c1 * b3))
    print("Det|a3| = ", a3, "(","(", c2 , "*", b1 ,")", " - ","(", c1, " * ", b2, ")",")")
    dec_c = a3 * ((c2 * b1) - (c1 * b2))
    print("(",dec_a, "-", dec_b, "+", dec_c,")")
    dec_t = dec_a - dec_b + dec_c
    print ("The Determinant Of The Matrix Is ", "Det A =", dec_t)

    '''---
                *******************************************
            ----*This Function Does Matrix Multiplication *--------
                *******************************************
            ---'''

def detmul():
    print("input for matrix 'A' ")
    print("[a1", "a2", "a3]")
    print("[b1", "b2", "b3]")
    print("[c1", "c2", "c3]")
    a1 = int(input('a1'))
    a2 = int(input('a2'))
    a3 = int(input('a3'))
    b1 = int(input('b1'))
    b2 = int(input('b2'))
    b3 = int(input('b3'))
    c1 = int(input('c1'))
    c2 = int(input('c2'))
    c3 = int(input('c3'))
    print("input for matrix 'B' ")

    print("[A1", "A2", "A3]")
    print("[B1", "B2", "B3]")
    print("[C1", "C2", "C3]")
    A1 = int(input('A1'))
    A2 = int(input('A2'))
    A3 = int(input('A3'))
    B1 = int(input('B1'))
    B2 = int(input('B2'))
    B3 = int(input('B3'))
    C1 = int(input('C1'))
    C2 = int(input('C2'))
    C3 = int(input('C3'))
    print("X1 = ","[", a1 ,"*", A1,"(", a2 , "*", B1, ")","(", a3, "*", C1, ")", "]")
    print("X2 = ", "[", a1, "*", A2, "(", a2, "*", B2, ")", "(", a3, "*", C2, ")", "]")
    print("X3 = ", "[", a1, "*", A3, "(", a2, "*", B3, ")", "(", a3, "*", C3, ")", "]")
    dec_a1 = ((a1 * A1) + (a2 * B1) + (a3 * C1))
    dec_a2 = ((a1 * A2) + (a2 * B2) + (a3 * C2))
    dec_a3 = ((a1 * A3) + (a2 * B3) + (a3 * C3))
    print("Y1 = ", "[", b1, "*", A1, "(", b2, "*", B1, ")", "(", b3, "*", C1, ")", "]")
    print("Y2 = ", "[", b1, "*", A2, "(", b2, "*", B2, ")", "(", b3, "*", C2, ")", "]")
    print("Y3 = ", "[", b1, "*", A3, "(", b2, "*", B3, ")", "(", b3, "*", C3, ")", "]")
    dec_b1 = ((b1 * A1) + (b2 * B1) + (b3 * C1))
    dec_b2 = ((b1 * A2) + (b2 * B2) + (b3 * C2))
    dec_b3 = ((b1 * A3) + (b2 * B3) + (b3 * C3))
    print("Z1 = ", "[", c1, "*", A1, "(", c2, "*", B1, ")", "(", c3, "*", C1, ")", "]")
    print("Z2 = ", "[", c1, "*", A2, "(", c2, "*", B2, ")", "(", c3, "*", C2, ")", "]")
    print("Z3 = ", "[", c1, "*", A3, "(", c2, "*", B3, ")", "(", c3, "*", C3, ")", "]")
    dec_c1 = ((c1 * A1) + (c2 * B1) + (c3 * C1))
    dec_c2 = ((c1 * A2) + (c2 * B2) + (c3 * C2))
    dec_c3 = ((c1 * A3) + (c2 * B3) + (c3 * C3))

    print("The product Of The Matrix Is :",)
    print("[",dec_a1, dec_a2, dec_a3,"]")
    print("[",dec_b1, dec_b2, dec_b3,"]")
    print("[",dec_c1, dec_c2, dec_c3,"]")

'''
     *************************************************
 ----*This Function Calculates The Sum Of Two Matrix *--------
     *************************************************
'''

def add_mat():
    print("input for matrix 'A' ")
    print("[a1", "a2", "a3]")
    print("[b1", "b2", "b3]")
    print("[c1", "c2", "c3]")
    a1 = int(input('a1'))
    a2 = int(input('a2'))
    a3 = int(input('a3'))
    b1 = int(input('b1'))
    b2 = int(input('b2'))
    b3 = int(input('b3'))
    c1 = int(input('c1'))
    c2 = int(input('c2'))
    c3 = int(input('c3'))
    print("input for matrix 'B' ")
    print("input for matrix 'A' ")
    print("[A1", "A2", "A3]")
    print("[B1", "B2", "B3]")
    print("[C1", "C2", "C3]")
    A1 = int(input('A1'))
    A2 = int(input('A2'))
    A3 = int(input('A3'))
    B1 = int(input('B1'))
    B2 = int(input('B2'))
    B3 = int(input('B3'))
    C1 = int(input('C1'))
    C2 = int(input('C2'))
    C3 = int(input('C3'))
    add_a1 = (a1 + A1)
    add_a2 = (a2 + A2)
    add_a3 = (a3 + A3)
    add_b1 = (b1 + B1)
    add_b2 = (b2 + B2)
    add_b3 = (b3 + B3)
    add_c1 = (c1 + C1)
    add_c2 = (c2 + C2)
    add_c3 = (c3 + C3)

    print("Y1 = ", "[", a1, "+", A1, "(", a2, "+", A2, ")", "(", a3, "+", A3, ")", "]")
    print("Y2 = ", "[", b1, "+", B1, "(", b2, "+", B2, ")", "(", b3, "+", B2, ")", "]")
    print("Y3 = ", "[", c1, "+", C1, "(", c2, "+", C2, ")", "(", c3, "+", C3, ")", "]")

    print("The sum Of The Matrix Is :", )
    print("[", add_a1, add_a2, add_a3, "]")
    print("[", add_b1, add_b2, add_b3, "]")
    print("[", add_c1, add_c2, add_c3, "]")


'''---
            ************************************************************************************************************
        ----*This Function Calculates The Inverse Of The Matrix And Also Calculates For Missing Variables Of X,Y, and Z *--------
            ************************************************************************************************************
        ---'''
def inverse_matix():
    print("input the matrix you wish to find it's determinant")
    print("[a1", "a2", "a3]")
    print("[b1", "b2", "b3]")
    print("[c1", "c2", "c3]")
    a1 = int(input('a1'))
    a2 = int(input('a2'))
    a3 = int(input('a3'))
    b1 = int(input('b1'))
    b2 = int(input('b2'))
    b3 = int(input('b3'))
    c1 = int(input('c1'))
    c2 = int(input('c2'))
    c3 = int(input('c3'))
    print("Det|a1| = ", a1, "(", "(", c3, "*", b2, ")", "-", "(", c2, "*", b3, ")", ")")
    dec_a = a1 * ((c3 * b2) - (c2 * b3))
    print("Det|a2| = ", a2, "(", "(", c3, "*", b1, ")", " - ", "(", c1, " * ", b3, ")", ")")
    dec_b = a2 * ((c3 * b1) - (c1 * b3))
    print("Det|a3| = ", a3, "(", "(", c2, "*", b1, ")", " - ", "(", c1, " * ", b2, ")", ")")
    dec_c = a3 * ((c2 * b1) - (c1 * b2))
    print("(", dec_a, "-", dec_b, "+", dec_c, ")")
    dec_t = dec_a - dec_b + dec_c

    aa1 =(+1 * ((c3 * b2) - (c2 * b3)))
    aa2 = (-1 * ((c3 * b1) - (c1 * b3)))
    aa3 = (+1 * ((c2 * b1) - (c1 * b2)))
    bb1 = (-1 * ((c3 * a2) - (c2 * a3)))
    bb2 = (+1 * ((c3 * a1) - (c1 * a3)))
    bb3 = (-1 * ((c2 * a1) - (c1 * a2)))
    cc1 = (+1 * ((b3 * a2) - (b2 * a3)))
    cc2 = (-1 * ((b3 * a1) - (b1 * a3)))
    cc3 = (+1 * ((b2 * a1) - (b1 * a2)))
    print("The Determinant Of The Matrix Is ", "Det A =", dec_t)

    aa1 = aa1/dec_t
    aa2 = aa2 / dec_t
    aa3 = aa3 / dec_t
    bb1 = bb1 / dec_t
    bb2 = bb2 / dec_t
    bb3 = bb3 / dec_t
    cc1 = cc1 / dec_t
    cc2 = cc2 / dec_t
    cc3 = cc3 / dec_t
    print("the inverse of the matrix is :")
    print("[", aa1, bb1, cc1,"]")
    print("[", aa2, bb2," ", cc2,"]")
    print("[", aa3, bb3,cc3, "]")
    print("now put in the values for X, Y, Z")
    x = float(input('X'))
    y = float(input('Y'))
    z = float(input('Z'))
    X = ((aa1 * x) + (bb1 * y)+ (cc1 * z))
    Y = ((aa2 * x) + (bb2 * y) + (cc2 * z))
    Z = ((aa3 * x) + (bb3 * y) + (cc3 * z))
    print("The values For x is :", X)
    print("The values For y is :", Y)
    print("The values For z is :", Z)

'''---***Function Call***---'''
welcome()
