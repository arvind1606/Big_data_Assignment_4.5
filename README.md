# Big_data_Assignment_4.5
import math

#Total number of trials
n = 50
#probability of getting D
p_get_D = 1/5
#probability of geting anything other than D
p_dont_get_D = (1-1/5)
#probability of exactly 5 times D
P = (math.factorial(50)/(math.factorial(5)*math.factorial(50-5))) * (p_get_D**5) * (p_dont_get_D**45)

print("P(exactly 5 D's out of 50 trials) = {:.10f}".format(P))
