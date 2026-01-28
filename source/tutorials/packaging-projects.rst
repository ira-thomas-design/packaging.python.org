def ai_robot():
    print("🤖 Hi! I am your AI robot. Type 'bye' to stop.")

    while True:
        user = input("You: ").lower()

        if "hello" in user:
            print("🤖 Robot: Hello human!")
        elif "how are you" in user:
            print("🤖 Robot: I am operating perfectly.")
        elif "your name" in user:
            print("🤖 Robot: I am Robo-One.")
        elif "bye" in user:
            print("🤖 Robot: Goodbye!")
            break
        else:
            print("🤖 Robot: I am still learning.")

ai_robot()
