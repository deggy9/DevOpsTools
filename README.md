# DevOpsTools

## Cloudformation 2 Terraform
[cf2tf](https://github.com/DontShaveTheYak/cf2tf) is a CLI tool that attempts to convert Cloudformation to Terraform. We say attempt because it's not really possible to make the conversion with 100% accuracy (currently) because of several reasons mostly around converting a Map value in Cloudformation to [the correct value in HCL](https://github.com/hashicorp/hcl/issues/294#issuecomment-446388342).

## terradozer
[terradozer](https://github.com/jckuester/terradozer) takes a Terraform state file as input and destroys all resources it finds in it - without needing any *.tf files. This works currently only for resources of the Terraform AWS Provider. If you need support for any other provider, let me know, and I will try to help.

## Terrakube Platform
[Terrakube Platform](https://github.com/AzBuilder/terrakube) The server defines a rest API based on Yahoo Elide and expose a JSON:API or GraphQL.

## Devbox
[Devbox](https://github.com/jetpack-io/devbox) is a command-line tool that lets you easily create isolated shells and containers. You start by defining the list of packages required by your development environment, and devbox uses that definition to create an isolated environment just for your application.

