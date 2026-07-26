import random
import time

print("===GAME SUIT===")

komputer = random.choice("batu", "gunting", "kertas")

print(suit)

pemain = input("Pilih batu/gunting/kertas:")

print("pilihan mu", pemain)
print("pilihan komputer", komputer)

if pemain == komputer:
    print("Seri!")
elif pemain == "batu" and komputer == "gunting":
    print("Kamu menang!")
elif pemain == "gunting" and komputer == "kertas":
    print("Kamu menang!")
elif pemain == "kertas" and komputer == "batu":
    print("Kamu menang!")
else:
    print("Kamu kalah!")
