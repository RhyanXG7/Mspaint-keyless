# mspaint
A decent script hub that is free and open source 🥶
> dito isso, Keyless ;D

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/RhyanXG7/Mspaint-keyless/refs/heads/BetterStar/main.lua"))()
```

**Links**:
- [🌐 Website]()
- [💬 Discord](https://dsc.gg/betterstar)

# Addons
Você pode encontrar documentação sobre como criar um complemento aqui: https://docs.upio.dev/mspaint/addons/getting_started


> [!IMPORTANT]
> Este script agora usa o [wax bundler](https://github.com/latte-soft/wax) to organize code

## Bundling mspaint via wax
Para agrupar todos os scripts, você precisa seguir estes passos:Para agrupar todos os scripts, você precisa seguir estes passos:

1. Install [rokit](https://github.com/rojo-rbx/rokit) if you haven't already
2. Open Powershell or the command-line shell of your liking and [cd to this repository](https://www.quora.com/What-does-it-mean-to-CD-into-a-directory-and-how-can-I-do-that-Can-someone-explain-it-in-a-laymans-term)
3. Run `rokit install` and wait for it to install all the dependencies
4. Run `lune run Build bundle input='default.project.json' minify=false output='Distribution/Script.luau' env-name="Script" darklua-config-path="Build/DarkLua.json" temp-dir-base="Distribution" verbose=true`

You can find the bundled script in `/Distribution/Script.luau`.
