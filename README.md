# Carbon-dioxide-concentration

Carbon dioxide (CO₂) is a greenhouse gas that contributes to Earth's warming by absorbing and emitting infrared radiation. Its atmospheric concentration has increased due to human activities. Historical CO₂ measurements show both a long-term upward trend and a seasonal cycle associated with vegetation growth and decay, particularly in the Northern Hemisphere.

This project focuses on forecasting monthly atmospheric CO₂ concentration using historical measurements from the Mauna Loa Observatory. Concentration is expressed in parts per million (ppm). These measurements describe atmospheric background conditions at a specific monitoring location and should not be interpreted as direct measurements of air quality in a Polish city or as the exact global average.

The forecasting task is to use past observations to estimate future monthly values. A Holt-Winters exponential smoothing model will be used to represent the trend and seasonal pattern.

## Workflow
1. Select and Verify the dataset.
2. Prepare the Python environment.
3. Load and clean the data.
4. Split the data chronologically.
5. Train the forecasting model.
6. Evaluate the predictions.
7. Save and present the results.

## Requirements

Python newest version:

```powershell
python --version
```

Download latest python version here: https://www.python.org/

Project, all resources and libraries are set in python virtual environment. In order to use application, create new python environment:

```powershell
python -m venv environment_name
```

Then, use the environment:

```powershell
.\environment_name\Scripts\activate
```

Now inside the environment, update pip and install dependencies:

```powershell
in future there will be commands here
```
