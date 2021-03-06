.. _Developing Course Subsections:

###################################
Developing Course Subsections
###################################

To develop subsections in your course, you must first understand the
following topics.

.. contents::
  :local:
  :depth: 2

****************************
What Is a Subsection?
****************************

Sections are divided into subsections, which in turn contain one or more units.
A subsection may represent a topic in your course, or another organizing
principle. Subsections are sometimes called "lessons" or they might represent a
week's worth of material.

***********************************
Viewing Subsections in the Outline
***********************************

The following example shows three subsections in a section, all collapsed, in
the course outline.

.. image:: ../../../shared/images/subsections.png
 :alt: Three collapsed subsections in the outline.

*********************************
The Learner View of a Subsection
*********************************

Learners see subsections on the **Course** page, listed beneath the
expanded section. In the following example, two subsections are circled, and
the first one is open in the LMS.

.. image:: ../../../shared/images/subsections_student.png
 :width: 500
 :alt: The learner view of the outline.

************************************************
Subsections and Visibility to Learners
************************************************

Learners cannot see any content in a subsection until you schedule a release
date, and that release date has passed.

If a subsection's release date has passed, learners can see content in the
subsection if the following conditions are met.

* The release date of the parent section has passed.
* The units have been published.
* The subsection or the units are not hidden from learners.

To control whether learners have access to the subsection and its units after
a subsection's release date, you can apply various visibility settings.

By default, the subsection and its units are available to learners, except for
any units that you have explicitly hidden from learners.

You can also choose to entirely hide a subsection so that the subsection and its
units are not visible to learners at all in the course navigation, or you can
hide the contents of a subsection after the subsection due date has passed. For
more information about subsection visibility settings, see :ref:`Hide a
Subsection from Students`.


.. note:: Release dates and times that you set are in Coordinated Universal Time
   (UTC). You might want to verify that you have specified the time that you
   intend by using a time zone converter such as `Time and Date Time Zone
   Converter <http://www.timeanddate.com/worldclock/converter.html>`_.

   Learners who have specified a time zone in their account settings see
   course dates and times converted to their specified time zone. Learners who
   have not specified a time zone in their account settings see course dates
   and times in UTC.


************************************************
Release Statuses of Subsections
************************************************

As a course author, you control the release status of subsections. For the
content of a subsection to be visible to learners, the subsection must be
released. See the following topics for more information about the possible
release statuses of subsections.

* `Scheduled with the Section`_
* `Unscheduled`_
* `Scheduled Later than the Section`_
* `Scheduled with Unpublished Changes`_
* `Released with Unpublished Changes`_
* `Released`_

==========================
Scheduled with the Section
==========================

When you create a subsection, it is set by default to release on the same date
and time as the section it is in. Therefore, published content in the
subsection is visible to learners at the date and time the section is released.

The following example shows how a subsection in the Scheduled with Section
state displays in the outline, summarized with a green bar.

.. image:: ../../../shared/images/subsection-scheduled.png
 :alt: A subsection scheduled to release with the section.

You can change the release date for a subsection to be different from the
section it is in. For more information, see :ref:`Set a Subsection Release
Date`.

========================
Unscheduled
========================

If the parent section is unscheduled, when you create a new subsection it
will also be unscheduled.

Regardless of the publishing status of units within the subsection, no content
in an unscheduled subsection is visible to learners.

The following example shows how an unscheduled subsection displays in the
outline, summarized with a gray bar.

.. image:: ../../../shared/images/subsection-unscheduled.png
 :alt: An unscheduled subsection.

Content in the subsection is not visible to learners until you set a release
date and the date passes.

===================================
Scheduled Later than the Section
===================================

You can set a subsection to release on a date after the section releases.

Content in a subsection that is scheduled for release on a future date is not
visible to learners, even if some or all of the units in the subsection are
published.

The following example shows the way that a subsection that will release after
its parent subsection displays in the course outline.

.. image:: ../../../shared/images/subsection-scheduled-different.png
 :alt: A subsection scheduled to release later than the section.

The scheduled date must pass for the subsection to be visible to learners.

==================================
Scheduled with Unpublished Changes
==================================

You can make changes to a published unit before its parent subsection
is released.

In this situation, when the release date for the subsection passes, the last
published version of units within the subsection are made visible to learners.
The changes in units are not visible to learners until you publish them.

The following example shows how a scheduled subsection with unpublished changes
displays in the outline, summarized with a yellow bar.

.. image:: ../../../shared/images/section-scheduled-with-changes.png
 :alt: A scheduled subsection with unpublished changes.

==================================
Released with Unpublished Changes
==================================

If you modify a unit within a released subsection, those modifications are not
visible to students until you publish them.

The following example shows how a released section that has unpublished changes
displays in the outline, summarized with a yellow bar.

.. image:: ../../../shared/images/section-released-with-changes.png
 :alt: A released subsection with unpublished changes.

===========================
Released
===========================

A subsection that is released is visible to learners; however, learners see
only units within the subsection that are published.

The following example shows how a released subsection displays in the
outline, summarized with a blue bar.

.. image:: ../../../shared/images/subsection-released.png
 :alt: A released subsection.

===========================
Staff Only Content
===========================

A subsection can contain a unit that is hidden from learners and available to
members of the course team only. That unit is not visible to learners, even if
the subsection has been released.

The following example shows how a section with a subsection that contains a
unit with staff only content displays in the outline, summarized with a black
bar.

.. image:: ../../../shared/images/section-hidden-unit.png
 :alt: A subsection with a hidden unit.

.. _Create a Subsection:

****************************
Create a Subsection
****************************

To create a new subsection, follow these steps.

#. In the outline, expand the section in which you want to create a new
   subsection.
#. Select **New Subsection** at the bottom of the expanded section. A new
   subsection appears at the end of the section, with the subsection name
   selected.
#. Enter the name for the new subsection. A descriptive name can help learners
   locate content in the course. It can also help you select content when you
   analyze performance in edX Insights.
#. :ref:`Add units<Create a Unit>` to the new subsection as needed.

It is recommended that you :ref:`test course content <Testing Your Course
Content>` as you create new subsections.

********************************
Change a Subsection Name
********************************

To change a subsection name, select the **Edit** icon next to the subsection
name. The name field becomes editable. Enter the new name, and then tab or
click outside of the field to save the name.

.. _Set a Subsection Release Date:

********************************
Set a Subsection Release Date
********************************

To set the subsection release date, follow these steps.

#. Select the **Configure** icon in the subsection box.

   .. image:: ../../../shared/images/subsections-settings-icon.png
    :alt: A subsection in the course outline with the configure icon indicated.
    :width: 600

   The **Settings** dialog box opens.

#. Enter the release date and time for the subsection.

   .. note:: The time that you set is in Coordinated Universal Time (UTC). You
      might want to verify that you have specified the time that you intend by
      using a time zone converter such as `Time and Date Time Zone Converter <http://www.timeanddate.com/worldclock/converter.html>`_

      Learners who have specified a time zone in their account settings see
      course dates and times converted to their local time zone. Learners who
      have not specified a time zone in their account settings see course dates
      and times in UTC.

#. Select **Save**.

For more information, see :ref:`Release Dates`.

.. _Set the Assignment Type and Due Date for a Subsection:

********************************************************
Set the Assignment Type and Due Date for a Subsection
********************************************************

You set the assignment type for problems at the subsection level.

When you set the assignment type for a subsection, all problems within the
subsection are graded and weighted as a single type. For example, if you
designate the assignment type for a subsection as **Homework**, then all
problem types in that subsection are graded as homework.

.. note:: Unlike other problem types, ORA assignments are not governed by the
   subsection due date. Due dates for each ORA assignment are set in the
   assignment's settings. For details, see :ref:`PA Specify Name and Dates`.

To set the assignment type and due date for a subsection, follow these steps.

#. Select the **Configure** icon in the subsection box.

   The **Settings** dialog box opens.

#. In the **Grading** section, select the assignment type for this subsection
   in the **Grade as** field.

#. Enter or select a due date and time for problems in this subsection.

   .. note:: The time that you set is in Coordinated Universal Time (UTC). You
      might want to verify that you have specified the time that you intend by
      using a time zone converter such as `Time and Date Time Zone Converter <http://www.timeanddate.com/worldclock/converter.html>`_

       Learners who have specified a time zone in their account settings see
       course dates and times converted to their local time zone. Learners who
       have not specified a time zone in their account settings see course dates
       and times in UTC.

#. Optionally, for a course that has the timed exam feature enabled, select the
   **Advanced** tab to set the subsection to be :ref:`timed<Timed Exams>`.

#. Select **Save**.

For more information, see :ref:`Grading Index`.

.. _Publish all Units in a Subsection:

**********************************
Publish All Units in a Subsection
**********************************

To publish all new and changed units in a subsection, select the **Publish**
icon in the box for the subsection.

.. image:: ../../../shared/images/outline-publish-icon-subsection.png
 :alt: Publishing icon for a subsection

.. note::
 The **Publish** icon only appears when there is new or changed content within
 the subsection.

See :ref:`Unit Publishing Status` for information about statuses and visibility
to learners.

.. _Hide a Subsection from Students:

***********************************
Hiding a Subsection from Learners
***********************************

You can hide a subsection from learners in the following ways.

* :ref:`Entirely hide the subsection <Entirely Hide a Subsection>` so that it
  does not appear in course navigation. Subsections that are hidden in this
  way are not included when grades are calculated.

* :ref:`Prevent learners from accessing <Hide a Subsection After its Due
  Date>` a subsection's contents after its due date has passed, but keep the
  subsection visible in course navigation. Subsections that are hidden in
  this way remain included when grades are calculated.

For more information, see :ref:`Content Hidden from Students`.


.. _Entirely Hide a Subsection:

========================================
Entirely Hide a Subsection from Learners
========================================

You can completely hide a subsection and its content from learners, regardless
of the status of units within the section. Subsections hidden in this way are
not shown in the course navigation, and are not included when grades are
calculated.

To entirely hide a subsection from learners, follow these steps.

#. Select the **Configure** icon in the subsection box.

   .. image:: ../../../shared/images/subsections-settings-icon.png
     :alt: A subsection in the course outline with the configure icon
      indicated.
     :width: 600

   The **Subsection Settings** dialog box opens.

#. In the **Subsection Visibility** section, select **Hide entire subsection**.

#. Select **Save**.

None of the content in the subsection is visible to learners. In the course
outline, the subsection is shown with a lock icon, indicating that it is
available only to course staff.

   .. image:: ../../../shared/images/subsection-hidden.png
     :alt: A subsection in the course outline with the lock icon
      indicating that it is available only to staff.
     :width: 400

To make the subsection visible to learners, repeat these steps and select
**Show entire subsection**.

.. warning::  When you make a previously hidden subsection visible, not all
   content in the subsection is necessarily made visible to learners. Units
   that were explicitly hidden from learners remain hidden.


.. _Hide a Subsection After its Due Date:

========================================
Hide a Subsection after its Due Date
========================================

You can make a subsection's content unavailable when its due date has passed.
Subsections that are hidden in this way remain visible in the course
navigation, and are included when grades are calculated. However, learners can
no longer access the assignments or exams after the subsection due date.

To hide a subsection after its due date, follow these steps.

#. Select the **Configure** icon in the subsection box.

   The **Subsection Settings** dialog box opens.

#. In the **Subsection Visibility** section, select **Hide content after due
   date**.

#. Select **Save**.

Learners who access the subsection after its due date has passed see a message
indicating that the subsection is no longer available because the due date has
passed.

In the course outline in Studio, the subsection is shown with an indication
that it is hidden after its due date.

   .. image:: ../../../shared/images/subsection-hidden-after-due-date.png
     :alt: A subsection in the course outline with the lock icon
      indicating that it is hidden after its due date.

.. _Delete a Subsection:

********************************
Delete a Subsection
********************************

When you delete a subsection, you delete all units within the subsection.

.. warning::
 You cannot restore course content after you delete it. To ensure you do not
 delete content you may need later, you can move any unused content to a
 section in your course that you set to never release.

To delete a subsection, follow these steps.

#. Select the **Delete** icon in the subsection that you want to delete.

  .. image:: ../../../shared/images/subsection-delete.png
   :alt: The subsection with Delete icon circled.

2. When the confirmation prompt appears, select **Yes, delete this
   subsection**.
