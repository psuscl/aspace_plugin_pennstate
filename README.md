# aspace_plugin_pennstate

This plugin performs overrides to staff interface defaults.

* Add "pennstate.png" to assets and set it as `frontend_branding_img` with alt text (configurations set in `frontend/plugin_init.rb`)
* Custom CSS assigned in `theme.css` (declared in `views/layout_head.html.erb`)
* A `public/views/shared` directory that doesn't actually do anything, but that I can't delete without breaking the PUI. Need to test more to figure out why that is so we can get rid of it, but it's here for now.

Tested and confirmed working on ArchivesSpace version 3.5.0.