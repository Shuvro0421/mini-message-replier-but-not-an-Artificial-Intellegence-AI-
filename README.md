# mini-message-replier-but-not-an-Artificial-Intellegence-AI-
# Using python to make this little project and using if-else statements and functions but not using any loops.
    def age():
    
            print('Guess my age haha...: ')
            age1 = int(input())

            if age1 in range(0,13):
                print('Not even close')
            elif age1 in range(13,19):
                print('You are very close!!!')
            elif age1 in range(19,20):
                print('Wow!! right answer!!!')
    def bot():
        user = input('Enter a message: ')
            
        if user.lower() == 'hi':
            print('Hello')
        elif user.lower() == 'how are you' or user.lower() == 'how are you?':
            print('I am fine , Thank you')
        elif user.lower() == 'how old are you' or user.lower() == 'what is your age?' or user.lower() == 'what is your age' or    user.lower() ==  'how old are you?':
            return age()
        else:
            print('Please say your message celarly')
    
            
    bot()  
