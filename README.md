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

| Fonctionnalité         | Commande                 | Description                                                                             | Damien ordi perso | Damien ordi ICDC (G11)             | Ben ordi perso | Ben ordi ICDC (G10)       |
|------------------------|--------------------------|-----------------------------------------------------------------------------------------|-------------------|------------------------------------|----------------|---------------------------|
| Installer les packages | `npm install`            | Installe les dépendances du projet (suppression du node_modules avant chaque tentative) | 15.24s            | 1min15s (min 30s et max 2min31)    | 32.42s / 9.43s | 3min30 / 1min31           |
| Construire le projet   | `ng build`               | Lance le build du projet                                                                | 3.81s             | 4.89s                              | 3.53s          | 56.49s / 7.23s avec cache |
| Démarrer le serveur    | `ng serve`               | Lance le serveur de développement local                                                 | 3.35s             | 4.45s                              | 2.91s          | 9.86s                     |
| Lancer les tests unit. | `ng test --no-watch`     | Exécute les tests unitaires avec Vitest                                                 | 5.28s             | 8.66s (min 6s48 et max 16s)        | 2.63s          | 26.23s                    |
| ouverture du terminal  |                          | git bash dans l'IDE                                                                     | instantané        | 5.5s (min1s39 et max 21s50)        | instantané     | 5.76s / 52.72s*           |
| tests cypress          | `npm run cypress:run`    | tests en mode run de cypress (le serveur Angular doit être démarré avant le lancement)  | 8.57s             | 1min03s (min 45s49 et max 2min06s) | 4.13s          | 2min05 / 39s              |

Faire 5 mesures pour chaque cas.

\* Cette mesure est suspecte, il faudrait continuer les tests pour voir si elle se produit pour l'une des raisons suivantes : git non reconnu dans Jetbrais (le terminal est git bash), ou le fait que c'est git bash qui est configuré en terminal par défaut (est-ce que c'est plus rapide avec powershell ?) 
