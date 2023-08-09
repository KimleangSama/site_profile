A [Hugo](https://gohugo.io/) theme for a personal portfolio with minimalist design and responsiveness.

![Thumbnail](https://raw.githubusercontent.com/hugo-toha/toha/main/images/screenshot.png)

- **My Profile Site:** [keakimleang.com](https://keakimleang.com)
- [Documentation Here](https://toha-guides.netlify.app/posts)

## Features

- Minimalist Design
- Fully Responsive
- Multiple Language Support
- Carefully Designed Cards
- Experience Timeline
- Achievement Gallery
- Sidebar to Categorize the Posts
- Short Codes

For more details about the features please visit [here](https://toha-guides.netlify.app/posts/features/).

## Available Translations

- English
- 한국어
- Others

To know more about how to translate your site, please visit [here](https://toha-guides.netlify.app/posts/translation/). Follow, the data and post format from this [example site](https://hugo-toha.github.io).

## Requirements

- Hugo Version 0.109.0 (extended) or higher
- Go language 1.18 or higher (require for hugo modules)
- Node version v18.x or later and npm 8.x or later.

## Usage

The easiest way to use this theme is to fork [hugo-toha.github.io](https://github.com/hugo-toha/hugo-toha.github.io) sample repo. Then clone and change the configurations according to your need.

#### 1. Submodule the toha theme

Init your git repo in cloned folder and add this theme as a submodule.

```bash
$ git init
$ git submodule add https://github.com/hugo-toha/toha.git themes/toha
```

#### 2. Update your module

Now, run this command to load this theme as your module.

```bash
hugo mod tidy
```

#### 3. Running Locally

Now, you can run your hugo site locally with the following steps:

##### 1. Generate node dependency configuration

Now run the following command to generate node dependency configuration. This will create the a `package.json` file in you repo.

```bash
hugo mod npm pack
```

##### 2. Install dependencies

Install the node dependencies using following command:
```bash
npm install
```

##### 3. Run your site

Now, run you site locally using following command.

```bash
hugo server -w
```

When you run your site for first time, it will start with the default parameters. It should look similar to the [example site](https://hugo-toha.github.io). However, it will not have any sections in the homepage as we haven't configured them yet. You can configure your site by following the guides from [here](https://toha-guides.netlify.app/posts/configuration/).

## Contributing

You can contribute to this theme in various ways. You can report a [bug](https://github.com/hugo-toha/toha/issues/new?template=bug.md), file an [feature request](https://github.com/hugo-toha/toha/issues/new?template=feature_request.md), send a PR, [share your thoughts](https://github.com/hugo-toha/toha/issues/new?template=question.md) etc.

Pull requests are most welcome and I will be happy to review. Just follow the following principles:

- Keep it simple.
- Keep it consistent with the design.
- Use as few dependencies as possible.
- Have patience.

## Credit
I would like to thank the toha developer teams for this awesome theme.