![](https://cdn.discordapp.com/attachments/1028835888475680848/1050416732944224346/image.png)
-
#### The **only** [surviv.io](https://surviv.io/) librery written for Python.
>##### Library written by [**PhysxDev#9448**](https://discord.gg/Du3PeShf)
>##### Contributor: [**AzartX47#6188**](https://discord.gg/Du3PeShf)

## ● **Features**
### *Download*
```python
pip install survivpy
```
### *Import*
```python
from surviv import surviv
```

### *Latest Update News*
```python
data = surviv.getNews()
print(data)
```

### *Pass Information*
```python
data = surviv.getPass()
print(data)
```

### *Create Team*
```python
data = surviv.teams.create()
print(data)
```

### *Get Team Information*
```python
data = surviv.teams.getInfo("Team Code")
print(data)
```

### *Create Prestige*
```python
data = surviv.prestige.create()
print(data)
```

### *Get Prestige Information*
```python
data = surviv.prestige.getInfo()
print(data)
```

### *Battle Modes*
```python
data = surviv.battleModes()
print(data)
```

### *Site Information*
```python
data = surviv.siteInfo()
print(data)
```

### *Region Information*
```python
data = surviv.regionInfo()
print(data)
```

### *Streaming Surviv.io (Twitch)*
```python
data = surviv.streamingSurviv()
print(data)
```

### *Featured Youtuber*
```python
data = surviv.featuredYoutuber()
print(data)
```

### *Find Match*
```python
data = surviv.findMatch()
print(data)
```

### *Proxies*
```python
data = surviv.proxies()
print(data)
```

### *Leaderboard Information*
```python
data = surviv.leaderboard()
print(data)
```

### *Clan Information*
```python
data = surviv.clanStats("ClanID")
print(data)
```

### *Clan Recent Matches*
```python
data = surviv.clanMatches("ClanID")
print(data)
```

### *Clan Leaderboard Information*
```python
data = surviv.clanLeaderboard()
print(data)
```

### *User Information*
```python
data = surviv.user("username")
print(data)
```

## ● **Extras**
### *Binary Feature*
```python
from surviv import binary

encoded = binary.encode("Hello, World.") # Returns binary into List Format.
binary.decode(encoded) # Returns decoded binary into a string.

rawBinary = binary.toRaw(encoded) # Converts list into String.
binary.unRaw(rawBinary) # Converts string binary into List Format.
```

# [Join our Discord!](https://discord.gg/Du3PeShf)
