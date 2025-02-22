<div id="top"></div>

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/Sriharika09">
    <img src="https://cdn-icons-png.flaticon.com/512/3408/3408473.png" alt="Logo" width="80" height="80"/> 
  </a>

<h3 align="center">Web Scraping Project</h3>

  <p align="center">
    Project Files
    <br />
    <a href="https://github.com/Sriharika09/Flask_app_project"><strong>Explore the Repo »</strong></a>
    <br />
    <br />
    <a href="https://github.com/Sriharika09/Flask_app_project/blob/main/app.py">View app code</a>
    ·
    <a href="https://github.com/Sriharika09/Flask_app_project/blob/main/Scrapper.py"> Scraper module</a>
    ·
  </p>
</div>


<!-- ABOUT THE PROJECT -->
## 👨‍💻 About The Project
* Building a Web scraper for lms website to get all courses information.
* Storing the scrapped data to MongoDB.
* Building a Flask App to view scrapped data.

<!-- USAGE -->
## ❇️ Usage
*  Web scraping is a term for various methods used to collect data from across the Internet.
*  This web scraper extracts all the data on `lms website's` all course information.
*  The scrapped data is then stored to user specified Mongodb database.

<!-- STEPS -->
## 📌 Steps

* Installing Python, PyCharm, Monogodb, Git to Computer.
* Creating Flask app by importing `Flask` module.
* Getting information about lms website.
* Gathering data from most static websites is a relatively straightforward process. However, **dynamic website like iNeuron**, JavaScript is used to load their content. These web pages require a different approach to collecting the desired public data.
* Scraping dynamic website using one of the most popular Python libraries, `BeautifulSoup `which can load the data into Json format by using `"script"` in `soup.find` method.

### Scraping and Inserting to DB
* With the Json data all the required data is stored into Dictionary format.
* Extracted all the course data using loops and stored as list.
* Mongodb Altas is used as DB here, with `pymongo library` mongodb is connected to python.
* Database and collections created via python and the list of dictionaries is uploaded using `collection.insert_many` method.
* Created an `app.py` to initialize

### Flask
* Importing the Flask module and creating a Flask web server from the Flask module.
* Create an object **app** in flask class with `__name__` which represents current app.py file.
* Create `/` route to render default page html.
* Create a route `/course` to get user input and if keyword is present in the Mongo DB it is shown in `results.html` page.
* Run the flask app with `app.run()` code.

<p align="right">(<a href="#top">back to top</a>)</p>




### 🧰 **Technologies used**
[![Language | Python](https://img.shields.io/badge/Python-eeeeee?style=for-the-badge&logo=python&logoColor=ffffff&labelColor=3776AB)][python]
[![Framework & Library | Flask](https://img.shields.io/badge/Flask-eeeeee?style=for-the-badge&logo=flask&logoColor=000000&labelColor=fefefe)][flask]
[![Language | MongoDB](https://img.shields.io/badge/Mongo_DB-eeeeee?style=for-the-badge&logo=mongodb&logoColor=47A248&labelColor=fefefe)][mongodb]

### 🔧 **Tools used**
[![Tools used | PyCharm](https://img.shields.io/badge/PyCharm-eeeeee?style=for-the-badge&logo=PyCharm&logoColor=008000&labelColor=2C2C32)][PyCharm]
[![Tools used | Git](https://img.shields.io/badge/Git-eeeeee?style=for-the-badge&logo=git&logoColor=F05032&labelColor=f0efe7)][git]
[![Tools used | GitHub](https://img.shields.io/badge/Github-eeeeee?style=for-the-badge&logo=github&logoColor=ffffff&labelColor=181717)][github]
[![Tools used | Postman](https://img.shields.io/badge/Postman-eeeeee?style=for-the-badge&logo=postman&logoColor=FF6C37&labelColor=fefefe)][postman]
<p align="right">(<a href="#top">back to top</a>)</p>


<!-- CONTACT -->
## 📌 Contact
[![Sriharika09 | LinkedIn](https://img.shields.io/badge/Sriharika-eeeeee?style=for-the-badge&logo=linkedin&logoColor=ffffff&labelColor=0A66C2)][reach_linkedin]
[![Sriharika09 | G Mail](https://img.shields.io/badge/Sriharika-eeeeee?style=for-the-badge&logo=gmail&logoColor=ffffff&labelColor=EA4335)][reach_gmail]

<p align="right">(<a href="#top">back to top</a>)</p>




<!-- MARKDOWN LINKS  -->

<!-- Tools Used -->
[PyCharm]: https://code.visualstudio.com/
[postman]: https://www.postman.com/
[git]: https://git-scm.com/
[github]: https://github.com/
[microsoft_azure]: https://azure.microsoft.com/en-in/features/azure-portal/
[python]: https://www.python.org/
[mongodb]: https://www.mongodb.com/
[flask]: https://flask.palletsprojects.com/en/2.1.x/

<!--contact-->
[reach_linkedin]:https://github.com/Sriharika09/Course-Web-Scraping
[reach_gmail]: mailto:https://sriharika59@gmail.com 
