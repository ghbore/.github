## Starter Workflow
### Repo clone stats memorizer
Store Clone Statistics in a Gist for a Repository. It draws inspiration from [MShawon/github-clone-count-badge](https://github.com/MShawon/github-clone-count-badge). Before implementing this workflow, ensure you,

- Generate a Secret token encompassing **repo** and **gist** scopes, and then store it within a secret variable named **_TOKEN_**
- Create an environment labeled as **_monitor_**
- Establish an initial JSON gist and retain its ID within the **_GIST_** variable, housed under the **_monitor_** environment
