# bolsalaboral
A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.
A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

# Tools
## Gitflow
Se utilizo la herramiento giflow para manejar las distintas ramas del proyecto.
### Creación de ramas
```
$ git init
$ git-flow init

No branches exist yet. Base branches must be created now.
Branch name for production releases: [master]
Branch name for "next release" development: [develop]

How to name your supporting branch prefixes?
Feature branches? []
Bugfix branches? []
Release branches? []
Hotfix branches? []
Support branches? []
Version tag prefix? []
Hooks and filters directory? [C:/laragon2/www/bolsa/bolsalaboral/.git/hooks]
```

### Gestión de Features
```
$ git-flow feature start H-1
Switched to a new branch 'feature/H-2'

Summary of actions:
- A new branch 'feature/H-1' was created, based on 'develop'
- You are now on branch 'feature/H-2'

Now, start committing on your feature. When done, use:

     git flow feature finish H-2
```
### Listando ramas, features ho
```
$ git branch -av
  develop     b7bd517 Merge branch 'feature-H-1' into develop
* feature/H-2 4604003 Introduciendo el texto definitivo
  master      87ee184 Initial commit
```
```
$ git flow feature
* H-2
```
Documentación : 
- http://aprendegit.com/git-flow-la-rama-develop-y-uso-de-feature-branches/

## GitActions
Tiene como finalidad permitir realizar la CI/CD de nuestro proyecto
### Comandos principales
documentación : 
- https://help.github.com/en/actions/automating-your-workflow-with-github-actions/configuring-a-workflow

## Terraform - Infrastructure as code
El proposito de utilizar Terraform es la de gestionar nuestra infraestructura a partir del codigo
### Comandos principales

- https://www.terraform.io/

