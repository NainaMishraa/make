print("☆☆☆☆WELCOME TO THE WORLD OF HOROSCOPES☆☆☆☆ \n") 
print("In layman's terms, astrology is the study of the correlation between the positions of the planets and other astronomical events at the time of your birth, your personality, and the overall course of your life.Your zodiac sign, according to astrology, tells you almost everything about yourself: strengths, weaknesses, likes, and dislikes.\n")
print("1.KNOW YOUR ZODIAC SIGN\n2.MORE ABOUT SIGNS\n")
ch=int(input("Enter your choice:"))
if ch==1:
    print("\n1.KNOW YOUR ZODIAC SIGN")
    name=input("Enter your name:")
    gen=input("Enter your gender:")
    birthday=input("Enter your birthday [dd/mm/yyyy]:").split("/")
    date=int(birthday[0])
    month=int(birthday[1])
    year=int(birthday[2])
    print()
    if month==1:
        print("The month is January")
        if date>=20:
            print("Your zodiac sign: Aquarius")
        elif date<=19:
            print("Your zodiac sign: Capricorn")
    elif month==2:
        print("The month is February")
        if date>=19:
            print("Your zodiac sign: Pisces")
        elif date<=18:
            print("Your zodiac sign: Aquarius")
    elif month==3:
        print("The month is March")
        if date>=21:
            print("Your zodiac sign: Aries")
        elif date<=20:
            print("Your zodiac sign: Pisces")
    elif month==4:
        print("The month is April")
        if date>=20:
            print("Your zodiac sign: Taurus")
        elif date<=19:
            print("Your zodiac sign: Aries")
    elif month==5:
        print("The month is May")
        if date>=21:
            print("Your zodiac sign: Gemini")
        elif date<=20:
            print("Your zodiac sign: Taurus")
    elif month==6:
        print("The month is June")
        if date>=21:
            print("Your zodiac sign: Cancer")
        elif date<=20:
            print("Your zodiac sign: Gemini")
    elif month==7:
        print("The month is July")
        if date>=23:
            print("Your zodiac sign: Leo")
        elif date<=22:
            print("Your zodiac sign: Cancer")
    elif month==8:
        print("The month is August")
        if date>=23:
            print("Your zodiac sign: Virgo")
        elif date<=22:
            print("Your zodiac sign: Leo")
    elif month==9:
        print("The month is September")
        if date>=23:
            print("Your zodiac sign: Libra")
        elif date<=22:
            print("Your zodiac sign: Virgo")
    elif month==10:
        print("The month is October")
        if date>=23:
            print("Your zodiac sign: Scorpio")
        elif date<=22:
            print("Your zodiac sign: Libra")
    elif month==11:
        print("The month is November")
        if date>=22:
            print("Your zodiac sign: Sagittarius")
        elif date<=21:
            print("Your zodiac sign: Scorpio")
    elif month==12:
        print("The month is December")
        if date>=22:
            print("Your zodiac sign: Capricorn")
        elif date<=21:
            print("Your zodiac sign: Sagittarius")
    else:
        print("INVALID OPTION")
elif ch==2:
    print("\n2. MORE ABOUT SIGNS")
    print("Choose the zodiac sign which you want to know more about:")
    print("1.Capricorn")
    print("2.Aquarius")
    print("3.Pisces")     
    print("4.Aries")     
    print("5.Taurus")     
    print("6.Gemini")     
    print("7.Cancer")     
    print("8.Leo")     
    print("9.Virgo")     
    print("10.Libra")
    print("11.Scorpio")     
    print("12.Sagittarius")
    ch2=int(input("Enter your choice:"))
    print()
    if ch2==1:
        print("Element: Earth")
        print("Power Color: Dark green and brown")
        print("Ruling Planet: Saturn")
        print("Symbol: Goat")
    elif ch2==2:
        print("Element: Air")
        print("Power Color: Electric blue")
        print("Ruling Planet: Uranus and Saturn")
        print("Symbol: The Water Bearer")
    elif ch2==3:
        print("Element: Water")
        print("Power Color: Pale green and turquoise")
        print("Ruling Planet: Neptune and Jupiter")
        print("Symbol: The Fish") 
    elif ch2==4:
        print("Element: Fire")
        print("Power Color: Red")
        print("Ruling Planet: Mars")
        print("Symbol: Ram")
    elif ch2==5:
        print("Element: Earth")
        print("Power Color: Pink and pale blue")
        print("Ruling Planet: Venus")
        print("Symbol: Bull")
    elif ch2==6:
        print("Element: Air")
        print("Power Color: Yellow")
        print("Ruling Planet: Mercury")
        print("Symbol: The Twins")
    elif ch2==7:
        print("Element: Water")
        print("Power Color: Silver and sea green")
        print("Ruling Planet: Moon")
        print("Symbol: The Crab")
    elif ch2==8:
        print("Element: Fire")
        print("Power Color: Gold and Orange")
        print("Ruling Planet: Sun")
        print("Symbol: Lion")
    elif ch2==9:
        print("Element: Earth")
        print("Power Color: navy blue and gray")
        print("Ruling Planet: Mercury")
        print("Symbol: The Virgin")
    elif ch2==10:
        print("Element: Air")
        print("Power Color: Pale blue and pik")
        print("Ruling Planet: Venus")
        print("Symbol: The Scales")
    elif ch2==11:
        print("Element: Water")
        print("Power Color: Crimson and burgundy")
        print("Ruling Planet: Pluto and Mars")
        print("Symbol: Scorpion")
    elif ch2==12:  
        print("Element: Fire")
        print("Power Color: Purple and dark blue")
        print("Ruling Planet: Jupiter")
        print("Symbol: The Archer")       
    else:
        print("INVALID OPTION")
else:
    print("INVALID OPTION")    
print("\nWithout astrology man treads, as it were, in the dim twilight of ignorance." ) 
print("THANK YOU")
