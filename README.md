# Continous Integrations with TravisCI
https://github.com/sahbanagold/continous_integrations

go to https://travis-ci.org/

sign in with github account

1. Add new repository by click plus sign at left sidebar next to My Repositories

2. click Sync account button first
3. check the list of repositories desired to be use on travis-ci
4. click one of the repositories list
5. watch it,  when git push fires from terminal travis will automatically test & build it


##### ** Note
create .travis.yml file on master folder where needed to include before_install script as below:

```yml
before_install:
  - nvm install "6"
```
at the top of yml file

screenshots of success build examples:

![alt tag](https://github.com/arctic-fox-2016/ci/blob/sahbana/screenshots/citesting.png)
![alt tag](https://github.com/arctic-fox-2016/ci/blob/sahbana/screenshots/citesting2.png)
![alt tag](https://github.com/arctic-fox-2016/ci/blob/sahbana/screenshots/citestinggithub.png)
