# python-loop-password-with-lock-
program to check the grant access or lock account 

attempt = 0 

while attempt < 3:
    password = int(input("Enter the password:"))
    if password == 2026:
        print("Access granted")
        break
    else:
        attempt += 1
        print("Wrong password...Try again!...")
    if attempt == 3:
        print("Account locked")
