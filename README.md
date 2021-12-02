# AngularTourOfHeroes

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.0.2.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

## Summary

- You created the initial application structure using the Angular CLI.
- You learned that Angular components display data.
- You used the double curly braces of interpolation to display the application title.
- You used the CLI to create a second HeroesComponent.
- You displayed the HeroesComponent by adding it to the AppComponent shell.
- You applied the UppercasePipe to format the name.
- You used two-way data binding with the ngModel directive.
- You learned about the AppModule.
- You imported the FormsModule in the AppModule so that Angular would recognize and apply the ngModel directive.
- You learned the importance of declaring components in the AppModule and appreciated that the CLI declared it for you.
- The Tour of Heroes application displays a list of heroes with a detail view.
- The user can select a hero and see that hero's details.
- You used \*ngFor to display a list.
- You used \*ngIf to conditionally include or exclude a block of HTML.
- You can toggle a CSS style class with a class binding.
- You created a separate, reusable HeroDetailComponent.
- You used a property binding to give the parent HeroesComponent control over the child HeroDetailComponent.
- You used the @Input decorator to make the hero property available for binding by the external HeroesComponent.
- You refactored data access to the HeroService class.
- You registered the HeroService as the provider of its service at the root level so that it can be injected anywhere in the application.
- You used Angular Dependency Injection to inject it into a component.
- You gave the HeroService get data method an asynchronous signature.
- You discovered Observable and the RxJS Observable library.
- You used RxJS of() to return an observable of mock heroes (Observable<Hero[]>).
  The component's ngOnInit lifecycle hook calls the HeroService method, not the constructor.
- You created a MessageService for loosely-coupled communication between classes.
- The HeroService injected into a component is created with another injected service, MessageService.
