[![](https://visitcount.itsvg.in/api?id=johnstclair&label=Visitors&color=11&icon=5&pretty=true)](https://visitcount.itsvg.in)

# Yahaha! You found me!

```nix
{ config, ... }: {
  let
    profile = {
      username = "johnstclair";
      name = "John St. Clair";
      collaborative = true;
      student = true;
      organizations = [ "stlrapp" ];
      learning = [
        nix # i will always be learning nix
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
