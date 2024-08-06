# Kross Finance Coding challenge(QA-Automation-Engineer)

Hi, thanks for applying for the QA Automation Engineer position at Kross Finance Korea.
This coding challenge is aiming to evaluate a candidate's problem-solving skills in real-world experiences.
The specific tasks are listed in **the Github issue tracker** and you could submit and merge a PR as you might work with the GitHub issue tracker. The tasks include a bug fix and feature request.

#### Before you start

-   This `README` file has a basic description of the project. Please read it carefully.
-   Look through the tasks and give a quick time estimation for completing the challenge.
-   Submit the PR and merge by yourself for each task. Make sure to specify how much time you spent on the task.
-   use `yarn` over `npm`

## Installation

1. Make sure you have [**node**](https://nodejs.org/), [**yarn**](https://yarnpkg.com/), [**docker**](https://www.docker.com/products/docker-desktop) installed.
2. install dependencies

```
$ yarn install
```


### if you have docker installed then below commands 
If you have docker installed then build Docker Image by following command

```
docker build -t QA-Automation-tests .
```

## Running Tests

And then, you can run the container from the built image

```
docker run QA-Automation-tests
```

OR 
(if playwright and broswers are globally added to your PC)
```
npx playwright test
```





