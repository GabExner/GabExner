class GabExner:
    def __init__(self):
        self.interests = ["games", "music"]
        self.current_learning = "AI"
        self.pronouns = "He/His"
        self.fun_fact = "I love cats!"

    def collaborate(self):
        return "Looking to collaborate on projects where I can use my marketing knowledge."

    def say_hi(self):
        return "Hi, I’m @GabExner!"

# Exemplo de uso
gab = GabExner()
print(gab.say_hi())
print("Interests:", ", ".join(gab.interests))
print("Currently learning:", gab.current_learning)
print(gab.collaborate())
print("Pronouns:", gab.pronouns)
print("Fun fact:", gab.fun_fact)
