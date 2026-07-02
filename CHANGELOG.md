# Changelog

## 0.1.0

- Ajoute `Velt\Ui\Providers\UiServiceProvider` pour l'integration avec `velt/kernel`.
- Enregistre `ViewFactory`, `WebRenderer` et `JsonRenderer` dans le container kernel.
- Expose les alias container `view`, `ui.renderer.web` et `ui.renderer.json`.
- Utilise `velt/kernel` comme dependance Composer explicite.
- Documente la convention des vues d'exemple en francais avec fichiers `*.velt.php`, comme `login.velt.php`.
