# Contact — Mythadubiz apps

Shared contact form for the apps' support and legal pages: `https://mythadubiz.github.io/contact/?app=<app>&lang=<fr|en|de>&topic=<support|privacy|other>`.
Messages are written to Firestore (project `mythadubiz-apps`, europe-west1) under write-only rules (`firestore.rules`); nothing is publicly readable.
