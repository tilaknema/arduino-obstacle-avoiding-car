# ⚙️ Working Principle

The obstacle avoiding car uses ultrasonic sensing to detect objects.

## Steps:
1. Sensor sends ultrasonic waves
2. Waves reflect from obstacle
3. Echo is received back
4. Distance is calculated using time delay

## Logic:
- Distance > threshold → Move forward
- Distance < threshold → Stop and turn

## Formula:
Distance = (Time × Speed of Sound) / 2
