[![](https://visitcount.itsvg.in/api?id=johnstclair&label=Visitors&color=11&icon=5&pretty=true)](https://visitcount.itsvg.in)

# Yahaha, you found me!

## About Me

```nix
{ config, ... }: {
  let
    profile = {
      username = "johnstclair";
      name = "John St. Clair";
      collaborative = true;
      student = true;
      organizations = none;
      learning = [
        nix # i will always be learning this
        react-native
      ];
    };
  in
  {
    users.users.${profile.username} = {
      isNormalUser = true;
      description = ${profile.name};
      organizations = ${profile.organizations};
    };
    programs.collaborative.enable = ${profile.collaborative};
    programs.student.enable = ${profile.student};
  }
}
```

## Skills

### Languages

<details open>
<summary><b>Programming Languages</b></summary>
<br>

[![Programming Languages](https://skillicons.dev/icons?i=c,cs,js,typescript,python)](https://skillicons.dev)
</details>

<details open>
<summary><b>Markup and Style Languages</b></summary>
<br>

[![Markup and Style Languages](https://skillicons.dev/icons?i=html,css,markdown)](https://skillicons.dev)
</details>

<details open>
<summary><b>Spoken Languages</b></summary>
&emsp;None Yet
</details>


### Tools

<details open>
  <summary><b>Operating System</b></summary>
  <br>

[![Operating Systems](https://skillicons.dev/icons?i=linux,nix)](https://skillicons.dev)
</details>

<details open>
  <summary><b>Frameworks and Databases</b></summary>
  <br>

[![Frameworks and Databases](https://skillicons.dev/icons?i=react,express,mongodb)](https://skillicons.dev)
</details>

<details open>
  <summary><b>Applications, CLI's and Technologies</b></summary>
  <br>

[![Applications, CLI's and Technologies](https://skillicons.dev/icons?i=git,github,godot,neovim,arduino,vite)](https://skillicons.dev)
</details>



## Stats (dont look)

<details>
  <summary><b>General</b></summary>
  <br>
  
<img height="180em" src="https://denvercoder1-github-readme-stats.vercel.app/api/?username=johnstclair&show_icons=true&include_all_commits=true&count_private=true&theme=react&hide_border=true&bg_color=0d1117&title_color=A594FD&icon_color=A594FD"/>
<img height="180em" src="https://denvercoder1-github-readme-stats.vercel.app/api/top-langs/?username=johnstclair&langs_count=8&layout=compact&theme=react&hide_border=true&bg_color=0d1117&title_color=A594FD&icon_color=A594FD"/>

</details>

<details>
  <summary><b>Streak</b></summary>
  <br>

[![GitHub Streak](https://streak-stats.demolab.com?user=johnstclair&theme=transparent&date_format=%5BY%20%5DM%20j)](https://git.io/streak-stats)
</details>
