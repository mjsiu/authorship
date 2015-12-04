# authorship

git filter-branch -f --env-filter "GIT_AUTHOR_NAME='Mack Siu'; GIT_AUTHOR_EMAIL='msiu23@gmail.com'; GIT_COMMITTER_NAME='Mack'; GIT_COMMITTER_EMAIL='msiu23@gmail.com';" HEAD
