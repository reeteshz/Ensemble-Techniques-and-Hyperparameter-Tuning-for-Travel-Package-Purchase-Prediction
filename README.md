# Ensemble Techniques and Hyperparameter Tuning for Travel Package Purchase Prediction

<h3>Problem Statement:</h3>

<p>
The company is seeking to enable and establish a viable business model in order to grow its customer base. Introducing a new package offering is one way to broaden the customer base. Currently, the company offers five different types of packages: basic, standard, deluxe, super deluxe, and king. Looking at data recorded in the previous year, company discovered that 18% of customers purchased the packages. The marketing cost, on the other hand, was quite high because customers were contacted at random without analyzing the available information. </p>
<p>The company is now preparing to launch a new product called the Wellness Tourism Package. Wellness tourism is defined as travel that allows the traveller to maintain, improve, or begin a healthy lifestyle, as well as support or increase one's sense of well-being. However, this time the company wishes to leverage the available data of existing and potential customers in order to make marketing expenditure more efficient.
</p>

<h3>Data Dictionary </h3>
<h5>Customer details:</h5>

- CustomerID: Unique customer ID
- ProdTaken: Whether the customer has purchased a package or not (0: No, 1: Yes)
- Age: Age of customer
- TypeofContact: How customer was contacted (Company Invited or Self Inquiry)
- CityTier: City tier depends on the development of a city, population, facilities, and living standards. The categories are ordered i.e. Tier 1 > Tier 2 > Tier 3
- Occupation: Occupation of customer
- Gender: Gender of customer
- NumberOfPersonVisiting: Total number of persons planning to take the trip with the customer
- PreferredPropertyStar: Preferred hotel property rating by customer
- MaritalStatus: Marital status of customer
- NumberOfTrips: Average number of trips in a year by customer
- Passport: The customer has a passport or not (0: No, 1: Yes)
- OwnCar: Whether the customers own a car or not (0: No, 1: Yes)
- NumberOfChildrenVisiting: Total number of children with age less than 5 planning to take the trip with the customer
- Designation: Designation of the customer in the current organization
- MonthlyIncome: Gross monthly income of the customer

<h5>Customer interaction data:</h5>

- PitchSatisfactionScore: Sales pitch satisfaction score
- ProductPitched: Product pitched by the salesperson
- NumberOfFollowups: Total number of follow-ups has been done by the salesperson after the sales pitch
- DurationOfPitch: Duration of the pitch by a salesperson to the customer
