================================
ITA - Comunicazione dati fatture
================================

.. 
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! source digest: sha256:b507ef09398558f6f4c1c1608dc686887a33621ba26b4163073c8711f6b0df8c
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fl10n--italy-lightgray.png?logo=github
    :target: https://github.com/OCA/l10n-italy/tree/12.0/l10n_it_invoices_data_communication
    :alt: OCA/l10n-italy
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/l10n-italy-12-0/l10n-italy-12-0-l10n_it_invoices_data_communication
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runboat-Try%20me-875A7B.png
    :target: https://runboat.odoo-community.org/builds?repo=OCA/l10n-italy&target_branch=12.0
    :alt: Try me on Runboat

|badge1| |badge2| |badge3| |badge4| |badge5|

**Italiano**

Gestione comunicazione dati fatture ed esportazione file XML conforme alle specifiche dell'Agenzia delle Entrate.

Riferimento: https://bit.ly/2N2Rhv8

**English**

Invoices data comunication and XML file export, compliant to specifications of Revenue Agency.

Reference: https://bit.ly/2N2Rhv8

**Table of contents**

.. contents::
   :local:

Known issues / Roadmap
======================

Qualora questo modulo venisse installato in un DB dove ``l10n_it_comunicazione_dati_iva`` è già installato, è necessario eseguire la sequente procedura:

#. Installare ``openupgradelib``
#. Lanciare odoo con il paramentro ``shell``
#. Eseguire i seguenti comandi

    >>> from openupgradelib import openupgrade
    >>> openupgrade.update_module_names(env.cr, [('l10n_it_comunicazione_dati_iva', 'l10n_it_invoices_data_communication'),], merge_modules=False,)
    >>> env.cr.commit()

#. Riavviare odoo
#. Aggiornare ``l10n_it_invoices_data_communication``

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/l10n-italy/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us to smash it by providing a detailed and welcomed
`feedback <https://github.com/OCA/l10n-italy/issues/new?body=module:%20l10n_it_invoices_data_communication%0Aversion:%2012.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* Openforce di Camilli Alessandro

Contributors
~~~~~~~~~~~~

* Alessandro Camilli
* Lorenzo Battistini
* Francesco Apruzzese
* Glauco Prina

Other credits
~~~~~~~~~~~~~

The development of this module has been financially supported by:

* Odoo Italia Network

Maintainers
~~~~~~~~~~~

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

This module is part of the `OCA/l10n-italy <https://github.com/OCA/l10n-italy/tree/12.0/l10n_it_invoices_data_communication>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
