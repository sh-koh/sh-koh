# 🙋 About me
```nix
let
  lib = import <nixpkgs/lib>;
  me = {
    name = "Abdel B.";
    job = "student";
    hobbies = [
      "networks"
      "systems"
      "devops"
      "programming"
      "gaming"
    ];
  };
in
  with lib;
  ''
    Hi ! ${me.name}, I love ${strings.concatStringsSep "," me.hobbies} !
    I'm a ${me.job} at ENI to become a "DevSecOps" engineer.
  ''
```

## 🔁 My Skills 

<details open>
  <summary><b>📦 DevOps</b></summary>
  <br>

[![DevOps Tools](https://skillicons.dev/icons?i=bash,powershell,docker,nix,githubactions)](https://skillicons.dev)
</details>

<details open>
  <summary><b>🔧 Tools</b></summary>
  <br>

[![Software and Tools](https://skillicons.dev/icons?i=linux,neovim,git,github,gitlab)](https://skillicons.dev)
</details>

<details open>
  <summary><b>🧠 Programming</b></summary>
  <br>

[![Programming languages](https://skillicons.dev/icons?i=python,go,js,haskell,zig)](https://skillicons.dev)
</details>

<details open>
  <summary><b>🎨 Markup and style</b></summary>
  <br>

[![Markup and style languages](https://skillicons.dev/icons?i=html,css,sass,markdown,regex)](https://skillicons.dev)
</details>
