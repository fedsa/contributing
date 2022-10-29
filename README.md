# Contributing

## Contributing to The Other Radio

When contributing, please follow the [Code of Conduct](/blob/main/code-of-conduct).

### Issues

Feel free to submit issues and enhancement requests.

### Contributing

We use [Github Flow](https://guides.github.com/introduction/flow/index.html), so all code changes happen through pull requests.
Pull requests are the best way to propose changes to the codebase.

#### Process

1. Fork the repo and create your branch from `develop`.
```bash
# after forking
git clone your-repo-url # for example: git clone https://github.com/your-name/fedsa-website-new.git
git remote rename origin your-username
git remote add origin origin-repo-url # for example https://github.com/fedsa/fedsa-website-new.git
git fetch origin develop:develop
git switch develop # if switch does not work use: git checkout develop

# create your feature branch
git switch -c feature-branch-name # for example 82-add-contributing-md-pointing-to-repo
# again, if switch does not work do: git checkout -b feature-branch-name
# make something!
```
2. Make sure your code lints.
3. Issue that pull request!

NOTE: Be sure to merge the latest from "upstream" before making a pull request!
