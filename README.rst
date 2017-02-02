
======
Gource
======

OpenGL-based 3D visualisation tool for source control repositories. This formulas helps to generate video from multiple git reposiotires.

Sample pillars
==============

Single gource service

.. code-block:: yaml

    gource:
    client:
      enabled: true
      workspace: /media/majklk/9ECC42B6CC42890B
      video:
        leonardo:
          resolution: 1920x1080
          convert: true
          source:
            core:
              address: https://github.com/django-leonardo/django-leonardo.git
            package_index:
              address: https://github.com/leonardo-modules/leonardo-package-index.git
            blog:
              address: 'git@repo1.robotice.cz:leonardo-modules/leonardo-module-blog.git'

Read more
=========

* links

Documentation and Bugs
======================

To learn how to install and update salt-formulas, consult the documentation
available online at:

    http://salt-formulas.readthedocs.io/

In the unfortunate event that bugs are discovered, they should be reported to
the appropriate issue tracker. Use Github issue tracker for specific salt
formula:

    https://github.com/salt-formulas/salt-formula-gource/issues

For feature requests, bug reports or blueprints affecting entire ecosystem,
use Launchpad salt-formulas project:

    https://launchpad.net/salt-formulas

You can also join salt-formulas-users team and subscribe to mailing list:

    https://launchpad.net/~salt-formulas-users

Developers wishing to work on the salt-formulas projects should always base
their work on master branch and submit pull request against specific formula.

    https://github.com/salt-formulas/salt-formula-gource

Any questions or feedback is always welcome so feel free to join our IRC
channel:

    #salt-formulas @ irc.freenode.net
