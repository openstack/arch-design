.. meta::
   :description: This guide targets OpenStack Architects
                 for architectural design
   :keywords: Architecture, OpenStack

===================================
OpenStack Architecture Design Guide
===================================

.. important::

   **This guide is in the process of being updated after a period of
   ownership transition. If you wish to update this guide, propose a
   patch at your own leisure.**

   This guide was last updated as of the Pike release, documenting
   the OpenStack Ocata, Newton, and Mitaka releases. It may
   not apply to EOL releases Kilo and Liberty.

   We advise that you read this at your own discretion when planning
   on your OpenStack cloud. This guide is intended as advice only.

Abstract
~~~~~~~~

The Architecture Design Guide provides information on planning and designing
an OpenStack cloud. It explains core concepts, cloud architecture design
requirements, and the design criteria of key components and services in an
OpenStack cloud. The guide also describes five common cloud use cases.

Before reading this book, we recommend:

* Prior knowledge of cloud architecture and principles.
* Linux and virtualization experience.
* A basic understanding of networking principles and protocols.

For information about deploying and operating OpenStack, see the
`Installation Guides <https://docs.openstack.org/rocky/install/>`_,
`Deployment Guides <https://docs.openstack.org/rocky/deploy/>`_,
and the `OpenStack Operations Guide <https://docs.openstack.org/operations-guide/>`_.

Contents
~~~~~~~~

.. toctree::
   :maxdepth: 2

   common/conventions.rst
   arch-requirements.rst
   design.rst
   use-cases.rst
   common/appendix.rst
