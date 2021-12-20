# Rails Templates

Quickly generate a rails app with the default [Wagon](https://www.lewagon.com) configuration
using [Rails Templates](http://guides.rubyonrails.org/rails_application_templates.html).


## Devise

Same as minimal **plus** a Devise install with a generated `User` model.

```bash
rails new \
  --database postgresql \
  --webpack \
  -m https://raw.githubusercontent.com/gn13008/rails-templates/master/devise.rb \
  CHANGE_THIS_TO_YOUR_RAILS_APP_NAME
```


## Minimal (don't use this for the moment)

Get a minimal rails app ready to be deployed on Heroku with Bootstrap, Simple form and debugging gems.

```bash
rails new \
  --database postgresql \
  --webpack \
  -m https://raw.githubusercontent.com/lewagon/rails-templates/master/minimal.rb \
  CHANGE_THIS_TO_YOUR_RAILS_APP_NAME
```