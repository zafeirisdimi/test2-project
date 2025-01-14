[![GitHub Actions Demo](https://github.com/zafeirisdimi/GithubActions-test-project/actions/workflows/github-actions-demo.yml/badge.svg?branch=main)](https://github.com/zafeirisdimi/GithubActions-test-project/actions/workflows/github-actions-demo.yml)

-------------------------------------------------------------------------------------------------------------------------------------------------------------------


<div align="center">
  <img src="https://img2.storyblok.com/672x0/filters:format(webp)/f/79165/1200x630/ebb5571e69/github-action-01.png" width="600"/>
  </div>


---------------------------------------------------------------------------------------------------------------------------------------------------------------------


# Github Actions-test-project #



## FAQs ##

- What are Github Actions ? 

GitHub Actions is a CI/CD and general automation system introduced by GitHub in 2018. It is integrated right into GitHub and enabled by default in every GitHub repository. GitHub Actions is completely free of charge.

- What means CI/CD?

  CI = Continuous Integration.
  CD = Continuous Delivery.

- What is a CI/CD pipeline?

<div align="center">
<img  src="https://miro.medium.com/max/1400/1*bceEG8JBhgjnMoZCGXHb2Q.png" alt='Image on Miro' width="500" height="auto" />
</div>

A CI/CD pipeline is the full set of processes that run when you trigger work on your projects. Pipelines encompass your workflows, which coordinate your jobs, and this is all defined in your project configuration file.

- How do i create an Github Action? 

Steps:

1) In the home page of our repository, we click to the 'Add New' button,
2) Click on the 'Create new file' button,
3) Our 'Create new file' page, we type in the path of our file, `.github/workflow/firstgithubaction.yml`,
4) We inserts the necessary options in the dialog box
5) At last, we click on 'Commit new file'
6) We check in the tab of Actions of our repository, our first github action is created
7) We notice that below the title of action, there is a blinked circle icon with yellow. It means that our action is tested if it is correct.
8) If our action run without error, the blinked circle icon will be green check icon. Otherwise, the blinked circle icon will be red icon.

- What kind of language is this yml file?

YAML is a digestible data serialization language often used to create configuration files with any programming language.

Designed for human interaction, YAML is a strict superset of JSON, another data serialization language. But because it’s a strict superset, it can do everything that JSON can and more. One major difference is that newlines and indentation actually mean something in YAML, as opposed to JSON, which uses brackets and braces.
 
- Important segments about this yaml file and Github actions?

  Events
  Jobs
  Runners
  Steps
  Actions
  
  - Other alternative popular CI/CD platforms 
  
  <ol>
    <li>Jetkins</li>
    <li>Travis CI</li>
    <li>Circle CI</li>
    <li>Drone CI</li>
    <li>Bamboo</li>
 
  </ol>


## Tech ##

- Github
- CI/CD pipelines
- Jetkins

## Useful resources ##

- [Getting started with Actions| Morioh](https://morioh.com/p/aadcfe6cac57)
- [Yaml file for beginner | CircleCi](https://circleci.com/blog/what-is-yaml-a-beginner-s-guide/)
- [The IDEAL & Practical CI / CD Pipeline - Concepts Overview | Youtube](https://www.youtube.com/watch?v=OPwU3UWCxhw&t=1s)

