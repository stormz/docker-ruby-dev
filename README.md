# Ruby development

Docker image to run ruby services on development:

- mount your local code on docker
- configure bundler config
- export default rack port

## Usage

    docker run --rm -ti -p 9292:9292 -v $(pwd):/code stormz/ruby-dev bundle install
