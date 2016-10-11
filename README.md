# ci
https://github.com/sahbanagold/continous_integrations

go to https://travis-ci.org/

sign in with github account

1. Add new repository by click plus sign at left sidebar next to My Repositories

- click Sync account button first
- check the list of repositories desired to be use on travis-ci
- click one of the repositories list
- watch it,  when git push fires from terminal travis will automatically test & build it


##### ** Note
create .travis.yml file on master folder where needed to include before_install script as below:

```yml
before_install:
  - nvm install "6"
```
at the top of yml file
