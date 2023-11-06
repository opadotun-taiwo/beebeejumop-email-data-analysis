# beebeejumop-email-data-analysis

# Month on Month analysis of Lead generation for a solar start up in NIgeria

![dashboard1](https://github.com/opadotun-taiwo/beebeejumop-email-data-analysis/assets/63159381/60243e46-3394-4a02-a464-cd6a8335ed31)


One thing I like about data is that it does not lie. "Well, unless it helps". 
While working on this dataset one insight that fascinated me was that people signed up more during the dry season (which is plausible). 
There was an average of 12.01% increase in email sign up during the dry season month compared to the rainy season months.

The marketing manager should put more resources in marketing during dry season months. 

##Data cleaning
df_mail = pd.read_excel("./beebeejump data4.xlsx")

df_mail1.drop('CONFIRM_IP', inplace=True, axis=1)

df_mail1.to_csv('beebeejumpcleaned.csv', encoding='utf-8')
