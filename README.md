# Splurty

A database-powered quote generator with a mobile-first design, using the Ruby on Rails framework, HTML, and CSS. Uses Git and GitHub for version control, and launched on Heroku.

![splurty](/app/assets/images/splurty.png)


### Prerequisites

Setting up ruby on rails enviroment

[Getting Started with Rails](https://guides.rubyonrails.org/v5.0/getting_started.html)

### Installing

Once the ruby on rails enviroment has been set up.

Git clone the repository to your local machine:

HTTPS:
```
$ https://github.com/joelpankito/splurty.git
```
SSH:
```
$ git@github.com:joelpankito/splurty.git

```
Next, cd into the repository you cloned and install the necessary dependencies 
* In order to create your local database run:
```
rake db:create
```
```
rake db:migrate
```
* Install the necessary libraries:
```
$ bundle install
```
You will then be able to start the app locally by runnning:
```
$ rails server -b 0.0.0.0 -p 3000
```


## Built With

* [Rails](https://rubyonrails.org/) - web application framework

* [Postgres](https://www.postgresql.org/) - The database engine.

* [Bootstrap](https://getbootstrap.com/) - Bootstrap is a free and open-source CSS framework

* [Simple_form](https://github.com/heartcombo/simple_form) - building forms


## Authors

* **Joel Pankito** - *Complete work* - [Splurty](https://github.com/joelpankito)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
