# gh-release-body

Updates a github release with the true commit body.

Meant as a companion to [progrium/gh-release](https://github.com/progrium/gh-release).

## Installation

```shell
curl -o /usr/local/bin/gh-release-body "https://raw.githubusercontent.com/dokku/gh-release-body/master/gh-release-body"
chmod +x /usr/local/bin/gh-release-body
```

## Usage

```shell
export GITHUB_ACCESS_TOKEN="ghp_SOME_PERSONAL_ACCESS_TOKEN"
gh-release-body $user/$repo $tag
````
