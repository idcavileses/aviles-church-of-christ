# Avilés Church of Christ / Iglesia de Cristo en Avilés

Spanish and English website for the congregation in Avilés, Asturias, Spain.

## Visit and contact

- Meeting room at Centro Empresarial La Curtidora.
- Camino La Curtidora, 1, 33402 Avilés, Asturias, Spain.
- Sundays, 12:00–13:00 (Avilés local time).
- Telephone: +34 602 59 45 41.
- Email: idcaviles.es@gmail.com.

## Website files

This is a static website: index.html, app.js, styles.css, research.html, credits.html and the assets folder. No build step or backend is required. Keep the Spanish text in index.html and the English translations in app.js synchronized.

The congregation identifies with the Way of Jesus Christ and the first-century church recorded in the New Testament. Acts 24:14 appears with the welcome statement.

Photo authors and licenses are listed in credits.html. The regional heritage church photo is not the congregation's meeting place.

Domain registration, DNS and GitHub Pages settings are managed separately. Uploading these files does not confirm a domain purchase or activate a custom domain.

## Search and language pages

Canonical production: https://idc-aviles-asturias.org/
Spanish HTML is at the root; `/en/` serves pre-rendered English. After editing root HTML or translation strings in `app.js`, run `python build_locales.py` (Python 3 + beautifulsoup4 and Node.js), then commit generated `en/` files. No build is required on GitHub Pages. Keep canonical, hreflang and sitemap URLs on the production origin. No passwords belong in this public repository.
