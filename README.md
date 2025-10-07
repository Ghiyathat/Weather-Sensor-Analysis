## Weather Sensor Data Analysis

This project analyzes synthetic weather sensor data (temperature and humidity) for three Nigerian cities - Lagos, Abuja, Kano- Over a 4-day period. It demonstrates how to extract, manipulate, and analyze multidimensional data using Numpy

### Dataset Structure

The dataset is stored as a Numpy array with the following dimensions:

- Axis 0: City --- (0: Lagos, 1: Abuja, 2: Kano)
- Axis 1: Day --- (0: Day 1, 1: Day 2, 2: Day 3, 3: Day 4)
- Axis 2: Measurement --- (0: Temperature in degree celsius, 1: Humidity %
- Shape: (3, 4, 2)

### What I Did?
- Loaded and structured weather sensor readings into a '(3, 4, 2)' Numpy array
- Extracted temperature and humidity readings using slicing and indexing
- Identified days with temperature greater than 30 degree celsius and cities with humidity less than 50%
- Created a separate arrays for temperature(3 * 4) and humidity (3 * 4)
- Computed:
   - Sorted temperature readings
   - Average temperature per cities
   - Day with highest temperature in Abuja
   - City with the lowest overall humidity
- Documented clear City-Day-Measurement mappings

### Key Concepts Demonstrated
- Multidimensional Numpy arrays
- Array slicing, indexing, and filtering
- Statistical computations (mean, sorting, comparisons)

### Tools Used
- Python
- Numpy

### Reference
- [Awibi Medtech Data Science Project](https://www.linkedin.com/company/awibimedtech/?originalSubdomain=ng)
