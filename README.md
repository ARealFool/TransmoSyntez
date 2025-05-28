# TransmoSyntez
A Deobfuscator for Molek Syntez built on the Opus Mutatum architecture made by Yut23.

To run the deobfuscator, extract the zip to a directory that isnt MOLEK SYNTEZ, copy all the game files to the same directory, then run

>dotnet run --project OpusMutatum.csproj -- "path/to/original/Vegas.exe" --lib-dir "libs" --dump-strings
