# What-Drives-the-Price-of-a-Car-
The goal is to understand what factors make a used car more or less expensive.

# Overview
The project checks dataset with information on 3 million used cars. The provided dataset contains information on 426K cars to ensure the speed of processing. In the end, we need to provide clear recommendations to the client—a used car dealership—as to what consumers value in a used car. The data used is dataset from Kaggle. vehicle.csv

# Modeling
With your (almost?) final dataset in hand, it is now time to build some models. Here, you should build a number of different regression models with the price as the target. In building your models, you should explore different parameters and be sure to cross-validate your findings.

# Evaluation
With some modeling accomplished, we aim to reflect on what we identify as a high-quality model and what we are able to learn from this. We should review our business objective and explore how well we can provide meaningful insight into drivers of used car prices. Your goal now is to distill your findings and determine whether the earlier phases need revisitation and adjustment or if you have information of value to bring back to your client.

# Deployment
Summary of Findings
Newer model years command higher prices, confirming clear depreciation with age.
Mileage (odometer) shows a strong negative relationship with price — cars lose value rapidly at lower mileage and then more slowly.
Condition has a major categorical impact: “excellent” cars are priced much higher than “fair” or “poor” ones.
Brand matters: luxury makes (BMW, Lexus, Cadillac) have the highest median prices, while mainstream brands (Nissan, Ford, Hyundai) occupy lower ranges.
Drive type: AWD/4WD vehicles are generally priced higher than FWD and RWD models, especially valuable in colder regions.
Fuel type: hybrid and electric cars show price premiums over gasoline or diesel vehicles.
Transmission: automatic cars consistently sell for more than manual ones.
Vehicle type: SUVs and trucks lead in resale value, followed by sedans and coupes.
Overall Insight: car prices are primarily driven by year, mileage, condition, brand, and vehicle type, with supporting influence from drive, fuel, and transmission — aligning with real-world resale trends.
