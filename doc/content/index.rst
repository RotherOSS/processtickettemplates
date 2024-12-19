.. toctree::
    :maxdepth: 2
    :caption: Contents

Sacrifice to Sphinx
===================

Description
===========
The package ProcessTicketTemplates enables standard templates for process management activity dialogs in the agent interface.

System requirements
===================

Framework
---------
OTOBO 11.0.x

Packages
--------
\-

Third-party software
--------------------
\-

Usage
=====
After installation, it is possible to use standard templates in process activity dialog articles in the agent interface.

For the feature to work, it is necessary to create standard templates of type 'ProcessDialog' first in the templates screen in the admin area.

When opening an activity dialog containing an article, a drop down input field will appear, offering all standard templates of type 'Process dialog' and activated for the selected queue (compare figure 3.1).

 .. figure:: images/standard_templates_dropdown.png
    :scale: 50%
    :alt: Drop down input field for standard templates in agent process ticket mask.

    Drop down input field for standard templates in agent process ticket mask.

.. attention::

   The feature will be enabled by default in the agent interface for all activity dialogs containing articles.

Setup
-----
The package introduces the new standard template type 'Process dialog'. Only templates of this type can be used in process activity dialogs. The feature is enabled by default.

Optionally, the feature can be enabled or disabled per activity dialog. To achieve this, please perform the following steps:

#. Navigate to 'Process Management' in the administration area
#. Select the process which you want to edit
#. In the widget 'Available Process Elements' on the left, expand 'Activity Dialogs'
#. Click on the 'Edit' symbol in the row of the activity dialog which you want to edit
#. Click on the 'Edit' symbol next to the entry 'Article' in the list 'Assigned Fields'
#. Check or uncheck the 'Standard Templates' check box as desired
#. Save everything
#. Deploy the process

Configuration Reference
-----------------------

Core::Ticket
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

StandardTemplate::Types
""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""
Defines the list of types for templates.

About
=======

Contact
-------
| Rother OSS GmbH
| Email: hello@otobo.io
| Web: https://otobo.io

Version
-------
Author: |doc-vendor| / Version: |doc-version| / Date of release: |doc-datestamp|
