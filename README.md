Here are some ideas to get you started:

- š­ Iām currently working on ... my own project/freelancer project
- š± Iām currently learning ... Flutter
- šÆ Iām looking to collaborate on ... Projects like any kind of potential Start-up's where I can contribute my knowledge.
- š¤ Iām looking for help with ... Experienced Flutter Developer & MERN Developer
- š¬ Ask me about ... Anything
- š« How to reach me: ... sankaramdas@gmail.com
- š Pronouns: ... He
- ā” Fun fact: ... Want to be an Entrepreneur. I'm Serious.


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
            ### Hi there š
            """
        
    def collaborate(self, role, organization, location):
        opportunity = self.employment
        opportunity[role] = [organization, location]

Me = ReadMe[2020]
