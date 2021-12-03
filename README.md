**Docker Templates**

- Aurora-Files (v1.0)
- Bitcoin-NODE (v1.0)
- Composerize (v1.0)
- Jellyfin (v1.0)
- LogicalDOC-CE (v1.0)
- Mayan-EDMS (v1.0)
- Monero-NODE (v1.0)
- OpenKM-CE (v1.0)
- Tanoshi (v1.0)
- Webmail-Lite-PHP (v1.0)
- Webmail-Pro-PHP (v1.0)
- WhatsApp-Analyzer (v1.0)

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
