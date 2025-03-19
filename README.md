﻿# Godot v4+

## Install

``` shell
git clone https://github.com/VulpesDust/godot-dir-template.git
```

## Windows PowerShell
``` shell
$newName = Read-Host "Enter your project name"
$newName = 'config/name="' + $newName + '"'
(Get-Content project.godot) -replace 'config/name="Template"', $newName | Set-Content project.godot
```

### p.s. if you want to add something call me

## Author
- **Nickname**: VulpesDust
- **Name**: George Noise
- **Email**: george.noise.dev+github@gmail.com
- **Alternate Email**: vulpesdust+github@gmail.com
- **GitHub**: [VulpesDust](https://github.com/VulpesDust)
