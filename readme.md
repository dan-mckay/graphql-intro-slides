# GraphQL - An Intro & Building an API with Hasura

Slides from a talk I did at HMH Eng Talks in Nov 2019

### Hasura

[hasura.io](https://hasura.io/)

Get it running with [Docker](https://docs.hasura.io/1.0/graphql/manual/getting-started/docker-simple.html) or [Heroku](https://docs.hasura.io/1.0/graphql/manual/getting-started/heroku-simple.html)

In the console, create a table called `user` with the following rows:
```
id - integer
name - text
email - text
```

You can then use this simple [client](https://gist.github.com/dan-mckay/9a0bbe93986626fd746ec05cba51ec42) to write to the database using the autogenerated mutation & API