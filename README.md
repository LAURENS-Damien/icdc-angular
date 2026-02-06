# IcdcAngular

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 21.0.2.

## Development server

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

## Code scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

## Building

To build the project run:

```bash
ng build
```

This will compile your project and store the build artifacts in the `dist/` directory. By default, the production build optimizes your application for performance and speed.

## Running unit tests

To execute unit tests with the [Vitest](https://vitest.dev/) test runner, use the following command:

```bash
ng test
```

## Running end-to-end tests

For end-to-end (e2e) testing, run:

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.

## Mesures collectés

| Fonctionnalité         | Commande                 | Description                                                                             | Damien ordi perso | Damien ordi ICDC | Ben ordi perso | Ben ordi ICDC |
|------------------------|--------------------------|-----------------------------------------------------------------------------------------|-------------------|------------------|----------------|---------------|
| Installer les packages | `npm install`            | Installe les dépendances du projet (suppression du node_modules avant chaque tentative) | 15.24s            |                  |                |               |
| Construire le projet   | `ng build`               | Lance le build du projet                                                                | 3.81s             |                  |                |               |
| Démarrer le serveur    | `ng serve`               | Lance le serveur de développement local                                                 | 3.35s             |                  |                |               |
| Lancer les tests unit. | `ng test --no-watch`     | Exécute les tests unitaires avec Vitest                                                 | 5.28s             |                  |                |               |
| ouverture du terminal  |                          | git bash dans l'IDE                                                                     | instantané        |                  |                |               |
| tests cypress          | `npm run cypress:run`    | tests en mode run de cypress (le serveur Angular doit être démarré avant le lancement)  | 8.57s             |                  |                |               |

Faire 5 mesures pour chaque cas.
