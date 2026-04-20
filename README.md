# nickname-generator
import random

def generate_nickname():
    adject = ["Shadow", "Golden", "Silent", "Cyber", "Brave", "Mad", "Frozen", "Neon"]
    nouns = ["Hunter", "Wizard", "Wolf", "Knight", "Talant", "Runner", "Dragon", "Storm"]
    adj = random.choice(adject)
    noun = random.choice(nouns)
    number = random.randint(1, 999)
    return f"{adj}{noun}_{number}"
print("Варианты ваших ников:")
for _ in range(5):
    print(generate_nickname())
