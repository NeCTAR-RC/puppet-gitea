# puppet-gitea

[![Build Status][build-shield]][build-status]
[![Puppet Forge][forge-shield]][forge-gitea]
[![Puppet Forge - downloads][forge-shield-dl]][forge-gitea]
[![Puppet Forge - scores][forge-shield-sc]][forge-gitea]

Welcome to the Puppet module for [Gitea][gitea], self-hosted Git is here!

## Table of Contents

1. [Description](#description)
2. [Setup - The basics of getting started with gitea](#setup)
    * [What gitea affects](#what-gitea-affects)
    * [Setup requirements](#setup-requirements)
    * [Beginning with gitea](#beginning-with-gitea)
3. [Usage - Configuration options and additional functionality](#usage)
4. [Reference - An under-the-hood peek at what the module is doing and how](#reference)
5. [Limitations - OS compatibility, etc.](#limitations)
6. [Development - Guide for contributing to the module](#development)

## Description

With this module you can install any Gitea release version using Puppet either
standalone, or behind a proxy of your choice. Configuration is Hiera compatible
and allows for easy upgrades of Gitea.

In addition to installing Gitea, it also takes care for having an unprivileged
user, all dependencies and a service definition to keep Gitea running. All of
these features are _optional_ and enabled by default. You can ditch them if you
have other modules handling these things.

## Setup

### What gitea affects

If it's obvious what your module touches, you can skip this section. For example,
folks can probably figure out that your mysql_instance module affects their MySQL
instances.

If there's more that they should know about, though, this is the place to mention:

* Files, packages, services, or operations that the module will alter, impact,
  or execute.
* Dependencies that your module automatically installs.
* Warnings or other important notices.

### Setup Requirements

`puppet-gitea` does not ask for much, it will be happy if you use a supported
Puppet agent/server.

### Beginning with gitea

The very basic steps needed for a user to get the module up and running. This
can include setup steps, if necessary, or it can be an example of the most basic
use of the module.

## Usage

This section is where you describe how to customize, configure, and do the fancy
stuff with your module here. It's especially helpful if you include usage examples
and code samples for doing things with your module.

## Reference

Users need a complete list of your module's classes, types, defined types
providers, facts, and functions, along with the parameters for each. You can
provide this list either via Puppet Strings code comments or as a complete list
in the README Reference section.

* If you are using Puppet Strings code comments, this Reference section should
  include Strings information so that your users know how to access your
  documentation.

* If you are not using Puppet Strings, include a list of all of your classes,
  defined types, and so on, along with their parameters. Each element in this
  listing should include:

  * The data type, if applicable.
  * A description of what the element does.
  * Valid values, if the data type doesn't make it obvious.
  * Default value, if any.

## Limitations

This is where you list OS compatibility, version compatibility, etc. If there
are Known Issues, you might want to include them under their own heading here.

## Development

Since your module is awesome, other users will want to play with it. Let them
know what the ground rules for contributing are.

[build-status]: https://travis-ci.org/kogitoapp/puppet-gitea
[build-shield]: https://travis-ci.org/kogitoapp/puppet-gitea.png?branch=master
[forge-gitea]: https://forge.puppetlabs.com/kogitoapp/gitea
[forge-shield]: https://img.shields.io/puppetforge/v/kogitoapp/gitea.svg
[forge-shield-dl]: https://img.shields.io/puppetforge/dt/kogitoapp/gitea.svg
[forge-shield-sc]: https://img.shields.io/puppetforge/f/kogitoapp/gitea.svg

[gitea]: https://gitea.io/
