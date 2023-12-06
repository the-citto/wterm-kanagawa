# wterm-kanagawa
Kanagawa colours for Windows Terminal, from [kanagawa.nvim](https://github.com/rebelot/kanagawa.nvim) [colors.lua](https://github.com/rebelot/kanagawa.nvim/blob/master/lua/kanagawa/colors.lua)

## baground image
under `"profiles"` `"list"` add `"backgroundImage": <path-to-image>` to the profile

additionally, `"backgroundImageOpacity": <value>` 

the Penrose triangle [here](https://github.com/lexxx-c/wterm-kanagawa/blob/main/Penrose-dreieck-blue.png) has kanagawa blues 😉 and it's quite bright, so values close to `0.02`/`0.01` seem better

## palette
all kanagawa colours commented

writing a json like this is quite a monstruosity, but [it appears](https://windowsterminalthemes.dev/) that there's no better way than to copy and paste

add to `"schemes": ` in the Windows Terminal's `settings.jsonn`

```json
{
    //////////////////////////////////////////////////////////
    // # Text color codes:
    // # 30=black 31=red 32=green 33=yellow 34=blue 35=magenta 36=cyan 37=white
    // # Background color codes:
    // # 40=black 41=red 42=green 43=yellow 44=blue 45=magenta 46=cyan 47=white
    //////////////////////////////////////////////////////////
    // sakuraPink = "#D27E99",
    // dragonPink = "#a292a3",
    // lotusPink = "#b35b79",
    // -- "#8a9aa3",
    //////////////////////////////////////////////////////////
    // sumiInk0 = "#16161D",
    // sumiInk1 = "#181820",
    // sumiInk2 = "#1a1a22",
    // sumiInk3 = "#1F1F28",
    // sumiInk4 = "#2A2A37",
    // sumiInk5 = "#363646",
    // sumiInk6 = "#54546D", --fg
    // lotusInk1 = "#545464",
    // lotusInk2 = "#43436c",
    // dragonBlack0 = "#0d0c0c",
    // dragonBlack1 = "#12120f",
    // dragonBlack2 = "#1D1C19",
    // dragonBlack3 = "#181616",
    // dragonBlack4 = "#282727",
    // dragonBlack5 = "#393836",
    // dragonBlack6 = "#625e5a",
    "background": "#0D0C0C",
    "selectionBackground": "#282727",
    "black": "#0D0C0C",
    "brightBlack": "#625e5a",
    // winterRed = "#43242B",
    // autumnRed = "#C34043",
    // samuraiRed = "#E82424",
    // waveRed = "#E46876",
    // peachRed = "#FF5D62",
    // dragonRed = "#c4746e",
    // lotusRed = "#c84053",
    // lotusRed2 = "#d7474b",
    // lotusRed3 = "#e82424",
    // lotusRed4 = "#d9a594",
    "red": "#C34043",
    "brightRed": "#c4746e",
    // winterGreen = "#2B3328",
    // autumnGreen = "#76946A",
    // springGreen = "#98BB6C",
    // dragonGreen = "#87a987",
    // dragonGreen2 = "#8a9a7b",
    // lotusGreen = "#6f894e",
    // lotusGreen2 = "#6e915f",
    // lotusGreen3 = "#b7d0ae",
    "green": "#76946A",
    "brightGreen": "#87a987",
    // winterYellow = "#49443C",
    // roninYellow = "#FF9E3B",
    // boatYellow1 = "#938056",
    // boatYellow2 = "#C0A36E",
    // carpYellow = "#E6C384",
    // dragonYellow = "#c4b28a",--"#a99c8b",
    // lotusYellow ="#77713f",
    // lotusYellow2 = "#836f4a",
    // lotusYellow3 = "#de9800",
    // lotusYellow4 = "#f9d791",
    // surimiOrange = "#FFA066",
    // autumnYellow = "#DCA561",
    // dragonOrange = "#b6927b",
    // dragonOrange2 = "#b98d7b",
    // lotusOrange = "#cc6d00",
    // lotusOrange2 = "#e98a00",
    "yellow": "#DCA561",
    "brightYellow": "#c4b28a",
    // waveBlue1 = "#223249",
    // waveBlue2 = "#2D4F67",
    // winterBlue = "#252535",
    // crystalBlue = "#7E9CD8",
    // springBlue = "#7FB4CA",
    // lightBlue = "#A3D4D5", -- unused yet
    // dragonBlue = "#658594",
    // dragonBlue2 = "#8ba4b0",
    // lotusBlue1 = "#c7d7e0",
    // lotusBlue2 = "#b5cbd2",
    // lotusBlue3 = "#9fb5c9",
    // lotusBlue4 = "#4d699b",
    // lotusBlue5 = "#5d57a3",
    "blue": "#2D4F67",
    "brightBlue": "#658594",
    // oniViolet = "#957FB8",
    // oniViolet2 = "#b8b4d0",
    // springViolet1 = "#938AA9",
    // springViolet2 = "#9CABCA",
    // dragonViolet= "#8992a7",
    // lotusViolet1 = "#a09cac",
    // lotusViolet2 = "#766b90",
    // lotusViolet3 = "#c9cbd1",
    // lotusViolet4 = "#624c83",
    "purple": "#766b90",
    "brightPurple": "#938AA9",
    // -- waveAqua2  = "#68AD99",
    // -- waveAqua4  = "#7AA880",
    // -- waveAqua5  = "#6CAF95",
    // -- waveAqua3  = "#68AD99",
    // waveAqua1 = "#6A9589",
    // waveAqua2 = "#7AA89F", -- improve lightness: desaturated greenish Aqua
    // dragonAqua = "#8ea4a2",
    // lotusAqua = "#597b75",
    // lotusAqua2 = "#5e857a",
    // lotusCyan = "#d7e3d8",
    // dragonTeal = "#949fb5",
    // lotusTeal1 = "#4e8ca2",
    // lotusTeal2 = "#6693bf",
    // lotusTeal3 = "#5a7785",
    "cyan": "#597b75",
    "brightCyan": "#8ea4a2",
    // fujiGray = "#727169",
    // katanaGray = "#717C7C",
    // dragonGray = "#a6a69c",
    // dragonGray2 = "#9e9b93",
    // dragonGray3 = "#7a8382",
    // fujiWhite = "#DCD7BA",
    // lotusGray = "#dcd7ba",
    // lotusGray2 = "#716e61",
    // lotusGray3 = "#8a8980",
    // oldWhite = "#C8C093",
    // dragonAsh = "#737c73",
    // dragonWhite = "#c5c9c5",
    // lotusWhite0 = "#d5cea3",
    // lotusWhite1 = "#dcd5ac",
    // lotusWhite2 = "#e5ddb0",
    // lotusWhite3 = "#f2ecbc",
    // lotusWhite4 = "#e7dba0",
    // lotusWhite5 = "#e4d794",
    "foreground": "#a6a69c",
    "cursorColor": "#625e5a",
    "white": "#7a8382",
    "brightWhite": "#a6a69c",
    "name": "Kanagawa"
},

