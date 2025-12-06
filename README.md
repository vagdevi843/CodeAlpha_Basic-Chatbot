# CodeAlpha_Basic-Chatbot
def basic_chatbot():
    print("===== Welcome to the Basic Chatbot =====")
    print("Type 'bye' to exit.\n")

    while True:
        user_input = input("You: ").lower().strip()

        # Rule-based replies
        if user_input in ["hello", "hi", "hey"]:
            print("Bot: Hi!")
        
        elif user_input in ["how are you", "how are you?"]:
            print("Bot: I'm fine, thanks!")
        
        elif user_input in ["bye", "exit", "quit"]:
            print("Bot: Goodbye!")
            break
        
        else:
            print("Bot: I didn't understand that. Try saying 'hello' or 'bye'.")

    print("\nChat ended.")

# Run Chatbot
basic_chatbot()
