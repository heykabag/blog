# HeyKabag Blog

| Status | Badge |
| --- | --- |
| Prod Deployment | [![Netlify Status](https://api.netlify.com/api/v1/badges/d0a5e923-acc1-4b8e-b199-80d1dcd78504/deploy-status)](https://app.netlify.com/sites/heykabag/deploys) |


[![Open in Dev Containers](https://img.shields.io/static/v1?label=Dev%20Containers&message=Open&color=blue&logo=visualstudiocode)](https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/heykabag/blog)

## FAQ

How to add your content:

See this: https://gohugo.io/content-management/organization/


### First time setup

To run it locally:

1. Install [Direnv](https://direnv.net/docs/installation.html)
2. Install [Devbox](https://www.jetpack.io/devbox/docs/quickstart/)
3. Either execute `devbox shell` or `direnv allow`
4. Run `make first-time-setup`

To run local webserver, run `make serve` or `yarn serve` or `npm run serve`

To run it as devcontainer, from inside vscode just use Cmd/Ctrl + Shift + P > Reopen in container.