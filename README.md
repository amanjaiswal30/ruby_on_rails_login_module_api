# Ruby on Rails API with MySQL Database
A sample Ruby on Rails RESTful API created with endpoints for Login and Signup with MySQL database as backend.This project covers all fundamentals of Ruby on Rails and creating APIs using Ruby on Rails.For Authentication it uses the JSON Web Tokens(JWTs) and for encrypting the data in database it uses Bcrypt Encoder.
## Getting Started
Before cloning the project make sure you have the following softwares installed and set up on your machine.I have configured the port for MySQL as 9000 in config/database.yml.
### Prerequisites
Ruby 2.3.3 & Rails 5.1.7. For more information on installing it,go to
```
http://railsinstaller.org/en
```
MySQL Workbench. For more information on installing it,go to
```
https://dev.mysql.com/downloads/workbench/
```
## Running the project
Go to the desired directory on your machine, open the terminal and type the following command to clone the project
```
https://github.com/amanjaiswal30/ruby_on_rails_login_module_api/git
```
Go to your cloned directory and install the gems by running the following command
```
bundle install
```
Next,migrate the database
```
rails db:migrate
```
Finally run the server
```
 rails s
```
