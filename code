#Simple today daily energy expenditure calculator. This will determine the calories one should consume for a weight loss goal

#Tell the user the goal of the calculator
print('This calculator gives you your total daily expenditure based on the Harris-Benidict equation. ')
print('Based on this number and your weight loss goals, a daily caloric goal will be provided. ')

#Set the variables according to the individuals statistics
age = float(input('What is your age? '))
height = float(input('What is your height in inches? '))
weight = float(input('What is your weight in pounds? '))
sex = input('What is your gender? (Please choose M or F) ')

#Choose the correct formula to use based upon the individual's gender
if sex == 'F':
    tdee = 655 + (9.6 * (weight * 0.453592)) + (1.8 * (height * 2.54)) - (4.7 * age)
if sex == 'M':
    tdee = 66 + (13.7 * (weight * 0.453592)) + (5 * (height * 2.54)) - (6.8 * age)

#Tell them their calculated tdee
print('Your total daily expenditure is ' + str(tdee) + ' calories')

#Ask the goals of their weight loss to give them a timeline
goal = float(input('How many pounds do you want to lose? '))
deficit = float(input('How much of a daily caloric deficit are you willing to undertake? 500 is recommended.'))

#Calculate the amount of weeks it will take them to reach their goal
timeline = goal / ((deficit * 7) / 3500)

print('It will take you ' + str(timeline) + ' weeks to lose your goal amount.')
