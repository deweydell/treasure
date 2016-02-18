# Treasure

# About

Treasure is a Ruby on Rails web application that allows users to list an item and swipe against others' items based on whether or not users would be willing to trade it. The app was created as a final project at the end of [Dev Bootcamp](http://devbootcamp.com/).

Created by [Carolina Medellin](http://github.com/caromedellin), [Darius Atmar](http://github.com/datmar), [Natalie Polen](http://github.com/nataliecodes) & [Nicola Beuscher](http://github.com/deweydell)

## Built With
Treasure is built with the following open source components:
- [Ruby on Rails](https://github.com/rails/rails)
- [PostgreSQL](http://www.postgresql.org/)
- [jQuery](http://jquery.com/)
- [OmniAuth](https://github.com/intridea/omniauth)
- [Paperclip](https://github.com/thoughtbot/paperclip)

###Dependencies
- [PostgreSQL](http://www.postgresql.org/)
- Bundler gem ('gem install bundler')

##How to Run Our App Locally (OS X 10.8 or later)
1. In the terminal:
~~~
git clone https://github.com/deweydell/treasure.git
~~~
2. Enter the root directory and run the following commands:
~~~
bundle install
bundle exec rake db:drop && rake db:create && rake db:migrate && rake db:seed
bundle exec rails s
~~~
3. The app will now be running on localhost:
~~~
=> Booting WEBrick
=> Rails 4.2.5 application starting in development on http://localhost:3000
=> Run `rails server -h` for more startup options
=> Ctrl-C to shutdown server
~~~

##Screenshots
###List an item to trade
Below is a shot of Steven's bicycle's profile. He can see his item and the other items his bike has matched with.
![My Treasure](screenshots/my-treasure.png)
###Swipe right or left on other users' items
Below is a shot of our 'main page' where users can swipe right or left on other items.
![Swipe Item](screenshots/swipe-page2.png)
###A match is made when two users like each other's items
There is a pop-up message when a match is made.
![Match Modal](screenshots/match-modal.png)
###In-app messaging for matched items
The below page is an item's match page. Steven can message with the owner of the jeans and coordinate exchanging their items.
![Match Messages](screenshots/message-page.png)

##Future Features
- Location-based filtering
- User ratings and reviews
- Multiple item listings for highly-rated users
