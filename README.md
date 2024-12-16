# Placed Light
- [Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/135488)

## Dev setup
- Download [SpriggitCLI.zip](https://github.com/Mutagen-Modding/Spriggit/releases/tag/0.35.1) and place it in `SpriggitCLI` folder (git ignored so it wont show up in git)

### Serialize
- Copy content from zip into `package`
- Make sure `serialize.bat` matches the esp/esm files from package
- Delete `Spriggit` folder
- Run `serialize.bat`
- Commit changes

### Deserialize (Create esp/esm from git contents)
- Make sure `deserialize.bat` matches the esp/esm files that should be packaged
- Run `deserialize.bat`
- Now dist folder will have all contents that can be zipped up and deployed