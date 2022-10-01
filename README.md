# GitLab docker

```
docker exec -it gitlab_gitlab_1 gitlab-rake gitlab:backup:restore --trace

docker exec -it gitlab-gitlab-1 grep 'Password:' /etc/gitlab/initial_root_password
```
