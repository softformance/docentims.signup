.. This README is meant for consumption by humans and pypi. Pypi can render rst files so please do not use Sphinx features.
   If you want to learn more about writing documentation, please check out: http://docs.plone.org/about/documentation_styleguide_addons.html
   This text does not appear on pypi or github. It is a comment.

==============================================================================
docentims.signup
==============================================================================

This is Plone 5 CMS addon that extends Registration form with few group related fields.

Features
--------

- Separate control panel /@@docentims-settings that allows you to select and enter field vocabularies
- "I am" field that allows anonymous to select group he/her belongs to
- "I am associated with" field to pick organization from


Examples
--------

This add-on can be seen in action at the following sites:
- Is there a page on the internet where everybody can see the features?


Documentation
-------------

Full documentation for end users can be found in the "docs" folder, and is also available online at http://docs.plone.org/foo/bar


Translations
------------

This product has been translated into

- Klingon (thanks, K'Plai)


Installation
------------

Install docentims.signup by adding it to your buildout::

    [buildout]

    ...

    eggs =
        docentims.signup


and then running ``bin/buildout``

Then install addon via Plone Addon Control Panel.


Contribute
----------

- Issue Tracker: https://github.com/collective/docentims.signup/issues
- Source Code: https://github.com/collective/docentims.signup
- Documentation: https://docs.plone.org/foo/bar


Support
-------

If you are having issues, please let us know.
We have a mailing list located at: project@example.com


License
-------

The project is licensed under the GPLv2.
