## Hi, I'm Ivanoe !

```nix
{ lib, ... }: {
    ivanoe = {
        description = "Software Developper";
        specialisation = "back-end";
        pronouns = [ "he" "him" ];
        age = 23;

        languages = with lib.languages; [
            java
            C
            php
            CSharp
            GDScript
            MIPS32
        ];
        
        tools = with lib.tools; [
            git
            docker
            nix(os)
            java.swing
            php.laravel
        ];

        interests = [
            "Linux" "Self-Hosting" "Rock Climbing" 
            "Reading" "Cinema" "Shows" "Hiking"
        ];

        projects = { 
            nixpkgs.maintainer.enable = true;
        };

        lets-go-attitude.enable = true;

        softwares = [
            neovim
            kitty
            hyprland
            nix

            # others code editor I know and use
            intelliJ
            vscode
            visual-studio
        ];
    };
}
```
