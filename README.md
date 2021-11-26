## Pull Request Templates

### Purpose

Adding a pull request template to your project helps add clarity around
contributing guidelines. The template helps enforce consistency and
transparency around contributions to your code base. By supplementing your
pull request with a detailed description, you help the contributor aggregate
their work into a meaningful summary while providing more context for the
code reviewer.

This repo was created to share pull request templates we
consider to be useful during our code review process for our different kinds of projects (react, react-native etc).

### Installation

Create a `.github` directory (if it does not already exist):

```
mkdir .github && cd .github
```

Once thats created, you need to download the template from this repo. To
download the template you would like to use, you can run the following
cURL command:

```
curl -O https://raw.githubusercontent.com/redmindab/pr-templates/master/frontend/PULL_REQUEST_TEMPLATE
```

Every template is named `PULL_REQUEST_TEMPLATE` for easy installation, so you
just need to update the path in order to retrieve the correct template.
