.. include:: ../../../links/links.rst

.. _Office Mix Tool:

##########################
Office Mix Tool
##########################

.. note:: EdX offers full support for this tool.

`Office Mix`_ is a third-party tool that you can use to turn PowerPoint
presentations into interactive online lessons, called mixes. This topic
describes how to embed mixes in your course.

.. contents::
  :local:
  :depth: 2

Before you make content from an external site available through your course, be
sure to review the content to ensure that it is accessible to people with
disabilities. For more information, see :ref:`Accessibility Best Practices for
Course Content Development`.

*********
Overview
*********

Office Mix is an extension to PowerPoint. With Office Mix, you can create
lessons by integrating narration, screen recordings, quizzes, polls, web site
links, and more into your PowerPoint presentations. You use the Office Mix tool
in Studio to add mixes to your course.

.. note:: Mixes are not assessments that can be graded. At this
 time, you should not add Office Mix components to the graded
 subsections of your course.

The following example shows a mix as learners see it in the edX LMS.

.. image:: ../../../shared/building_and_running_chapters/Images/office_mix.png
  :alt: An Office mix in courseware.
  :width: 800

For information about how to create mixes, see the `Office Mix Knowlege Base`_.

.. _Enable the Office Mix Tool:

*********************************************
Enable the Office Mix Tool
*********************************************

Before you can add a mix to your course, you must enable this tool in Studio.

To enable the Office Mix tool in Studio, you add the ``"officemix"`` key to the
**Advanced Module List** on the **Advanced Settings** page. For more
information, see :ref:`Enable Additional Exercises and Tools`.

***********************************
Add a Mix in Studio
***********************************

You must :ref:`enable the Office Mix tool <Enable the Office Mix Tool>` before
you add a component with a mix to your course. You must also select the mix
that you want to add, and obtain its URL.

#. On the **Course Outline** page, open the unit in an ungraded subsection
   where you want to add the mix.

#. Under **Add New Component**, select **Advanced**, and then select **Office
   Mix**. Studio adds the new component, which includes a sample mix, to the
   unit.

#. In the new component, select **Edit**.

   .. image:: ../../../shared/building_and_running_chapters/Images/office_mix_studio.png
     :alt: The Edit component dialog box for a Mix in Studio.
     :width: 600

#. In the **Component Display Name** field, enter an identifying name for the
   component. This name appears to learners as a tooltip in the learning
   sequence at the top of the **Courseware** page.

#. In the **Office Mix URL** field, enter the complete URL for the mix that you
   want to add. For example, ``https://mix.office.com/watch/1otxpj7hz6kbx``.

#. Select **Save**.

   To verify your work, select **play**.

