Developer Documentation
***********************

Contributions are in the form of issues, code, documentation are always very welcome. The
following are a set of guidelines to help ensure that contributions can be smoothly 
merged into the existing code base.


Testing
-------

All code contributions should be accompanied by a test. Tests can be placed into the `test`
folder. The list of tests to be run is specified in `karma.conf.js`. To run individual test
files, either uncomment or add them to the ``files:`` section and comment out the ``'test/**/*.+(js|jsx)'``
line.

Documentation
--------------

All added functions should include a jsdoc string for javascript code or a numpy style 
docstring for python code. Changes to the viewconf should be documented in the 
`view config </view_config.html>`_ section of the documentation.

The main documentation repository is: `https://github.com/higlass/higlass-docs <https://github.com/higlass/higlass-docs>`_

Documentation for new features should go into: `https://github.com/higlass/higlass-docs-dev <https://github.com/higlass/higlass-docs-dev>`_

Documentation can also be added to the ``docs`` folder in: `https://github.com/higlass/higlass <https://github.com/higlass/higlass>`_. The
docs folder there should be a git subtree pointing to ``higlass-docs-dev``.

Linting
-------

Code should be run through eslint using the rules in ``.eslintrc``. Not all files currently
abide by all the rules. If fixing code in a non-conforming file, changes to update the style
are appreciated.

Branching
---------

All contributions should be submitted through GitHub as pull requests.

We try to follow all of the `GitFlow branching model <https://datasift.github.io/gitflow/IntroducingGitFlow.html>`_ 
to the extent that we can but exceptions are often made.
