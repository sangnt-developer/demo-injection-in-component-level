# DI Injecion in component level - Angular 9

This project demostrate how to inject a service to many components. Each components having it, we need to inject concrete dependencies for the service.

## Where was the issue raised ?
Link: https://stackoverflow.com/questions/62852327/strategy-pattern-with-angular-and-typescript/62853300

## What is my approach ?
I have AppModule with 3 components (app-root, app-other, child-of-app), 1 service (calculator-service), 3 models (IStrategy, PlusStrategy, MinusStrategy). Then, I declared "app-root" component use MinuStrategy and affected to its child component "child-of-app", and the "app-other" component use PlusStrategy.

## References

https://angular.io/guide/dependency-injection-providers#tree-shakable-providers

## Author
Sang Nguyen - Friendly Software Engineer :D
