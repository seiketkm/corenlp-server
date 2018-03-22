# CoreNLP with Maven

```
mvn exec:java 
```

# example curl request

```
curl "http://localhost:9000/?properties={%22annotators%22%3a%22openie%22%2c%22outputFormat%22%3a%22json%22}" --data "The quick brown fox jumped over the lazy dog."
```

or open in browser `http://localhost:9000`


# detail
https://stanfordnlp.github.io/CoreNLP/corenlp-server.html


# package

```
mvn package
```

