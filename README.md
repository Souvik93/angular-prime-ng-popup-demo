# angular-prime-ng-popup

[Edit on StackBlitz ⚡️](https://stackblitz.com/edit/angular-prime-ng-popup)


Steps Angular 9 -> 

1. Disable IVY in ts.config file ("enableIvy": false)
2. Do following np install
npm install primeng --save
npm install primeicons --save
3. import {DialogModule} from 'primeng/dialog'; in  app.module.ts  .  Sample Code - https://www.primefaces.org/primeng/showcase/#/dialog
4. Add prime ng cs in index.html file. Link - https://www.primefaces.org/primeng/showcase/#/setup

<link rel="stylesheet" type="text/css" href="/node_modules/primeicons/primeicons.css" />
<link rel="stylesheet" type="text/css" href="/node_modules/primeng/resources/themes/nova-light/theme.css" />
<link rel="stylesheet" type="text/css" href="/node_modules/primeng/resources/primeng.min.css" />

5. Add BrowserAnimationModule in a app.module.ts 
