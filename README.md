# bggn213_github
My class work

##Connecting RStudio to GitHub

1. Create a Personal Access Token (PAT) on GitHub

library(usethis)
create_github_token()

2. Store Personal Access Token to Connect RStudio and GitHub

library(gitcreds)
gitcreds_set()

