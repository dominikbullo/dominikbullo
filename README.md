# hi human! 👋

<p align="center">
      <img src="https://www.vectorlogo.zone/logos/djangoproject/djangoproject-icon.svg" alt="django" width="auto" height="55"/>   
      <img src="https://www.vectorlogo.zone/logos/vuejs/vuejs-icon.svg" alt="vue.js" width="auto" height="55"/> 
      <img src="https://www.vectorlogo.zone/logos/docker/docker-official.svg" alt="docker" width="auto" height="50"/>
      <img src="https://www.vectorlogo.zone/logos/postgresql/postgresql-vertical.svg" alt="postgresql" width="auto" height="55"/> 
      <img src="https://www.django-rest-framework.org/img/logo.png" alt="drf" width="auto" height="55"/>   
      <img src="https://www.vectorlogo.zone/logos/graphql/graphql-ar21.svg" alt="graphql" width="auto" height="55"/>
      <img src="https://www.vectorlogo.zone/logos/amazon_aws/amazon_aws-ar21.svg" alt="awq" width="auto" height="55"/>
</p>


```python
#!/usr/bin/python

class SoftwareEngineer:

    def __init__(self):
        self.name = "Dominik Bullo"
        self.role = "Full-stack developer"
        self.language_spoken = ["sk_SK", "en_US"]
        self.code = ["Python", "Javascript", "PHP", "Java"]

    @staticmethod
    def tools() -> dict[str, list[str]]:
        return {
            "backend": ["Django", "Django Rest Framework", "GraphQL", "pytest"],
            "frontend": ["Javascript", "Vue.js", "Vuexy", "Vuetify"],
            "general": ["Docker, Git, CI/CD, Github Actions", "WordPress", "WooCommerce"],
        }

    @staticmethod
    def favourite_tech_stack() -> str:
        return "Django | Vue.js | Docker | PostgreSQL"

    @staticmethod
    def say_hi() -> None:
        print("Thanks for dropping by, hope you find some of my work interesting.")


me = SoftwareEngineer()
me.say_hi()
```

