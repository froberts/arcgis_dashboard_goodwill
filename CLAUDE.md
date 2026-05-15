# GeoTrace Dashboard - Goodwill

## Auto-Start Dev Server

**IMPORTANT**: When this project is opened, automatically start the dev server in the background:

```bash
cd /c/data/aiclass/arcgis_dashboard_goodwill && python server.py
```

The server runs on **https://localhost:8443**

## Project Overview

ArcGIS WebMap dashboard for tracking e-waste/recycling data from Goodwill stores.

- **Portal**: geotracesystems.maps.arcgis.com
- **WebMap ID**: 0d0974a1106d4f4fbaf33b45b4c054d4
- **OAuth App ID**: AsPDdwI8hCgoXNeX

## Key Files

| File | Purpose |
|------|---------|
| `index.html` | Main dashboard UI |
| `server.py` | Local HTTPS dev server (port 8443) |
| `server_prod.py` | Production HTTP server for Railway |
| `oauth-callback.html` | OAuth redirect handler |

## Features

- OAuth authentication with ArcGIS Online
- Time slider for date filtering
- Stats panel (total weight)
- Bar chart (weight by item type)
- Data table with sorting, CSV export, row selection
- Map highlighting on row click
