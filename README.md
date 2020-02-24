
# Overview

This is a system wide set of Protobuf files, which should be used in:
- mobile device;
- routing application;
- business logic services;
- web dashboard.

It's highly recommend to attach the repository as a [Git submodule](https://git-scm.com/book/en/v2/Git-Tools-Submodules).

## The commands snippets

- **add this repository as a submodule to a project:**

```bash
$> git submodule add git@github.com:binary-routing/proto-files.git src/main/proto
...
```

Where `src/main/proto` is a destination folder from a project's root folder.

- **clone a project with a submodule:**

```bash
$> git clone --recursive <git@github.com:PATH>
```

- **update all the submodules:**

```bash
$> git submodule update --remote
```
