df = pd.read_csv("Titanic.csv")
df.head()

# Sex is the factor to determine the survival as females are likely
# to survive over males

df.describe()
# Such incidents require a life boat to survive and according to
# the stats, more than 75% survived were in Pclass 2 and above 
# which means prefernce was given to upper class

# More than 75% of age 29 and above survived, preference must have
# been given to older women


df.describe().T
# Such incidents require a life boat to survive and according to
# the stats, more than 75% survived were in Pclass 2 and above 
# which means prefernce was given to upper class

# More than 75% of age 29 and above survived, preference must have
# been given to older women

# More than 75%  of passengers had a family member(SibSp) in the ship




