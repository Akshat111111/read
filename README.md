print("Welcome to the Interactive Application!")

while True:
    user_input = input("What would you like to do today? (Enter 'quit' to exit) ")

    if user_input == 'quit':
        break
    elif user_input == 'hello':
        print("Hello! How can I help you today?")
    elif user_input == 'what is your name':
        print("My name is ChatGPT, I'm a language model developed by OpenAI.")
    else:
        print("Sorry, I didn't understand your request.")

print("Goodbye!")
