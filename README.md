# **.gitignore** boilerplate

The inspirational .gitignore boilerplate

[![license](https://img.shields.io/badge/License-MIT-blue.svg?style=flat)](LICENSE)

Files and directories that Git should ignore (for a general web project)

Download [.gitignore](.gitignore)

```
## .gitignore boilerplate v1.2.0 (2025-02-28) sandromiguel@sandromiguel.com

## Editor directory
**/.vscode

## Ignore Node.js and Composer dependencies
**/node_modules
**/vendor

## Ignore logs and debug files
**/logs
**/log
yarn-error.log*
npm-debug.log*
*.log

## PHPUnit result cache
.phpunit.result.cache

## Ignore generated files
*.map
*.bak

## Ignore environment file (secrets inside)
.env

## Ignore NPM configuration file
.npmrc

## Yarn - Not using Zero-Installs
.pnp.*
.yarn/*
!.yarn/patches
!.yarn/plugins
!.yarn/releases
!.yarn/sdks
!.yarn/versions

## Ignore storage and miscellaneous files
**/storage
**/.misc
```

## Tips

Here are some tips and tricks for working with `.gitignore` files:

### Negating Rules with `!`

In a `.gitignore` file, you can use the `!` symbol to negate a rule. This means that a file or directory matching the negated rule will be included, even if it matches a previous rule. For example:

```
# Ignore all .txt files
*.txt

# Except for specific.txt
!specific.txt
```

### Recursive Directory Matching with `**/`

You can use `**/` to match directories recursively. For example:

```
# Ignore all .log files in any directory
**/*.log
```

### Ignoring Entire Directories

To ignore an entire directory and its contents, use a trailing `/` like this:

```
# Ignore the entire "logs" directory
logs/
```

### Using Wildcards `*`

The `*` wildcard can be used to match zero or more characters. For example:

```
# Ignore all .bak files
*.bak
```

## Contributing

Want to contribute? All contributions are welcome. Read the [contributing guide](CONTRIBUTING.md).

## Questions

If you have questions tweet me at [@sandro_m_m](https://twitter.com/sandro_m_m) or [open an issue](../../issues/new).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

**~ sharing is caring ~**
