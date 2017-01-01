# oscar-dev
Development environment for the Oscar game application

### How to get started

``` sh
git -v
yarn -v
docker -v
docker-compose -v
git clone git@github.com:delta62/oscar-dev.git && cd oscar-dev
git submodule init && git submodule update
git submodule foreach yarn install
docker-compose up -d
```

Now you can access the UI at `http://localhost:3000`.
