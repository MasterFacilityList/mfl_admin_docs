Synchronization with regulators
==================================
.. note::
    In order to try out the functions contained in this section, it is assumed that
    one has read the :doc:`01_intro` section and has logged into the system and
    also referred to the implementation guide.
    A copy of the **KMHFL implementation guide** can be downloaded `here`_.

.. _here: http://admin.kmhfl.health.go.ke/#/downloads

The Kenya Master Health Facility List will be communicating with the regulator's system
to determine the facilities that have been registered by the regulators and not yet in the
KMFHL. Such facilities will be pushed to MFL under the ``regulators sync`` section.

The regulator sync tab is located in the facilities side-bar as the screen-shot below shows:

.. figure:: /_images/regulator_sync/01_location.png
    :scale: 100%
    :alt: Location of the regulator sync tab


If facilities have been pushed to KMFHL, the list will look as follows:

.. figure:: /_images/regulator_sync/02_pushed_facilities.png
    :scale: 100%
    :alt: Facilities pushed by regulators

To indicate that a facility is in MFL click on  the ``update`` button on the screen as shown above.

A screen with possible matches such as the one shown below will appear. Go through the list and pick the facility
that matches the one pushed by regulators and click on ``validate``.

.. figure:: /_images/regulator_sync/03_available_actions.png
    :scale: 100%
    :alt: Location of the regulator sync tab


To see further details of the facility ``click on the name of the facility``. If there is need to print the facility details, the print button will be provided in the facilities page.

.. note::
    If the desired facility is not in KMFHL, follow the process of registering a new facility and the come back to this
    screen and follow the steps above again.

.. note::
    On clicking validate, the facility will be be updated with a registration number from the regulators and
    the regulators will be able to get the MFL code of the facility.
    The facility will then disappear from the regulator synchronization screen


The screen will be visible to the national level officers, the CHRIOs and the SCHRIOs.
    #. It is the duty of the SCHRIOs to match the pushed facilities to the ones in MFL.
    #. The CHRIO ensures that the facilities pushed have been resolved(matched to the correct facility in MFL).
    #. The national officers oversee this process
