# Elasticsearch Cookbook

This is the cookbook for the elasticsearch instance within our infrastructure. The kitchencloud.yml completes this action on AWS cloud web server, kitchen.yml can be used for local.

## Unit tests:

To start the unit test, run the command:

```
chef exec rspec spec
```

To run integration tests, run the command:

```
kitchen test
```


