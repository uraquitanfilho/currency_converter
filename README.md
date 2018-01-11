![CSCore Logo](http://www.syx.com.br/projetos/screenshot.png)


# Exchange - Currency Converter #

Exchange - Currency Converter is a free and easyly page to help you fast converter between two Currency.
You will understand how to **CONSUME** an **external RESTful service**.

DEMO

    http://syx-exchange.herokuapp.com

Feel free to download or clone the source code:

    https://github.com/uraquitanfilho/currency_converter.git

#### HOW TO INSTALL: ####
- git clone https://github.com/uraquitanfilho/currency_converter.git
- cd currancy_converter
- bundle install

#### HOW TO EXECUTE: ####
- rails server

#### EXTRA INFORMATIONS: ####
**Exchange - Currency Converter** is using some gems:

## layout ##
- gem 'bootstrap', '~> 4.0.0.alpha3'

**HOW TO SETUP BOOTSTRAP**
- rename app/assets/stylesheets/**application.css** to app/assets/stylesheets/**application.scss**
- ADD: @import "bootstrap";
- Go to  app/assets/javascript/application.js and ADD: //= require bootstrap

## RESTful ACCESS ##
- gem 'rest-client'

## MAKE TEST using Capybara and rspec ##
<pre>
group :development, :test do
  gem 'capybara', '~> 2.13'  
  gem 'rspec-rails', '~> 3.5'
end
</pre>
