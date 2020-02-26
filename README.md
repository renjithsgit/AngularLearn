# AngularLearn
To test angular projects
--some angular commands
ng new angular-tour-of-heroes
cd angular-tour-of-heroes
ng serve --open

ng generate component heroes
ng generate service hero
ng generate module app-routing --flat --module=app

npm install angular-in-memory-web-api --save

ng serve
ng test
ng build
ng generate directive highlight
ng generate pipe filter

--
<li *ngFor="let hero of heroes" (click)="onSelect(hero)">
