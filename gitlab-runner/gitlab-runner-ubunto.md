1 - install gitlab runner and docker on ypur local server get the download link on : https://docs.gitlab.com/runner/install/linux-manually.html
2 - sudo chmod +x /usr/local/bin/gitlab-runner
3 - sudo useradd --comment 'GitLab Runner' --create-home gitlab-runner --shell /bin/bash
4 - sudo gitlab-runner install --user=gitlab-runner --working-directory=/home/gitlab-runner 
5 - sudo gitlab-runner start
