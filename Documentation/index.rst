.. The Linux Kernel documentation master file, created by
   sphinx-quickstart on Fri Feb 12 13:51:46 2016.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

The Linux Kernel documentation
==============================

This is the top level of the kernel's documentation tree.  Kernel
documentation, like the kernel itself, is very much a work in progress;
that is especially true as we work to integrate our many scattered
documents into a coherent whole.  Please note that improvements to the
documentation are welcome; join the linux-doc list at vger.kernel.org if
you want to help out.

User-oriented documentation
---------------------------

The following manuals are written for *users* of the kernel — those who are
trying to get it to work optimally on a given system.

.. toctree::
   :maxdepth: 2

   admin-guide/index

Application-developer documentation
-----------------------------------

The user-space API manual gathers together documents describing aspects of
the kernel interface as seen by application developers.

.. toctree::
   :maxdepth: 2

   userspace-api/index	      


Introduction to kernel development
----------------------------------

These manuals contain overall information about how to develop the kernel.
The kernel community is quite large, with thousands of developers
contributing over the course of a year.  As with any large community,
knowing how things are done will make the process of getting your changes
merged much easier.

.. toctree::
   :maxdepth: 2

   process/index
   dev-tools/index
   doc-guide/index
   kernel-hacking/index

Kernel API documentation
------------------------

These books get into the details of how specific kernel subsystems work
from the point of view of a kernel developer.  Much of the information here
is taken directly from the kernel source, with supplemental material added
as needed (or at least as we managed to add it — probably *not* all that is
needed).

.. toctree::
   :maxdepth: 2

   driver-api/index
   core-api/index
   media/index
   networking/index
   input/index
   gpu/index
   security/index
   sound/index
   crypto/index
   filesystems/index

Architecture-specific documentation
-----------------------------------

These books provide programming details about architecture-specific
implementation.

.. toctree::
   :maxdepth: 2

   sh/index
   x86/index

Korean translations
-------------------

.. toctree::
   :maxdepth: 1

   translations/ko_KR/index

Chinese translations
--------------------

.. toctree::
   :maxdepth: 1

   translations/zh_CN/index

Japanese translations
---------------------

.. toctree::
   :maxdepth: 1

   translations/ja_JP/index

This section describes CPU vulnerabilities and their mitigations.

.. toctree::
   :maxdepth: 1

   hw-vuln/index

Architecture-specific documentation
-----------------------------------

These books provide programming details about architecture-specific
implementation.

.. toctree::
   :maxdepth: 2

   x86/index

Indices and tables
==================

* :ref:`genindex`
