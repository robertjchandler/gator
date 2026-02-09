# Welcome to Gator

To run gator, you will need to have Postgres and Go installed.

To install gator, type go install gator anywhere.

In your root directory, create gatorconfig.json with the following contents:

   `{"db_url":"postgres://postgres:postgres@localhost:5432/gator?sslmode=disable","current_user_name":"USERNAME"}`

To get started you can run `gator users` to see which users are already registered.

Run `gator register <USERNAME>` to register a new user.

Gator browse shows the posts from all the feeds that the current user follows.

Run `gator addfeed <FEED>` to add a new feed.

To unfollow a feed, simply run `gator unfollow <FEED>`.
