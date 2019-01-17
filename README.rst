RapidSMS
========

RapidSMS is a free and open source framework for building interactive SMS
applications, which integrates tightly with `Django`_ to provide a rich
reporting interface. It was created by the Innovation Team at `UNICEF`_, and is
under development by `the RapidSMS Team`_. 

Visit `the parent repo <https://github.com/rapidsms/rapidsms>`_ to learn about installation, 
licensing, and contributing. Go to `Read The Docs <http://readthedocs.org/docs/rapidsms/>`_ to learn more. 

DataMade forked and customized RapidSMS to meet the requirements of 
`Coordinated Entry Screening (CES) <https://github.com/datamade/coordinated-entry-screening>`_, a tool to help
people experiencing homelessness find resources. 

.. _Django: http://djangoproject.com
.. _UNICEF: http://unicef.org
.. _the RapidSMS Team: http://github.com/rapidsms

Customizations
-------------
This fork includes a few minor, but meaningful adjustments. These include:

* `making RapidSMS compatible <https://github.com/datamade/rapidsms/pull/1>`_ with Django 1.11
* `adding logic <https://github.com/datamade/rapidsms/pull/3>`_ that accounts for `connections <https://github.com/datamade/rapidsms/blob/master/rapidsms/models.py#L159>`_ that may have a hashed identity
