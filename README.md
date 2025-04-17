# 🙋 About me
```nix
let
  inherit (builtins) concatStringsSep;
  me = {
    name = "Abdel B.";
    job = "student";
    hobbies = [
      "networks"
      "systems"
      "devops"
      "programming"
    ];
  };
in
  ''
    Hi ! ${me.name}, I love ${concatStringsSep "," me.hobbies} !
    I'm a ${me.job} @ ENI, studying to become a "DevSecOps" engineer.
  ''
```

## 🔁 My Skills

<details open>
  <summary><b>📦 DevOps</b></summary>
  <br>

[![DevOps](https://go-skill-icons.vercel.app/api/icons?i=bash,powershell,docker,nix,githubactions,vagrant,terraform)](https://skillicons.dev)
</details>

<details open>
  <summary><b>🔧 Tools</b></summary>
  <br>

[![Software and Tools](https://go-skill-icons.vercel.app/api/icons?i=linux,wireshark,neovim,tmux,git,github,gitlab)](https://skillicons.dev)
</details>

<details open>
  <summary><b>🧠 Programming</b></summary>
  <br>

[![Programming languages](https://go-skill-icons.vercel.app/api/icons?i=rust,haskell,python,c)](https://skillicons.dev)
</details>

<details open>
  <summary><b>🎨 Markup and style</b></summary>
  <br>

[![Markup and style languages](https://go-skill-icons.vercel.app/api/icons?i=html,css,sass,markdown,yaml,regex)](https://skillicons.dev)
</details>
