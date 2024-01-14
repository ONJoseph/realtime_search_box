# Real-time Search box
> This project is a realtime search box that shows analytics on whats people searched for the most.

## Note
This project is realtime search box built with `Vanilla JS`, `ruby on rails` and `Turbo_Frames` to manage the realtime page load features connected with `Stimulus Js`.

## Live Link
[Live Link]()

## Built With

- Ruby on Rails
- Vanilla JS
- Turbo_frames
- Postgresql
- stimulus

## Getting Started

To get a local copy up and running follow these simple steps:

```sh
git clone https://github.com/ONJoseph/realtime_search_box.git
cd realtime_search_box
```

### Prerequisites
Before starting make sure that you have the following runing on your computer

- `Ruby 3.2.2`
- `Rails 7.1.2`
- `PostgresSQL`

### Setup

Install gems with:

```sh
bundle install
```

Create a file `.env` in the root of your project directory to store your database name and the password.

```sh
touch .env
```

`.env` file content

```ruby
DB_USERNAME=your_database_name
DB_PASSWORD=your_database_password
```

Setup database

```sh
rails db:setup
rails db:migrate
rails db:seed
```

Start server 

```sh
rails server
```

Open [http://localhost:3000/](http://localhost:3000/]) in your browser.
 
### Run tests

```
bundle exec rspec
```

## Authors

👤 **Joseph Ogbole**

- GitHub: [@ONJoseph](https://github.com/ONJoseph)
- Twitter: [@ONJCodes](https://twitter.com/ONJCodes)
- LinkedIn: [LinkedIn](https://www.linkedin.com/in/o-n-joseph-ba8425147/)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/ONJoseph/realtime_search_box/issues).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- Shoutout to Helpjuice, Google and ChatGPT!

## 📝 License

This project is [MIT](./MIT.md) licensed.
