# auto-commit

🌳 Making green your Github stats, powered by [Github Actions](https://github.com/features/actions)

[![Auto commit](https://github.com/mazipan/auto-commit/workflows/Auto%20commit/badge.svg)](https://github.com/mazipan/auto-commit/actions?query=workflow%3A%22Auto+commit%22)

## Make it your own

- Fork this repo
- Activate your Github Actions, go to tab **Actions**, and enable it if you see this below image.

![Enable github actions](screenshoot-actions.png)

- Change the `email` and `name` information on file [autocommit.yml, line 29 and 30](https://github.com/mazipan/auto-commit/blob/master/.github/workflows/autocommit.yml#L29)
- Change the scheduling time on file [autocommit.yml, line 10](https://github.com/mazipan/auto-commit/blob/master/.github/workflows/autocommit.yml#L10). You can use [crontab.guru](https://crontab.guru/) if you are not familiar with the cron schedule string. For the starter you can try to run it in every hour with string `1 * * * *` .

## Credits

- [Github Actions](https://github.com/features/actions)
- [ad-m/github-push-action](https://github.com/ad-m/github-push-action)


