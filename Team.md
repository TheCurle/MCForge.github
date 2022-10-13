## Team breakdown
```
- AbrarSyed         (Perms: Write to Documentation)
- Actuarius         (Perms: Write to 21 Repos)
- agaricusb !       (Perms: None)
- amadornes         (Perms: None)
- asherslab         (Perms: Triage)
- AterAnimAvis      (Perms: Triage)
- bloodmc           (Perms: None)
- boni              (Perms: Write to Documentation)
- bs2609 !          (Perms: None)
- ChampionAsh5357   (Perms: Triage)
- covers1624        (Perms: Write to 21 Repos)
- cpw               (Perms: Owner)
- DaemonUmbra       (Perms: Triage, Write to Private)
- diesieben07       (Perms: Triage)
- dpeter99          (Perms: Triage)
- gigaherz          (Perms: Write to 20 Repos)
- ichttt            (Perms: Triage)
- illyohs           (Perms: Triage, Write to Private, Owner to Scorge)
- tamashenning      (Perms: Write to some Infrastructure)
- JDLogic           (Perms: Write to 15 Repos)
- kashike           (Perms: Triage, Write to Private)
- KingLemming       (Perms: None)
- LatvianModder     (Perms: Write to some Infrastructure)
- LexManos          (Perms: Owner)
- marchermans       (Perms: Write to 15 Repos)
- marvin-roesch !   (Perms: Write to Documentation, Web)
- Matyrobbrt        (Perms: Triage)
- md-5 !            (Perms: None)
- mezz              (Perms: Triage, Write to some Toolchain)
- OvermindDL1 !     (Perms: None)
- pupnewfster       (Perms: Triage, Write to Private)
- RainWarrior       (Perms: Write to 15 Repos)
- ravenbuilder934   (Perms: Triage)
- sciwhiz12         (Perms: Triage, Write to Private, Write to Documentation)
- Shadows-Of-Fire   (Perms: Triage)
- SizableShrimp     (Perms: Write to Toolchain, Backend)
- Tahg              (Perms: None)
- Curle             (Perms: Owner)
- tterrag1098       (Perms: Write to 30 Repos)
- Unbekannt1998     (Perms: Triage)
- Unnoen            (Perms: Triage, Write to Private)

- SmokeySalmon      (Team: RetroGradle)
- zml               (Team: ModLauncher)
- boq               (Team: Contributor / Problem Causer)
- cojo              (Team: Contributor / Problem Causer)
- JoJoModding       (Team: Contributor)
- coehlrich         (Team: Collaborator)
- Direwolf20        (Team: Collaborator)
- Mumfrey           (Team: Collaborator)
- Peterix           (Team: Collaborator)
- ProfMobius        (Team: Collaborator)
- senox13           (Team: Superhelper)
- Shroom Agent      (Team: Superhelper)
```

# Team Stories

## Core Team

### LexManos

Lex's journey with Forge started way back in the pre-alpha days of Minecraft.  
Back when SpaceToad and Eloraam were designing the Forge API for their mods Buildcraft and RedPower, Lex submitted some fixes and cleanups for the code and buildscript.  
This led to eventually Lex joining the duo in developing the API proper, forming a team of three.  
When SpaceToad and Eloraam grew tired of developing Forge, instead preferring to work on their own mods, Lex was left as the sole team member - he was working on Forge itself, without desire or need to work on it for another mod like the other two.  

After creating a new, small team to keep working on Forge and some collaborations with the MCP team, Lex managed to keep Forge going up to now, expanding the API, adding a modloader with the help of some other team members, and growing the team to what it is today.  

His role today is as the project manager, making sure all of the teams work properly, and as one of the core developers, making some of the harder decisions about how certain things are implemented.

### cpw

cpw started in the Bukkit ecosystem - finding that plugins were limited, and disappointed with the fact that mods couldn't be used alongside them. He joined the MCPC team, attempting to join mods and plugins once and for all.

However, when encountering issues with multiplayer, cpw ported Risugami's Mod Loader to work on a server (separately from ModLoaderMP) so that it could be integrated into both Bukkit and Forge. This gathered the attention of the Forge team, who were having issues with RML and saw the potential in the port that cpw made.

Eventually, cpw was recruited to make a client side of his server modloader, forming the FML that was eventually merged into Forge itself.

He also influenced a lot of other systems in the modding world; he consulted with Mumfrey on some of the designs that went into SpongePowered's Mixin, developed what eventually became Mojang's Legacy Launcher, and built the super-speedy Event Bus system that Forge uses.

His role today is as one of the developers of the McModLauncher ecosystem that Forge is built on top of, the Mod Loader that is ultimately of his own design, and is one of the core maintainers keeping Forge running.



## Triage Team

### AshersLab

Ashers joined the team through the Forge Annual Parley of 2020 (FAP20, as we call it).
It was announced that Forge was, at the time, in need of extra triage team members, and Ashers was one of three people that answered the call.

Ashers was accepted on the basis that they had already been a positively contributing member of the community; their knowledge of modding stemming from their experience on the Minecolonies mod made them an excellent helper, and their code review was excellent.

Ashers quickly moved into more of a moderator role, due to time constraints from work and their personality being far more relaxed and forgiving, something we wanted for our moderation team at the time.

Today, he is one of several of our moderators keeping the community spaces relaxed and friendly.

### OrionOnline

Orion also joined through FAP20, and was also one of the Minecolonies developers, so he fit in well alongside AshersLab.

Orion had more of a taste for the backend development due to his day job, so he quickly moved to work on our toolchain; contributing lots of fixes to the ForgeGradle system that builds Forge and its' mods.

Eventually, Orion pioneered the change to a TeamCity CI system, a huge migration effort from the Jenkins system we were using before.

With Orion's work on the toolchain, rendering expertise, and knowledge of necessary infrastructure systems, he came to be a dependable member of the team.


## Collaborators

### Illyohs

Illy orginally joined to help out with language loaders - his Scorge project allows loading mods written with the Scala language (hence, language loader). He was later conscripted into updating Forge itself, earning the nickname "Patcherman".

He is currently a moderator in our communities.

`<filler>` Illy was born 10,000 years ago before the age of modern man. Born on the tallest mountain on the highest peak when the sun was at it's highest. An oracle came forth and said "This child shall be a forge contributor" to which the the child's parents asked "The fuck is forge? Reginald are you drunk? You have to lay off the hooch man" to which Reginald replied "I don't need to lay off you lay off!" but little did they know that Reginald was right and Illy spent the next 10 millennia honing their skills to lurk in the forge discord `</filler>`






## Discord Users

### Retrogradle

- AterAnimAvis
- Curle
- sciwhiz12
- SmokeySalmon ?
- Unbekannt

### ModLauncher Team

- AterAnimAvis
- cpw
- Curle
- Ichttt
- kashike
- Lex
- Orion
- sciwhiz12
- zml ?

### Contributor

- boq ?
- cojo ?
- covers
- JDLogic
- JoJoModding ?
- Lat
- Tahg

### Collaborator

- illy
- AbrarSyed
- amadornes
- Bloodshot
- boq ?
- coehlrich ?
- cojo ?
- Direwolf20 ?
- fry
- kashike
- KingLemming
- Mumfrey ?
- peterix ?
- ProfMobius ?
- SizableShrimp
- TamasHenning

### superhelper

- Curle
- diesieben07
- sciwhiz12
- senox13 ?
- Shroom Agent ?

### Triage Team

#### Junior

- Illy
- Asherslab
- AterAnimAvis
- ChampionAsh5357
- covers1624
- DaemonUmbra
- dpeter99
- ichttt
- kashike
- matyrobbrt
- Orion
- Raven
- Shadows
- Unbekannt
- Unnoen

#### Senior

- Curle
- pupnewfster
- Sciwhiz12

### LTS

- covers1624
- Curle
- gigaherz
- mezz
- tterrag

### Moderator

- illy
- Asherslab
- Curle
- DaemonUmbra
- gigaherz
- Mumfrey
- Orion
- sciwhiz12
- tterrag

### Forge Team

- cpw
- Curle
- gigaherz
- Lex
- mezz
- tterrag
