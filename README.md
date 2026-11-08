import datetime
current_year = datetime.date.today().year
user_name = input("what is your name?")
user_age = int(input("how old are you?"))
birth_year = current_year - user_age
print(f\n hello {user_name}! you were born in {birth_year}")
