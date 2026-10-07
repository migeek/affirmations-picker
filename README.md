# MyAffirmations — Google Doc picker

A single static page used by the MyAffirmations app to let you choose a Google Doc
to import (Google Picker). The app opens it with a short-lived access token in the
URL fragment; the page hands the chosen Doc back to the app. No data is stored.

The API key here is restricted to the Google Picker API and this site's origin.
Source of truth: `web/picker/index.html` in the (private) app repo.
