# Smart Charging Mode of Electric Vehicles and Peak Power Demand Forecasting (MAtlab Code Implementation)

​  
Contents
0. Preface
1 Electric vehicle
1.1 Electric Vehicle (EV)
1.2 Electric vehicle charging
1.3 Intelligent Charging and Vehicle-to-Grid (V2G)
1.4 V2G Application
1.5 Availability of renewable energy
2. Smart Charging for Electric Vehicles
2.1 Intelligent Charging
2.2 Real-time electricity price
2.3 Intelligent Charging Mode - Example 1
2.4 Insights
2.5 Intelligent Charging Mode - Example 2
2.6 Newsstand Issues - Example 3
3. Complete Matlab code implementation
Editor
0. Introduction to the powerful CVX learning in power systems (Matlab & Python)
1 Electric vehicle 1.1 Electric vehicle (EV)
I Reduce Maintenance Costs I Lower Taxes I Cheaper Fuel (Electricity) I Government Subsidies
1.2 Electric vehicle charging
I Typical Battery Capacity: 30kWh - 100kWh
Editor
1.3 Intelligent Charging and Vehicle-to-Grid (V2G)
I use electric vehicle batteries to feed back power to the grid through bidirectional EV chargers.
2. Electric Vehicle Intelligent Charging
You have an EV that can be charged at home. The electricity price is real-time pricing (RTP). You need 20kW to charge your electric vehicle. The charging rate of the charger is 2kW. Assuming the electric vehicle can be charged at any time during the day, what time do you need to charge to minimize the daily electricity bill?
2.3 Intelligent Charging Mode - Example 1 Editor
Editor
2.4 Insights
Smart charging? Am I being too radical? How does battery degradation cost me? How much time do I spend at home, leaving, and driving? What about my charging status? How many cars do I have? How convenient and private is it? How reliable is the power system? Facing these questions, we enter the next example, carefully considering all the constraints. 2.5 Smart Charging Mode - Example 2 Editor
One more constraint:
Machine Learning: Data Fitting:
Editor
Editor
The loss function is defined as:
Editor
Power Peak Demand Forecasting:
Editor
2.6 Newsstand Issues - Example 3
Combining two stages:
Editor
Assuming that the demand d is a discrete random variable with S scenarios (d1,...,ds), each scenario di has a probability pi. Correspondingly, the sales volume for each scenario di is and.
Example:
(1) Assuming there are three scenarios, d1 = 10 with a probability of 1/4; d2 = 30 with a probability of 5/12; d3 = 50 with a probability of 1/3.
(3) Production Capacity:
Editor
Result:
Editor
Editor
2.7 Handling General Situations
How is the optimization problem actually solved?
(1) Unconstrained Problem
Set the derivative (1D) or gradient (high-dimensional)
Editor
So, how to find ∇xf(x) = 0?
I Solution: Analysis and calculation
Gradient Descent:
Edit
Newton's Method:
Edit
(2) Constraint Optimization
Barrier Method: Approximate problem of unconstrained optimization:
Edit
As t approaches 0, this approximates the original problem:
Maximizing the Lagrangian dual problem
Edit
(3) Example
I. What if it's difficult to define the scenario? Or if our distribution is not discrete? I. Sampling in most general conditions is sufficient.
Edit
3 Complete Matlab Code Implementation
This article only showcases a part of the code, all codes can be found in:

## Images

![Electric Vehicle Intelligent Charging Mode and Peak Electricity Demand Forecasting (MAtlab Code Implementation)](01.gif)
![Electric Vehicle Intelligent Charging Mode and Peak Electricity Demand Forecasting (MAtlab Code Implementation)](02.png)
![Electric Vehicle Intelligent Charging Mode and Peak Electricity Demand Forecasting (MAtlab Code Implementation)](03.png)
![Electric Vehicle Intelligent Charging Mode and Peak Electricity Demand Forecasting (MAtlab Code Implementation)](04.png)
![Electric Vehicle Intelligent Charging Mode and Peak Electricity Demand Forecasting (MAtlab Code Implementation)](05.png)
![Electric Vehicle Intelligent Charging Mode and Peak Electricity Demand Forecasting (MAtlab Code Implementation)](06.png)
![Electric Vehicle Intelligent Charging Mode and Peak Electricity Demand Forecasting (MAtlab Code Implementation)](07.png)
![Electric Vehicle Intelligent Charging Mode and Peak Electricity Demand Forecasting (MAtlab Code Implementation)](08.png)
![Electric Vehicle Intelligent Charging Mode and Peak Electricity Demand Forecasting (MAtlab Code Implementation)](09.png)
![Electric Vehicle Intelligent Charging Mode and Peak Electricity Demand Forecasting (MAtlab Code Implementation)](10.png)
![Electric Vehicle Intelligent Charging Mode and Peak Electricity Demand Forecasting (MAtlab Code Implementation)](11.png)
![Electric Vehicle Intelligent Charging Mode and Peak Electricity Demand Forecasting (MAtlab Code Implementation)](12.png)
![Electric Vehicle Intelligent Charging Mode and Peak Electricity Demand Forecasting (MAtlab Code Implementation)](13.png)
![Electric Vehicle Intelligent Charging Mode and Peak Electricity Demand Forecasting (MAtlab Code Implementation)](14.png)
![Electric Vehicle Intelligent Charging Mode and Peak Electricity Demand Forecasting (MAtlab Code Implementation)](15.png)
![Electric Vehicle Intelligent Charging Mode and Peak Electricity Demand Forecasting (MAtlab Code Implementation)](16.png)
![Electric Vehicle Intelligent Charging Mode and Peak Electricity Demand Forecasting (MAtlab Code Implementation)](17.png)
![Electric Vehicle Intelligent Charging Mode and Peak Electricity Demand Forecasting (MAtlab Code Implementation)](18.png)
![Electric Vehicle Intelligent Charging Mode and Peak Electricity Demand Forecasting (MAtlab Code Implementation)](19.png)
![Electric Vehicle Intelligent Charging Mode and Peak Electricity Demand Forecasting (MAtlab Code Implementation)](20.png)
![Electric Vehicle Intelligent Charging Mode and Peak Electricity Demand Forecasting (MAtlab Code Implementation)](21.png)
![Electric Vehicle Intelligent Charging Mode and Peak Electricity Demand Forecasting (MAtlab Code Implementation)](22.png)
![Electric Vehicle Intelligent Charging Mode and Peak Electricity Demand Forecasting (MAtlab Code Implementation)](23.png)
![Electric Vehicle Intelligent Charging Mode and Peak Electricity Demand Forecasting (MAtlab Code Implementation)](24.png)
![Electric Vehicle Intelligent Charging Mode and Peak Electricity Demand Forecasting (MAtlab Code Implementation)](25.png)
![Electric Vehicle Intelligent Charging Mode and Peak Electricity Demand Forecasting (MAtlab Code Implementation)](26.png)
![Electric Vehicle Intelligent Charging Mode and Peak Electricity Demand Forecasting (MAtlab Code Implementation)](27.png)

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
