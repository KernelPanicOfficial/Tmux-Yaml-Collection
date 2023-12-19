# Tmux Yaml Collection

Custom yaml files collection for tmux.

## Table of Contents

- [Tmux Yaml Collection](#tmux-yaml-collection)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
  - [Scripts Table](#scripts-table)
  - [Usage](#usage)
 
## Installation

In order to use the yaml files with tmux, you should install tmuxp:

```
sudo apt install tmuxp -y
```

## Scripts Table

The following table illustrates my custom yaml files used during various engagements:

| Yaml file | Description |
| ---- | ----------- |
| [pentest.yml](/Files/pentest.yml) |  Penetration Test yaml file.  |
| [redteam.yml](Files/redteam.yml)  | Red Team yaml file. |


## Usage

In order to load yaml in tmuxp use the following:

```
tmuxp <yaml_filename>.yml
```

Example:

```
tmuxp pentest.yml
```

