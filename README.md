## REQUIREMENTS ##

- Drupal 8.x+


-----------------------

## INSTALLATION ##

1. Clone our module or download [latest release](//github.com/UserEngage/userengage-drupal8/archive/master.zip) (recommended)
2. Put `userengage` folder into `your_drupal_root_dir/modules`
3. Your modules directory structure should look like this:

        modules
        └── userengage
            ├── config
            │   ├── install
            │   │   └── userengage.settings.yml
            │   └── schema
            │       └── userengage.settings.yml
            ├── js
            │   └── userengage.js
            ├── src
            │   └── Form
            │       └── SettingsForm.php
            ├── userengage.info.yml
            ├── userengage.install
            ├── userengage.libraries.yml
            ├── userengage.links.menu.yml
            ├── userengage.links.task.yml
            ├── userengage.module
            ├── userengage.permissions.yml
            └── userengage.routing.yml
        └── <other modules>...
        └── <other modules>...
