= Nomster

A simple Yelp clone with a mobile-fist design, listing restaurants in Chicago.

View the {Live Site}[https://nomster-edwin-f.herokuapp.com/].


Features:

Built with Ruby on Rails and Bootstrap
Integrates with the Google Map API, and Bing API 
Includes user comments, star ratings, image uploading, and user authentication

= Install
      
=== System Requirements
- Ruby `2.3.1` recommended
- Rails 5.0.1
- Postgres 9.2+
 
=== Fork and bundle
- Fork the project
- Run bundle to install gems

  <tt> bundle install </tt>   
        
=== Database setup

Download and Install Postgres[https://www.postgresql.org/download/]

- Create the databases:

  <tt> rails db:create </tt>
        
- Run migrations to create tables:

  <tt> rails db:migrate </tt>
