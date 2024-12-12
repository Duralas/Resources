# Dùralas - Resources

Site statique pour les ressources utilisées par le forum français de JDR [Dùralas].

## 🔨 Scripts utiles

- `bin/dev/start`
  - Initialise l'environnement Docker en créant l'image utilisée par le container.
  - Crée un container en "one-shot" en se basant sur le `entrypoint`.
- `bin/dev/build`
  - Exécute la commande `jekyll build` (par le biais de `bundler`) dans le container Docker.
  - Il est parfois nécessaire de forcer un *build* pour que les modifications soient prises en compte, notamment sur
    la config, le style ou encore le templating dynamique.

[Dùralas]: https://www.lemondededuralas.org/
