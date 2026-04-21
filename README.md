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
#сперва с помощью def обьявляем функциюбкоторая создаст 1ник,потом создаем списки прилагательных и существительных.дальше случайным образом выбираем по одному слову из списков.потом генерируем одно число от 1 до 999.и собираем все в одну строку,дальше создаем заголовок,делаем цикл,и print,чтобы было несколько вариантов для выбора
