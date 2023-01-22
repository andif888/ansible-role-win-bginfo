# ansible-role-win-bginfo

Role install BGInfo

## Table of content

- [Default Variables](#default-variables)
  - [bginfo_download_url](#bginfo_download_url)
  - [bginfo_install_dir](#bginfo_install_dir)
  - [bginfo_startmenu_autostart](#bginfo_startmenu_autostart)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Default Variables

### bginfo_download_url

Download URL

#### Default value

```YAML
bginfo_download_url: https://download.sysinternals.com/files/BGInfo.zip
```

### bginfo_install_dir

Installation directory

#### Default value

```YAML
bginfo_install_dir: '%SystemDrive%\BGInfo'
```

### bginfo_startmenu_autostart

Add BGInfo into startmenu autostart

#### Default value

```YAML
bginfo_startmenu_autostart: true
```



## Dependencies

None.

## License

license (GPLv2, CC-BY, etc)

## Author

andif888
