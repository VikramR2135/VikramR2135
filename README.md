class VikramR:
    def __init__(self):
        self.name           = "Vikram R"
        self.location       = "Coimbatore, Tamil Nadu, India"
        self.degree         = "B.E - ECE @ Sri Krishna College of Technology (2023–2027)"
        self.email          = "Vikram009d@gmail.com"
        self.stack          = [
            "Python", "Java", "C++", "JavaScript",
            "React.js", "Node.js", "Express.js",
            "MongoDB", "MySQL", "Scikit-Learn"
        ]
        self.currently_learning = [
            "Cloud Architecture (AWS / Azure)",
            "Deep Learning & Neural Networks",
            "Advanced DSA for Competitive Programming"
        ]
        self.fun_fact       = "I have built an E-Tongue that tastes ingredients and also display the adulteration percentage with 90% accuracy"

    def motto(self):
        return "Build smart. Lead boldly. Learn always. 🚀"

me = VikramR()
print(me.motto())
