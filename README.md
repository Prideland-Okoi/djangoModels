## Task Title: Django Models

Assignment

1. Create a new GitHub repository with a README.md, and Python .gitignore file.

2. Clone it to your machine/computer, which will create a new folder on your computer with your repository’s content.

3. Create a new virtual environment in that folder named .env and install Django in it.

4. Create a new Django project. Use your Zuriboard Student ID as the name of the project.

5. Create a new application using the Django startapp command. The app should be called blog.

6. Add the blog app to the main_projects INSTALLED_APPS.

7. Create a new model in the blog app called Post. It should have the following fields:

** Post **

---

Title : A string of maxlength 200, use Django’s models.CharField

Text : Any amount of text, use Django’s TextField

Author : A Foreign Key to the current user model. Make use of Django’s get_user_model function

Created_date : A date-time column, use Django’s models.DateTimeField.

Published_date : A date-time column, use Django’s models.DateTimeField.

Create migrations for your new model using the makemigrations Django command.

Run all migrations using the migrate Django command.

Stage and Commit your Django project and push your changes to your GitHub repository.

Ensure your final code/submission is on the default branch of your GitHub repository.

8. Submit the link to the Github repository e.g https://github.com/github_username/repo_name

## Resources:

I. Python: Environment Variables in Django I(https://www.youtube.com/watch?v=ceSm2yE97VE&list=PLxuUHF3OiqfWAITD4gPUHZ1GcYRqmyF7P&index=36)

II. https://www.youtube.com/watch?v=EexZAwPI2FM&list=PLxuUHF3OiqfWAITD4gPUHZ1GcYRqmyF7P&index=33

III. Introduction To Django by Eniola and Mildness(https://www.youtube.com/watch?v=fun0b0C2hAM&list=PLxuUHF3OiqfUre0fws5Y33YMfGJnzTBMZ&index=11)
