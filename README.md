Overview

As Electric Vehicle (EV) adoption surges, urban planners and policymakers must proactively anticipate infrastructure needs—especially EV charging stations. Inadequate planning could lead to bottlenecks, reduced user satisfaction, and delays in achieving sustainability goals.

This project focuses on forecasting future EV adoption using historical vehicle registration data. By predicting the growth of EVs, we can better inform infrastructure development strategies across regions.
Problem Statement

    Using the Electric Vehicle dataset (which includes information on EV populations, vehicle types, and regional data), develop a regression model to forecast future EV adoption.
    For example, predict the number of electric vehicles in upcoming years based on trends observed in the data.

Goal

Build a regression model that can:

    Forecast the future demand for EVs.

    Identify growth patterns based on historical EV data, vehicle types, and regional (county-level) records.

    Support urban infrastructure planning for EV adoption.

Dataset Description

Source:
Washington State Department of Licensing (DOL)

Key Features:
Feature	Description
Date	Month-end date of vehicle registration.
County	Geographic region (Washington State county) where the vehicle is registered.
State	Geographic region associated with the record. Addresses may include out-of-state vehicles.
Vehicle Primary Use	Describes primary use of the vehicle: Passenger (83%) or Truck (17%).
Battery Electric Vehicles (BEVs)	Count of fully battery-propelled electric vehicles.
Plug-In Hybrid Electric Vehicles (PHEVs)	Count of plug-in hybrid vehicles with partial battery propulsion.
EV Total	Sum of BEVs + PHEVs.
Non-Electric Vehicle Total	Count of vehicles that are not electric.
Total Vehicles	All registered vehicles (EVs + Non-EVs).
Percent Electric Vehicles	Percentage comparison of EVs to non-EVs.
Why This Matters

    Urban Planning: Helps planners design the right number of charging stations per region.

    Sustainability: Assists in setting and achieving clean energy transportation goals.

    Data-Driven Policy: Provides insight for EV incentives and infrastructure investments.
