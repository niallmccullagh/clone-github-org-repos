# Clone Github Organisation Repos


This script clones/pulls the latest code for all the repositories in a github organisation. You must have access to the repositories in order to clone them.


*Usage:*

    ./clone-github-org.sh -u {GITHUB_USERNAME} -t {GITHUB_ORG_NAME}
    
By default the script will prompt you for your Github password or if you need to pass it in you can by passing using the `-p` flag. Note you can generate a specific token for this script at https://github.com/settings/tokens rather than using you main password.


For more info have a look at:

    ./clone-github-org.sh -h
