# hvajava.github.io

```
$ git clone https://github.com/hvajava/hvajava.github.io.git
$ cd hvajava.github.io.git
$ jbake -b . docs
```

... and you can run and test it with:

```
$ jbake -b -s . docs
$ "your browser" http://localhost:8820
```

... do your changes until satisfied and:
... and just commit the changes to the repo.

```
$ cp -r WEB-INF docs && cd docs && zip -r ../pages.war . && cd ..
$ Deploy the war at your favourite application server
```
