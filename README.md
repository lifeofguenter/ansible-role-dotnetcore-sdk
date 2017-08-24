[![Build Status](https://travis-ci.org/lifeofguenter/ansible-role-dotnetcore-sdk.svg?branch=master)](https://travis-ci.org/lifeofguenter/ansible-role-dotnetcore-sdk)

# Ansible Role for .NET Core (SDK)

This ansible role will install .NET Core (SDK)

## Requirements

_None_

## Role Variables

```
dotnet_version: 2.0.0
dotnet_download_url: https://download.microsoft.com/download/1/B/4/1B4DE605-8378-47A5-B01B-2C79D6C55519/dotnet-sdk-2.0.0-linux-x64.tar.gz
```

## Dependencies

_None_

## Example Playbook

```
- hosts: dotnet
  roles:
    - { role: lifeofguenter.dotnet-sdk }
```

## License

MIT

## Author Information

Gunter Grodotzki <gunter@grodotzki.co.za>
