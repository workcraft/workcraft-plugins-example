# workcraft-plugins-example

![Repo size](https://img.shields.io/github/repo-size/workcraft/workcraft-plugins-example.svg)

This is a collection of plugins for [Workcraft](https://workcraft.org/)
that are used as examples in the
[plugin development tutorial](https://workcraft.org/devel/plugin/start).
Note that each plugin is included as a submodule and, if necessary, can
be used independently.

Suggested usage:

1. If has not been done yet, setup Workcraft development directory ``workcraft``
   as instructed in [workcraft](https://github.com/workcraft/workcraft) repo.

2. Clone example plugins repo with all submodules in ``workcraft-plugins-example``
   at the same level of hierarchy as ``workcraft`` directory:
   ```
   git clone --recursive https://github.com/workcraft/workcraft-plugins-example.git
    ```

3. In ``workcraft`` directory create symbolic links to the specific example
   plugins that you plan to use, e.g.:
    ````
    ln -s ../workcraft-plugins-example/_PetriPlugin
    ````

Note that ``_`` prefix of the plugin directory prevents it from propagating to
[workcraft](https://github.com/workcraft/workcraft) repo and to Workcraft
binary distribution.
