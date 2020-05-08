# linear-equation
Essential math for machine learning: python edition
Linear equation : 2𝑦+3=3𝑥−1
#Solving linear equation
import pandas as pd
df = pd.DataFrame({'x': range(-11,13)})
df['y']=(3*df['x']-4/2)
df
#Visualize
%matplotlib inline
from matplotlib import pyplot as plt
plt.plot(df.x,df.y,color="grey",marker="o")
plt.xlabel('x')
plt.ylabel('y')
plt.grid()
# intercept 
0=3𝑥−42/2 and 𝑦=3⋅0−42/2
plt.annotate('x-intercept',(1,33,0)
plt.annotate('y-intercept',(0,-2))
##Slop 𝑚=𝑦2−𝑦1/𝑥2−𝑥1
#(0,-2)
#(6,7)
#𝑚=7−−2/6−0
# label the y-intercept
plt.annotate('y-intercept',(0,yInt))

# plot the slope from the y-intercept for 1x
mx = [0, 1]
my = [yInt, yInt + m]
plt.plot(mx,my, color='red', lw=5)

#
plt.show()
