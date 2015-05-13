# ForkResearch
Why and How Developers Fork What from Whom in GitHub

This repository is the dataset in the research of fork.

## 1. newRepository.txt

All the repositories for study, formated as follow:

owner{login}, id, name, is_fork, created_at, pushed_at, updated_at, size, stargazers_count, language, forks, open_issues, has_downloads, has_wiki

The data is crawled through Github API: /repos/:owner/:repo  
You can get meanings of these items on https://developer.github.com/v3/repos/#get
