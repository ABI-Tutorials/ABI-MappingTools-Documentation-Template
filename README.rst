
Template for ABI Mapping Tools Documentation
============================================

This GitHub template is for initialising documentation for ABI mapping tools.

Usage
-----

These are instructions on how to make use of this documentation template to add documentation to an existing ABI mapping tools repository, be that a UI or engine repository.
The instructions are given based on using a bash command line environment.

Follow these steps:

#. download this `template <https://github.com/ABI-Tutorials/ABI-MappingTools-Documentation-Template/archive/refs/heads/main.zip>`_ as a zip archive.
#. make the current directory the root directory of the repository that the documentation template is to be applied to::

    cd <root-directory-of-repository>

#. unzip the contents of the template downloaded above::

    unzip -d docs -j <absolute-path-to-download-directory>/ABI-MappingTools-Documentation-Template-main.zip

#. remove template README.rst::

    rm docs/README.rst

#. remove template hidden file .gitignore::

    rm docs/.gitignore

#. edit the docs/index.rst file, and replace the 'XXXXXXXX' text with an appropriate name for the project.
#. edit the docs/conf.py file, and replace the 'XXXXXXXX' text with an appropriate name for the project, replace 'YYYY' with the copyright year, and possibly change the author.
#. stage and commit the new documentation files::

    git add docs/
    git commit -m "Add initial documentation."

#. push the changes to a remote repository::

    git push

