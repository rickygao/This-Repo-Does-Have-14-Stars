# This-Repo-Does-Have-X-Stars

The SIMPLEST-EVER "This-Repo-Has-X-Stars" implemented via [GitHub Actions](https://docs.github.com/actions/learn-github-actions). The original idea comes from [this repo](https://github.com/RealPeha/This-Repo-Has-0-Stars).

## Usage

1. Fork this repo;
2. Generate a [personal access tokens](https://github.com/settings/tokens) with "repo_public" scope, and copy it;
3. Set the token as a secret named "ADMIN_TOKEN" in the "Settings -> Secret" tab of your forked repo;
4. Star your own repo, check "StarWatcher" workflow runs, and refresh the repo page in a minute.

## Security

Don't worry about your token being used for malicious purposes. `.github/workflows/star_watcher.yml` describes how your generated token is used and it is only be used to [update a repository](https://docs.github.com/en/rest/reference/repos#update-a-repository).

## Awesome

There are several awesome implementations via different approaches. Try them! :heart:

- Polling (original): [This-Repo-Has-X-Stars](https://github.com/RealPeha/This-Repo-Has-0-Stars);
- WebHooks (AWS Lambda): [This-Repo-Has-X-Stars](https://github.com/iBug/This-Repo-Has-0-Stars);
- GitHub Actions (nodejs): [This-repo-has-x-stars-y-forks-action](https://github.com/ouuan/This-repo-has-x-stars-y-forks-action);
- GitHub Actions (curl, ours): [This-Repo-Has-X-Stars](https://github.com/RealPeha/This-Repo-Has-0-Stars).
