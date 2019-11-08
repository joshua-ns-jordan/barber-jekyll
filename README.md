# The tour
This is the website/blog for our trip through europe surfing and DJ'ing. 

It is built using the jekyll static website generator based on the barber theme. Currently hosted using an AWS buket instance.

## setup
Jekyll requires all dependencies to be saved in the Gemfile. Install the dependancies using the ruby bundler.

`gem install bundler`

Then install the libraries required with:
`bundle install`

You may need to delete the node_modules folder and run 
`npm install`

## build
To build the production ready site preview, run:
`npm run build`

## run
To see the generated site 
`npm run start`

## deploy
This will deploy the latest build to the aws bucket which should be seen immediately for the whole wide web.
`npm run deploy`
