**English** | [中文](readme-zh_cn.md)

\>\>\> [Back to index](/readme.md)

## mirror_control

### Basic Information

- Plugin ID: `mirror_control`
- Plugin Name: Mirror Control
- Version: 1.0.0
  - Metadata version: 1.0.1
  - Release version: 1.0.0
- Total downloads: 0
- Authors: [Chara_SS](https://github.com/charassss/)
- Repository: https://github.com/charassss/Mirror-Control
- Labels: [`Management`](/labels/management/readme.md)
- Description: A plugin to control mirror server

### Dependencies

| Plugin ID | Requirement |
| --- | --- |

### Requirements

| Python package | Requirement |
| --- | --- |
| [mcdreforged](https://pypi.org/project/mcdreforged) | ~=2.6.0 |

### Introduction

Mirror Control
-----

####  [中文版本](./README_CN.md)
---

#### Usage

* `!!mirror` Help messages and quick manage
* `!!mirror start <server_name>` Start mirror server (Including sync)
* `!!mirror restart <server_name>` Sync mirror server (Including sync)
* `!!mirror stop <server_name>` Stop mirror server
* `!!mirror sync <server_name>` Sync mirror server

`server_name` just like *default*.

#### Configuration file structure

Please modify the configuration file before you use it *After your first loading

\* means you you need to modify

```
config.json
	|- permission (int 1->4)
	|		|- start
	|		|- sync
	|		|- stop
	|		|- restart
	|
    |- this_server (str dir)
    |    	|- work_directory *
    |
    |- server
    		|- default * (just don't 'default', any other name you want is ok)
    		|		|- name * (anything you want, it is this server's nickname)
    		|		|- location * (absolute dir)
    		|		|- target_region_location * (its region file's dir)
    		|		|- command * (command to start.use 'start.bat' or 'sh start.sh')
    		|		|- rcon
    		|			|- enable * (boolean true)
    		|			|- port * 
    		|			|- passwd *
    		|
    		|- ...
```

### Download

> :warning: Warning: Read the README file in plugin repository before using it.

| File | Version | Upload Time | Size | Downloads | Operations |
| --- | --- | --- | --- | --- | --- |
| [MirrorControl-v1.0.0.mcdr](https://github.com/charassss/Mirror-Control/releases/tag/v1.0.0) | 1.0.0 | 2022/12/06 09:27:33 | 3.86KB | 0 | [Download](https://github.com/charassss/Mirror-Control/releases/download/v1.0.0/MirrorControl-v1.0.0.mcdr) |

