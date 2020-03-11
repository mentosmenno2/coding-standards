[![GitHub Actions status](https://github.com/mentosmenno2/coding-standards/workflows/Build%20%26%20test/badge.svg)](https://github.com/mentosmenno2/coding-standards/actions)

# Mentosmenno2 Coding Standards

Coding standards for multiple project types.

## Installation

Add the repo to the project by adding this in the `composer.json` file.

```json
"repositories": [
    {
        "url": "https://github.com/mentosmenno2/coding-standards.git",
        "type": "git"
    }
],
```

Install this dependency with composer.

`composer require mentosmenno2/coding-standards --dev`

## Configuration

Open your phpcs configuration file (`phpcs.xml.dist`) and add the ruleset you want there.

There are multiple rulesets available for multiple type of projects.

```xml
<rule ref="Mentosmenno2-Laravel"/>
<rule ref="Mentosmenno2-WordPress"/>
```
