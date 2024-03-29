# Dynamic modular website front with Ruby on Rails
## Work in progress

This is a website front that is modular and dynamic. It is a light Ruby on Rails application and uses a [Strapi back-office](https://github.com/JulesPR1/dynamic-modular-website-bo) to manage the content.

Things you may want to cover:

## 📚 Versions

- Ruby 2.7.x
- Rails 7.0.4.3

## 💎 Addtionnal gems

- HTTParty

Make sure to run `bundle install` to install all the gems.

## 💾 Database

This project has been set up with no database. It uses the [Strapi back-office](https://github.com/JulesPR1/dynamic-modular-website-bo) to manage the content.

## 🚀 Run the project

Run `rails s` to start the server. Then go to `localhost:3000` to see the website.

Please note that in order to manage the content of the website, you will need to use the [Strapi back-office](https://github.com/JulesPR1/dynamic-modular-website-bo). You can find the code for the back-office on [GitHub](https://github.com/JulesPR1/dynamic-modular-website-bo).

If you want to customize the front-end of the website, you can edit the ERB files in the `app/views/home/partials` directory. Note that __they have to be correctly linked__ to the back-office components.

In summary, this project offers a modular and dynamic website front-end that is easy to customize and manage. By using the [Strapi back-office](https://github.com/JulesPR1/dynamic-modular-website-bo), you can edit, add and delete content on the website but you can also move around the components and change their order easily.