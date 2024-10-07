# CoS_Characters
Character Files for CoS

## Git Workflow

---

### Initial Setup

Install git if you do not have it (https://git-scm.com/download/)

Decide where you want your character sheet to live w/in your file system

Open up a terminal (cmd+Space then search terminal)

```
cd <where you want your character sheet folder to live>
```

```
git clone https://github.com/zeke-long/CoS_Characters.git
```

---

### Start of a Session

Open a terminal (cmd+Space then search for terminal)

```
cd <path to your character sheet's folder>
```

```
git pull
```

VV **MOST IMPORTANT STEP** VV
```
git checkout -b <Your Name> 
```

---
### During a Session

Just make changes as you would normally

---

### End of a Session (If You Have Updates)
```
git add .
```

```
git commit -m "<Some Message About Updates>"
```

```
git push
```
(This may have something that pops up and says like "You need to do this instead" - do that instead)

---

### If you want to make my life easier

1. Go to https://github.com/zeke-long/CoS_Characters
2. At the top where it says "Do you want to make a pull request?" - click yes
3. Fill out the request - don't merge

