.. index::
   single: Forms; Fields; password

``password`` Field Type
=======================

The ``password`` field renders an input password text box.

============  ======
Rendered as   ``input`` ``password`` field
Options       ``always_empty``, ``max_length``, ``required``, ``label``, ``read_only``, ``trim``, ``error_bubbling``
Parent type   :doc:`text</reference/forms/types/text>`
Class         :class:`Symfony\\Component\\Form\\Type\\PasswordType`
============  ======

Options
-------

* ``always_empty`` [type: Boolean, default: true]
    If set to true, the field will *always* render blank, even if the corresponding
    field has a value. When set to false, the password field will be rendered
    with the ``value`` attribute set to its true value.
    
    Put simply, if for some reason you want to render your password field
    *with* the password value already entered into the box, set this to false.

.. include:: /reference/forms/types/options/max_length.rst.inc

.. include:: /reference/forms/types/options/required.rst.inc

.. include:: /reference/forms/types/options/label.rst.inc

.. include:: /reference/forms/types/options/read_only.rst.inc

.. include:: /reference/forms/types/options/trim.rst.inc

.. include:: /reference/forms/types/options/error_bubbling.rst.inc