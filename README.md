# The Record Store

#### By Frank Proulx, Drew Henderson, Morgan Waites
 
#### This is an app for a site that allows the user to add albums, artists, and songs for imaginary record store site.

## Technologies Used

* Ruby
* Gems
* Bundler
* Rspec
* Pry
* Sinatra
* Capybara
* Postgres
* SQL
* SQL Designer

## Description

  Webpage display list of albums for hypothetical Record Store. User can add, edit, delete albums as well as artists and songs. Shows CRUD functionality and knowledge in relational databases. Database has tables for artists, albums, and songs and, lastly, a join table to show many to many relationship between albums and artists.
  
## Setup Instructions

* Create and/or navigate to the directory you would like to contain this project on your computer.
* Git clone this repo.
* Navigate into project directory 
* Type bundle install in the terminal to populate gems
* To create a database using the database backup included in this project, type in your terminal: 
      createdb [DATABASE NAME] 
      psql [DATABASE_NAME] < record_store.sql
      createdb -T [DATABASE_NAME] [TEST_DATABASE_NAME]
* Type rspec in the terminal to confirm passing of all tests  
* Type ruby app.rb to run the program with Sinatra
* Open browswer and enter the url "http://localhost:3000/" unless otherwise prompted in the terminal

## Known Bugs

* When album that user tries to add to artist does not exist, error page is not handled.
* Not all rspec tests pass; we left two useful fails in artists spec file.

## License

[MIT](https://opensource.org/licenses/MIT)

If you have any issues, questions, ideas or concerns, please reach out to me at my email and/or make a contribution to the code via GitHub.  

Copyright (c) 2021 Frank Proulx, Drew Henderson, Morgan Waites
