<!-- AUTO-GENERATED-CONTENT:START (STARTER) -->
<p align="center">
  <a href="https://www.gatsbyjs.org">
    <img alt="Gatsby" src="https://www.gatsbyjs.org/monogram.svg" width="60" />
  </a>
</p>
<h1 align="center">
  Gatsby's Typescript Jest Starter
</h1>

Barebones Gatsby starter with Typescript, Jest, and other useful configurations.

This starter includes configurations for Typescript, Jest (ts-jest), EditorConfig, ESLint, Prettier, GitHub pull request templates, and even Gitlab-CI. Enjoy!

## Prerequisites

In addition to [Gatsby's recommended pre-requisites](https://www.gatsbyjs.org/tutorial/part-zero/), this starter suggests to do the following:

- Install these extensions:
  - [EditorConfig](https://editorconfig.org/)
  - [Prettier](https://prettier.io/)
  - [ESLint](https://eslint.org/)
- Use [Visual Studio Code](https://code.visualstudio.com/) or another IDE which supports these extensions

If you plan to use GitLab-CI as your CI tool, see [Deploying Your Gatsby Site to an S3 Bucket](#-deploying-your-gatsby-site-to-an-s3-bucket).

## Getting Started

1.  **Create a Gatsby site.**

    Use the Gatsby CLI to create a new site, specifying this starter.

    ```sh
    # create a new Gatsby site using this starter
    gatsby new my-gatsby-starter https://github.com/denningk/gatsby-starter-typescript-jest
    ```

1.  **Start developing.**

    Navigate into your new site’s directory and start it up.

    ```sh
    cd my-gatsby-starter/
    gatsby develop
    ```

1.  **Open the source code and start editing!**

    Your site is now running at `http://localhost:8000`!

    _Note: You'll also see a second link: _`http://localhost:8000/___graphql`_. This is a tool you can use to experiment with querying your data. Learn more about using this tool in the [Gatsby tutorial](https://www.gatsbyjs.org/tutorial/part-five/#introducing-graphiql)._

    Open the `my-gatsby-starter` directory in your code editor of choice and edit `src/pages/index.js`. Save your changes and the browser will update in real time!

## Type-Checking and Linting

The `package.json` in this starter includes scripts for performing type-checking and linting on your project.

To check for correct typing run `npm run type-check` on the command line.

To check for correct code formatting with ESLint, run `npm run lint` on the command line.

## Testing

### Creating New Tests

One example test has been included in this starter. It can be found under `/src/components/__tests__/header.tsx`. This test creates a `Header` component and makes sure it renders correctly. Check out the [Jest documentation](https://jestjs.io/docs/en/snapshot-testing) for how to write more tests.

### Running Tests

To run Jest tests on the project, run `npm test` on the command line.

## Deploying Your Gatsby Site to an S3 Bucket

### AWS Set Up

## Project Structure

A quick look at the top-level files and directories you'll see in a Gatsby project using this starter.

    .
    ├── __mocks__
    ├── .github
    ├── node_modules
    ├── src
    ├── .editorconfig
    ├── .eslintrc.js
    ├── .gitignore
    ├── .gitlab-ci.yml
    ├── .prettierrc
    ├── gatsby-browser.js
    ├── gatsby-config.js
    ├── gatsby-node.js
    ├── gatsby-ssr.js
    ├── jest-preprocess.js
    ├── jest.config.js
    ├── LICENSE
    ├── loadershim.js
    ├── package-lock.json
    ├── package.json
    └── README.md

1.  **`/__mocks__`**: This directory contains [manual mocks](https://jestjs.io/docs/en/manual-mocks) which are used to stub out functionality with mock data. For example, instead of accessing a remote resource like a website or a database, you might want to create a manual mock that allows you to use fake data. This ensures your tests will be fast and not flaky. This description can be found in the [Jest documentation](https://jestjs.io/docs/en/getting-started.html).

1.  **`/.github`**: This directory contains GitHub-specific files such as a [pull request template](https://help.github.com/en/articles/creating-a-pull-request-template-for-your-repository) (`pull_request_template.md`) or a [contributing guide](https://help.github.com/en/articles/setting-guidelines-for-repository-contributors) (`contributing.md`). GitHub will automatically read and use these files.

1.  **`/node_modules`**: This directory contains all of the modules of code that your project depends on (npm packages). These packages are automatically installed when `gatsby develop` is run.

1.  **`/src`**: This directory will contain all of the code related to what you will see on the front-end of your site (what you see in the browser) such as your site header or a page template. `src` is a convention for “source code”.

1.  **`.editorconfig`**: This is a configuration file for [EditorConfig](https://editorconfig.org/). EditorConfig helps maintain consistent coding styles for multiple developers working on the same project across various editors and IDEs. It is recommended to download the EditorConfig extension for the IDE you will be using.

1.  **`.eslintrc.js`**: This is a configuration file for [ESLint](https://eslint.org/). ESLint is a linting tool for JavaScript. Code linting is a type of static analysis that is frequently used to find problematic patterns or code that doesn’t adhere to certain style guidelines. This description can be found in the [ESLint documentation](https://eslint.org/docs/about/).

1.  **`.gitignore`**: This file tells git which files it should not track / not maintain a version history for.

1.  **`.gitlab-ci.yml`**: This is a configuration file for deploying your site with [Gitlab-CI](https://about.gitlab.com/product/continuous-integration/). This YAML file details stages for building, testing, and deploying your Gatsby site to an AWS S3 bucket using Gitlab-CI. See [Deploying Your Gatsby Site to an S3 Bucket](#-deploying-your-gatsby-site-to-an-s3-bucket) for more info.

1.  **`.prettierrc`**: This is a configuration file for [Prettier](https://prettier.io/). Prettier is a tool to help keep the formatting of your code consistent.

1.  **`gatsby-browser.js`**: This file is where Gatsby expects to find any usage of the [Gatsby browser APIs](https://www.gatsbyjs.org/docs/browser-apis/) (if any). These allow customization/extension of default Gatsby settings affecting the browser.

1.  **`gatsby-config.js`**: This is the main configuration file for a Gatsby site. This is where you can specify information about your site (metadata) like the site title and description, which Gatsby plugins you’d like to include, etc. (Check out the [config docs](https://www.gatsbyjs.org/docs/gatsby-config/) for more detail).

1.  **`gatsby-node.js`**: This file is where Gatsby expects to find any usage of the [Gatsby Node APIs](https://www.gatsbyjs.org/docs/node-apis/) (if any). These allow customization/extension of default Gatsby settings affecting pieces of the site build process.

1.  **`gatsby-ssr.js`**: This file is where Gatsby expects to find any usage of the [Gatsby server-side rendering APIs](https://www.gatsbyjs.org/docs/ssr-apis/) (if any). These allow customization of default Gatsby settings affecting server-side rendering.

1.  **`jest-preprocess.js`**: This is a configuration file containing Babel settings for Jest. `jest.config.js` points to this file in order to transform all `.tsx` and `jsx` files that will be tested.

1.  **`jest.config.js`**: This is a configuration file for [Jest](https://jestjs.io/). Jest is a JavaScript testing framework.

1.  **`LICENSE`**: Gatsby is licensed under the MIT license.

1.  **`loadershim.js`**: This file contains a function used by Jest when tests are run.

1.  **`package-lock.json`** (See `package.json` below, first). This is an automatically generated file based on the exact versions of your npm dependencies that were installed for your project. **(You won’t change this file directly).**

1.  **`package.json`**: A manifest file for Node.js projects, which includes things like metadata (the project’s name, author, etc). This manifest is how npm knows which packages to install for your project.

1.  **`README.md`**: A text file containing useful reference information about your project.

1.  **`tsconfig.json`**: This is a configuration file for [Typescript](https://www.typescriptlang.org/). Typescript is a typed superset of JavaScript.
