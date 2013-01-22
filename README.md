# Starter

Starter is a boilerplate Rails for quickly starting lasting Rails projects. It's optimized for deployment to Heroku using a PostgreSQL database.

Recommended process:
  * Download this repo as a ZIP-File, extract it, rename the folder and `cd` to it.
  * `git init`, `git add .` and `git commit -m "First commit"`.
  * Create your own project on Github, add the remote as `origin`. and push for the first time
  * Globally replace `Selfstarter` (case-sensitive, the current application name) with your app name (every texteditor should offer a case-sensitive find-and-replace option).
  * Go through all files, especially config files, and name your database and session stores correctly.
  * Create your db with `rake db:create`.
  * Run `rails generate figaro:install` and add a `SECRET_TOKEN: random_string` to the generated `config/application.yml` file holding environment variables (this file is not checked into version control).
  * Link up the project to a great development domain with pow and powder: `powder link`
  * Point your browser to the domain powder presented you with: `http://myapp.dev` and see if everything is working.
  * Improve your app :-D

See the Gemfile for standard technology choices. Feel free to help further optimize this starting point.

Thomas Klemm - A Starter
@thomasjklemm || github@tklemm.eu