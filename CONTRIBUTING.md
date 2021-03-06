<img src=".github/images/peak.gif" width="100" height="100" />

# Contributing to Peak's Terraform Modules

Despite being primarily maintained by Peak, we welcome pull requests to this repo! We thank you for your time and efforts in making these modules better 🙌🏻

## Consider raising an issue first if your proposed PR:

* introduces breaking changes
* changes a major version of a key dependency

## Process/Things to consider

* `Fork` this repo, make a branch with your changes and then make a PR to `Peak`

* Follow best pacticies for Terraform modules like
    - Folder Structure ( distribute code in `variables.tf`, `main.tf` and `outputs.tf`)
    - Name each resource as `default` for consistency of this repo (this makes outputs consistent).
    - Do not hardcode values and keep them configurable
    - Mention minimum required provider version
    - Provide default values when possible
    - Make sure code all actions pass. Beast to run `terraform fmt -recursive` before commiting
    - Update List in base [README](README.md) when adding or removing a module

## Raising a pull request

When you open a PR, the description will be prepopulated with our template. Please read the notes and add the requested details; **failure to do so will result in your PR being rejected**.
