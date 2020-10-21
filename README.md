[21Oct2020 06:05:13.882] [main/INFO] [cpw.mods.modlauncher.Launcher/MODLAUNCHER]: ModLauncher running: args [--username, FireyAlex12, --version, 1.16.3-forge-34.1.25, --gameDir, C:\Users\alexn\AppData\Roaming\.minecraft, --assetsDir, C:\Users\alexn\AppData\Roaming\.minecraft\assets, --assetIndex, 1.16, --uuid, c3cc55c45f154a90ab639ce94cc068e3, --accessToken, ????????, --userType, mojang, --versionType, release, --launchTarget, fmlclient, --fml.forgeVersion, 34.1.25, --fml.mcVersion, 1.16.3, --fml.forgeGroup, net.minecraftforge, --fml.mcpVersion, 20200911.084530]
[21Oct2020 06:05:13.887] [main/INFO] [cpw.mods.modlauncher.Launcher/MODLAUNCHER]: ModLauncher 7.0.1+78+master.e9771d8 starting: java version 1.8.0_51 by Oracle Corporation
[21Oct2020 06:05:14.707] [main/INFO] [net.minecraftforge.fml.loading.FixSSL/CORE]: Added Lets Encrypt root certificates as additional trust
[21Oct2020 06:05:14.783] [main/INFO] [mixin/]: SpongePowered MIXIN Subsystem Version=0.8.2 Source=file:/C:/Users/alexn/AppData/Roaming/.minecraft/libraries/org/spongepowered/mixin/0.8.2/mixin-0.8.2.jar Service=ModLauncher Env=CLIENT
[21Oct2020 06:05:14.861] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: java.lang.RuntimeException: Failed to load FML config from C:\Users\alexn\AppData\Roaming\.minecraft\config\fml.toml
[21Oct2020 06:05:14.862] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at net.minecraftforge.fml.loading.FMLConfig.loadFrom(FMLConfig.java:64)
[21Oct2020 06:05:14.863] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at net.minecraftforge.fml.loading.FMLConfig.load(FMLConfig.java:77)
[21Oct2020 06:05:14.864] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at net.minecraftforge.fml.loading.FMLServiceProvider.initialize(FMLServiceProvider.java:81)
[21Oct2020 06:05:14.866] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at cpw.mods.modlauncher.TransformationServiceDecorator.onInitialize(TransformationServiceDecorator.java:68)
[21Oct2020 06:05:14.866] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at cpw.mods.modlauncher.TransformationServicesHandler.lambda$initialiseTransformationServices$7(TransformationServicesHandler.java:107)
[21Oct2020 06:05:14.867] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at cpw.mods.modlauncher.TransformationServicesHandler$$Lambda$84/1620890840.accept(Unknown Source)
[21Oct2020 06:05:14.867] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at java.util.HashMap$Values.forEach(HashMap.java:972)
[21Oct2020 06:05:14.868] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at cpw.mods.modlauncher.TransformationServicesHandler.initialiseTransformationServices(TransformationServicesHandler.java:107)
[21Oct2020 06:05:14.869] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at cpw.mods.modlauncher.TransformationServicesHandler.initializeTransformationServices(TransformationServicesHandler.java:59)
[21Oct2020 06:05:14.870] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at cpw.mods.modlauncher.Launcher.run(Launcher.java:75)
[21Oct2020 06:05:14.870] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at cpw.mods.modlauncher.Launcher.main(Launcher.java:65)
[21Oct2020 06:05:14.871] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1061]: Caused by: com.electronwill.nightconfig.core.io.ParsingException: Not enough data available
[21Oct2020 06:05:14.871] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1061]: 	at com.electronwill.nightconfig.core.io.ParsingException.notEnoughData(ParsingException.java:22)
[21Oct2020 06:05:14.872] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1061]: 	at com.electronwill.nightconfig.core.io.ReaderInput.directReadChar(ReaderInput.java:36)
[21Oct2020 06:05:14.872] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1061]: 	at com.electronwill.nightconfig.core.io.AbstractInput.readChar(AbstractInput.java:49)
[21Oct2020 06:05:14.873] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1061]: 	at com.electronwill.nightconfig.core.io.AbstractInput.readCharsUntil(AbstractInput.java:123)
[21Oct2020 06:05:14.873] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1061]: 	at com.electronwill.nightconfig.toml.TableParser.parseKey(TableParser.java:166)
[21Oct2020 06:05:14.874] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1061]: 	at com.electronwill.nightconfig.toml.TableParser.parseDottedKey(TableParser.java:145)
[21Oct2020 06:05:14.874] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1061]: 	at com.electronwill.nightconfig.toml.TableParser.parseNormal(TableParser.java:55)
[21Oct2020 06:05:14.875] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1061]: 	at com.electronwill.nightconfig.toml.TomlParser.parse(TomlParser.java:44)
[21Oct2020 06:05:14.875] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1061]: 	at com.electronwill.nightconfig.toml.TomlParser.parse(TomlParser.java:37)
[21Oct2020 06:05:14.875] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1061]: 	at com.electronwill.nightconfig.core.io.ConfigParser.parse(ConfigParser.java:113)
[21Oct2020 06:05:14.875] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1061]: 	at com.electronwill.nightconfig.core.io.ConfigParser.parse(ConfigParser.java:219)
[21Oct2020 06:05:14.876] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1061]: 	at com.electronwill.nightconfig.core.io.ConfigParser.parse(ConfigParser.java:202)
[21Oct2020 06:05:14.876] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1061]: 	at com.electronwill.nightconfig.core.file.WriteSyncFileConfig.load(WriteSyncFileConfig.java:73)
[21Oct2020 06:05:14.877] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1061]: 	at com.electronwill.nightconfig.core.file.AutoreloadFileConfig.load(AutoreloadFileConfig.java:41)
[21Oct2020 06:05:14.877] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1061]: 	at com.electronwill.nightconfig.core.file.AutosaveCommentedFileConfig.load(AutosaveCommentedFileConfig.java:85)
[21Oct2020 06:05:14.877] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1061]: 	at net.minecraftforge.fml.loading.FMLConfig.loadFrom(FMLConfig.java:60)
[21Oct2020 06:05:14.878] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1061]: 	... 10 more
