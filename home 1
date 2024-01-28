from datetime import datetime as dt

def get_days_from_today(enter_date):
    try:
        user_date = dt.strptime(enter_date, "%Y-%m-%d")
        now = dt.today()
        delta_days = now - user_date
        return int(delta_days.days)
    
    except ValueError:
        print("Введена дата не відповідає формату yyyy.dd.mm", ValueError)
        return None

num = get_days_from_today("2024-02-02")

print(num)




   
    
    


