# daily_update.py
from datetime import datetime

def main():
    today = datetime.now().strftime("%Y-%m-%d %H:%M:%S")
    print(f"Hello GitHub! Today is {today}")

if __name__ == "__main__":
    main()
