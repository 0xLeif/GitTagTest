# GitTagTest

Repo for messing around with git tags. [🏷](https://git-scm.com/book/en/v2/Git-Basics-Tagging)

## GitHub Issues

### 1) Release page Next button doesn't work

The next button takes you to tags/ releases after the last tag on the page.

#### Steps to reproduce
- Go to the Releases page [🔗](https://github.com/0xLeif/GitTagTest/releases)
- Go to the bottom
- Click the next button [🔗](https://github.com/0xLeif/GitTagTest/releases?after=😎)
- Notice you will still be on the same page

**How to get to the next page**

Edit the URL to a valid tag. i.e. [0.0.0](https://github.com/0xLeif/GitTagTest/releases?after=0.0.0)

