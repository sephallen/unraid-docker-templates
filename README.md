**Docker Templates**

- 2FAuth (v1.0)
- Aurora-Files (v1.0)
- Bitcoin-NODE (v1.0)
- Blender-Desktop-G3 (v1.0)
- Chromium-Desktop-G3 (v1.0)
- Composerize (v1.0)
- Cowyo (v1.0)
- Cryptgeon (v1.0)
- DailyTxT (v1.0)
- Docker-Hub-RSS (v1.0)
- Etherpad (v1.0)
- Euterpe (v1.0)
- FileShelter (v1.0)
- Firefox-Desktop-G3 (v1.0)
- FlashPaper (v1.0)
- FreeCAD-Desktop-G3 (v1.0)
- Gerbera (v1.0)
- GIMP-Desktop-G3 (v1.0)
- Gokapi (v1.0)
- h5ai (v1.0)
- Hiccup (v1.0)
- HRConvert2 (v1.0)
- imgpush (v1.0)
- Inkscape-Desktop-G3 (v1.0)
- Jellyfin (v1.1)
- Jirafeau (v1.0)
- KeeWeb (v1.0)
- Linx-Server (v1.0)
- LogicalDOC-CE (v1.0)
- MailDev (v1.0)
- Mayan-EDMS (v1.0)
- MiniNote (1.0)
- Mojopaste (v1.0)
- Monero-NODE (v1.0)
- Monitoror (v1.0)
- OpenBooks (v1.0)
- OpenGL-Desktop-G3 (v1.0)
- OpenKM-CE (v1.0)
- Pastefy (v1.0)
- Photo-Stream (v1,0)
- Portainer-Agent (v1.0)
- Portainer-CE (v1.0)
- RSS-Proxy (v1.0)
- Rustpad (v1.0)
- Sharry (v1.0)
- Simply-Shorten (v1.0)
- SQLite-Web (v1.0)
- Tanoshi (v1.0)
- Todo (v1.0)
- VLMCSD-KMS-Server (v1.0)
- Vorta (v1.2)
- Vorta2 (v1.0)
- Webmail-Lite-PHP (v1.0)
- Webmail-Pro-PHP (v1.0)
- WebP-Server (v1.0)
- WhatsApp-Analyzer (v1.0)
- WireGuard-Easy (v1.0)
- YouTube-DL (v1.0)

**How To Use Docker Templates?**

If it's your first time installing a docker container on unRAID and you are not really sure how to proceed, I will try to guide you:

For templates already available from within the 'APPS' tab...
1. Go to the 'APPS' tab, and wait while unRAID loads all the content.
2. Search for the docker app (template) that you would like to install on your server.
3. Click the 'Install' button that will appear somewhere inside the template you have seached before.
4. You will be taken to the docker template creation page, within the 'DOCKER' tab.
5. Configure all the required fields that are needed for the template that you just selected previously, paying attention to each one, specially for the ones that have a 'red asterisk'.
6. Click on the 'APPLY' button, located at the bottom of the page. The container will start building itself based on the template that we have configured before.
7. Done!

For templates that do not exist (yet) within the 'APPS' tab...
1. Go to the 'DOCKER' tab and scroll down until you see the 'ADD CONTAINER' button. Click on it.
2. Start filling in all the required fields, based on the information given by the owner of the docker image. (paths, ports, repo, etc...)
3. Click on the 'APPLY' button, located at the bottom of the page. The container will start building itself based on the information that we have configured before.
4. Done!

If it failed to create the container, check what could be the reason: ports already in use by another container, paths not set correctly, wrong repo or tag, external DB needed (MariaDB, MySQL...), etc.
