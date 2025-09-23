## Hi, I'm Ivanoe !

```nix
{ lib, ... }: {
    ivanoe = {
        description = "Software Developper";
        pronouns = [ "he" "him" ];
        age = 22;

        languages = with lib.languages; [
            nix
            java
            C
            CSharp
            GDScript
            php
            MIPS32
        ];
        
        tools = with lib.tools; [
            docker
        ];

        interests = [
            "FOSS" "Linux" "Self-Hosting" "Tech" 
            "Reading" "Cinema" "Rock Climbing"
        ];

        # other
        projects.nixpkgs.maintainer = true;

        lets-go-attitude.enable = true;

        softwares = [
            nvim
            kitty
            hyprland niri
            nix
        ];

        quote = "I use nixos btw";
    };
}
```
