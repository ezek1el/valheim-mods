#  Road2Valheim – Modpack

Das Modpack für unsere Valheim-Server. Ein Klick, alle Mods aktuell, verbunden.

[![Latest Release](https://img.shields.io/github/v/release/ezek1el/valheim-mods?label=Modpack&style=for-the-badge&color=6366F1)](https://github.com/ezek1el/valheim-mods/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/ezek1el/valheim-mods/total?style=for-the-badge&color=4ADE80)](https://github.com/ezek1el/valheim-mods/releases)

> **Wichtig:** Ohne diese Mods ist keine Verbindung zum Server möglich.
> Server und Clients müssen immer denselben Stand haben.

---

##  Schnellstart (empfohlen)

Der **Valheim Updater** hält dein Spiel automatisch auf dem Stand der Server.
Einmal einrichten, danach reicht ein Doppelklick.

### Einmalig - falls BepInEx noch nie installiert wurde (sollte bei Stammspielern nicht der Fall sein)

1. **BepInEx installieren** – [BepInExPack Valheim](https://thunderstore.io/c/valheim/p/denikson/BepInExPack_Valheim/) herunterladen und den Inhalt nach
   `…\Steam\steamapps\common\Valheim\` entpacken.
2. **Updater herunterladen** und in einen beliebigen Ordner legen
   (z. B. `Desktop\ValheimUpdater`).
3. **Umsteiger:** Wer vorher Mods von Hand installiert hat, leert einmalig den Ordner
   `…\Valheim\BepInEx\plugins`. Danach nie wieder nötig – der Updater pflegt ihn selbst.

### Der neue Updater

Doppelklick auf **`Valheim Updater.bat`** → das Fenster zeigt an, ob ein Update
vorliegt → auf *Jetzt aktualisieren* klicken → fertig.

Der Updater findet deine Steam-Installation selbst, zeigt dir die Änderungen des
aktuellen Releases an und legt vor jedem Update ein Backup an.

**Was er nicht anfasst:** deine eigenen Client-Mods und deine Einstellungen unter
`BepInEx\config` – diese bleiben erhalten.

---

##  Manuelle Installation

Geht auch ohne Updater ... nur umständlicher 

1. **Vorher** den Ordner `plugins` im BepInEx-Verzeichnis löschen:

   ```
   …\Steam\steamapps\common\Valheim\BepInEx\
   ```

   Alternativ: Rechtsklick auf Valheim in der Steam-Bibliothek → *Verwalten* →
   *Lokale Dateien durchsuchen* → Ordner `BepInEx` öffnen → `plugins` löschen.

2. [Aktuelles Release](https://github.com/ezek1el/valheim-mods/releases/latest)
   herunterladen (`valheim_plugins_*.zip`).

3. Den Ordner `plugins` aus dem Archiv in das BepInEx-Verzeichnis entpacken.

> BepInEx selbst ist **nicht** im Archiv enthalten – das ist eine einmalige
> Installation und bleibt unverändert.

---

##  Enthaltene Mods

| Mod | Läuft auf |
|---|---|
| [ValheimPlus (Grantapher)](https://thunderstore.io/c/valheim/p/Grantapher/ValheimPlus_Grantapher_Temporary/) | Server + Client |
| [Jotunn](https://thunderstore.io/c/valheim/p/ValheimModding/Jotunn/) | Server + Client |
| [JsonDotNET](https://thunderstore.io/c/valheim/p/ValheimModding/JsonDotNET/) | Server + Client |
| [EpicLoot](https://thunderstore.io/c/valheim/p/RandyKnapp/EpicLoot/) | Server + Client |
| [EquipmentAndQuickSlots](https://thunderstore.io/c/valheim/p/RandyKnapp/EquipmentAndQuickSlots/) | Server + Client |
| [AzuCraftyBoxes](https://thunderstore.io/c/valheim/p/Azumatt/AzuCraftyBoxes/) | Server + Client |
| [PetPantry](https://thunderstore.io/c/valheim/p/Azumatt/PetPantry/) | Server + Client |
| [PlantEasily](https://thunderstore.io/c/valheim/p/Advize/PlantEasily/) | Server + Client |
| [PlantEverything](https://thunderstore.io/c/valheim/p/Advize/PlantEverything/) | Server + Client |
| [OdinsFoodBarrels](https://thunderstore.io/c/valheim/p/OdinPlus/OdinsFoodBarrels/) | Server + Client |
| [TeleportEverything](https://thunderstore.io/c/valheim/p/OdinPlus/TeleportEverything/) | Server + Client |
| [XPortal](https://thunderstore.io/c/valheim/p/SpikeHimself/XPortal/) | Server + Client |
| [Cross Server Portals](https://thunderstore.io/c/valheim/p/lunarbin/Cross_Server_Portals/) | Server + Client |
| [Custom Raids](https://thunderstore.io/c/valheim/p/ASharpPen/Custom_Raids/) | Server + Client |
| [BetterNetworking](https://thunderstore.io/c/valheim/p/CW_Jesse/BetterNetworking_Valheim/) | Server + Client |
| [FloorsAreRoofs](https://thunderstore.io/c/valheim/p/bonesbro/FloorsAreRoofs/) | Server + Client |
| [Venture Floating Items](https://thunderstore.io/c/valheim/p/VentureValheim/Venture_Floating_Items/) | Server + Client |
| [Weather Tweaks](https://www.nexusmods.com/valheim/mods/1850) | Server + Client |
| [roll](https://thunderstore.io/c/valheim/p/1010101110/roll/) | Server + Client |
| [BetterUI ForeverMaintained](https://thunderstore.io/c/valheim/p/BetterUI_ForeverMaintained/BetterUI_ForeverMaintained/) | nur Client |
| [Quick Stack – Store – Sort – Trash – Restock](https://thunderstore.io/c/valheim/p/Goldenrevolver/Quick_Stack_Store_Sort_Trash_Restock/) | nur Client |
| [Configuration Manager](https://thunderstore.io/c/valheim/p/Pineapple/EnhancedBepInExConfigurationManager/) | nur Client |
| [BetterLaddersContinued](https://thunderstore.io/c/valheim/p/Valphi/BetterLaddersContinued/) | nur Client |
| [InstantMonsterDrop](https://thunderstore.io/c/valheim/p/mchangrh/InstantMonsterDropFork/) | nur Client |
| [Slope Combat Fix](https://thunderstore.io/c/valheim/p/lashiernexusmodport/Slope_Combat_Fix/) | nur Client |
| [PregnancyStatus](https://www.nexusmods.com/valheim/mods/1634) | nur Client |

Die genauen Versionen stehen in den
[Release Notes](https://github.com/ezek1el/valheim-mods/releases/latest).

---

##  Probleme

**„Incompatible version" beim Verbinden**
Dein Modstand weicht vom Server ab. Updater starten – oder das aktuelle Release
manuell installieren.

**Valheim startet, aber ohne Mods**
BepInEx fehlt oder ist nicht im richtigen Ordner. Es gehört direkt neben die
`valheim.exe`, nicht in einen Unterordner.

**Updater meldet „BepInEx fehlt"**
Siehe Schritt 1 im Schnellstart.


---

<sub>Die Releases werden automatisch erzeugt: Ein Skript auf dem Server prüft die Mod-Quellen,
aktualisiert beide Server und veröffentlicht den neuen Stand als Release.</sub>
