# NO.

A fresh reason to say no. This TRMNL plugin displays one deadpan refusal per day. It rotates through 22 short lines curated from [No-as-a-Service](https://github.com/hotheadhacker/no-as-a-service) and uses the UTC date to keep the wording stable across views and refreshes.

Frame uses red on cream. OG and X use high-contrast monochrome. There are full, half-horizontal, half-vertical, and quadrant views.

## Install as a private plugin

1. Clone or download this repository.
2. From the repository root, run:

   ```sh
   cd src
   zip ../TRMNL_NO.zip settings.yml shared.liquid full.liquid half_horizontal.liquid half_vertical.liquid quadrant.liquid
   ```

3. Open [Private Plugins](https://trmnl.com/plugin_settings?keyname=private_plugin), select **Import new**, and choose `TRMNL_NO.zip`.

The bundled text is available under the [upstream MIT license](LICENSE-No-as-a-Service).
