# Rails Templates

Quickly generate a rails app with the default [Mihivai](https://www.mihivai.com) configuration
using [Rails Templates](http://guides.rubyonrails.org/rails_application_templates.html).

Get a minimal rails 5.2+ app ready to be deployed on Heroku with Bootstrap, Simple form, Webpack, debugging gems and Devise install with a generated `User` model.

```bash
rails new \
  --database postgresql \
  --webpack \
  -m https://raw.githubusercontent.com/mharribey/templates/master/minimal.rb \
  CHANGE_THIS_TO_YOUR_RAILS_APP_NAME
```
