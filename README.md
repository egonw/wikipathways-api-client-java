# wikipathways-api-client-java
Java library for WikiPathways webservice

Currently under development and testing.

With this library you can access the pathway database WikiPathways from Java through the REST webservice API (http://webservice.wikipathways.org).
The old SOAP webservice will be discontinued in the near future (spring 2015) and all functionality (also updating and uploading information) have been implemented in the REST API. 

Be aware that update and upload functionality provide special permissions that need to be requested before using those webservice functions. 

Compile the code and run the tests with:

```
cd org.wikipathways.client
ant test
```

If you want to use a different web service, use (for example):

```
cd org.wikipathways.client
ant -Dwp.webserver=http://otherservice.wikipathways.org test
```

### TODO
- [x] set up automated testing framework on Jenkins (https://jenkins.bigcat.unimaas.nl/view/WikiPathways/job/WikiPathways%20REST%20Java%20library/)
- [ ] detailed documentation (JavaDoc!)

### Known bugs
