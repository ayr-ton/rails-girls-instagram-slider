# Rails Girls Instagram Slider

[![Build Status](https://snap-ci.com/jlucasps/rails-girls-instagram-slider/branch/master/build_image)](https://snap-ci.com/jlucasps/rails-girls-instagram-slider/branch/master)


#### Build docker image
````
$ docker-compose build
````

#### Run rubocop
````
$ docker-compose run web rubocop
````

#### Run tests
````
 $ docker-compose run -e RAILS_ENV=test web rake test
````

#### Run rake tasks
````
$ docker-compose run web rake db:create
````

#### Boot the app
````
$ docker-compose up
````

