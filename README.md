# NO.

A fresh reason to say no. This TRMNL plugin displays one deadpan refusal per day. It polls the [No-as-a-Service community mirror](https://naas.api.nixie.online/no) once per day and uses its JSON `reason` field. The mirror was shared in the upstream [service outage report](https://github.com/hotheadhacker/no-as-a-service/issues/112).

Frame uses red on cream. OG and X use high-contrast monochrome. There are full, half-horizontal, half-vertical, and quadrant views.

## Install as a private plugin

1. Clone or download this repository.
2. From the repository root, run:

   ```sh
   cd src
   zip ../TRMNL_NO.zip settings.yml shared.liquid full.liquid half_horizontal.liquid half_vertical.liquid quadrant.liquid
   ```

3. Open [Private Plugins](https://trmnl.com/plugin_settings?keyname=private_plugin), select **Import new**, and choose `TRMNL_NO.zip`.

The source for the original service is [No-as-a-Service](https://github.com/hotheadhacker/no-as-a-service).
