#### [Assignment](https://github.com/buz-zard/_archive/blob/master/problem-mld/ASSIGNMENT.md) - quiz web app.


---

Deployment
- `make install` - install and setup deployment environment __*__ :wrench:
- `make deploy.api-dev` - deploy API to AWS Eslatic Beanstalk __dev__ [environment](http://mld-dev.eu-central-1.elasticbeanstalk.com/) :rocket:


---
__*__ Manualy append above line at the bottom of `.elasticbeanstalk/config.yml` file:
```
deploy:
  artifact: build.zip
```