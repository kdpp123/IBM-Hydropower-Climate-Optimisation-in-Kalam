Can you forecast climate and operational effects on load generation for micro-hydropower plants in off-grid communities?

In the remote Kalam region of Pakistan, micro-hydropower plants (MHPs) are the backbone of energy generation for rural communities. But nature doesn’t always play along. Water flow fluctuates, maintenance disrupts supply, and the weather throws in its own surprises. From rainfall to temperature shifts, climate conditions impact how much energy is available—and how much is needed.

In this challenge, your task is to build a model that accurately predicts energy load generation (in kWh), drawing on MHP data like voltage, current, power factors, and energy metrics, combined with climate indicators like temperature, dew point, wind speed, and precipitation. The goal is to uncover patterns and insights that can improve forecasting, optimise energy distribution, and enhance system reliability.

Predicting energy needs means less waste, fewer blackouts, and smarter resource management—all crucial for keeping the lights on in off-grid communities. Understanding how climate affects energy demand, and what that means for sustainable power planning, is a critical insight for sustainable power projects all over the world.

About
You are provided with time series data recorded at 5-minute intervals.

Each consumer device represents a power pole, and the data user associated with the device is identified in the ID column. Some data users are connected to three-phase systems, while others have single-phase connections. This distinction is reflected in the dataset:

Single-phase houses have only v_red.
Three-phase houses include v_red, v_blue, and v_yellow.
The dataset includes measured values for voltage, current, power factor, and energy consumption (kWh).

Your Task

Your objective is to forecast the total daily energy consumption (kWh) per data user for one month into the future.

Additional Information

To support your predictions, you are provided with climate indicators, including:

Temperature
Dew point
Wind speed
Precipitation
