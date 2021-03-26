# crash-log---- Minecraft Crash Report ----
// I let you down. Sorry :(

Time: 3/25/21 9:35 PM
Description: Ticking entity

java.lang.NullPointerException: Ticking entity
	at uniquee.handler.EntityEvents.onLootingLevel(EntityEvents.java:918) ~[uniquee:1.0] {re:classloading}
	at net.minecraftforge.eventbus.ASMEventHandler_508_EntityEvents_onLootingLevel_LootingLevelEvent.invoke(.dynamic) ~[?:?] {}
	at net.minecraftforge.eventbus.ASMEventHandler.invoke(ASMEventHandler.java:85) ~[eventbus-4.0.0.jar:?] {}
	at net.minecraftforge.eventbus.EventBus.post(EventBus.java:302) ~[eventbus-4.0.0.jar:?] {}
	at net.minecraftforge.eventbus.EventBus.post(EventBus.java:283) ~[eventbus-4.0.0.jar:?] {}
	at net.minecraftforge.common.ForgeHooks.getLootingLevel(ForgeHooks.java:401) ~[forge:?] {re:mixin,re:classloading}
	at net.minecraftforge.common.ForgeHooks.getLootingLevel(ForgeHooks.java:394) ~[forge:?] {re:mixin,re:classloading}
	at net.minecraft.loot.LootContext.getLootingModifier(LootContext.java:99) ~[?:?] {re:mixin,re:classloading}
	at net.minecraft.loot.conditions.RandomChanceWithLooting.test(RandomChanceWithLooting.java:36) ~[?:?] {re:classloading,pl:accesstransformer:B}
	at net.minecraft.loot.conditions.RandomChanceWithLooting.test(RandomChanceWithLooting.java:18) ~[?:?] {re:classloading,pl:accesstransformer:B}
	at java.util.function.Predicate.lambda$and$0(Predicate.java:69) ~[?:1.8.0_242] {}
	at net.minecraft.loot.LootPool.func_216091_a(LootPool.java:84) ~[?:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B}
	at net.minecraft.loot.LootTable.func_216114_a(LootTable.java:68) ~[?:?] {re:mixin,re:computing_frames,re:classloading,pl:mixin:APP:performant.mixins.json:loot.LoottableMixin,pl:mixin:A}
	at net.minecraft.loot.TableLootEntry.func_216154_a(SourceFile:33) ~[?:?] {re:classloading,pl:accesstransformer:B}
	at net.silentchaos512.scalinghealth.loot.TableGlobalModifier.doApply(TableGlobalModifier.java:30) ~[scalinghealth:4.0.5+5] {re:classloading}
	at net.minecraftforge.common.loot.LootModifier.apply(LootModifier.java:53) ~[forge:?] {re:classloading}
	at net.minecraftforge.common.ForgeHooks.modifyLoot(ForgeHooks.java:1307) ~[forge:?] {re:mixin,re:classloading}
	at net.minecraft.loot.LootTable.func_216113_a(LootTable.java:86) ~[?:?] {re:mixin,re:computing_frames,re:classloading,pl:mixin:APP:performant.mixins.json:loot.LoottableMixin,pl:mixin:A}
	at net.minecraft.block.AbstractBlock.func_220076_a(AbstractBlock.java:214) ~[?:?] {re:computing_frames,pl:accesstransformer:B,re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B}
	at net.minecraft.block.AbstractBlock$AbstractBlockState.func_215693_a(AbstractBlock.java:636) ~[?:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,xf:fml:forgeendertech:randomTickBlock,pl:mixin:APP:losttrinkets.mixins.json:AbstractBlockStateMixin,pl:mixin:APP:betterweather.mixins.json:block.MixinAbstractBlockstate,pl:mixin:APP:ferritecore.blockstatecache.mixin.json:AbstractBlockStateMixin,pl:mixin:A}
	at net.minecraft.world.Explosion.func_77279_a(Explosion.java:250) ~[?:?] {re:classloading,pl:accesstransformer:B}
	at net.minecraft.world.server.ServerWorld.func_230546_a_(ServerWorld.java:1038) ~[?:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,xf:fml:forgeendertech:coremod,pl:mixin:APP:performant.mixins.json:world.ServerWorldBlockUpdateMixin,pl:mixin:APP:betterweather.mixins.json:server.MixinServerWorld,pl:mixin:APP:abnormals_core.mixins.json:ServerWorldMixin,pl:mixin:APP:endergetic.mixins.json:ServerWorldMixin,pl:mixin:APP:quark.mixins.json:ServerWorldMixin,pl:mixin:APP:charm.mixins.json:ServerWorldMixin,pl:mixin:APP:charm.mixins.json:accessor.ServerWorldAccessor,pl:mixin:APP:performant.mixins.json:world.ServerWorldMixin,pl:mixin:APP:performant.mixins.json:entity.MobServerWorldMixin,pl:mixin:A}
	at net.minecraft.world.World.func_217385_a(World.java:566) ~[?:?] {re:computing_frames,pl:accesstransformer:B,re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:betterweather.mixins.json:MixinWorld,pl:mixin:APP:performant.mixins.json:world.WorldMixin,pl:mixin:A}
	at net.minecraft.entity.monster.CreeperEntity.func_146077_cc(CreeperEntity.java:222) ~[?:?] {re:classloading,pl:accesstransformer:B,pl:runtimedistcleaner:A}
	at net.minecraft.entity.monster.CreeperEntity.func_70071_h_(CreeperEntity.java:146) ~[?:?] {re:classloading,pl:accesstransformer:B,pl:runtimedistcleaner:A}
	at net.minecraft.world.server.ServerWorld.func_217479_a(ServerWorld.java:611) ~[?:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,xf:fml:forgeendertech:coremod,pl:mixin:APP:performant.mixins.json:world.ServerWorldBlockUpdateMixin,pl:mixin:APP:betterweather.mixins.json:server.MixinServerWorld,pl:mixin:APP:abnormals_core.mixins.json:ServerWorldMixin,pl:mixin:APP:endergetic.mixins.json:ServerWorldMixin,pl:mixin:APP:quark.mixins.json:ServerWorldMixin,pl:mixin:APP:charm.mixins.json:ServerWorldMixin,pl:mixin:APP:charm.mixins.json:accessor.ServerWorldAccessor,pl:mixin:APP:performant.mixins.json:world.ServerWorldMixin,pl:mixin:APP:performant.mixins.json:entity.MobServerWorldMixin,pl:mixin:A}
	at net.minecraft.world.World.func_217390_a(World.java:554) ~[?:?] {re:computing_frames,pl:accesstransformer:B,re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:betterweather.mixins.json:MixinWorld,pl:mixin:APP:performant.mixins.json:world.WorldMixin,pl:mixin:A}
	at net.minecraft.world.server.ServerWorld.func_72835_b(ServerWorld.java:404) ~[?:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,xf:fml:forgeendertech:coremod,pl:mixin:APP:performant.mixins.json:world.ServerWorldBlockUpdateMixin,pl:mixin:APP:betterweather.mixins.json:server.MixinServerWorld,pl:mixin:APP:abnormals_core.mixins.json:ServerWorldMixin,pl:mixin:APP:endergetic.mixins.json:ServerWorldMixin,pl:mixin:APP:quark.mixins.json:ServerWorldMixin,pl:mixin:APP:charm.mixins.json:ServerWorldMixin,pl:mixin:APP:charm.mixins.json:accessor.ServerWorldAccessor,pl:mixin:APP:performant.mixins.json:world.ServerWorldMixin,pl:mixin:APP:performant.mixins.json:entity.MobServerWorldMixin,pl:mixin:A}
	at net.minecraft.server.MinecraftServer.func_71190_q(MinecraftServer.java:851) ~[?:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:structure_gel.mixins.json:MinecraftServerMixin,pl:mixin:APP:betterweather.mixins.json:server.MixinMinecraftServer,pl:mixin:APP:charm.mixins.json:accessor.MinecraftServerAccessor,pl:mixin:A}
	at net.minecraft.server.MinecraftServer.func_71217_p(MinecraftServer.java:787) ~[?:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:structure_gel.mixins.json:MinecraftServerMixin,pl:mixin:APP:betterweather.mixins.json:server.MixinMinecraftServer,pl:mixin:APP:charm.mixins.json:accessor.MinecraftServerAccessor,pl:mixin:A}
	at net.minecraft.server.integrated.IntegratedServer.func_71217_p(IntegratedServer.java:118) ~[?:?] {re:classloading,xf:OptiFine:default}
	at net.minecraft.server.MinecraftServer.func_240802_v_(MinecraftServer.java:642) ~[?:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:structure_gel.mixins.json:MinecraftServerMixin,pl:mixin:APP:betterweather.mixins.json:server.MixinMinecraftServer,pl:mixin:APP:charm.mixins.json:accessor.MinecraftServerAccessor,pl:mixin:A}
	at net.minecraft.server.MinecraftServer.func_240783_a_(MinecraftServer.java:232) ~[?:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:structure_gel.mixins.json:MinecraftServerMixin,pl:mixin:APP:betterweather.mixins.json:server.MixinMinecraftServer,pl:mixin:APP:charm.mixins.json:accessor.MinecraftServerAccessor,pl:mixin:A}
	at java.lang.Thread.run(Thread.java:748) [?:1.8.0_242] {}


A detailed walkthrough of the error, its code path and all known details is as follows:
---------------------------------------------------------------------------------------

-- Head --
Thread: Server thread
Stacktrace:
	at uniquee.handler.EntityEvents.onLootingLevel(EntityEvents.java:918) ~[uniquee:1.0] {re:classloading}
	at net.minecraftforge.eventbus.ASMEventHandler_508_EntityEvents_onLootingLevel_LootingLevelEvent.invoke(.dynamic) ~[?:?] {}
	at net.minecraftforge.eventbus.ASMEventHandler.invoke(ASMEventHandler.java:85) ~[eventbus-4.0.0.jar:?] {}
	at net.minecraftforge.eventbus.EventBus.post(EventBus.java:302) ~[eventbus-4.0.0.jar:?] {}
	at net.minecraftforge.eventbus.EventBus.post(EventBus.java:283) ~[eventbus-4.0.0.jar:?] {}
	at net.minecraftforge.common.ForgeHooks.getLootingLevel(ForgeHooks.java:401) ~[forge:?] {re:mixin,re:classloading}
	at net.minecraftforge.common.ForgeHooks.getLootingLevel(ForgeHooks.java:394) ~[forge:?] {re:mixin,re:classloading}
	at net.minecraft.loot.LootContext.getLootingModifier(LootContext.java:99) ~[?:?] {re:mixin,re:classloading}
	at net.minecraft.loot.conditions.RandomChanceWithLooting.test(RandomChanceWithLooting.java:36) ~[?:?] {re:classloading,pl:accesstransformer:B}
	at net.minecraft.loot.conditions.RandomChanceWithLooting.test(RandomChanceWithLooting.java:18) ~[?:?] {re:classloading,pl:accesstransformer:B}
	at java.util.function.Predicate.lambda$and$0(Predicate.java:69) ~[?:1.8.0_242] {}
	at net.minecraft.loot.LootPool.func_216091_a(LootPool.java:84) ~[?:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B}
	at net.minecraft.loot.LootTable.func_216114_a(LootTable.java:68) ~[?:?] {re:mixin,re:computing_frames,re:classloading,pl:mixin:APP:performant.mixins.json:loot.LoottableMixin,pl:mixin:A}
	at net.minecraft.loot.TableLootEntry.func_216154_a(SourceFile:33) ~[?:?] {re:classloading,pl:accesstransformer:B}
	at net.silentchaos512.scalinghealth.loot.TableGlobalModifier.doApply(TableGlobalModifier.java:30) ~[scalinghealth:4.0.5+5] {re:classloading}
	at net.minecraftforge.common.loot.LootModifier.apply(LootModifier.java:53) ~[forge:?] {re:classloading}
	at net.minecraftforge.common.ForgeHooks.modifyLoot(ForgeHooks.java:1307) ~[forge:?] {re:mixin,re:classloading}
	at net.minecraft.loot.LootTable.func_216113_a(LootTable.java:86) ~[?:?] {re:mixin,re:computing_frames,re:classloading,pl:mixin:APP:performant.mixins.json:loot.LoottableMixin,pl:mixin:A}
	at net.minecraft.block.AbstractBlock.func_220076_a(AbstractBlock.java:214) ~[?:?] {re:computing_frames,pl:accesstransformer:B,re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B}
	at net.minecraft.block.AbstractBlock$AbstractBlockState.func_215693_a(AbstractBlock.java:636) ~[?:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,xf:fml:forgeendertech:randomTickBlock,pl:mixin:APP:losttrinkets.mixins.json:AbstractBlockStateMixin,pl:mixin:APP:betterweather.mixins.json:block.MixinAbstractBlockstate,pl:mixin:APP:ferritecore.blockstatecache.mixin.json:AbstractBlockStateMixin,pl:mixin:A}
	at net.minecraft.world.Explosion.func_77279_a(Explosion.java:250) ~[?:?] {re:classloading,pl:accesstransformer:B}
	at net.minecraft.world.server.ServerWorld.func_230546_a_(ServerWorld.java:1038) ~[?:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,xf:fml:forgeendertech:coremod,pl:mixin:APP:performant.mixins.json:world.ServerWorldBlockUpdateMixin,pl:mixin:APP:betterweather.mixins.json:server.MixinServerWorld,pl:mixin:APP:abnormals_core.mixins.json:ServerWorldMixin,pl:mixin:APP:endergetic.mixins.json:ServerWorldMixin,pl:mixin:APP:quark.mixins.json:ServerWorldMixin,pl:mixin:APP:charm.mixins.json:ServerWorldMixin,pl:mixin:APP:charm.mixins.json:accessor.ServerWorldAccessor,pl:mixin:APP:performant.mixins.json:world.ServerWorldMixin,pl:mixin:APP:performant.mixins.json:entity.MobServerWorldMixin,pl:mixin:A}
	at net.minecraft.world.World.func_217385_a(World.java:566) ~[?:?] {re:computing_frames,pl:accesstransformer:B,re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:betterweather.mixins.json:MixinWorld,pl:mixin:APP:performant.mixins.json:world.WorldMixin,pl:mixin:A}
	at net.minecraft.entity.monster.CreeperEntity.func_146077_cc(CreeperEntity.java:222) ~[?:?] {re:classloading,pl:accesstransformer:B,pl:runtimedistcleaner:A}
	at net.minecraft.entity.monster.CreeperEntity.func_70071_h_(CreeperEntity.java:146) ~[?:?] {re:classloading,pl:accesstransformer:B,pl:runtimedistcleaner:A}
	at net.minecraft.world.server.ServerWorld.func_217479_a(ServerWorld.java:611) ~[?:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,xf:fml:forgeendertech:coremod,pl:mixin:APP:performant.mixins.json:world.ServerWorldBlockUpdateMixin,pl:mixin:APP:betterweather.mixins.json:server.MixinServerWorld,pl:mixin:APP:abnormals_core.mixins.json:ServerWorldMixin,pl:mixin:APP:endergetic.mixins.json:ServerWorldMixin,pl:mixin:APP:quark.mixins.json:ServerWorldMixin,pl:mixin:APP:charm.mixins.json:ServerWorldMixin,pl:mixin:APP:charm.mixins.json:accessor.ServerWorldAccessor,pl:mixin:APP:performant.mixins.json:world.ServerWorldMixin,pl:mixin:APP:performant.mixins.json:entity.MobServerWorldMixin,pl:mixin:A}
-- Entity being ticked --
Details:
	Entity Type: minecraft:creeper (net.minecraft.entity.monster.CreeperEntity)
	Entity ID: 671
	Entity Name: Creeper
	Entity's Exact location: 74.70, 58.00, 108.70
	Entity's Block location: World: (74,58,108), Chunk: (at 10,3,12 in 4,6; contains blocks 64,0,96 to 79,255,111), Region: (0,0; contains chunks 0,0 to 31,31, blocks 0,0,0 to 511,255,511)
	Entity's Momentum: 0.00, -0.16, 0.00
	Entity's Passengers: []
	Entity's Vehicle: ~~ERROR~~ NullPointerException: null
Stacktrace:
	at net.minecraft.world.World.func_217390_a(World.java:554) ~[?:?] {re:computing_frames,pl:accesstransformer:B,re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:betterweather.mixins.json:MixinWorld,pl:mixin:APP:performant.mixins.json:world.WorldMixin,pl:mixin:A}
	at net.minecraft.world.server.ServerWorld.func_72835_b(ServerWorld.java:404) ~[?:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,xf:fml:forgeendertech:coremod,pl:mixin:APP:performant.mixins.json:world.ServerWorldBlockUpdateMixin,pl:mixin:APP:betterweather.mixins.json:server.MixinServerWorld,pl:mixin:APP:abnormals_core.mixins.json:ServerWorldMixin,pl:mixin:APP:endergetic.mixins.json:ServerWorldMixin,pl:mixin:APP:quark.mixins.json:ServerWorldMixin,pl:mixin:APP:charm.mixins.json:ServerWorldMixin,pl:mixin:APP:charm.mixins.json:accessor.ServerWorldAccessor,pl:mixin:APP:performant.mixins.json:world.ServerWorldMixin,pl:mixin:APP:performant.mixins.json:entity.MobServerWorldMixin,pl:mixin:A}


-- Affected level --
Details:
	All players: 1 total; [ServerPlayerEntity['Leekll'/670, l='ServerLevel[Main World]', x=70.33, y=57.77, z=103.98]]
	Chunk stats: ServerChunkCache: 2337
	Level dimension: minecraft:overworld
	Level spawn location: World: (246,70,101), Chunk: (at 6,4,5 in 15,6; contains blocks 240,0,96 to 255,255,111), Region: (0,0; contains chunks 0,0 to 31,31, blocks 0,0,0 to 511,255,511)
	Level time: 12236 game time, 12236 day time
	Level name: Main World
	Level game mode: Game mode: survival (ID 0). Hardcore: false. Cheats: false
	Level weather: Rain time: 79350 (now: false), thunder time: 0 (now: false)
	Known server brands: forge
	Level was modded: true
	Level storage version: 0x04ABD - Anvil
Stacktrace:
	at net.minecraft.server.MinecraftServer.func_71190_q(MinecraftServer.java:851) ~[?:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:structure_gel.mixins.json:MinecraftServerMixin,pl:mixin:APP:betterweather.mixins.json:server.MixinMinecraftServer,pl:mixin:APP:charm.mixins.json:accessor.MinecraftServerAccessor,pl:mixin:A}
	at net.minecraft.server.MinecraftServer.func_71217_p(MinecraftServer.java:787) ~[?:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:structure_gel.mixins.json:MinecraftServerMixin,pl:mixin:APP:betterweather.mixins.json:server.MixinMinecraftServer,pl:mixin:APP:charm.mixins.json:accessor.MinecraftServerAccessor,pl:mixin:A}
	at net.minecraft.server.integrated.IntegratedServer.func_71217_p(IntegratedServer.java:118) ~[?:?] {re:classloading,xf:OptiFine:default}
	at net.minecraft.server.MinecraftServer.func_240802_v_(MinecraftServer.java:642) ~[?:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:structure_gel.mixins.json:MinecraftServerMixin,pl:mixin:APP:betterweather.mixins.json:server.MixinMinecraftServer,pl:mixin:APP:charm.mixins.json:accessor.MinecraftServerAccessor,pl:mixin:A}
	at net.minecraft.server.MinecraftServer.func_240783_a_(MinecraftServer.java:232) ~[?:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:structure_gel.mixins.json:MinecraftServerMixin,pl:mixin:APP:betterweather.mixins.json:server.MixinMinecraftServer,pl:mixin:APP:charm.mixins.json:accessor.MinecraftServerAccessor,pl:mixin:A}
	at java.lang.Thread.run(Thread.java:748) [?:1.8.0_242] {}


-- System Details --
Details:
	Minecraft Version: 1.16.5
	Minecraft Version ID: 1.16.5
	Operating System: Windows 10 (amd64) version 10.0
	Java Version: 1.8.0_242, AdoptOpenJDK
	Java VM Version: OpenJDK 64-Bit Server VM (mixed mode), 
	Memory: 2641600160 bytes (2519 MB) / 6068633600 bytes (5787 MB) up to 11930697728 bytes (11378 MB)
	CPUs: 8
	JVM Flags: 5 total; -XX:HeapDumpPath=MojangTricksIntelDriversForPerformance_javaw.exe_minecraft.exe.heapdump -Xmx12800m -Xms12800m -XX:HeapDumpPath=MojangTricksIntelDriversForPerformance_javaw.exe_minecraft.exe.heapdump -Xms256m
	ModLauncher: 8.0.9+86+master.3cf110c
	ModLauncher launch target: fmlclient
	ModLauncher naming: srg
	ModLauncher services: 
		/mixin-0.8.2.jar mixin PLUGINSERVICE 
		/eventbus-4.0.0.jar eventbus PLUGINSERVICE 
		/forge-1.16.5-36.1.2.jar object_holder_definalize PLUGINSERVICE 
		/forge-1.16.5-36.1.2.jar runtime_enum_extender PLUGINSERVICE 
		/accesstransformers-3.0.1.jar accesstransformer PLUGINSERVICE 
		/forge-1.16.5-36.1.2.jar capability_inject_definalize PLUGINSERVICE 
		/forge-1.16.5-36.1.2.jar runtimedistcleaner PLUGINSERVICE 
		/mixin-0.8.2.jar mixin TRANSFORMATIONSERVICE 
		/OptiFine_1.16.5_HD_U_G6.jar OptiFine TRANSFORMATIONSERVICE 
		/forge-1.16.5-36.1.2.jar fml TRANSFORMATIONSERVICE 
	FML: 36.1
	Forge: net.minecraftforge:36.1.2
	FML Language Providers: 
		javafml@36.1
		minecraft@1
		kotlinforforge@1.10.0
	Mod List: 
		CyclopsCore-1.16.5-1.11.4.jar                     |Cyclops Core                  |cyclopscore                   |1.11.4              |DONE      |NOSIGNATURE
		DungeonsMod-1.16.3-1.3.0.jar                      |Dungeons Mod                  |dungeonsmod                   |1.16.3-1.3.0        |DONE      |NOSIGNATURE
		randomloot-1.16.5-2.3.6.jar                       |Random Loot Mod               |randomloot                    |1.16.5-2.3.6        |DONE      |NOSIGNATURE
		curiousshulkerboxes-forge-1.16.5-4.0.1.0.jar      |Curious Shulker Boxes         |curiousshulkerboxes           |1.16.5-4.0.1.0      |DONE      |NOSIGNATURE
		refinedpipes-0.5.jar                              |Refined Pipes                 |refinedpipes                  |0.5                 |DONE      |NOSIGNATURE
		Uppers-0.3.2.jar                                  |Uppers                        |uppers                        |0.3.2               |DONE      |NOSIGNATURE
		mcw-windows-1.0.3-mc1.16.5.jar                    |Macaw's Windows               |mcwwindows                    |1.0.3               |DONE      |NOSIGNATURE
		Neat 1.7-27.jar                                   |Neat                          |neat                          |1.7-27              |DONE      |NOSIGNATURE
		ForgeEndertech-1.16.4-7.1.0.0-build.0075.jar      |Forge Endertech               |forgeendertech                |7.1.0.0             |DONE      |NOSIGNATURE
		XaerosWorldMap_1.13.1_Forge_1.16.5.jar            |Xaero's World Map             |xaeroworldmap                 |1.13.1              |DONE      |NOSIGNATURE
		CookingForBlockheads_1.16.5-9.3.1.jar             |Cooking for Blockheads        |cookingforblockheads          |9.3.1               |DONE      |NOSIGNATURE
		Controlling-7.0.0.14.jar                          |Controlling                   |controlling                   |7.0.0.14            |DONE      |NOSIGNATURE
		Placebo-1.16.4-4.4.1.jar                          |Placebo                       |placebo                       |4.4.1               |DONE      |NOSIGNATURE
		dankstorage-3.16.jar                              |Dank Storage                  |dankstorage                   |3.16                |DONE      |NOSIGNATURE
		citadel-1.6.2.jar                                 |Citadel                       |citadel                       |1.6.2               |DONE      |NOSIGNATURE
		alexsmobs-1.8.1.jar                               |Alex's Mobs                   |alexsmobs                     |1.8.1               |DONE      |NOSIGNATURE
		YungsApi-1.16.4-Forge-4.jar                       |YUNG's API                    |yungsapi                      |1.16.4-Forge-4      |DONE      |NOSIGNATURE
		Powah-1.16.5-2.3.16.jar                           |Powah                         |powah                         |2.3.16              |DONE      |NOSIGNATURE
		jumbofurnace-1.16.4-2.2.0.1.jar                   |Jumbo Furnace                 |jumbofurnace                  |1.16.4-2.2.0.1      |DONE      |NOSIGNATURE
		Bookshelf-1.16.5-10.0.7.jar                       |Bookshelf                     |bookshelf                     |10.0.7              |DONE      |eb:c4:b1:67:8b:f9:0c:db:dc:4f:01:b1:8e:61:64:39:4c:10:85:0b:a6:c4:c7:48:f0:fa:95:f2:cb:08:3a:e5
		reliquary-1.16.3-1.3.4.1061.jar                   |Reliquary                     |xreliquary                    |1.16.3-1.3.4.1061   |DONE      |NOSIGNATURE
		ChanceCubes-1.16.3-5.0.2.394.jar                  |Chance Cubes                  |chancecubes                   |1.16.3-5.0.2.394    |DONE      |NOSIGNATURE
		DarkUtilities-1.16.5-8.0.3.jar                    |Dark Utilities                |darkutils                     |8.0.3               |DONE      |eb:c4:b1:67:8b:f9:0c:db:dc:4f:01:b1:8e:61:64:39:4c:10:85:0b:a6:c4:c7:48:f0:fa:95:f2:cb:08:3a:e5
		ProgressiveBosses-2.2.0-mc1.16.x.jar              |Progressive Bosses            |progressivebosses             |2.2.0               |DONE      |NOSIGNATURE
		WaterStrainer-1.16.3-10.0.0.jar                   |Water Strainer                |waterstrainer                 |1.16.3-10.0.0       |DONE      |NOSIGNATURE
		SnowRealMagic-1.16.4-2.3.3.jar                    |Snow! Real Magic!             |snowrealmagic                 |2.3.3               |DONE      |NOSIGNATURE
		Extra Ores 1.4.2 (MC 1.16.5).jar                  |Extra Ores                    |extra_ores                    |1.4.2               |DONE      |NOSIGNATURE
		carryon-1.16.5-1.15.3.13.jar                      |Carry On                      |carryon                       |1.15.3.13           |DONE      |8c:03:ac:7d:21:62:65:e2:83:91:f3:22:57:99:ed:75:78:1e:db:de:03:99:ef:53:3b:59:95:18:01:bc:84:a9
		JustEnoughResources-1.16.4-0.12.0.109.jar         |Just Enough Resources         |jeresources                   |0.12.0.109          |DONE      |NOSIGNATURE
		LostTrinkets-1.16.5-0.1.27.jar                    |Lost Trinkets                 |losttrinkets                  |0.1.27              |DONE      |NOSIGNATURE
		absentbydesign-1.16.5-1.4.1.jar                   |Absent By Design Mod          |absentbydesign                |1.16.5-1.4.1        |DONE      |1f:47:ac:b1:61:82:96:b8:47:19:16:d2:61:81:11:60:3a:06:4b:61:31:56:7d:44:31:1e:0c:6f:22:5b:4c:ed
		mob_grinding_utils-1.16.5-0.4.2.jar               |Mob Grinding Utils            |mob_grinding_utils            |1.16.5-0.4.2        |DONE      |NOSIGNATURE
		refinedstorage-1.9.12.jar                         |Refined Storage               |refinedstorage                |1.9.12              |DONE      |NOSIGNATURE
		Upgraded Netherite 1.16.4 - 1.8.1.jar             |Upgraded Netherite            |upgradednetherite             |1.7.0               |DONE      |NOSIGNATURE
		structure_gel-1.16.4-1.7.5.jar                    |Structure Gel API             |structure_gel                 |1.7.5               |DONE      |NOSIGNATURE
		alltheores-1.2.0-1.16.5-36.0.52.jar               |AllTheOres                    |alltheores                    |1.2.0-1.16.5-36.0.52|DONE      |NOSIGNATURE
		mcw-bridges-1.0.5-mc1.16.5-4.jar                  |Macaw's Bridges               |mcwbridges                    |1.0.5               |DONE      |NOSIGNATURE
		industrial-foregoing-1.16.5-3.2.10.2-d316328.jar  |Industrial Foregoing          |industrialforegoing           |3.2.10.2            |DONE      |NOSIGNATURE
		FarmersDelight-1.16.3-0.4.0.jar                   |Farmer's Delight              |farmersdelight                |1.16.3-0.4.0        |DONE      |NOSIGNATURE
		torchmaster-2.3.6.jar                             |Torchmaster                   |torchmaster                   |2.3.6               |DONE      |NOSIGNATURE
		CommonCapabilities-1.16.5-2.5.7.jar               |CommonCapabilities            |commoncapabilities            |2.5.7               |DONE      |NOSIGNATURE
		Compressium-1.16.5-1.2.2.jar                      |Compressium                   |compressium                   |1.2.2               |DONE      |NOSIGNATURE
		BiomesOPlenty-1.16.4-13.0.0.431-universal.jar     |Biomes O' Plenty              |biomesoplenty                 |1.16.4-13.0.0.431   |DONE      |NOSIGNATURE
		ToolStats-1.16.5-6.0.1.jar                        |ToolStats                     |toolstats                     |6.0.1               |DONE      |eb:c4:b1:67:8b:f9:0c:db:dc:4f:01:b1:8e:61:64:39:4c:10:85:0b:a6:c4:c7:48:f0:fa:95:f2:cb:08:3a:e5
		valhelsia_structures-16.0.5.jar                   |Valhelsia Structures          |valhelsia_structures          |16.0.5              |DONE      |NOSIGNATURE
		Lollipop-1.16.5-3.2.9.jar                         |Lollipop                      |lollipop                      |3.2.9               |DONE      |NOSIGNATURE
		dungeons_plus-1.16.4-1.1.3.jar                    |Dungeons Plus                 |dungeons_plus                 |1.1.3               |DONE      |NOSIGNATURE
		mcw-trapdors-1.0.1-mc1.16.5.jar                   |Macaw's Trapdoors             |mcwtrpdoors                   |1.0.1               |DONE      |NOSIGNATURE
		mining_dimension-1.16.5-1.0.3.jar                 |Mining World                  |mining_dimension              |1.16.5-1.0.3        |DONE      |NOSIGNATURE
		CNB-1.16.3_4-1.2.10.jar                           |Creatures and Beasts          |cnb                           |1.2.10              |DONE      |NOSIGNATURE
		randomenchants-4.0.6.jar                          |Random Enchants               |randomenchants                |4.0.6               |DONE      |NOSIGNATURE
		RoRmod-1.16.5-1.1.3b-Forge.jar                    |Risk of Rain Mod              |riskofrainmod                 |1.1.3               |DONE      |NOSIGNATURE
		curios-forge-1.16.5-4.0.5.0.jar                   |Curios API                    |curios                        |1.16.5-4.0.5.0      |DONE      |NOSIGNATURE
		eidolon-0.2.7.jar                                 |Eidolon                       |eidolon                       |0.2.7               |DONE      |NOSIGNATURE
		relics-0.1.10.1.jar                               |Relics                        |relics                        |0.1.10.1            |DONE      |NOSIGNATURE
		Curious Armor Stands-1.16.3-2.0.2.jar             |Curious Armor Stands          |curious_armor_stands          |1.16.3-2.0.2        |DONE      |NOSIGNATURE
		Patchouli-1.16.4-50.jar                           |Patchouli                     |patchouli                     |1.16.4-50           |DONE      |NOSIGNATURE
		betterweather-1.2.9.jar                           |Better Weather                |betterweather                 |1.2.8               |DONE      |NOSIGNATURE
		Unique Enchantments-1.16.5-1.9.1.jar              |Unique Enchantments           |uniquee                       |1.9.0               |DONE      |NOSIGNATURE
		angelring-1.16.3-1.3.3.jar                        |Angel Ring                    |angelring                     |1.3.3               |DONE      |NOSIGNATURE
		elevatorid-1.16.5-1.7.13.jar                      |Elevator Mod                  |elevatorid                    |1.16.5-1.7.13       |DONE      |NOSIGNATURE
		ftb-ultimine-1605.2.0-build.25-forge.jar          |FTB Ultimine                  |ftbultimine                   |1605.2.0-build.25   |DONE      |NOSIGNATURE
		Chunk Pregenerator-V1.16-3.0.5.jar                |Chunk Pregenerator            |chunkpregen                   |V1.16-3.0.5         |DONE      |NOSIGNATURE
		Nugget's Dungeons II v2.7.jar                     |Nugget's Dungeons II          |nuggets_dungeons_ii           |1.0.0               |DONE      |NOSIGNATURE
		architectury-1.10.138-forge.jar                   |Architectury                  |architectury                  |1.10.138            |DONE      |NOSIGNATURE
		curiouselytra-forge-1.16.5-4.0.2.3.jar            |Curious Elytra                |curiouselytra                 |1.16.5-4.0.2.3      |DONE      |NOSIGNATURE
		AI-Improvements-1.16.2-0.3.0.jar                  |AI-Improvements               |aiimprovements                |0.3.0               |DONE      |NOSIGNATURE
		globalxp-1.16.5-v1.7.1.jar                        |Global XP                     |globalxp                      |v1.7.1              |DONE      |NOSIGNATURE
		cloth-config-4.11.15-forge.jar                    |Cloth Config v4 API           |cloth-config                  |4.11.15             |DONE      |NOSIGNATURE
		enchantwithmob-1.16.5-1.2.2.jar                   |Enchant With Mob              |enchantwithmob                |1.16.5-1.2.1        |DONE      |NOSIGNATURE
		smallships-1.16.5-1.1.2.jar                       |Small Ships Mod               |smallships                    |1.1.2               |DONE      |NOSIGNATURE
		ScalingHealth-1.16.5-4.0.5+5.jar                  |Scaling Health                |scalinghealth                 |4.0.5+5             |DONE      |NOSIGNATURE
		FastLeafDecay-v25.jar                             |FastLeafDecay                 |fastleafdecay                 |v25                 |DONE      |NOSIGNATURE
		exoticbirds-1.16.4-1.1.0.jar                      |Exotic Birds                  |exoticbirds                   |1.1.0               |DONE      |NOSIGNATURE
		CodeChickenLib-1.16.4-3.5.1.408-universal.jar     |CodeChicken Lib               |codechickenlib                |3.5.1.408           |DONE      |31:e6:db:63:47:4a:6e:e0:0a:2c:11:d1:76:db:4e:82:ff:56:2d:29:93:d2:e5:02:bd:d3:bd:9d:27:47:a5:71
		BetterMineshafts-Forge-1.16.4-2.0.3.jar           |YUNG's Better Mineshafts      |bettermineshafts              |1.16.4-2.0.3        |DONE      |NOSIGNATURE
		geckolib-forge-1.16.5-3.0.15.jar                  |GeckoLib                      |geckolib3                     |3.0.15              |DONE      |NOSIGNATURE
		NekosEnchantedBooks-1.16-1.2.0.jar                |Neko’s Enchanted Books        |nebs                          |1.2.0               |DONE      |NOSIGNATURE
		dungeons_gear-1.16.4-3.0.6.jar                    |Dungeons Gear                 |dungeons_gear                 |3.0.6               |DONE      |NOSIGNATURE
		Cyclic-1.16.5-1.2.1.jar                           |Cyclic                        |cyclic                        |1.16.5-1.2.1        |DONE      |1f:47:ac:b1:61:82:96:b8:47:19:16:d2:61:81:11:60:3a:06:4b:61:31:56:7d:44:31:1e:0c:6f:22:5b:4c:ed
		BetterAdvancements-1.16.5-0.1.0.105.jar           |Better Advancements           |betteradvancements            |0.1.0.105           |DONE      |NOSIGNATURE
		QuarkOddities-1.16.3.jar                          |Quark Oddities                |quarkoddities                 |1.16.3              |DONE      |NOSIGNATURE
		mowziesmobs-1.5.14.jar                            |Mowzie's Mobs                 |mowziesmobs                   |1.5.14              |DONE      |NOSIGNATURE
		TrashSlot_1.16.3-12.2.1.jar                       |TrashSlot                     |trashslot                     |12.2.1              |DONE      |NOSIGNATURE
		Bountiful Baubles FORGE-1.16.3-0.0.2.jar          |Bountiful Baubles             |bountifulbaubles              |NONE                |DONE      |NOSIGNATURE
		jei-1.16.5-7.6.1.75.jar                           |Just Enough Items             |jei                           |7.6.1.75            |DONE      |NOSIGNATURE
		Druidcraft-1.16.5-0.4.52.jar                      |Druidcraft                    |druidcraft                    |0.4.52              |DONE      |NOSIGNATURE
		the-conjurer-1.16.4-1.0.13.jar                    |The Conjurer                  |conjurer_illager              |1.0.13              |DONE      |NOSIGNATURE
		abnormals_core-1.16.5-3.1.1.jar                   |Abnormals Core                |abnormals_core                |3.1.1               |DONE      |NOSIGNATURE
		environmental-1.16.5-1.0.0.jar                    |Environmental                 |environmental                 |1.0.0               |DONE      |NOSIGNATURE
		allurement-1.16.5-1.1.1.jar                       |Allurement                    |allurement                    |1.1.1               |DONE      |NOSIGNATURE
		buzzier_bees-1.16.5-3.0.1.jar                     |Buzzier Bees                  |buzzier_bees                  |3.0.1               |DONE      |NOSIGNATURE
		berry_good-1.16.5-4.1.1.jar                       |Berry Good                    |berry_good                    |4.1.1               |DONE      |NOSIGNATURE
		goblintraders-1.3.1-1.16.3.jar                    |Goblin Traders                |goblintraders                 |1.3.1               |DONE      |NOSIGNATURE
		caelus-forge-1.16.5-2.1.3.0.jar                   |Caelus API                    |caelus                        |1.16.5-2.1.3.0      |DONE      |NOSIGNATURE
		WAWLA-1.16.5-8.0.1.jar                            |WAWLA                         |wawla                         |8.0.1               |DONE      |eb:c4:b1:67:8b:f9:0c:db:dc:4f:01:b1:8e:61:64:39:4c:10:85:0b:a6:c4:c7:48:f0:fa:95:f2:cb:08:3a:e5
		extraboats-1.16.5-2.1.0.jar                       |Extra Boats                   |extraboats                    |2.1.0               |DONE      |NOSIGNATURE
		Waystones_1.16.5-7.4.0.jar                        |Waystones                     |waystones                     |7.4.0               |DONE      |NOSIGNATURE
		Clumps-6.0.0.17.jar                               |Clumps                        |clumps                        |6.0.0.17            |DONE      |NOSIGNATURE
		NastyMobs-1.16.3-1.0.0.7.jar                      |Nasty Mobs                    |nasty                         |1.0.0.7             |DONE      |NOSIGNATURE
		comforts-forge-1.16.4-4.0.1.0.jar                 |Comforts                      |comforts                      |1.16.4-4.0.1.0      |DONE      |NOSIGNATURE
		NaturesCompass-1.16.5-1.8.6.jar                   |Nature's Compass              |naturescompass                |1.16.5-1.8.6        |DONE      |NOSIGNATURE
		FruitTrees-1.16.4-2.3.0.jar                       |Fruit Trees                   |fruittrees                    |2.3.0               |DONE      |NOSIGNATURE
		Kiwi-1.16.5-3.4.2.jar                             |Kiwi                          |kiwi                          |3.4.2               |DONE      |NOSIGNATURE
		Artifacts-1.16.5-2.8.3.jar                        |Artifacts                     |artifacts                     |1.16.5-2.8.3        |DONE      |NOSIGNATURE
		compactmachines-4.0.0-beta.2.jar                  |Compact Machines 4            |compactmachines               |4.0.0-beta.2        |DONE      |NOSIGNATURE
		crimsonxp-1.0.0.jar                               |Crimson XP                    |crimsonxp                     |1.0.0               |DONE      |NOSIGNATURE
		champions-forge-1.16.5-2.0.1.5.jar                |Champions                     |champions                     |1.16.5-2.0.1.5      |DONE      |NOSIGNATURE
		iceandfire-2.1.6-1.16.4.jar                       |Ice and Fire                  |iceandfire                    |2.1.6-1.16.4        |DONE      |NOSIGNATURE
		walljump-forge-1.16.4-1.3.7.jar                   |Wall-Jump!                    |walljump                      |1.16.4-1.3.7        |DONE      |NOSIGNATURE
		inventorypets-2.0.12.jar                          |Inventory Pets                |inventorypets                 |2.0.12              |DONE      |NOSIGNATURE
		EnderStorage-1.16.4-2.7.1.166-universal.jar       |EnderStorage                  |enderstorage                  |2.7.1.166           |DONE      |31:e6:db:63:47:4a:6e:e0:0a:2c:11:d1:76:db:4e:82:ff:56:2d:29:93:d2:e5:02:bd:d3:bd:9d:27:47:a5:71
		forge-1.16.5-36.1.2-universal.jar                 |Forge                         |forge                         |36.1.2              |DONE      |22:af:21:d8:19:82:7f:93:94:fe:2b:ac:b7:e4:41:57:68:39:87:b1:a7:5c:c6:44:f9:25:74:21:14:f5:0d:90
		Bountiful-1.16.4-3.3.1.jar                        |Bountiful                     |bountiful                     |1.16.4-3.3.1        |DONE      |NOSIGNATURE
		BloodMagic-1.16.4-3.1.0-15.jar                    |Blood Magic                   |bloodmagic                    |1.16.4-3.1.0-15     |DONE      |NOSIGNATURE
		neapolitan-1.16.5-2.1.0.jar                       |Neapolitan                    |neapolitan                    |2.1.0               |DONE      |NOSIGNATURE
		DynamicSurroundings-1.16.4-4.0.4.1.jar            |§3Dynamic Surroundings        |dsurround                     |1.16.4-4.0.4.1      |DONE      |b4:98:14:b9:76:55:25:4f:e5:5f:4d:71:90:87:43:5b:f9:d5:3a:02:60:42:5e:da:1f:15:9c:ff:be:a9:7c:77
		dungeonsarise1.16.5-1.2.68a-HF.jar                |Dungeons Arise                |dungeons_arise                |1.2.68a             |DONE      |NOSIGNATURE
		CraftingTweaks_1.16.3-12.2.0.jar                  |Crafting Tweaks               |craftingtweaks                |12.2.0              |DONE      |NOSIGNATURE
		forge-1.16.5-36.1.2-client.jar                    |Minecraft                     |minecraft                     |1.16.5              |DONE      |NOSIGNATURE
		upgrade_aquatic-1.16.5-3.1.0.jar                  |Upgrade Aquatic               |upgrade_aquatic               |3.1.0               |DONE      |NOSIGNATURE
		cofh_core-1.16.4-1.2.1.jar                        |CoFH Core                     |cofh_core                     |1.2.1               |DONE      |NOSIGNATURE
		ensorcellation-1.16.4-1.2.0.jar                   |Ensorcellation                |ensorcellation                |1.2.0               |DONE      |NOSIGNATURE
		endergetic-1.16.4-3.0.0.jar                       |The Endergetic Expansion      |endergetic                    |3.0.0               |DONE      |NOSIGNATURE
		EnchantmentDescriptions-1.16.5-7.0.3.jar          |EnchantmentDescriptions       |enchdesc                      |7.0.3               |DONE      |eb:c4:b1:67:8b:f9:0c:db:dc:4f:01:b1:8e:61:64:39:4c:10:85:0b:a6:c4:c7:48:f0:fa:95:f2:cb:08:3a:e5
		theoneprobe-1.16-3.0.7.jar                        |The One Probe                 |theoneprobe                   |1.16-3.0.7          |DONE      |NOSIGNATURE
		swingthroughgrass-1.16.4-1.5.3.jar                |SwingThroughGrass             |swingthroughgrass             |1.16.4-1.5.3        |DONE      |NOSIGNATURE
		MouseTweaks-2.14-mc1.16.2.jar                     |Mouse Tweaks                  |mousetweaks                   |2.14                |DONE      |NOSIGNATURE
		ToolBelt-1.16.3-1.15.2.jar                        |Tool Belt                     |toolbelt                      |1.15.2              |DONE      |NOSIGNATURE
		titanium-1.16.5-3.2.8.jar                         |Titanium                      |titanium                      |3.2.8               |DONE      |NOSIGNATURE
		silent-lib-1.16.3-4.9.6.jar                       |Silent Lib                    |silentlib                     |4.9.6               |DONE      |NOSIGNATURE
		AdLods-1.16.4-4.1.4.0-build.0043.jar              |Large Ore Deposits            |adlods                        |4.1.4.0             |DONE      |NOSIGNATURE
		archers_paradox-1.16.4-1.2.0.jar                  |Archer's Paradox              |archers_paradox               |1.2.0               |DONE      |NOSIGNATURE
		atmospheric-1.16.5-3.1.0.jar                      |Atmospheric                   |atmospheric                   |3.1.0               |DONE      |NOSIGNATURE
		dimdungeons-1.093-forge-1.16.5.jar                |Dimensional Dungeons          |dimdungeons                   |1.16.4-1.093        |DONE      |NOSIGNATURE
		savageandravage-1.16.5-3.1.0.jar                  |Savage & Ravage               |savageandravage               |3.1.0               |DONE      |NOSIGNATURE
		Xaeros_Minimap_21.4.4_Forge_1.16.5.jar            |Xaero's Minimap               |xaerominimap                  |21.4.4              |DONE      |NOSIGNATURE
		gravestone-1.16.5-1.0.1.jar                       |Gravestone Mod                |gravestone                    |1.16.5-1.0.1        |DONE      |NOSIGNATURE
		FastWorkbench-1.16.4-4.5.1.jar                    |FastWorkbench                 |fastbench                     |4.5.1               |DONE      |NOSIGNATURE
		autumnity-1.16.5-2.1.0.jar                        |Autumnity                     |autumnity                     |2.1.0               |DONE      |NOSIGNATURE
		AutoRegLib-1.6-47.jar                             |AutoRegLib                    |autoreglib                    |1.6-47              |DONE      |NOSIGNATURE
		Quark-r2.4-308.jar                                |Quark                         |quark                         |r2.4-308            |DONE      |NOSIGNATURE
		Apotheosis-1.16.3-4.4.1.jar                       |Apotheosis                    |apotheosis                    |4.4.1               |DONE      |NOSIGNATURE
		charm-forge-1.16.5-2.3.2.jar                      |Charm                         |charm                         |2.3.2               |DONE      |NOSIGNATURE
		extragolems-11.3.0.jar                            |Extra Golems                  |golems                        |11.3.0              |DONE      |NOSIGNATURE
		abnormals_delight-1.16.5-1.1.0.jar                |Abnormals Delight             |abnormals_delight             |1.1.0               |DONE      |NOSIGNATURE
		performant-1.16.2-5-3.40m.jar                     |Performant                    |performant                    |3.40m               |DONE      |NOSIGNATURE
		simplytea-1.16.5-2.3.4.jar                        |Simply Tea                    |simplytea                     |2.3.4               |DONE      |NOSIGNATURE
		FastFurnace-1.16.4-4.4.0.jar                      |FastFurnace                   |fastfurnace                   |4.4.0               |DONE      |NOSIGNATURE
		ferritecore-2.0.3-forge.jar                       |Ferrite Core                  |ferritecore                   |2.0.3               |DONE      |41:ce:50:66:d1:a0:05:ce:a1:0e:02:85:9b:46:64:e0:bf:2e:cf:60:30:9a:fe:0c:27:e0:63:66:9a:84:ce:8a
		Aquaculture-1.16.5-2.1.16.jar                     |Aquaculture 2                 |aquaculture                   |1.16.5-2.1.16       |DONE      |NOSIGNATURE
		farmerstea-1.0.0.jar                              |Farmer's Tea                  |farmerstea                    |1.0.0               |DONE      |NOSIGNATURE
		refinedstorageaddons-0.7.2.jar                    |Refined Storage Addons        |refinedstorageaddons          |0.7.2               |DONE      |NOSIGNATURE
		CosmeticArmorReworked-1.16.5-v1b.jar              |CosmeticArmorReworked         |cosmeticarmorreworked         |1.16.5-v1b          |DONE      |5e:ed:25:99:e4:44:14:c0:dd:89:c1:a9:4c:10:b5:0d:e4:b1:52:50:45:82:13:d8:d0:32:89:67:56:57:01:53
		valhelsia_core-16.0.6.jar                         |Valhelsia Core                |valhelsia_core                |16.0.6              |DONE      |NOSIGNATURE
		forbidden_arcanus-16.2.0-beta-3.jar               |Forbidden & Arcanus           |forbidden_arcanus             |16.2.0-beta-3       |DONE      |NOSIGNATURE
		overloadedarmorbar-5.1.0.jar                      |Overloaded Armor Bar          |overloadedarmorbar            |5.1.0               |DONE      |NOSIGNATURE
		chiselsandbits-0.3.4-RELEASE.jar                  |Chisels & bits                |chiselsandbits                |NONE                |DONE      |NOSIGNATURE
		xptome-1.16.5-v2.1.jar                            |XP Tome                       |xpbook                        |v2.1                |DONE      |NOSIGNATURE
	Crash Report UUID: 541bc473-586f-4a21-9254-ed3fcc1fc72d
	Kiwi Modules: 
		fruittrees:cherry
		fruittrees:core
		fruittrees:hybridization
		kiwi:contributors
		kiwi:data
		snowrealmagic:core
		snowrealmagic:world
	Patchouli open book context: n/a
	Player Count: 1 / 8; [ServerPlayerEntity['Leekll'/670, l='ServerLevel[Main World]', x=70.33, y=57.77, z=103.98]]
	Data Packs: vanilla, mod:cyclopscore, mod:dungeonsmod, mod:randomloot, mod:curiousshulkerboxes, mod:refinedpipes, mod:uppers (incompatible), mod:mcwwindows, mod:neat (incompatible), mod:forgeendertech, mod:xaeroworldmap, mod:cookingforblockheads (incompatible), mod:controlling, mod:placebo (incompatible), mod:dankstorage, mod:citadel (incompatible), mod:alexsmobs, mod:yungsapi, mod:powah, mod:jumbofurnace (incompatible), mod:bookshelf, mod:xreliquary, mod:chancecubes (incompatible), mod:darkutils (incompatible), mod:progressivebosses, mod:waterstrainer, mod:snowrealmagic, mod:extra_ores, mod:carryon, mod:jeresources, mod:losttrinkets, mod:absentbydesign (incompatible), mod:mob_grinding_utils, mod:refinedstorage, mod:upgradednetherite (incompatible), mod:structure_gel, mod:alltheores, mod:mcwbridges, mod:industrialforegoing (incompatible), mod:farmersdelight, mod:torchmaster (incompatible), mod:commoncapabilities, mod:compressium (incompatible), mod:biomesoplenty, mod:toolstats, mod:valhelsia_structures (incompatible), mod:lollipop, mod:dungeons_plus, mod:mcwtrpdoors, mod:mining_dimension, mod:cnb, mod:randomenchants, mod:riskofrainmod, mod:curios, mod:eidolon, mod:relics, mod:curious_armor_stands (incompatible), mod:patchouli (incompatible), mod:betterweather (incompatible), mod:uniquee (incompatible), mod:angelring (incompatible), mod:elevatorid, mod:ftbultimine (incompatible), mod:chunkpregen, mod:nuggets_dungeons_ii, mod:architectury, mod:curiouselytra, mod:aiimprovements, mod:globalxp, mod:cloth-config (incompatible), mod:enchantwithmob, mod:smallships, mod:scalinghealth, mod:fastleafdecay (incompatible), mod:exoticbirds, mod:codechickenlib (incompatible), mod:bettermineshafts, mod:geckolib3 (incompatible), mod:nebs, mod:dungeons_gear, mod:cyclic (incompatible), mod:betteradvancements, mod:quarkoddities (incompatible), mod:mowziesmobs (incompatible), mod:trashslot (incompatible), mod:bountifulbaubles (incompatible), mod:jei, mod:druidcraft (incompatible), mod:conjurer_illager (incompatible), mod:abnormals_core, mod:environmental, mod:allurement, mod:buzzier_bees, mod:berry_good, mod:goblintraders, mod:caelus, mod:wawla, mod:extraboats, mod:waystones (incompatible), mod:clumps, mod:nasty, mod:comforts (incompatible), mod:naturescompass (incompatible), mod:fruittrees, mod:kiwi, mod:artifacts, mod:compactmachines, mod:crimsonxp, mod:champions (incompatible), mod:iceandfire (incompatible), mod:walljump (incompatible), mod:inventorypets (incompatible), mod:enderstorage (incompatible), mod:forge, mod:bountiful (incompatible), mod:bloodmagic, mod:neapolitan, mod:dsurround, mod:dungeons_arise, mod:craftingtweaks (incompatible), mod:upgrade_aquatic, mod:cofh_core (incompatible), mod:ensorcellation (incompatible), mod:endergetic, mod:enchdesc, mod:theoneprobe, mod:swingthroughgrass (incompatible), mod:mousetweaks, mod:toolbelt (incompatible), mod:titanium (incompatible), mod:silentlib (incompatible), mod:adlods, mod:archers_paradox (incompatible), mod:atmospheric, mod:dimdungeons, mod:savageandravage, mod:xaerominimap, mod:gravestone, mod:fastbench (incompatible), mod:autumnity, mod:autoreglib (incompatible), mod:quark (incompatible), mod:apotheosis (incompatible), mod:charm, mod:golems (incompatible), mod:abnormals_delight, mod:performant (incompatible), mod:simplytea (incompatible), mod:fastfurnace (incompatible), mod:ferritecore (incompatible), mod:aquaculture (incompatible), mod:farmerstea, mod:refinedstorageaddons, mod:cosmeticarmorreworked (incompatible), mod:valhelsia_core, mod:forbidden_arcanus (incompatible), mod:overloadedarmorbar (incompatible), mod:chiselsandbits (incompatible), mod:xpbook
	Type: Integrated Server (map_client.txt)
	Is Modded: Definitely; Client brand changed to 'forge'
	OptiFine Version: OptiFine_1.16.5_HD_U_G6
	OptiFine Build: 20210117-013236
	Render Distance Chunks: 8
	Mipmaps: 4
	Anisotropic Filtering: 1
	Antialiasing: 0
	Multitexture: false
	Shaders: null
	OpenGlVersion: 4.5.0 - Build 25.20.100.6373
	OpenGlRenderer: Intel(R) HD Graphics 630
	OpenGlVendor: Intel
	CpuCount: 8
