# The `credits` folder in the root

Just like any software, they sometimes use 3rd-Party libraries/tools/programs etc. to make their lives easier

## Structure of this document

The next section is one big table of the following:

- cell 1 = name of library/tool/program (may contain exact used version)
- cell 2 = description/feature of library/tool/program
- cell 3 = link to source code (if exists)
- cell 4 = link to website (if exists)
- cell 5 = license
- cell 6 = some random notes

## The libraries/tools/programs Them's Fightin' Herds uses

|Name|Description|Source Code|Website|License|Notes|
|----|-----------|-----------|-------|-------|-----|
|BehaviorTree.CPP|behavior trees for C++|<https://github.com/BehaviorTree/BehaviorTree.CPP>|<https://www.behaviortree.dev/>|MIT License|According to their GitHub page the behavior trees can be made via XML and there's an [GUI Editor](https://www.behaviortree.dev/groot) as well|
|Chipmunk2D|simple 2D physics engine|<https://github.com/slembcke/Chipmunk2D>|<http://chipmunk2d.net/>|MIT License|This is used by [GeoBox](./geobox.md)|
|cpp-base64|C++ base64 en-/decoder|<https://github.com/ReneNyffenegger/cpp-base64>||[Custom](https://raw.githubusercontent.com/ReneNyffenegger/cpp-base64/master/LICENSE)|The author has linked [a page](https://renenyffenegger.ch/notes/development/Base64/Encoding-and-decoding-base-64-with-cpp/) which contains docs and some other stuff|
|dbip|Database for geolocations and IP address lookup||<https://db-ip.com/db/lite.php>|Creative Commons Attribution 4.0 International License|in the license file it says the following: ```NOTE: this data is for pixel lobby server internal use only. We use it to estimate connection quality between players without using pings. No geolocation data leaves the server, and it only identifies their ISP, not their home location.```|
|Dear ImGui|GUI C++ library with no deps|<https://github.com/ocornut/imgui>|<https://github.com/ocornut/imgui/wiki>|MIT License|ImGui is normally used for giving more details in a developer enviroment, having access to this interface in a public enviroment isn't there|
|dlib|toolkit for making real world machine learning/data analysis|<https://github.com/davisking/dlib/tree/master/dlib>|<http://dlib.net/>|BSL-1.0 License||
|fast-cpp-csv-parser|CSV parser for C++|<https://github.com/ben-strasser/fast-cpp-csv-parser>||BSD-3-Clause License|Maybe used by `gamecontrollerdb.txt`?|
|FastLZ(v?)|C library impl of LZ77 compression algo|<https://github.com/ariya/FastLZ>||MIT License|I think they missspelled the GitHub link in the license file (there's an extra "v" letter at the end of the URL)|
|string_id|some string hashing library for finding strings easier|<https://github.com/foonathan/string_id>||Zlib License||
|gamecontrollerdb|a HUGE .txt (actually a .csv) file containing Game Controller configurations for SDL2|<https://github.com/mdqinc/SDL_GameControllerDB>|<http://libsdl.org/>|Zlib License|The game does not use SDL2 (there would be a SDL2 License + SDL2.dll file next to the executable)|
|Glicko2|C++ impl of a Rating System called Clicko2|<https://github.com/TaylorP/Glicko2>||MIT License|There's some information on this [paper](http://www.glicko.net/glicko/glicko2.pdf)|
|gpgoap|General Purpose Goal Oriented Action Planning|<https://github.com/stolk/GPGOAP>||Apache License 2.0 License|This makes AI not too stupid|
|gsl|C++ impl of the Guidelines Support Library|<https://github.com/Microsoft/GSL>||MIT License||
|hiberlite|C++ ORM for SQLite|<https://github.com/paulftw/hiberlite>||BSD-3-Clause License|The `.tfhres` files use this library|
|date|Date library based on \<chrono> headers|<https://github.com/HowardHinnant/date>||MIT License|So the games is not using C++11 or higher?|
|ink|scripting language for writing narrative|<https://github.com/inkle/ink>|<http://www.inklestudios.com/ink>|MIT License|Story Mode uses this for dialog, but it's C# (which explains why the game has C# .dll files, `ink_runtime.exe` and license to `mono`)|
|TinySWF|Adobe Flash Player but open source and shitty?|<https://github.com/jbyu/tinyswf>||MIT License|This library is 10+ years old (like any programming library, jk), also the game uses f**king Adobe Flash???|
|lua (`5.2.0`)|scripting language|<https://github.com/lua/lua/tree/v5-2>|<https://www.lua.org/>|MIT License||
|lust|lua testing framework|<https://github.com/bjornbytes/lust>||MIT License||
|lz4|lossless compression algo|<https://github.com/lz4/lz4>|<http://www.lz4.org/>|BSD 2-Claus & GPLv2 License||
|mathgeolib|Math library for linear algebra and geometry manipulation|<https://github.com/juj/MathGeoLib>|<http://clb.confined.space/MathGeoLib/>|Apache License 2.0 License||
|MicroPather|A* path finding/solver|<https://github.com/leethomason/MicroPather>|||This library is 9+ years old|
|Mono|Open Source version of .NET, aka C# runtime|<https://github.com/mono/mono>|<https://www.mono-project.com/>|MIT & BSD 3-Claus License|used by `ink`|
|motive|Animation System by Google|<https://github.com/google/motive>|<http://google.github.io/motive/>|Apache License 2.0 License|This library has been archived on Dec 29, 2022|
|nativefiledialog(v?)|cross-platform file dialog library|<https://github.com/mlabbe/nativefiledialog>||Zlib License|bro these people can't CTRL+V links 💀|
|ofPennerEasing|easing functions for C++|<https://github.com/jesusgollonet/ofpennereasing>||BSD License|This library has been archived on May 16, 2019, oldest file is 16 years old|
|picojson|Header-Only JSON library|<https://github.com/kazuho/picojson>||BSD-2-Clause License|this library is 7+ years old|
|recastnavigation|navmesh generater|<https://github.com/recastnavigation/recastnavigation>|<http://recastnav.com/>|Zlib License||
|reliable|UDP but it's TCP (well reliable)|<https://github.com/mas-bandwidth/reliable>||BSD-3-Clause License|Used for pixellobbies|
|Embedded_RingBuf_CPP|Ring (Circular) Buffer Queuing Library|<https://github.com/wizard97/Embedded_RingBuf_CPP>||MIT License|This library is made for embedded devices (you know... like an [Arduino](https://en.wikipedia.org/wiki/Arduino))|
|simpleini|`.ini` file reader/writer|<https://github.com/brofield/simpleini>||MIT License|used by `GameNews.ini` in the `Scripts` folder|
|SpriterPlusPlus|Animation library for sprites|<https://github.com/lucidspriter/SpriterPlusPlus>||Zlib License|used by [GeoBox?](geobox.md)|
|SQLite3|SQL database engine|<https://github.com/sqlite/sqlite>|<https://www.sqlite.org/index.html>|[🫡](https://github.com/sqlite/sqlite/blob/master/LICENSE.md)|every programmer's nightmare|
|StackWalker|stack walker for Windows|<https://github.com/JochenKalmbach/StackWalker>||BSD-2-Clause license|but what about Unix?|
|stbrumme's hash library|C++ hash library|<https://github.com/stbrumme/hash-library>|<https://create.stephan-brumme.com/hash-library/>|Zlib License||
|Epic Online Services SDK|SDk for handling Epic Games Services|<https://dev.epicgames.com/en-US/sdk>||[Custom](https://dev.epicgames.com/en-US/licensing)|Epic Shit|
|ThreadPool|Thread Pool impl for C++|<https://github.com/progschj/ThreadPool>||Zlib License||
|ratas|Time Queue library for C++|<https://github.com/jsnell/ratas>||MIT License|library is referred as `timerwheel`|
|tinyaes|AES encryption impl|<https://github.com/kokke/tiny-AES-c>||Unlicense License||
|TinyXML2|XML parser for C++|<https://github.com/leethomason/tinyxml2>||Zlib License|used by BehaviorTree.CPP?|
|tmxparser|parser for [Tiled](https://www.mapeditor.org) maps|<https://github.com/sainteos/tmxparser>||[MIT License with some additions](https://github.com/sainteos/tmxparser/blob/master/LICENSE)|`TinyXML2` is required for this|
|utfcpp|UTF-8 library for C++|<https://github.com/nemtrif/utfcpp>||BSL-1.0 License||
|yojimbc|Server/Client network library|<https://github.com/networkprotocol/yojimbo>||BSD-3-Clause License|used by pixellobbies?|

## libraries/tools/programs the game uses but isn't mentioned in the `credits` folder

|Name|Description|Source Code|Website|License|Notes|
|----|-----------|-----------|-------|-------|-----|
|GeoBox|game engine for Cave Story|would be cool...|<https://forum.cavestory.org/threads/geobox-engine-getting-ready-for-public-use.5844/>|MIT License|[See here for more information](./geobox.md)|
|OtterUI|library/tool for making in-game UI|<https://github.com/ppiecuch/OtterUI>||MIT License|SkullGirls uses this too and it's 11+ years old|
