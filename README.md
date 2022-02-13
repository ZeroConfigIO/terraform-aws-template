# AWS Terraform module template

---

[![CI](https://github.com/ZeroConfigIO/terraform-aws-template/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/ZeroConfigIO/terraform-aws-template/actions/workflows/ci.yml)
[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-success?logo=pre-commit&logoColor=white)](https://github.com/pre-commit/pre-commit)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## Description

Terraform module which sets up < something > ...

<!--- BEGIN_TF_DOCS --->

## Requirements

| Name                                                                     | Version  |
| ------------------------------------------------------------------------ | -------- |
| <a name="requirement_terraform"></a> [terraform](#requirement_terraform) | >= 1.0.0 |
| <a name="requirement_aws"></a> [aws](#requirement_aws)                   | >= 4.0   |

## Providers

| Name                                             | Version |
| ------------------------------------------------ | ------- |
| <a name="provider_aws"></a> [aws](#provider_aws) | >= 4.0  |

## Modules

No modules.

## Resources

No resources.

## Inputs

No inputs.

## Outputs

No outputs.

<!--- END_TF_DOCS --->

## Usage

```
module "template" {
  source = "git::https://github.com/zeroconfigio/terraform-aws-template.git?ref=v1.0.0""
}
```

## Contributing

See [CONTRIBUTING](CONTRIBUTING) for full details.

### Configuring the Environment

Before you can run hooks, you need to have the [pre-commit](https://pre-commit.com/) package manager installed.

Using pip:

```
pip install pre-commit
```

In a python project, add the following to your requirements.txt (or requirements-dev.txt):

```
pre-commit
```

Using homebrew:

```
brew install pre-commit
```

### Install the git hook scripts

Run pre-commit install to set up the git hook scripts

```
$ pre-commit install
pre-commit installed at .git/hooks/pre-commit
```

now `pre-commit` will run automatically on `git commit`!

### (optional) Manually run against all the files

it's usually a good idea to run the hooks against all of the files when adding new hooks (usually pre-commit will only run on the changed files during git hooks)

```
$ pre-commit run -a
```

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

See [LICENSE](LICENSE) for full details.

## Author

This project is maintained and funded by [ZeroConfig.io](https://zeroconfig.io) and [igor.js](https://github.com/igorjs)
