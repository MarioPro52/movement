# movementdef speed_of_sound(temperature):
    # Calculate speed of sound in air based on temperature in degrees Celsius
    # Formula used: speed = 331.3 * sqrt(1 + (temperature / 273.15))
    speed = 331.3 * (1 + (temperature / 273.15)) ** 0.5
    return speed

# Example temperature in degrees Celsius
temperature = 20

# Calculate speed of sound at the given temperature
speed = speed_of_sound(temperature)

# Output the result
print(f"The speed of sound at {temperature} degrees Celsius is {speed:.2f} meters per second.")
