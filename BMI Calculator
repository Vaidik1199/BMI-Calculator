from gtts import gTTS

def kg_lbs():
    print("If you know the weight in kg then insert it below")
    print("If you don't know then please press '0', and insert the weight in lbs")
    global a
    global b
    a=float(input("Insert your body weight in kg : "))
    if a==0:
        print("OHK, means you want to know your weight in kg, then Insert in lbs")
        b=float(input("Insert your body weight in lbs : "))
        a= b*0.453592
        print("Your weight in Kg = ",a," Kg")
    elif a>=1:
        b= a*2.20462
        print("Your weight in lbs = ", b," lbs")
    else :
        print("Dafa ho jao")

def met_feet():
    print("If you know the height in meter then insert it below")
    print("If you don't know then please press '0'. and insert the height in feet")
    global c 
    global d
    c = float(input("Insert you body height in Meter : "))
    if c==0:
        print("OHK, means you want to know your height in meter, then Insert in feet")
        d=float(input("Insert your body height in feet: "))
        c=d*0.3048
        print("Your height in meter = ",c," Meter")
    elif c>=1:
        d=c*3.28084
        print("Your height in Feet = ",d," feet")
    else:
        print("dafa ho jao ")
   
def BMI_calculator():
    global a
    global c
    global dj
    dj=(c*c)
    BMI=a/dj
    if BMI<=18.4:
        print("Your BMI =",BMI,", Hence you are Underweight")
         
    elif 18.5<=BMI<=24.9:
        print("Your BMI = ",BMI,", Hence You are Normal")
    elif 25.0<=BMI<=39.9:
        print("Your BMI = ",BMI,", Hence you are Overweight")
    elif BMI>=40.0:
        print("Your BMI = ",BMI,", Hence you are Obese! ")
    else:
        print("dafa ho jao, You are abnormal")

def Diff_mapak():
    need=int(input("If you need to change the unit press 1 or not then press 0 : "))
    if need==1:
        kg_lbs()
        met_feet()
        BMI_calculator()
    elif need==0:
        m=float(input("Input the weight in kg : "))
        n=float(input("Input the height in meter : "))
        ok= n*n
        BMI1= m/ok
        if BMI1<=18.4:
            print("Your BMI =",BMI1,", Hence you are Underweight")
        elif 18.5<=BMI1<=24.9:
            print("Your BMI = ",BMI1,", Hence You are Normal")
        elif 25.0<=BMI1<=39.9:
            print("Your BMI = ",BMI1,", Hence you are Overweight")
        elif BMI1>=40:
            print("Your BMI = ",BMI1,", Hence you are Obese! ")
        else:
            print("Dafa ho jao ")
    else:
        print("dafa ho jao")

Diff_mapak()
