=================
Supported options
=================

The recipe supports the following options:

    build (default: `docs`)
        Specify the build documentation root.

    source (default: `{build-directory}/source`)
        Speficy the source directory of documentation.

    outputs (default: `html`)
        Multiple-line value that defines what kind of output to produce. 
        Can be `doctest`, `html`, `latex`, `pdf` or `epub`.

    script-name (default: name of buildout section)
        The name of the script generated

    interpreter
        Path to python interpreter to use when invoking sphinx-builder.

    extra-paths
        Extra paths to be inserted into sys.path.

    products
        Extra product directories to be extend the Products namespace for
        old-style Zope Products.

    environment
        Point to a buildout part that will be used to define extra
        environment variables in the generated Makefile used to run
        Sphinx. This is useful for Sphinx extensions that can be
        configured that way.
