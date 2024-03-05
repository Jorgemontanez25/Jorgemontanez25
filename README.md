### Hi there 👋

<!--
**Jorgemontanez25/Jorgemontanez25** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

class Jorgemontanez25:
    def __init__(self):
        self._first_name = "Jorge Argel"
        self._last_name = "Montañez Aguilar"
        self._spoken_languages = {
            'Spanish': 'Native',
            'English': 'Advanced - C1',
            
        }
        self._schooling = {

            'Data Science and Machine Learning':  ['Bootcamp', '4Geeks Academy', 'Nov/2023'],
            'Mechanical Engineer': ['Master', 'Texas A&M University', 'Aug/2017-May/2019'],
            'Mechatronic Engineer': ['Degree', 'Universidad Modelo', 'Aug/2011-Jun/2015'],
            
        }

        self._roles = [
            'Data scientist', 
            'Mechanical Engineer', 
            'Mechathronic Engineer', 
            'Manufacturing Engineer',
           
        ]
        
        self._qualifications = {
            'Hard Skills': [
                'Python', 
                'Jupyter Notebooks', 
                'VSCode', 
                'Pandas', 
                'Matplotlib', 
                'Seaborn', 
                'Web Scraping', 
                'Numpy', 
                'Scikit-Learn', 
                'TensorFlow', 
                'SQL', 
                'APIs', 
                'Git/GitHub', 
                'Git Codespaces', 
                'SolidWorks',
              
            ],
            'Soft Skills': [
                'Lifelong Learning',
                'Analytical Thinking',
                'Attention to Detail',
                'Creativity', 
                'Discipline', 
                'Critical Thinking', 
                'Adaptability', 
                'Problem Solving', 
                'Communication', 
                'Teamwork', 
                'Confidence', 
                'Active Listening', 
                'Emotional Intelligence'
            ]
        }

    def presentation(self):
        print(f'Howdy! My name is {self._first_name} {self._last_name}, I speak {len(self._spoken_languages)}, I\'m  mechanical engineer transitioning into data science. With hands-on experience in manufacturing and automotive sectors, I bring a blend of analytical prowess and engineering ingenuity to the table. Proficient in Python and machine learning, I'm eager to leverage data-driven insights to drive innovation and optimize processes.')

    def get_qualifications(self):
        print('\n')
        print('---------------------------------------------------')
        print('------------------- Hard Skills -------------------')
        print('---------------------------------------------------')
        for hskill in self._qualifications['Hard Skills']:
            print('|---->', hskill)
        print('\n')

        print('---------------------------------------------------')
        print('------------------- Soft Skills -------------------')
        print('---------------------------------------------------')
        for sskill in self._qualifications['Soft Skills']:
            print('|---->', sskill)


