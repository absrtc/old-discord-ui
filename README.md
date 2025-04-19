# ⚠️ THIS IS NOT THE ACTUAL OLD DISCORD UI, RATHER A SIMILAR REPRESENTATION. ⚠️
## ✨ If this helped you, please consider giving a Star! ✨

# Old Discord UI
basically, this is a somewhat representation of the old discord UI.

This CSS was not made by me, rather it was a bunch of [vencord](https://vencord.dev) CSS snippets combined together.

If you would like to use this, do the following:

## 1. - Download Vencord
To download Vencord: Visit the [Vencord Website](https://vencord.dev) and install it. Once installed, you have to patch it and restart Discord.

## 2. - Add It to your Discord QuickCSS
First, open Settings. After settings is opened, scroll down the sidebar until you see the **Vencord** category. Then, click the Vencord button and under the **Quick Actions Section**, press **Edit QuickCSS**. You will see a new Window open. In that window, paste the following:

```
@import url("https://raw.githubusercontent.com/absrtc/old-discord-ui/refs/heads/master/ui.css");
```

## Credits
None of the CSS Above is made by me, all credits are below.


Server List - Scabau (scattagain)

User Area - evie (evie.flowers)

Remove Server List Cover - Obsidian (obsidianninja11)

Compact Frame - Chloe (chloecinders)

Timestamp - krekevyks1337

Nameplates - pointy

If your credits are not here, please contact me on Discord (@absst).

## Contributions

If you would like to Contribute to this repository, you can create a **Pull Request**. While editing, please make sure that:

1. Keep Imports at the top of the file.

Example:
```
:root {
    --guildbar-avatar-size: 48px;
    --blob-scale: 48;

    --guildbar-folder-size: var(--guildbar-avatar-size);
    --folder-blob-scale: var(--blob-scale);
}

@import url("https://scattagain.github.io/VencordStuff/css/GuildbarRevert.css"); ❌
@import url('https://raw.githubusercontent.com/surgedevs/visual-refresh-compact-title-bar/refs/heads/main/desktop.css'); ❌
```

```
@import url("https://scattagain.github.io/VencordStuff/css/GuildbarRevert.css"); ✅
@import url('https://raw.githubusercontent.com/surgedevs/visual-refresh-compact-title-bar/refs/heads/main/desktop.css'); ✅

:root {
    --guildbar-avatar-size: 48px;
    --blob-scale: 48;

    --guildbar-folder-size: var(--guildbar-avatar-size);
    --folder-blob-scale: var(--blob-scale);
}
```

2. Commment the section you have added, and what it changes on the Application.
Example:
```
span[class*="timestampInline_"] time::before {
  content: attr(aria-label);
  font-size: 12px;
}

span[class*="timestampInline_"] {
  font-size: 0px !important;
}
```

```

/* Adds detail back to Message Timestamps */ ✅
span[class*="timestampInline_"] time::before {
  content: attr(aria-label);
  font-size: 12px;
}

span[class*="timestampInline_"] {
  font-size: 0px !important;
}
```
