# Den Forsvundne Drage i Terminaldalen

Velkommen til et spændende eventyr med drager, alfer og magi,
som vil udfolde sig i Terminaldalen. En ond konge har taget
en troldmands drage til fange. Din opgave er at befri dragen.

```
                 ______====-_  _-====___
           __--^^^#####//      \\#####^^^--_
        __-^##########// (    ) \\##########^-_
       -############//  |\^^/|  \\############-
     _/############//   (@::@)   \\############\_
    /#############((     \\//     ))#############\
   -###############\\    (oo)    //###############-
  -#################\\  / VV \  //#################-
 -###################\\/      \//###################-
_#/|##########/\######(   /\   )######/\##########|\#_
|/ |#/\#/\#/\/  \#/\##\  |  |  /##/\#/  \/\#/\#/\#| \|
`  |/  V  V  `   V  \#\| |  | |/#/  V   '  V  V  \|  '
   `   `  `      `   / | |  | | \   '      '  '   '
                    (  | |  | |  )
                   __\ | |  | | /__
                  (vvv(VVV)(VVV)vvv)
```

Dragen bliver holdt fanget af en magisk lænke, som kun kan låses op hvis du kender kongens hemmelige kodeord.
Kongen er dårlig til computer-sikkerhed og har brugt navnene på sine kæledyr som adgangskode. Din opgave er derfor at finde ud af hvad kongens kæledyr hedder og sætte dem sammen til en adgangskode. Kongen har følgende kæledyr:

- En hest
- En guldfisk
- En papegøje
- En kat

Du starter eventyret på en vindebro der leder ind til kongens slot. Held og lykke med at finde navnene på kæledyrene og befri dragen!

```
                                  |>>>
                                  |
                    |>>>      _  _|_  _         |>>>
                    |        |;| |;| |;|        |
                _  _|_  _    \\.    .  /    _  _|_  _
               |;|_|;|_|;|    \\:. ,  /    |;|_|;|_|;|
               \\..      /    ||;   . |    \\.    .  /
                \\.  ,  /     ||:  .  |     \\:  .  /
                 ||:   |_   _ ||_ . _ | _   _||:   |
                 ||:  .|||_|;|_|;|_|;|_|;|_|;||:.  |
                 ||:   ||.    .     .      . ||:  .|
                 ||: . || .     . .   .  ,   ||:   |       \,/
                 ||:   ||:  ,  _______   .   ||: , |            /`\
                 ||:   || .   /+++++++\    . ||:   |
                 ||:   ||.    |+++++++| .    ||: . |
              __ ||: . ||: ,  |+++++++|.  . _||_   |
     ____--`~    '--~~__|.    |+++++__|----~    ~`---,              ___
-~--~                   ~---__|,--~'                  ~~----_____-~'   `~----~~
                             /  -   _  \
                            /  -   -_   \
```


## Sådan gør du

> Eventyret er til alle børn i alderen 7-15 år, som gerne vil lære at bruge Unix kommandoer.

For at starte eventyret, skal du hente en kopi af dette repository på en
Unix-lignende computer, f.eks. en computer med Mac OS X, Linux, Unix eller FreeBSD
installeret.

### Hent en kopi af eventyret

Du kan downloade en zip-fil med eventyret:

```
wget https://github.com/skipperkongen/den-forsvundne-drage-i-terminaldalen/archive/master.zip
unzip master.zip
```

Alternativt, kan du clone eventyret med `git` kommandoen:

```
git clone git@github.com:skipperkongen/den-forsvundne-drage-i-terminaldalen.git
```


### Start eventyret

> Dette eventyr foregår 100% i terminalen. På en Mac OS X computer kan du åbne terminalen ved at starte programmet "Applications/Utilities/Terminal". Alternativt, kan du bruge Finder ved blot at skrive "Terminal" i søgefeltet og trykke enter.

Når du har hentet en kopi af eventyret skal du åbne  det i terminalen for at komme igang. Bruge `cd` kommandoen for at åbne
den mappe, som indeholder eventyret. Du skal muligvis bruge `cd` kommandoen et par gange for at komme ind i den rigtige mappe, som indeholder eventyret:

Navne med små bogstaver er *steder*, som du kan gå til ved at skrive f.eks. `cd eventyr`.

```
┌──────────────────────────────────────────────────────────┐
│ Last login: Sat Feb 23 18:54:23 on ttys001               │
│ $ cd den-forsvundne-drage-i-terminaldalen                │
│ $ cd eventyr                                             │
└──────────────────────────────────────────────────────────┘
```

Du kan bruge kommandoen `ls` til at se dig omkring på et sted. Når du bruger `ls` kan du se både steder og ting.

```
┌──────────────────────────────────────────────────────────┐
│ $ ls                                                     │
│ BREV   vindebro                                          │
└──────────────────────────────────────────────────────────┘
```

Navne med STORE bogstaver er *ting*, så ovenfor så du både en ting (`BREV`) og et sted (`vindebro`). Se nærmere på ting med kommandoen `cat`.

```
┌──────────────────────────────────────────────────────────┐
│ $ cat BREV                                               │
│ Oh, modige helt!                                         │
│ Mit navn er Filikodus Den Vemodige.                      │                  
│ Jeg fik mit navn efter den onde konge                    │                    
│ stjal min elskede drage. Han har                         │                                       
│ spærret den inde i tårnet på sit slot                    │                                      
│ og lænket den med en magisk kæde. Vil                    │                                         
│ du befri min drage for mig? Så vil                       │
│ jeg belønne dig med mere guld end du                     │
│ nogensinde har set. Jeg ville redde                      │
│ dragen selv, men desværre har kongens                    │
│ troldmager kastet en forbandelse på                      │
│ mig, så jeg aldrig nogensinde vil                        │
│ kunne betræde slottet igen. Jeg har                      │
│ hørt at du kan låse den magiske kæde                     │
│ op hvis du siger navnene på alle                         │
│ kongens kæledyr efter hinanden.                          │
│                                                          │
│ Kærlig hilsen,                                           │
│ Filikodus Den Vemodige                                   │
└──────────────────────────────────────────────────────────┘
```

God fornøjelse og held og lykke!
