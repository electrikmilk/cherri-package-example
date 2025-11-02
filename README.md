# Cherri Package Example

In a future release of the [Cherri programming language](https://cherrilang.org/), you'll be able to install GitHub repos as dependencies that use this package structure and repo naming convention **cherri-{package_name}**.

The file at `main.cherri` is the entry point of the package, as it is the file that will be included.

A private package will be able to install this package using:

```bash
cherri --install=electrikmilk/package-example
```

Packages are initialized using:

```bash
cherri --init={github_username}/{package_name}
```

Packages can be removed using:

```bash
cherri --remove={github_username}/{package_name}
```
