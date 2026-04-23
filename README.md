There are two code style files within `codestyles`. The directory is intended
to be a drop-in replacement within the `.idea` folder of a project, which will
expose both code styles as selectable schemes.

The Project.xml code style is intended to be added to a project in IntelliJ,
living in `<project>/.idea/codestyles` as described above.

The Stellar.xml code style is intended to be an IDE-level code style within
IntelliJ but can also be used as a project style by placing it in the same
location described above. This code style has not well tested ever since
IntelliJ stopped supporting the "codestyle-from-remote-source" functionality.
Additionally, it originally came from IntelliJ Ultimate.
