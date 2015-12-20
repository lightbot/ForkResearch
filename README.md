# ForkResearch
Why and How Developers Fork What from Whom in GitHub

This repository is the dataset in the research of fork.

## 1. newRepository.txt

All the repositories for study, formated as follow:

owner{login}, id, name, is_fork, created_at, pushed_at, updated_at, size, stargazers_count, language, forks, open_issues, has_downloads, has_wiki

The data is crawled through Github API: /repos/:owner/:repo  
You can get meanings of these items on https://developer.github.com/v3/repos/#get

Take the first line as an example:
> r-x,2349443,fte_openid_whitelist,0,Fri Sep 09 00:02:20 CST 2011,Wed Sep 21 07:05:41 CST 2011,Fri Jan 04 12:56:34 CST 2013,212,1,Ruby,0,0,1,1,

The repository's name is fte_openid_whitelist. Its owner is r-x and its id on Github is 2349443. It isn't forked from other repository (is_fork == 0). It is coded in Ruby.

It is created at "Fri Sep 09 00:02:20 CST 2011", pushed as "Wed Sep 21 07:05:41 CST 2011" and lastly updated at "Fri Jan 04 12:56:34 CST 2013".

Until the date when we crawled the data, the repository is forked by 0 person, stared by 1 person, and has only 1 open issues.

The repository has files for downloading (has_downloads == 1) and it has wiki page (has_wiki == 1).

(Since the file ‘newRepositorys.zip’ is larger than 500MB, it is zipped and divided to 4 zip files, including newRepositorys.zip, newRepositorys.z01, newRepositorys.z02, and newRepositorys.z03. All files need to be downloaded at first. Then these 4 files can be uncompressed together to generate the original file.)

## 2. fork_report_x.xlsx

We did two surveies about the fork, the fork_report_1.xlsx and fork_report_2.xlsx are the result.
