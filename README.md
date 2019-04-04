# basicEDA
Data Set Information:

The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed. 

Attribute Information:

Input variables:
# bank client data:
1 - age 
2 - job : type of job 
3 - marital : marital status 
4 - education 
5 - default: has credit in default? 
6 - balance: checking account balance
7 - housing: has housing loan? 
8 - loan: has personal loan? 
# related with the last contact of the current campaign:
9 - contact: contact communication type 
10 - day: last contact day of the month
11 - month: last contact month of year 
12 - duration: last contact duration, in seconds. Important note: this attribute highly affects the output target (e.g., if duration=0 then y='no'). Yet, the duration is not known before a call is performed. Also, after the end of the call y is obviously known. Thus, this input should only be included for benchmark purposes and should be discarded if the intention is to have a realistic predictive model.
# other attributes:
13 - campaign: number of contacts performed during this campaign and for this client (includes last contact)
14 - pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)
15 - previous: number of contacts performed before this campaign and for this client (numeric)
16 - poutcome: outcome of the previous marketing campaign (categorical)

Output variable (desired target):
17 - y - has the client subscribed to a term deposit?

