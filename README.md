# Cherri Package Example

In a future release of the [Cherri programming language](https://cherrilang.org/), you'll be able to install GitHub repos using this package structure.

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
