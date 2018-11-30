---
title: Dovetail CLI
weight: 2030
pre: "<i class=\"fas fa-terminal\" aria-hidden=\"true\"></i> "
---
### Introduction
The dovetail cli is a tool to mainly generate smart contracts for a given model built using ui tool [Dovetail Studio](../getting-started-webui), so we recommend you to learn how to do that first.

### Before you get started
Before you can get started with the cli tools you need to make sure you have the [Go programming language](https://golang.org/doc/install) and [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) installed. Go v1.11.x is required.

{{% notice info %}}
Don't forget to set your `GOPATH` variable and make sure that `$GOPATH/bin` is part of your path. (see [here](https://golang.org/doc/code.html#GOPATH) or [here](https://github.com/golang/go/wiki/SettingGOPATH) for more details)
{{% /notice %}}

### Installing the cli tools

Copy and paste the following commands to install Project Dovetail™ commandline tool.

```
curl -sSL https://github.com/TIBCOSoftware/dovetail-cli/releases/download/v0.1.2/dovetail-cli-install.sh > install.sh && source install.sh && rm install.sh
```

**The binary dovetail will be in the dovetail-cli/bin directory, please prepend the /path/to/dovetail-cli to your GOPATH environment variable, and prepend /path/to/dovetail-cli/bin to your PATH environment variable in your user profile**
