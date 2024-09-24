import random

# List of random quotes
quotes = [
    "The only limit to our realization of tomorrow is our doubts of today. - Franklin D. Roosevelt",
    "Life is 10% what happens to us and 90% how we react to it. - Charles R. Swindoll",
    "Do not watch the clock; do what it does. Keep going. - Sam Levenson",
    "Keep your face always toward the sunshine—and shadows will fall behind you. - Walt Whitman",
    "The best way to predict the future is to create it. - Peter Drucker"
]

# Function to get a random quote
def get_random_quote():
    return random.choice(quotes)

# Generate and print a random quote
print(get_random_quote())
