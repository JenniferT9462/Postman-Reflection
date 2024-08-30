# Interacting with GitHub's API

## Base URL
<https://api.github.com/>

### Bearer Token Setup

![Bearer Token Setup](<img/bearerToken.png>)

### Variable Setup

![Setting up variables](<img/variableSetupGh.png>)

### GET Request for all my repos

#### End-point URl to get All Repos
<https://api.github.com/users/jennifert9462/repos>

![GET All Repos](<img/getAllRepos.png>)

### CREATE a New Repo

#### End-point URL to create a new repo
<https://api.github.com/user/repos>

* In the body tab you should have at least a name for the new repo...

        {
            "name": "New-Repo-Aug-2024"
        }

![Create a Repo](<img/createRepo.png>)

#### My Github Repos that were made in Postman

![Github Repos](<img/myGhReposMadeInPostman.png>)

### Delete a Repo in Postman

#### End-point URL to Delete a Repo

<https://api.github.com/repos/jennifert9462/My-New-Name-Repo>

![Delete a Repo in Postman](<img/deleteRepo.png>)

#### My Github Repos w/out the Repo I just deleted

![Github Repos](<img/githubRepos.png>)

## Summary

This was a lot of fun, once you get all the kinks worked out. The roadblock that I faced was when I wanted to post something, like create a repo, I forgot to set something up in the body section. So, I kept getting a 'Not Found' or 'Forbidden' error. Also, knowing the correct end-point urls for the different actions is very important. 