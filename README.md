# Rails 7 + Hotwire (Turbo + Stimulus) = Modern web applications


## Steps used to generate this project:

```
rails new rails-7-fullstack -j esbuild -c tailwind
cd rails-7-fullstack
echo "rails-7-fullstack" > .ruby-gemset
rvm use @rails-7-fullstack
bin/rails d stimulus hello
# Created .editorconfig
rails g scafolld Kit::Product name:string
rails g scaffold Kit::Component product:references name:string
bin/rails db:migrate
# Changed the root route
# Applied Tailwind styles
bundle add simple_form
bin/rails generate simple_form:install
```

