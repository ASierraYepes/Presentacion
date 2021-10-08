
    class Developer:

    def __init__(self):
      self.name = "Andres Sierra"
      self.role = "Web Developer"
      self.from = "Colombia"
      self.about = {'Hobbies': ['VideoGamess', 'Movie', 'Read'],
                    'Sports': ['Judo', 'Run', 'Travel']}
                  
    def hello(self):
    print('''
    👀 I’m interested in on: Improving my scripts languajes skills, focus on Python(Flask y Django), Java, HTML5, CSS3, JS
    🌱 I’m currently learning: English in a higher level that is conversation level,
    💞️ I’m looking to collaborate on: web development projects firstly then we will see,
    😔 I’m looking for help with: Java
    ''')
    
    me = Developer()
    me.hello()
