class Abdullah_aish:
    def __init__(self, pronouns, code, tools, challenge):
        self.pronouns = pronouns
        self.code = code
        self.tools = tools
        self.challenge = challenge
    
    def info(self):
        return f"Pronouns: {self.pronouns}\nCode: {self.code}\nTools: {self.tools}\nChallenge: {self.challenge}"
    
    def contact(self):
        return "How to reach me? Contact me at abdullahaish7@gmail.com or visit my portfolio https://abdullahaish.herokuapp.com/"

ab = Abdullah_aish("he / him", ['Python', 'Javascript', 'HTML', 'CSS', 'Bootstrap'], ['Scikit-Learn', 'Keras', 'Tensorflow', 'Pytorch', 'SciPy', 'Pandas', 'NumPy', 'Seaborn', 'Matplotlib'], "I'm working on my skills set to become one of the best Machine Learning Engineer in the world!")

print(ab.info())
print(ab.contact())

<!---
abdullahaish/abdullahaish is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
