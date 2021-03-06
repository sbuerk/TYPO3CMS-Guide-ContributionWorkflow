.. include:: ../Includes.txt

.. _introduction:

============
Introduction
============


.. _overview:

Overview
========

This guide will provide you with everything you need to become a TYPO3
contributor.

.. _getting-started-video:

Getting started video
=====================

Here is a video to get you started. Just make sure you come back here, 
to read the rest of the guide afterwards. 

.. youtube:: gN8BVSBlgfU

.. _intended-audience:

Intended audience
=================

This document is intended to help developers who wish to contribute to the TYPO3 CMS source code. It also
provides useful guidance for people who are reporting bugs and testing patches. If you are not a developer,
you can still post a bug report and help in this area is always appreciated.

.. _how-to-read-this-document:

How to read this document
=========================

If open-source development, git, composer, developing web applications, using Gerrit etc. is nothing new for you, you
may not have to read this document. Make sure that you **at least** look at the following sections as they are required for TYPO3 development:

* :ref:`Contribution workflow <t3contrib:workflow-explained>`
* :ref:`Setting-up-your-Git-environment`
* :ref:`commitmessage`

You must setup a specific git hook for the commit message, for example.

.. _whats-new-in-this-document:

What's new in this document
===========================

If you have already read this manual but want to see what's new, check these
new chapters:

* :ref:`cheat-sheet-git` (May 28, 2018)
* :ref:`settting-up-typo3-with-ddev` (Mar 13, 2018)
* :ref:`phpstorm-setup` (Mar 12, 2018)
* :ref:`phpstorm-setup-xdebug` (Mar 12, 2018)
* :ref:`testing` (Mar 10, 2018)
* This :ref:`introduction` chapter (Feb 28, 2018)


.. _recommended-reading:

Further reading
===========================

In order to efficiently contribute to the TYPO3 core, you should familiarize yourself with its basic concepts. Helpful
reading for this can be found here:

* :ref:`TYPO3 Core API <t3coreapi:start>`

You will need to format your Source Code according to the TYPO3 Coding Guidelines:

* :ref:`TYPO3 Coding Guidelines <t3coreapi:cgl>`


.. _slack-intro:

Slack
=====


If you wish to contribute, joining the `TYPO3 slack workspace <https://typo3.slack.com>`__ is 
recommended as it is the projects chosen platform for communication. In order to join the slack workspace, you
must create a `typo3.org <https://my.typo3.org/index.php?id=2>`__ account and then  `Register 
for TYPO3's Slack Platform <https://my.typo3.org/index.php?id=35>`__. On that page, you will also find 
information about recomended channels.

.. hint::
   You will need a typo3.org account for contribution anyway in order to use Forge and Gerrit.

Slack channels
--------------

* **#typo3-cms-coredev** is your channel of choice for core development 
* **#typo3-cms** is for general support issues
* **#random** if you are not sure which channel to use or have a general question


.. hint::
   You do not need to ask for permission when asking a question. Ask your question directly to the channel and 
   await a response.


As always, make sure to read the `Code of conduct <https://typo3.org/community/code-of-conduct/>`__.


.. _botty:

Botty on Slack
~~~~~~~~~~~~~~

Also checkout the help page on `"Botty" <https://wiki.typo3.org/T3Bot>`__, the TYPO3 slack bot. We will show you
some of its commands later in this manual.


.. hint::

   You cannot use Botty in your private channel or in a direct messaging channel with someone else. Botty will
   only be available in a public channel, to which it has been invited (which is the case in #typo3-cms-coredev).


.. _other-resources-for-contribution:

Other ways to contribute
========================

Besides developing for the TYPO3 core, there are many other ways to contribute and help the TYPO3 community.

You can find general information here:

* General information about the various `Teams & Committes <https://typo3.org/teams-committees/>`__
* General information on how you can `Participate <https://typo3.org/participate/>`__

Some examples of areas where you can contribute are:

* `TYPO3 documentation <https://typo3.org/teams-committees/documentation/>`__:
  You can get in touch with the TYPO3 documentation team in the
  #typo3-documentation channel on :ref:`slack-intro` or just
  use the "Edit me on github" button which is located on the top right of every documentation page.
* `Translation <https://forge.typo3.org/projects/team-translation>`__
* A large number of extensions available for TYPO3 are hosted on github
  and "issues" and "pull requests" are welcome. If you are interested
  in helping with an extension, check out where the source is located
  by visiting the `TYPO3 Extension Repository <https://extensions.typo3.org/>`__
  (TER). In the detail view for each extension, you will usually find
  a "Take a look in the code" link, which will link directly to
  the source code repository.


   .. image:: _assets/ter_detail.png


.. _general-recommendations-contributions:

General recommendations for contribution
========================================

In general: If you wish to make a contribution, familiarize yourself with the basics and general conventions used. In
Open-source projects it is usually mandatory that your code must follow the general coding guidelines for the
project and that your commit messages either follow general recommendations for commit messages or use specific
constraints for the project.

Some github projects have a contribution guide available, the TYPO3 CMS project has this guide.

If in doubt, ask on slack. Other contributors will be happy to help you.


.. Credits
.. ==========
.. To be filled later or removed ...


.. What's new
.. ==========
.. To be filled later or removed ...


Feedback
========

If you find a bug in this manual, please be so kind as to check the
online version on https://docs.typo3.org/typo3cms/ContributionWorkflowGuide/.
From there you can hit the "Edit me on GitHub" button in the top right corner
and submit a pull request via GitHub. Alternatively you can just report an `issue
on Github <https://github.com/TYPO3-Documentation/TYPO3CMS-Guide-ContributionWorkflow/issues>`__.

Maintaining high quality documentation requires time and effort
and the TYPO3 Documentation Team always appreciates support.
If you want to support us, please join the slack channel `#typo3-documentation
<https://typo3.slack.com/messages/C028JEPJL>`__.

Visit https://forger.typo3.org/slack to gain access to Slack.

Have a look at the contribution page for more information about how to contribute to the TYPO3
documentation: https://docs.typo3.org/Contribute/Index.html

And finally, as a last resort, you can get in touch with the documentation team `by mail <documentation@typo3.org>`_.
