# Astodos
 

## Created scaffoling
ng new astodos

## Refer below medium link to create basic skeleton for styles 
https://medium.com/@aaronverones/using-the-7-1-sass-scss-pattern-with-angular-7-bb210c015dcc
https://remote.com/blog/how-to-structure-your-sass-project/

## Adding material ui components

### ng add uses the package manager to download dependencies and invoke installation scripts. We just need to execute:

ng add @angular/material

### for creating material dashboard navigation
https://www.smashingmagazine.com/2020/07/responsive-dashboard-angular-material-ng2-charts-schematics/

### it installs angualr material and theming into the project. Starter components are registered into ng generate and ready to use after using the commands:

#### Below will create a angular module with material dashboard and inject that in the app module

ng add @angular/material
ng generate @schematics/angular:module --name=layouts/default --module=app.module.ts
ng generate @schematics/angular:component --name=layouts/default --module=default --export=true
ng generate @schematics/angular:module --name=shared --module=app.module.ts
ng generate @angular/material:navigation --name=shared/components/sidebar --module=shared --export=true





## Other usefull styles references links
https://medium.com/@luis_sserrano/how-to-structure-your-sass-codebase-78277c683c24
https://medium.com/swlh/how-to-structure-scss-in-an-angular-app-a1b8a759a028
https://medium.com/@stefaniefluin/quick-guide-to-angular-schematics-how-i-built-my-first-schematic-2c81a486dd3a
https://sass-guidelin.es/#architecture
https://github.com/twbs/bootstrap-sass
https://www.drupal.org/node/864912
https://matthewelsom.com/blog/simple-scss-playbook.html
https://github.com/HugoGiraudel/sass-boilerplate
Important Guide to style : https://sass-guidelin.es/#architecture
https://engageinteractive.co.uk/blog/top-10-scss-mixins

fonts: https://fonts.google.com
Bootstrap + Angular Material : https://www.amadousall.com/the-good-parts-of-bootstrap-4-you-are-missing-in-your-angular-material-projects/
best material dashboards: https://flatlogic.com/blog/top-material-design-dashboards/







Open command Prompt git bash



