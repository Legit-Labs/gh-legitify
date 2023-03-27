# gh-legitify
GitHub CLI extension for running "legitify"

## Install

```
gh extension install legit-labs/gh-legitify
```

## Usage
```
gh legitify 
```

### Flags

 * --org: analyze only the specific GitHub organization (instead of all the organizations the token has access to)
 * --repo: comma separated list of repo names to analyze only selected repositories (--repo legit-labs/legitify)
 * --scorecard yes/no/verbose run scorecard as part of the analysis
