# repo-boiler-plate

This is a boilerplate you can use to have your repo set with my best practices: a README, git workflows, necessary tools, dependencies, file structure etc

You can [create a repo out of this template](https://github.com/NdagiStanley/repo-boiler-plate/generate).

Otherwise for a repo you've already started; here's a simple command to run at the root of your repository. (Please, ensure you commit your code before doing so. By that I mean; nothing should be in the staging area of git before running this so that you can much more easily decide which changes you are pulling in)

```bash
git clone https://github.com/NdagiStanley/repo-boiler-plate/.git && rm -rf repo-boiler-plate.git && cp -r repo-boiler-plate/. . && rm -rf repo-boiler-plate
```

## Git

Workflows:

- `main` (Simple solo project)
- `main - dev` (Low complexity project with collaborators)
- `main - staging - develop` (Standard project)
- `main - staging - develop - feature-review-...` (Highly complex project)

Branch naming conventions:

- `task/...`
- `fix/...` or `fx-..`
- `feat/...` or `ft-..`

## Necessary Tools

A bad workman blames his tools! Nonetheless, build your tooling so that it in hand builds you.

Here's mine:

<details>
  <summary>Continuous Integration with <b>AppVeyor</b>, <b>CircleCI</b>, <b>Github actions</b>, <b>Netlify</b>, <b>SemaphoreCI</b>...</summary>

  * Repo: [electron-bot/electron](https://github.com/electron-bot/electron)

    ![AppVeyor](https://img.shields.io/appveyor/build/electron-bot/electron)

  * Repo: [workforce-data-initiative/tpot-abacus](https://github.com/workforce-data-initiative/tpot-abacus)

    ![CircleCI](https://img.shields.io/circleci/build/github/workforce-data-initiative/tpot-abacus)

  * Repo: [github/hub](https://github.com/github/hub)

    ![GitHub Workflow Status](https://img.shields.io/github/workflow/status/github/hub/CI)

  * Repo: [NdagiStanley/lumen](https://github.com/NdagiStanley/lumen) | Deployment [stanmd.tk](https://stanmd.tk)

    ![Netlify](https://img.shields.io/netlify/ba0b4698-8569-4e8d-bfca-b7bff0cfee57)

  * Repo: [NdagiStanley/vue-django](https://github.com/NdagiStanley/vue-django)

    [![Build Status](https://semaphoreci.com/api/v1/stanmd/vue-django/branches/master/shields_badge.svg)](https://semaphoreci.com/stanmd/vue-django)

</details>

<details>
  <summary>Code quality analysis with <b>Code Climate</b></summary>

  * Repo: [NdagiStanley/django_girls_complete](https://github.com/NdagiStanley/django_girls_complete)

    ![Code Climate coverage](https://img.shields.io/codeclimate/coverage/NdagiStanley/django_girls_complete)
    ![Code Climate issues](https://img.shields.io/codeclimate/issues/NdagiStanley/django_girls_complete)
    ![Code Climate maintainability](https://img.shields.io/codeclimate/maintainability/NdagiStanley/django_girls_complete)
    ![Code Climate lines of code](https://badgen.net/codeclimate/loc/NdagiStanley/django_girls_complete)

</details>

<details>
  <summary><b>Licensing</b></summary>

  * Repo: [NdagiStanley/repo-boiler-plate](https://github.com/NdagiStanley/repo-boiler-plate) (_this repo_)

    ![GitHub](https://img.shields.io/github/license/Ndagistanley/repo-boiler-plate)

</details>

<details>
  <summary>Containerization with <b>Docker</b></summary>

  * Repo: [NdagiStanley/vue-django](https://github.com/NdagiStanley/vue-django) | In DockerHub: [stanmd/vue-django](https://hub.docker.com/repository/docker/stanmd/vue-django)

    ![Docker Cloud Build Status](https://img.shields.io/docker/cloud/build/stanmd/vue-django)
    ![Docker Pulls](https://img.shields.io/docker/pulls/stanmd/vue-django)

  * Repo: [docker-library/postgres](https://github.com/docker-library/postgres) | In DockerHub: [postgres](https://hub.docker.com/_/postgres)

    ![Docker Image Version (latest semver)](https://img.shields.io/docker/v/_/postgres?sort=semver)
    ![Docker Image Size (latest semver)](https://img.shields.io/docker/image-size/_/postgres?sort=semver)

</details>

<details>
  <summary>Documentation on <b>Read the Docs</b></summary>

  * Repo: [psf/black](https://github.com/psf/black)

    ![Read the Docs](https://img.shields.io/readthedocs/black)

</details>

#### Packaging

<details>
  <summary>In general, <b>SemVer</b> - Semantic Versioning should be adhered to</summary>

  * Repo: [NdagiStanley/lifebuoy](https://github.com/NdagiStanley/lifebuoy)

    ![GitHub package.json version](https://img.shields.io/github/package-json/v/NdagiStanley/lifebuoy)

</details>

<details>
  <summary>Python packages on <b>PyPI</b></summary>

  * Repo: [encode/django-rest-framework](https://github.com/encode/django-rest-framework)

    ![PyPI - Django Version](https://img.shields.io/pypi/djversions/djangorestframework)
    ![PyPI - Python Version](https://img.shields.io/pypi/pyversions/djangorestframework)

  * Repo: [amos-o/pipexec](https://github.com/amos-o/pipexec)

    ![PyPI - Wheel](https://img.shields.io/pypi/wheel/pipexec)
    ![PyPI - Implementation](https://img.shields.io/pypi/implementation/pipexec)
    ![PyPI - Downloads](https://img.shields.io/pypi/dm/pipexec)

  * Repo: [psf/black](https://github.com/psf/black)

    ![PyPI - Status](https://img.shields.io/pypi/status/black)

  * Repo: [workforce-data-initiative/tpot-abacus](https://github.com/workforce-data-initiative/tpot-abacus)

    ![PyPI](https://img.shields.io/pypi/v/abacus-tpot)

</details>

<details>
  <summary>Packaging in <b>NPM</b></summary>

  * Repo: [vuejs/vue](https://github.com/vuejs/vue)

    ![npm](https://img.shields.io/npm/v/vue)

  * Repo: [http-party/http-server](https://github.com/http-party/http-server) | In NPM: [http-server](https://www.npmjs.com/package/http-server)

    ![node-current](https://img.shields.io/node/v/http-server)

</details>

<details>
  <summary>Packaging in <b>VS Marketplace</b></summary>

  * Repo: [NdagiStanley/lifebuoy](https://github.com/NdagiStanley/lifebuoy)

    ![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/NdagiStanley.lifebuoy)
    ![Visual Studio Marketplace Downloads](https://img.shields.io/visual-studio-marketplace/d/NdagiStanley.lifebuoy)
    ![Visual Studio Marketplace Ratings](https://badgen.net/vs-marketplace/rating/NdagiStanley.lifebuoy)

</details>

#### Matters open-source on GitHub

- *torvalds/linux*

  ![GitHub commit activity](https://img.shields.io/github/commit-activity/m/torvalds/linux)

- *NdagiStanley/vue-django*

  ![GitHub issues](https://img.shields.io/github/issues/NdagiStanley/vue-django)
  ![GitHub stars](https://img.shields.io/github/stars/NdagiStanley/vue-django?style=social)
  ![GitHub forks](https://badgen.net/github/forks/NdagiStanley/vue-django)

  ![GitHub contributors](https://badgen.net/github/contributors/NdagiStanley/vue-django)
  ![GitHub release](https://badgen.net/github/release/NdagiStanley/vue-django)
  ![Open Collective backers](https://badgen.net/opencollective/backers/vue-django)

These badges (seen when you collapse the above sections) are corresponding with the tooling needed. Upon cloning the repo you simply edit the service's username and repo-name or project-name and where applicable the branch-name.

### Dependencies

<details>
  <summary>Dependencies across different language stacks</summary>

  I use **Dependabot**, **David DM**, **Libraries** and **Requires**

  * Repo: [NdagiStanley/codango](https://github.com/NdagiStanley/codango)

    ![Dependabot](https://badgen.net/dependabot/NdagiStanley/codango?icon=dependabot)

- NPM dependencies with [David DM](https://david-dm.org/)

  * Repo: [vuejs/vue](https://github.com/vuejs/vue)

    ![David](https://img.shields.io/david/vuejs/vue)

- OpenSource libraries with [Libraries](https://libraries.io)

  * Repo: [NdagiStanley/vue-django](https://github.com/NdagiStanley/vue-django)

    ![Libraries.io dependency status for GitHub repo](https://img.shields.io/librariesio/github/NdagiStanley/vue-django)

- Python dependencies with [Requires](https://requires.io)

  * Repo: [NdagiStanley/django_girls_complete](https://github.com/NdagiStanley/django_girls_complete)

    [![Requirements Status](https://requires.io/github/NdagiStanley/django_girls_complete/requirements.svg?branch=master)](https://requires.io/github/NdagiStanley/django_girls_complete/requirements/?branch=master)
</details>

<details>
  <summary>Vulnerabilities on <b>Snyk</b></summary>

  * Repo: [NdagiStanley/vue-django](https://github.com/NdagiStanley/vue-django)

    ![Snyk Vulnerabilities for GitHub Repo](https://img.shields.io/snyk/vulnerabilities/github/NdagiStanley/vue-django)
</details>

### Files

```bash
curl https://raw.githubusercontent.com/NdagiStanley/repo-boiler-plate/main/.editorconfig > .editorconfig
```

- `.circleci/config.yml` file for *CircleCI* located at root of your repository
- `.dependabot/config.yml` file for *Dependabot* located at root of your repository (on the default branch)
- `.editorconfig` file, located at the root of the repo. Used to help contributors define and maintain consistent coding styles between different editors and IDEs
- `.gitignore` file. Works with my [.gitignore_global](https://github.com/NdagiStanley/dotfiles/blob/main/git/.gitignore_global) file.

---
References:

- All matters Git: [Atlassian](https://www.atlassian.com/git/tutorials), [Git SCM](https://git-scm.com/docs)
- Licenses: [Choose a license][license]
- For badges/ shields: [shields.io][shields], [badgen.net][badgen]
- [GitHub][gh]

[license]: https://choosealicense.com/
[shields]: https://shields.io/
[badgen]: https://badgen.net/
[gh]: https://github.com/features/
