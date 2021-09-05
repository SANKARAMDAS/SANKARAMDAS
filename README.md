Here are some ideas to get you started:

- 🔭 I’m currently working on ... my own project/freelancer project
- 🌱 I’m currently learning ... Flutter
- 👯 I’m looking to collaborate on ... Peojects like any kind of potential Start-up's where I can contribute my knowledge.
- 🤔 I’m looking for help with ... Experienced Flutter Developer
- 💬 Ask me about ... Anything
- 📫 How to reach me: ... sankaramdas@gmail.com
- 😄 Pronouns: ... He
- ⚡ Fun fact: ... Want to be an Entrepreneur. I'm Serious.


class Readme:

    def __init__(self, username="sankaram", year=2020):
        self.username = username
        self.name = 'Sankaram Das'
        self.education = {
            'programming': ['Full Stack Mobile Development', 'The AppBrewery/Udacity'],
            'bachelor ': ['Bachelor of Technology', 'DIATM']
        }
        self.employment = {
            'developer': ['company', 'city'],
        }

    def doing(self, now=2021):
        today = self.year

        if now < today:
            experience = self.employment['programming']
            return """
            I am currently learning {code} at {the_appbrewery}.
            """.format(code=dream[0], the_appbrewery=dream[1])
        
        elif now => today:
            goal = self.employment['developer']
            return """
            I am eager to collaborate with {teams} on {projects}.
            """.format(teams=goal[0], projects='mobile development')
        else:
            return """
            ### Hi there 👋
            """
        
    def collaborate(self, role, organization, location):
        opportunity = self.employment
        opportunity[role] = [organization, location]

Me = ReadMe[2020]
