# Git Immersion (2023 Edition)

A guided tour that walks through the fundamentals of Git, inspired by the premise that to know a thing is to do it.

---

`git` is an industry standard version control system. This workshop will give you a deep dive into how to use it on a project.

Large parts of this tutorial are based on the [Git Immersion](https://github.com/edgecase/git_immersion) tutorial which was originally presented at RailsConf 2010 by [Jim Weirich](https://en.wikipedia.org/wiki/Jim_Weirich). That tutorial is licensed as CC-BY-SA and this updated tutorial retains that license.

Changes from the original:

- Switch from `master` to `main` as the default branch
- Use `restore` instead of `checkout` to roll back unstaged changes
- Use `restore --staged` instead of `reset` to roll back staged changes
- Remove steps that add the Rakefile to remove the dependency on having `ruby` available
- Use `switch` instead of `checkout` to change branches
- Create a new change to demonstrate the difference between merge and rebase, instead of resetting both branches
- Round things out by pushing to a repository on Github

This version of Git Immersion was updated in 2022 by Brenton Cleeland for Publicis Sapient Australia for the Early Careers program. Like the original, it is released under a [Creative Commons Attribution Non-Commercial Share-Alike 4.0 International](https://creativecommons.org/licenses/by-nc-sa/4.0/) license.


## Build

This version uses [`imml`](https://github.com/leoncvlt/imml) to output the final HTML version of the workshop. You can use `npx` to run the build process:

```
npx --package commander --package imml --package jsdom --package html-minifier --yes imml git-immersion.imml
```

## Contributing

Updates, corrections and improvements are welcome. Please raise an issue to discussion new labs to ensure that they will be accepted.

Update the `git-immersion.imml` file.
