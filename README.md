house

# Setup

  * Setup the database and nginx `docker-compose -d nginx db`
  * Setup the api `docker-compose run --rm api mix deps.get`
  * Setup the api data `docker-compose run --rm api mix ecto.setup`
  * Setup the web `docker-compose run --rm web npm install` (This needs to be fixed)
  * Start systems `docker-compose up -d`

Now you can navigate to [http://localhost](http://localhost)
