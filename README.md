# Review Scraper 📜

## About Project
Review Scraper is a Python project aims at building an application for getting reviews for a product in E-commerce website.
The project was build on Python Flask framework and integrated with Web API. Deployed the application in Railway app.

Link for the application: https://web-production-5c0a.up.railway.app/

E-commerce Website used for searching is "Flipkart": https://www.flipkart.com/

### 🏡 Home page
In the Home page, user can able to enter the product name which he wants to view the product reviews. While clicking on Search, the application searches for the appropriate product which user entered. Then, collects all the reviews for that product from the E-commerce site and will list all those reviews in the reviews page.

<a><img src='templates/Home.png' width="60%" height="50%"></a><br>

### ⭐ Reviews page
In Reviews page, list of all the reviews for user searched product will be displayed. 
> So, this helps user a lot with just one-click he can view all the reviews for a product. It helps the customer by saving time to get clear picture on the product whether to buy it or not based on these reviews.

<a><img src='templates/results.png' width="60%" height="50%"></a><br>

Also, all the reviews for the searched project will be saved as a CSV file in Reviews folder of the project.

## 🛠️ Requirement packages

* Flask
* Flask-Cors
* gunicorn
* beautifulsoup4
* bs4
* certifi
* chardet
* click
* idna
* itsdangerous
* Jinja2
* MarkupSafe
* requests
* six
* soupsieve
* urllib3
* Werkzeug
* pymongo
* pandas


## ⚙️ SetUp

1. Creating conda environment
 ``` 
 conda create -p venv python==3.7 -y 
 ```

2. For activating environment
```
"conda activate venv/"
```
3. For installing packages in requirements.txt
```
pip install -r requirements.txt
```

4. To add files to git
```
git add <file_name> => for adding single file to git.
git add . => for adding all the files to your local git.
```
5. To check the git status
```
git status
```
6. To create version/commit all the changes to git

```
git commit -m "Message"
```
7. To send version/changes to github.
```
git push origin main
```
