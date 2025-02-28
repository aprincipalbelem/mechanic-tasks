# Demonstration: Fetch an external configuration file

Tags: Demonstration, External API

This task script demonstrates using the "http" action to retrieve external data, using a GET request. It also demonstrates saving the retrieved data to the Mechanic cache, where it can be used for future task runs.

* View in the task library: [tasks.mechanic.dev/demonstration-fetch-an-external-configuration-file](https://tasks.mechanic.dev/demonstration-fetch-an-external-configuration-file)
* Task JSON, for direct import: [task.json](../../tasks/demonstration-fetch-an-external-configuration-file.json)
* Preview task code: [script.liquid](./script.liquid)

## Default options

```json
{
  "save_data_to_cache__boolean": null
}
```

[Learn about task options in Mechanic](https://learn.mechanic.dev/core/tasks/options)

## Subscriptions

```liquid
mechanic/user/trigger
mechanic/actions/perform
```

[Learn about event subscriptions in Mechanic](https://learn.mechanic.dev/core/tasks/subscriptions)

## Documentation

This task script demonstrates using the "http" action to retrieve external data, using a GET request. It also demonstrates saving the retrieved data to the Mechanic cache, where it can be used for future task runs.

Learn more about this technique: [Can I load data from external sources?](https://docs.usemechanic.com/article/460-can-i-load-data-from-external-sources)

## Installing this task

Find this task [in the library at tasks.mechanic.dev](https://tasks.mechanic.dev/demonstration-fetch-an-external-configuration-file), and use the "Try this task" button. Or, import [this task's JSON export](../../tasks/demonstration-fetch-an-external-configuration-file.json) – see [Importing and exporting tasks](https://learn.mechanic.dev/core/tasks/import-and-export) to learn how imports work.

## Contributions

Found a bug? Got an improvement to add? Start here: [../../CONTRIBUTING.md](../../CONTRIBUTING.md).

## Task requests

Submit your [task requests](https://mechanic.canny.io/task-requests) for consideration by the Mechanic community, and they may be chosen for development and inclusion in the [task library](https://tasks.mechanic.dev/)!
