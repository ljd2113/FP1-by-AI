# FP1-by-AI
import random
import time

# Greeting and user name input
print("Hello! Welcome to the PowerBall number generator.")
varUserName = input("What's your name? ")
print(f"Hi, {varUserName}! Let's generate your lucky PowerBall numbers.")

# Generate random numbers for the lottery balls
white_ball_1 = random.randint(1, 69)
white_ball_2 = random.randint(1, 69)
white_ball_3 = random.randint(1, 69)
white_ball_4 = random.randint(1, 69)
white_ball_5 = random.randint(1, 69)
red_ball = random.randint(1, 26)

# Print numbers with a short delay
print("\nHere are your numbers:")
time.sleep(1)
print(f"{white_ball_1}  {white_ball_2}  {white_ball_3}  {white_ball_4}  {white_ball_5}    {red_ball}")

# Farewell message
print("\nGood luck! May the odds be ever in your favor.")