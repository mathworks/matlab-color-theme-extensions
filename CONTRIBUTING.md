# Contributing

>_If you believe you have discovered a security vulnerability, please **do not** open an issue or make a pull request.  Follow the instructions in the [SECURITY.md](SECURITY.md) file in this repository._

Thank you for your interest in contributing to a MathWorks repository!  We encourage contributions large and small to this repository.  

**Contributions do not have to be code!** If you see a way to explain things more clearly or a great example of how to use something, please contribute it (or a link to your content).  We welcome issues even if you don't code the solution.  We also welcome pull requests to resolve issues that we haven't gotten to yet!

## How to contribute

* **Open an issue:** Start by [creating an issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/creating-an-issue) in the repository that you're interested in.  That will start a conversation with the maintainer.  When you are creating a bug report, please include as many details as possible.  Please remember that other people do not have your background or understanding of the issue; make sure you are clear and complete in your description.
* **Work in your own public fork:** If you choose to make a contribution, you should [fork the repository](https://docs.github.com/en/get-started/quickstart/fork-a-repo).  This creates an editable copy on GitHub where you can write, test, and refine your changes.  We suggest that you keep your changes small and focused on the issue you submitted.
* **Sign a Contributor License Agreement (CLA):** We require that all outside contributors sign a [CLA](https://en.wikipedia.org/wiki/Contributor_License_Agreement) before we can accept your contribution.  When you create a pull request (see below), we'll reach out to you if you do not already have one on file.  Essentially, the CLA gives us permission to publish your contribution as part of the repository.
* **Make a pull request:** "[Pull Request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)" is a confusing term, but it means exactly what it says:  You're requesting that the maintainers of the repository pull your changes in.  If you don't have a CLA on file, we'll reach out to you.  Your contribution will be reviewed, and we may ask you to revise your pull request based on our feedback.  Once everyone is satisfied, we'll merge your pull request into the repository.

## Guidelines

At this time, we are not accepting contributions to the MATLAB scripts themselves, but we welcome and encourage contributions of new color schemes. Here are a few recommendations to help you get started:

- **Follow the format**: Your color scheme file should be in JSON format and adhere to the structure shown in the template.json file. You should validate the file using [validateJsonFile](./validateJsonFile.p) script.
- **Choose your palette**: You may use any popular or open-source color palette when creating your scheme. Please name your file in a way that reflects the palette or theme.
- Feel free to design your own color scheme that enhances the MATLAB GUI. Just ensure it aligns with either the Light or Dark MATLAB themes for consistency.
- Before submitting, please verify that your scheme loads correctly and provides good readability and contrast in MATLAB.

**Again, thanks for contributing, and we look forward to your issues and pull requests!**