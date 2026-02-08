# Diamond Chicken Addon (Bedrock 1.21+)

Dette er et simpelt test-addon til Minecraft Bedrock:

- Kyllinger dropper en diamant, når de dør.
- Lavet til hurtig test på iPad.

## Filer
```
behavior_packs/
  manifest.json
  loot_tables/entities/chicken.json
resource_packs/
  manifest.json
```

## Test i verden
1. Aktivér `Diamond Chicken BP` (og gerne også `Diamond Chicken RP`) i din verden.
2. Spawn en kylling.
3. Dræb kyllingen.
4. Den skal droppe en diamant.

## Lav en `.mcaddon` fil
Fra projektroden:

```bash
zip -r diamond-chicken.mcaddon behavior_packs resource_packs
```

Overfør `diamond-chicken.mcaddon` til iPad og åbn filen derfra for at importere i Minecraft.
