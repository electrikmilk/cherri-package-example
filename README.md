# 📦 Cherri Package Example

In a future release of the [Cherri programming language](https://cherrilang.org/), you'll be able to install GitHub repos as dependencies that use this package structure and repo naming convention **cherri-{package_name}**.

You can host Cherri packages anywhere you can host a Git repository with the same URL convention.

[Learn more](https://cherrilang.org/language/package-manager)

This package can be installed using:

```bash
cherri --install=@{github_username}/{package_name}
```

This package can be removed using:

```bash
cherri --remove=@{github_username}/{package_name}
```
