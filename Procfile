web: bundle exec thin start -p $PORT -e $RACK_ENV
worker: bundle exec rake jobs:work
slow: bundle exec rake jobs:slow
