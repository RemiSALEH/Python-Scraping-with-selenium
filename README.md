# Workshop - Python Scraping with selenium

- Learn how can you extract data from a website using selenium (https://www.selenium.dev/) and python
- After this workshop, you will have a program able to connect to Twitter and make few things.

# Step 0: Initialization

make sure that you have python and selenium installed, if not : go to [SETUP.md](./SETUP.md)

Now Create a .py file where you will create your functions.

# Step 1: first step with selenium

<ins> Exo 1 </ins> : Try to create a funcion that open a website, and return you if the website successfully oppend or not. You should call your function like that : 

``` open_website(url_of_webite) ``` 

Little tip, you should import this : ```` from selenium import webdriver ````.

# Step 2: how to bypass the new twitter api

Now that twitter api is no longer free, we have to find a way to bypass it. Web scraping is a good way to get information and also use twitter.

In this step, you will learn how to get user information from twitter website.

##

<ins> Exo 1 </ins> : Create a function that will open a twitter page and get the follower count of someone. You should call your function like that : 

``` get_user_follower_count(account) ```

##

<ins> Exo 2 </ins> : now that you can get the follower count of a user, make a big function that can get a user :

- follower count
- following count
- number of tweet
- last tweet

make sure that the information you get is the good one and it's undertable, and that you have error handling

##

<ins> Exo 3 </ins> : Now, create 2 function to accept cookies and notification automatically. same thing, be carefull about error handling.


# Step 3: go further with twitter

<ins> Exo 1 </ins> : Now that you can get information, you will now learn how to put information.

##

First create a function that will login you to twitter. You have 4 steps: 

- type your username
- click on the validation button
- type your password
- click on the login button

print something if you succeeded, if not -> error handling for every step.

##

<ins> Exo 2 </ins> : Now that you have the function to log in, create a function to like a tweet.

##

<ins> Exo 3 </ins> : Now that you can like a tweet, create a big function that like, rt, and comment a tweet, just by giving the URL.

(don't forget to use the login function ^^)

# Step 4: go further with twitter, 2

<ins> Exo 1 </ins> : create a function that make you a tweet, with the text wanted. 

##

