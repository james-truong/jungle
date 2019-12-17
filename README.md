# James Truong's "Jungle" Project (Lighthouse Labs)


## Background
This project was completed as part of the Week 10 requirements while I was a student in the Web Development bootcamp at Lighthouse Labs. Jungle is a mini e-commerce application built with Rails 4.2 for the purposes of teaching Rails by example. This project was not just about learning a new language, ecosystem and framework. It was moreso a simulation of the real world, as I inherited an existing code base in a language / framework that I was not comfortable with.


## Functional Requirements

There are multiple high-level goals to this project, as per Lighthouse Labs' curriculum:

- Become familiar with Ruby and the Rails framework
- Learn how to navigate an existing code-base
- Use existing code style and approach to implement new features in unfamiliar territory
- Apply previous learning tactics to research and become familiar with a new paradigm, language and framework
- A simulation of the real world where feature and bug-fix requests are listed instead of step-by-step instructions on how to implement a solution


## Getting Started

1. Fork & Clone
2. Run `bundle install` to install dependencies
3. Create `config/database.yml` by copying `config/database.example.yml`
4. Create `config/secrets.yml` by copying `config/secrets.example.yml`
5. Run `bin/rake db:reset` to create, load and seed db
6. Create .env file based on .env.example
7. Sign up for a Stripe account
8. Put Stripe (test) keys into appropriate .env vars
9. Run `bin/rails s -b 0.0.0.0` to start the server


## Stripe Testing

Use Credit Card # 4111 1111 1111 1111 for testing success scenarios.

More information in their docs: <https://stripe.com/docs/testing#cards>


## Dependencies, Scripts, and External Requirements/Resources

* Bcrypt
* Bootstrap
* Byebug
* Capybara
* Database_Cleaner
* Faker
* jQuery-Rails
* Money-Rails
* Poltergeist
* PostgreSQL 9.x
* Puma
* Rails 4.2 [Rails Guide](http://guides.rubyonrails.org/v4.2/)
* RMagick
* Sass
* Spring
* Stripe
* Turbolinks


## Final Product

!["Screenshot of Home Page"](https://raw.githubusercontent.com/jonosue/jungle-rails/master/docs/home-page.png)
!["Screenshot of New User Registration"](https://raw.githubusercontent.com/jonosue/jungle-rails/master/docs/new-user-registration.png)
!["Screenshot of Products in Cart"](https://raw.githubusercontent.com/jonosue/jungle-rails/master/docs/products-in-cart.png)
!["Screenshot of Stripe Payment"](https://raw.githubusercontent.com/jonosue/jungle-rails/master/docs/stripe-payment.png)
!["Screenshot of Order Confirmation"](https://raw.githubusercontent.com/jonosue/jungle-rails/master/docs/order-confirmation.png)
!["Screenshot of Product with Reviews"](https://raw.githubusercontent.com/jonosue/jungle-rails/master/docs/write-review.png)
!["Screenshot of a Submitted Review"](https://raw.githubusercontent.com/jonosue/jungle-rails/master/docs/rating-submitted.png)
!["Screenshot of Product with No Reviews"](https://raw.githubusercontent.com/jonosue/jungle-rails/master/docs/product-with-no-reviews.png)
