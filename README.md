# metaswarm-marketplace

Claude Code marketplace for the [metaswarm](https://github.com/dsifry/metaswarm) plugin.

## Install

```bash
claude plugin marketplace add dsifry/metaswarm-marketplace
claude plugin install metaswarm@metaswarm-marketplace
```

To update an existing install (auto-update is off by default for third-party marketplaces):

```bash
claude plugin marketplace update metaswarm-marketplace
claude plugin update metaswarm@metaswarm-marketplace
```

Then open Claude Code in your project and run `/metaswarm:setup`.

Or just tell Claude:

```text
> Read through https://github.com/dsifry/metaswarm and install it for my project.
```
