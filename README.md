# 91erValheimat – Modpack

Das Modpack für unsere Valheim-Server. Ein Klick, alle Mods aktuell.

[![Latest Release](https://img.shields.io/github/v/release/ezek1el/valheim-mods?label=Modpack&style=for-the-badge&color=6366F1)](https://github.com/ezek1el/valheim-mods/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/ezek1el/valheim-mods/total?style=for-the-badge&color=4ADE80)](https://github.com/ezek1el/valheim-mods/releases)

> **Wichtig:** Ohne diese Mods ist keine Verbindung zum Server möglich.
> Server und Clients müssen immer denselben Stand haben.

---

## Schnellstart (empfohlen)

1. **[ValheimModUpdater herunterladen](https://github.com/ezek1el/valheim-mods/releases/latest/download/ValheimModUpdater.zip)** und an einem Ort deiner Wahl entpacken.

2. Doppelklick auf **`ValheimModUpdater.bat`** → *Jetzt aktualisieren* klicken → fertig.

Der Updater findet deine Steam-Installation selbst, zeigt dir die Änderungen des
aktuellen Releases an und legt vor jedem Update ein Backup an.

**Was er nicht anfasst:** deine eigenen Client-Mods und deine Einstellungen unter
`BepInEx\config` – diese bleiben erhalten.

> Der Downloadlink zeigt immer auf die aktuelle Version – einmal herunterladen genügt.

### Einmalig – falls BepInEx noch nie installiert wurde

*(sollte bei Stammspielern nicht der Fall sein)*

1. **BepInEx installieren** – [BepInExPack Valheim](https://thunderstore.io/c/valheim/p/denikson/BepInExPack_Valheim/)
   herunterladen und den Inhalt nach `…\Steam\steamapps\common\Valheim\` entpacken.

2. **Umsteiger:** Wer vorher Mods von Hand installiert hat, leert einmalig den Ordner
   `…\Valheim\BepInEx\plugins`. Danach nie wieder nötig – der Updater pflegt ihn selbst.

---

## Manuelle Installation

Geht auch ohne Updater ... ist nur umständlicher

1. **Vorher** den Ordner `plugins` im BepInEx-Verzeichnis löschen:

   ```
   …\Steam\steamapps\common\Valheim\BepInEx\
   ```

   Alternativ: Rechtsklick auf Valheim in der Steam-Bibliothek → *Verwalten* →
   *Lokale Dateien durchsuchen* → Ordner `BepInEx` öffnen → `plugins` löschen.

2. Modpack aus dem [aktuellen Release](https://github.com/ezek1el/valheim-mods/releases/latest)
   herunterladen (`valheim_plugins_*.zip`).

3. Den Ordner `plugins` aus dem Archiv in das BepInEx-Verzeichnis entpacken.

> BepInEx selbst ist **nicht** im Archiv enthalten – das ist eine einmalige
> Installation und bleibt unverändert.

---

## Enthaltene Mods

<!-- MODS:START -->

| Mod | Version | Läuft auf |
|---|---|---|
| [AzuCraftyBoxes](https://thunderstore.io/c/valheim/p/Azumatt/AzuCraftyBoxes/) | `1.8.13` | Server + Client |
| [BetterNetworking Valheim](https://thunderstore.io/c/valheim/p/CW_Jesse/BetterNetworking_Valheim/) | `2.3.2` | Server + Client |
| [Cross Server Portals](https://thunderstore.io/c/valheim/p/lunarbin/Cross_Server_Portals/) | `1.2.0` | Server + Client |
| [Custom Raids](https://thunderstore.io/c/valheim/p/ASharpPen/Custom_Raids/) | `1.8.1` | Server + Client |
| [EpicLoot](https://thunderstore.io/c/valheim/p/RandyKnapp/EpicLoot/) | `0.12.11` | Server + Client |
| [EquipmentAndQuickSlots](https://thunderstore.io/c/valheim/p/RandyKnapp/EquipmentAndQuickSlots/) | `2.1.4` | Server + Client |
| [FloorsAreRoofs](https://thunderstore.io/c/valheim/p/bonesbro/FloorsAreRoofs/) | `2.0.2` | Server + Client |
| [Jotunn](https://thunderstore.io/c/valheim/p/ValheimModding/Jotunn/) | `2.27.1` | Server + Client |
| [JsonDotNET](https://thunderstore.io/c/valheim/p/ValheimModding/JsonDotNET/) | `13.0.4` | Server + Client |
| [OdinsFoodBarrels](https://thunderstore.io/c/valheim/p/OdinPlus/OdinsFoodBarrels/) | `1.2.2` | Server + Client |
| [PetPantry](https://thunderstore.io/c/valheim/p/Azumatt/PetPantry/) | `1.0.5` | Server + Client |
| [PlantEasily](https://thunderstore.io/c/valheim/p/Advize/PlantEasily/) | `2.0.3` | Server + Client |
| [PlantEverything](https://thunderstore.io/c/valheim/p/Advize/PlantEverything/) | `1.2.0` | Server + Client |
| [roll](https://thunderstore.io/c/valheim/p/1010101110/roll/) | `1.2.0` | Server + Client |
| [TeleportEverything](https://thunderstore.io/c/valheim/p/OdinPlus/TeleportEverything/) | `2.9.1` | Server + Client |
| [ValheimPlus Grantapher Temporary](https://thunderstore.io/c/valheim/p/Grantapher/ValheimPlus_Grantapher_Temporary/) | `9.17.1` | Server + Client |
| [Venture Floating Items](https://thunderstore.io/c/valheim/p/VentureValheim/Venture_Floating_Items/) | `0.3.3` | Server + Client |
| [Weather Tweaks](https://www.nexusmods.com/valheim/mods/1850) | `1.1.0` | Server + Client |
| [XPortal](https://thunderstore.io/c/valheim/p/SpikeHimself/XPortal/) | `1.2.24` | Server + Client |
| [BetterLaddersContinued](https://thunderstore.io/c/valheim/p/Valphi/BetterLaddersContinued/) | `0.217.24` | nur Client |
| [BetterUI ForeverMaintained](https://thunderstore.io/c/valheim/p/BetterUI_ForeverMaintained/BetterUI_ForeverMaintained/) | `2.5.9` | nur Client |
| [EnhancedBepInExConfigurationManager](https://thunderstore.io/c/valheim/p/Pineapple/EnhancedBepInExConfigurationManager/) | `0.1.1` | nur Client |
| [InstantMonsterDropFork](https://thunderstore.io/c/valheim/p/mchangrh/InstantMonsterDropFork/) | `0.6.0` | nur Client |
| [PregnancyStatus](https://www.nexusmods.com/valheim/mods/1634) | `1.0.0` | nur Client |
| [Quick Stack Store Sort Trash Restock](https://thunderstore.io/c/valheim/p/Goldenrevolver/Quick_Stack_Store_Sort_Trash_Restock/) | `1.4.13` | nur Client |
| [Slope Combat Fix](https://thunderstore.io/c/valheim/p/lashiernexusmodport/Slope_Combat_Fix/) | `1.3.0` | nur Client |

<!-- MODS:END -->

---

## Probleme

**„Incompatible version" beim Verbinden**
Dein Modstand weicht vom Server ab. Updater starten – oder das aktuelle Release
manuell installieren.

**Valheim startet, aber ohne Mods**
BepInEx fehlt oder ist nicht im richtigen Ordner. Es gehört direkt neben die
`valheim.exe`, nicht in einen Unterordner.

**Updater meldet „BepInEx fehlt"**
Siehe *Einmalig* im Schnellstart.

---

<sub>Die Releases werden automatisch erzeugt: Ein Skript auf dem Server prüft die Mod-Quellen,
aktualisiert beide Server und veröffentlicht den neuen Stand als Release.
Die Mod-Tabelle oben wird dabei ebenfalls automatisch aktualisiert.</sub>
