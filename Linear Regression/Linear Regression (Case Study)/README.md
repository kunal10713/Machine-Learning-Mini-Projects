## Case Study -Ecommerce company:

### Linear Regression
You just got some contract work with an Ecommerce company based in New York City that sells clothing online but they also have in-store style and clothing advice sessions. Customers come in to the store, have sessions/meetings with a personal stylist, then they can go home and order either on a mobile app or website for the clothes they want.

The company is trying to decide whether to focus their efforts on their mobile app experience or their website. They've hired you on contract to help them figure it out! Let's get started!

### Dataset:

We'll work with the Ecommerce Customers csv file from the company. It has Customer info, suchas Email, Address, and their color Avatar. Then it also has numerical value columns:

  * Avg. Session Length: Average session of in-store style advice sessions.
  * Time on App: Average time spent on App in minutes
  * Time on Website: Average time spent on Website in minutes
  * Length of Membership: How many years the customer has been a member
  
#### Coeffecient:

 	                    Coeffecient
Avg. Session Length	  25.981550

Time on App	          38.590159

Time on Website	      0.190405

Length of Membership	 61.279097


#### Interpreting the coefficients:

    Holding all other features fixed, a 1 unit increase in Avg. Session Length  is associated with an increase of 25.98 total dollars spent
    
    Holding all other features fixed, a 1 unit increase in Time on App  is associated with an increase of 38.59 total dollars spent
    
    Holding all other features fixed, a 1 unit increase in Time on Website is associated with an increase of 0.19 total dollars spent
    
    Holding all other features fixed, a 1 unit increase in Length of Membership is associated with an increase of 61.27 total dollars spent
    
    
#### Do you think the company should focus more on their mobile app or on their website?
#### Answer:
This is tricky, there are two ways to think about this: Develop the Website to catch up to the performance of the mobile app, or develop the app more since that is what is working better. This sort of answer really depends on the other factors going on at the company, you would probably want to explore the relationship between Length of Membership and the App or the Website before coming to a conclusion!
