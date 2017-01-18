## GitHub Graph

### Introduction
GitHub Graph is graphed the data of fetching repository.

### Usage
Note: We should be add `export GITHUBTOKEN="your github access token"` on your bash_profile.
Then, please execute `source bash_profile`.

Can execute command `gitgraph -h`.
    GitHub Graph
    usage: gitgraph [options] <text>

    <text>               text to store

    --hidden             hidden data of repository. default is false.
    -c, --color=COLOR    set bar color. default is red. supported colors are
                        yellow, cyan, white, magenta, green, red, grey, blue, or ascii.
    -h, --help           display help & usage
    -s, --sort=BOOLEAN   sort data. default is full_name. we can choose fromcreated, updated, pushed, full_name
    -v, --version        display cli name & version
    compare              compare repos. we should be input name of user.
    myrepo               search repos.
    search               search repos. we should be input name of repos.
