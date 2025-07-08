class WhoAmI:
    """Class to introduce Monica Echeverri :)"""
    def __init__(self, visitor_name):
        self.user = "monicaecheverri"
        self.profession = "Computer Engineer | Project Management Specialist"
        self.role = "Tech Lead & Backend Developer"
        self.goal = "Future AWS Solutions Architect ☁️"
        print(f"👋 Hi {visitor_name}, welcome to {self.user}'s GitHub!")
        print(f"💻 Profession: {self.profession}")
        print(f"🚀 Current Role: {self.role}")
        print(f"🎯 Career Goal: {self.goal}")
        print(f"📚 Currently learning: {self.get_current_learning()}")
        print(f"🛠️ Experienced with: {self.get_experience_areas()}")

    def get_current_learning(self):
        return ["AWS Solutions Architect – Associate exam prep",
                "Cloud architecture best practices",
                "Distributed systems design"]

    def get_experience_areas(self):
        return {
            "Cloud": "AWS (Architecting Solutions), Azure (Fundamentals)",
            "Databases": "DynamoDB, MongoDB, MySQL, PostgreSQL, Oracle SQL",
            "Backend & Frontend": "Python, JavaScript, Express, HTML, CSS",
            "DevOps": "Git, Linux, Docker, CloudFormation, Azure DevOps, SonarQube",
            "Chatbots": "3+ years with Dialogflow, Watson Assistant, Lex, RASA"
        }

moni = WhoAmI("your_name")
