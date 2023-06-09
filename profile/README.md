# What is Opal?

Opal is a collection of pretty QML components for SailfishOS, building on top of Sailfish's Silica components. It provides ready-made components, examples, snippets, recipes, and resources for building more sailfishy Sailfish apps.

Opal's focus lies on good visual design following Sailfish's [UI principles](https://docs.sailfishos.org/Develop/Apps/UI/#top) as well as good software design, so that other developers of all levels of experience can use it as examples.

See the [main repo](https://github.com/Pretty-SFOS/opal) for details or check out the [gallery app](https://openrepos.net/content/ichthyosaurus/opal-gallery) on OpenRepos or in Jolla's Harbour store.

# Translations

Some Opal modules provide translations that can then be used directly in apps using Opal. This is a step towards a truly multilingual app ecosystem on Sailfish. It would be wonderful if all modules etc. could be translated in as many languages as possible!

Translations are managed using [Weblate](https://hosted.weblate.org/projects/opal). Please prefer this over pull requests (which are still welcome, of course). If you just found a minor problem, you can also
[leave a comment in the forum](https://forum.sailfishos.org/t/opal-qml-components-for-app-development/15801) or [open an issue](https://github.com/Pretty-SFOS/opal/issues/new).

# Known issues

Opal is stable but still very young, so some documentation may be missing or unclear. All contributions are welcome! Don't hesitate to open an issue to clarify any questions you have, so that we can improve the documentation.

Qmllive, the live reloading tool in the Sailfish SDK, does not yet work properly with some modules. This is presumably due to a bug in Qmllive.

Right-to-left support is still lacking in Opal as well as in Sailfish. Please open an issue if any module does not work as intended using a right-to-left layout!
