> If you're using Dokku - especially for commercial purposes - consider donating to project development via [OpenCollective](https://opencollective.com/dokku) or [Patreon](https://www.patreon.com/dokku). Funds go to general development, support, and infrastructure costs.
>
> If you need help figuring out how to use a specific buildpack, or are having issues using multiple buildpacks, please see our [irc or slack channels](http://dokku.viewdocs.io/dokku/getting-started/where-to-get-help/#the-irc-and-slack-channels). Issues pertaining to buildpacks may be closed and locked.

## Description of problem

### How reproducible

### Steps to Reproduce

1.
2.
3.

#### Actual Results

#### Expected Results

## Environment Information

### `dokku report APP_NAME` output

> This is required! Issues missing this information may be closed.
>
> For problems affecting all applications, the report output for a broken application is useful for our debugging.
> You may also run `dokku report` without any arguments to display the top-level reporting information.

### How (deb/make/rpm) and where (AWS, VirtualBox, physical, etc.) was Dokku installed?:

### Additional information

- Container Inspect Output (if applicable):
  - 0.13.0+: `dokku inspect APP_NAME`
  - <0.13.0: `docker inspect CONTAINER_ID`: WARNING, `docker inspect` will print environment variables for some commands, be sure you're not exposing any sensitive information when posting issues. You may replace these values with XXXXXXX.
- `cat /home/dokku/<app>/nginx.conf` (if applicable):
- Link to the exact repository being deployed (if possible/applicable):
- If a deploy is failing or behaving unexpectedly:
  - Application name
  - The type of application being deployed (node, php, python, ruby, etc.)
  - If using buildpacks, which custom buildpacks are in use
  - If using a `Dockerfile`, the contents of that file
  - If it exists, the contents of your `Procfile`.
- Output of failing Dokku commands after running `dokku trace on`
  (BEWARE: `trace on` will print environment variables for some commands, be sure you're not exposing any sensitive information when posting issues. You may replace these values with XXXXXXX):
