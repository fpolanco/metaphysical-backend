# Metaphysical-Backend Setup


# Getting Started
You will need Ruby on Rails and Postgres to get started:

1. Install [Homebrew](https://brew.sh/)

   `$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
   
2. Install [Ruby](https://www.ruby-lang.org/en/)

   `$ brew install ruby`
   
3. Install [Rails](https://rubyonrails.org/)

   `gem install rails`
   
4. Install [PostgreSQL](https://www.postgresql.org/)

    `$ brew install postgresql`

# Executing Program
1. Bundle Install

`$ bundle install`

2. Create migrations, migrate and seed:

  ```
  
     $ rails db:create
     $ rails db:migrate
     $ rails db:seed
  ```   
     
  Last step, launch the rails server!

    `$ rails s`
