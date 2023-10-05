<h1 align="left">Hi 👋, I'm Ashish</h1>
<h3 align="left">I am a passionate software developer, specialised in Salesforce, Java and front-end development using ReactJS. Among my personal interests, I'm fascinated by gardening, astronomy, origami and design.</h3>
<hr/>

- 🔭 I’m currently exploring **X-AI for policy, financial markets and differential privacy**

<!-- - 🌱 I’m currently learning **Spring Boot for Rest Integrations**
 -->
- 👨‍💻 All of my projects are available at [ashishsalunkhe.in](https://www.ashishsalunkhe.in/) and here on [GitHub](https://github.com/ashishsalunkhe)

- 📝 I regularly write articles on [https://www.ashishsalunkhe.in/blog](https://www.ashishsalunkhe.in/blog)

- 💬 Ask me about **Formula 1, Cricket, TV Shows, Gardening**

- 📫 How to reach me **ashishvs@umd.edu**

- 📄 Know about my experiences [Resume](https://www.dropbox.com/s/ux6tj85po1dyp4w/AshishSalunkhe_Resume.pdf?dl=0)
<hr/>
<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://twitter.com/avsalunkhe98" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="avsalunkhe98" height="30" width="40" /></a>
<a href="https://linkedin.com/in/ashishsalunkhe" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="ashishsalunkhe" height="30" width="40" /></a>

</p>
<hr/>
<h3 align="left">Languages and Tools:</h3>
<br/>
<p align="left"> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.djangoproject.com/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/django.svg" alt="django" width="40" height="40"/> </a> <a href="https://www.figma.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://kubernetes.io" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg" alt="kubernetes" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://www.postgresql.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/> </a> <a href="https://postman.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="postman" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> </a> <a href="https://spring.io/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/springio/springio-icon.svg" alt="spring" width="40" height="40"/> </a> <a href="https://tailwindcss.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" alt="tailwind" width="40" height="40"/> </a> </p>
<hr/>

# Standardizing Rows in the 'name' Column of a DataFrame

In data analysis and preprocessing, it's often necessary to standardize values in a column to ensure consistency and cleanliness. This example demonstrates how to standardize the rows in the 'name' column of a pandas DataFrame using Python.


import pandas as pd
import re

# Sample DataFrame with a 'name' column
data = {'name': ['ABC Corporation Inc.', 'XYZ Group - Limited', 'Company & Co', 'Tech Services, LLC']}
df = pd.DataFrame(data)

# Define a function for standardization
def standardize_name(name):
    # Remove special characters and punctuation
    name = re.sub(r'[^\w\s]', '', name)
    # Convert to uppercase
    name = name.upper()
    # Remove leading and trailing spaces
    name = name.strip()
    return name

# Apply the standardization function to the 'name' column
df['name'] = df['name'].apply(standardize_name)

# Display the standardized DataFrame
print(df)

<picture>
<source
  srcset="https://github-readme-stats.vercel.app/api?username=ashishsalunkhe&show_icons=true&theme=dark"
  media="(prefers-color-scheme: dark)"
/>
<source
  srcset="https://github-readme-stats.vercel.app/api?username=ashishsalunkhe&show_icons=true"
  media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)"
/>
<img src="https://github-readme-stats.vercel.app/api?username=ashishsalunkhe&show_icons=true" />
</picture>
