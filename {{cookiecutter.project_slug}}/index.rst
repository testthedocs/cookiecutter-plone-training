{{ '=' * cookiecutter.project_name|length }}
{{cookiecutter.project_name}}
{{ '=' * cookiecutter.project_name|length }}

:About: {{cookiecutter.short_description}}
:Level: {{cookiecutter.training_level}}

.. note::

   This training is meant to be used in a course or read and worked through by an individual user.
   Instructors should note that this makes it more discursive than it would be if it was only meant for classroom use.

   Many sections may be zipped through in a class, noting to students that the full text is available for review.

..  toctree::
    :hidden:
    :maxdepth: 3
    :caption: {{cookiecutter.project_name}}

    intro

..  toctree::
    :hidden:
    :maxdepth: 3
    :caption: Plone Trainings

    ../about/index
    ../about/glossary

