# NO.

A fresh reason to say no. This TRMNL plugin displays one deadpan refusal per day. It polls [noasaservice.lol](https://noasaservice.lol/api/get) once per day and displays the JSON `message` field. The template also accepts `reason` from older feeds.

Frame uses red on cream. OG and X use high-contrast monochrome. There are full, half-horizontal, half-vertical, and quadrant views.

## Install as a private plugin

1. Clone or download this repository.
2. From the repository root, run:

   ```sh
   cd src
   zip ../TRMNL_NO.zip settings.yml shared.liquid full.liquid half_horizontal.liquid half_vertical.liquid quadrant.liquid
   ```

3. Open [Private Plugins](https://trmnl.com/plugin_settings?keyname=private_plugin), select **Import new**, and choose `TRMNL_NO.zip`.

The source of the bundled fallback refusals is [No-as-a-Service](https://github.com/hotheadhacker/no-as-a-service).
