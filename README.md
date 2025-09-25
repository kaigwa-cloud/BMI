def calculate ():
    """bmi  calculator"""
    weight = float(input("Enter weight in kg: "))
    height = float(input("Enter height in meters: "))
    bmi = weight / (height**2)
    print("Your BMI is :{bmi:.2f}".format(bmi=bmi))

    """bmi category"""
    if bmi < 18.5:
        print("underweight \n")
    elif bmi >= 18.5 and bmi < 25:
        print("normal weight \n")
    elif bmi >= 25 and bmi < 30:
        print("Overweight\n")
    else:
        print("Obesity\n")
    
calculate()
