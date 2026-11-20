# ZhiftCRM Form — releases

Release channel for the **ZhiftCRM Form** WordPress plugin (formerly Pangea CRM Forms).

- Each release is tagged `zhiftcrm-form-v<version>` and carries one asset, `zhiftcrm-form-<version>.zip`.
- Installed copies check this repository's Releases for updates and show them in WP Admin → Plugins.
- `assets/` holds the icon and banner shown in the plugin's "View details" screen.

**Installing:** download the latest `zhiftcrm-form-<version>.zip` from Releases and upload it in WP Admin → Plugins → Add New → Upload Plugin, then activate. On activation it copies the settings from Pangea CRM Forms and removes that plugin; existing `[pangea_form]` shortcodes keep working.

**Option groups (2.1.9 and later):** a form can offer several sets of choices at once — pick one from some, as many as you like from others — with each choice priced from its own product, so the order arrives as one line per selection. The plugin draws them only when the ZhiftCRM form it is given is set up to use them. On every other form it behaves exactly as before, so updating changes nothing you can see until a form is built that way.

Source is private (crm360). Releases are published by hand; nothing here is built automatically.
