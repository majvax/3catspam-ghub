
<div align="center">
    <img src="https://github.com/majvax/3catspam-ghub/assets/77504686/224bb1e8-9d7d-4f95-913a-946b3d66b198" style="border-radius: 50%; width: 300px; height: 300px" alt="logo">
    <H3>3 cat spam script</H3>
    <p> 
        <a href="https://github.com/majvax/3catspam-ghub/stargazers"><img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/majvax/3catspam-ghub?style=for-the-badge&labelColor=363a4f&color=b7bdf8"></a>
        <a href="https://github.com/majvax/3catspam-ghub/issues"><img alt="GitHub issues" src="https://img.shields.io/github/issues/majvax/3catspam-ghub?style=for-the-badge&labelColor=363a4f&color=f5a97f"></a>
        <a href="https://github.com/majvax/3catspam-ghub/contributors"><img src="https://img.shields.io/github/contributors/majvax/3catspam-ghub?colorA=363a4f&colorB=a6da95&style=for-the-badge"></a>
    </p>    
</div>

> [!CAUTION]
> Don't use it against other people, it is for educational purposes only
<hr>


<div align="center" id="preview" >
    <H3>Preview 📸</H3>
</div>

https://github.com/majvax/3catspam-ghub/assets/77504686/bb5bc130-cffa-4fe9-99d8-b85273225f34
<hr>
<div align="center" id="usage">
    <H3>Usage 📕</H3>
</div>

##### Just make a new script in logitech and wrote this code inside the editor (change the path)
```lua
data =  dofile[[C:\path_to_the_folder\script.lua]]
```

##### You only need an extra configuration (this one is for the loadout shown in the video)
```lua
settings = {
  cat_spam_key = 5,
  ultimatum_save = 4,
  weapon = {
      heavy    = {key = 0x07, delay = 400},
      sniper   = {key = 0x06, delay = 450},
      special  = {key = 0x05, delay = 450},
      melee    = {key = 0x04, delay = 400},
      backup   = {key = 0x03, delay = 450},
      primary  = {key = 0x02, delay = 400}
  },
  order = {
      "sniper",
      "special",
      "backup",
      "melee"
  }
}
```
##### `cat_spam_key` is the key you need to hold to cat spam
##### `ultimatum_save` can be use with any shotgun as show in the preview, it just stop cat spam and use shotgun
##### `weapon` contain the configuration for each weapon where
##### => `key` is the key the script has to emulate the take this weapon in hand
##### => `delay` is the delay after taking the weapon in hand and shooting
##### `order` order of the cat spam
> [!NOTE]
> You should be ok using `450` in delay for every weapon, for every cat spam loadout.
> Just change the order, maybe replacing melee by heavy if you own a good one

> [!NOTE]
> scripting api documentation can be found [here](https://douile.com/logitech-toggle-keys/APIDocs.pdf), page 42-44 for keycode




