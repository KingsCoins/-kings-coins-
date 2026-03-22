import random
import time

def auto_spin():
    print("Firing up the slots...")
    spins = 50  # change this to whatever you need
    for i in range(spins):
        delay = random.uniform(1.0, 1.5)
        print(f"Spin {i+1}: pausing {delay:.2f}s")
        time.sleep(delay)
        # Add your click/refresh logic here—selenium or whatever
    print("Bonus cleared? Cash out time.")

auto_spin()