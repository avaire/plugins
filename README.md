AvaIre Plugins
==============

This is the source list of public plugins that are officially recognized by Ava, plugins on the list can be searched for, looked up, and installed through the `;plugin` system command.

## Acceptance criteria

At this time, we are accepting plugins which meet the following criteria:

1. Your plugin must **not** break any of Discords Terms of Service, or Privacy Policy.
2. Your plugin must **not** cache or save any sensitive data from the main configuration file, this includes:
    
    * The bot token.
    * The database hostname, username, or password.
    * The lavalink hostname or password.
    * The Sentry DSN url.
    * The auth token used for vote locking.
    * Any of the API keys.

## Adding your project

1.  Fork the repo.
3.  Add your project to [`plugins.json`](https://github.com/avaire/plugins/blob/master/plugins.json), like so:

```json
{
    "name": "Your project name",
    "description": "A description of the project",
    "author": "Your name",
    "authors": [
        "Your name",
        "Your contributors"
    ],
    "repository": "username/repo-name",
    "source": "github"
}
```

4.  Submit a PR with your change, and if all is well, we'll merge it and display it in Avas `;plugins` command.

Officially recognized plugins may also show up on the website at some point.
