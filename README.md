These are modules that I include as part of my special build of RattleSnakeOS.
Add the following lines to the end of your '.rattlesnakeos.toml' file.

    [[custom-prebuilts]]
      modules = [
             "Chronus","CtrlKeyboard", "DavX5","FolderSync","FreedomPop","GappsBrowser",
             "GoogleVoice","HackersKeyboard","KeePassDX","LibreOfficeViewer","Maps",
             "MuPDFMini","NortonAppLock","PrivacyBrowser","SimpleCalendar","SimpleTask","SkyTube",
             "Slide","SpaRSS","TCDrive","TCDropbox","TCWebDAV","TotalCommander","Wallabag","Yalp","iAWriter"
      ]
      repo = "https://github.com/simmule-turner/snake-apps"


# Applications for ROM

## FDroid Open-source
- [x] CtrlKeyboard - Keyboard for terminal/termux
- [x] DavX5 - CalDAV/CardDAV synchronization
- [x] GappsBrowser - Sandbox for google web apps
- [x] KeePassDX - password manager
- [x] LibreOfficeViewer - Microsoft Office document viewer
- [x] Maps - Offline OpenStreetMap navigation
- [x] MuPDFMini - document viewer (PDF, CBZ)
- [x] PrivacyBrowser - A privacy web browser
- [x] SimpleCalendar - Calendar application
- [x] SkyTube - A YouTube player.
- [x] Slide - Companion app for reddit
- [x] SpaRSS - RSS reader
- [x] Wallabag - Read it later app
- [x] Yalp Store - Store to download from Google Play Store

## (non) FDroid Open-source
- [x] Simpletask - task manager (no cloudsync)
- [x] Total Commander - file manager (WebDAV, Drive, TotalDrip)

## Free Commercial
- [x] Norton App Lock - Application Locker (no ads)
- [x] Chronous - Screen Wodget (ads)
- [x] FolderSync - Copy files between cloud services (ads)
- [x] iA Writer - Markdown editor (no ads)
- [x] Voice - Google Voice (no ads)

## Paid Commercial
- [x] Messaging - FreedomPop application (ads)
