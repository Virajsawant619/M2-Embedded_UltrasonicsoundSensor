# Test Plan


## Obstacle Detection:
### How: Our implementation for this step requires multiple steps :
#### Step 1: Find a distance value between each pair of sensors. To test the distance
value, we may use the numbers we see for the height and length, as well as the
Pythagorean Theorem.
####Step 2: Check the angle found between each pair of sensors using the distance value
initially found.
####Step 3: Using these values, determine what each angle should approximately be to
detect different types of obstacles.
####Step 4: Detect the obstacles.


## Output: As we had steps for each test, we will again make steps for the expected outputs:
#### Step 1: Compare the outputted (through serial) value for the hypotenuse to the
Pythagorean calculated value. We expect them to be the same.
####  Step 2: Using the same technique as step 1 except calculating the angle, we should
see the same value for this calculation as well.
#### Step 3 : The values and outputs for the “obstacle detected” will be constantly
checked and rechecked to make sure the angles determine the correct obstacle.
#### Step4 : Adding Audio to the Ultrasonic Sensors.

## Testing cases

| Average Speed(m/s)                    | 0.8                           | 1.5    | 2.0    |
| ----------------- | -----------------------|-------------|---------|
| Mean RMS error (cm)* | 19.4  |12.7  |10.2|
|SD** |11.2   |14.3  | 13.4|
|Sensing error (%) | 5.0 | 1.6| 1.0|
|----------------------------------------------------------|


#### RMS error : Root mean square error between actual and sensing distance.
#### SD** : Standard deviation of the RMS errors.

