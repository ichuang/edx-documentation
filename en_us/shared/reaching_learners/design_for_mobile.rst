.. _Designing For a Mobile Experience:

###############################################
Designing Your Course For a Mobile Experience
###############################################

The percentage of learners who access MOOCs using their mobile devices is
increasing every day. Most courses on edx.org can be viewed on mobile devices,
although we still recommend that learners complete graded assignments on a
desktop computer, depending on the type of assessments that their courses
include. For information on which exercises and tools are mobile-ready, see the
table in the :ref:`Introduction to Exercises and Tools<Create Exercises>`
section.

To make the course experience for mobile learners as rewarding as it is for
learners using desktop computers, keep the following best practices in mind as
you design, test, and run your course.

* When learners access your course using the edX Android and iPhone apps, they
  progress from component to component by swiping through them. It might seem
  useful to include an HTML component in a unit for the purpose of providing a
  demarcation point or guiding learners to the next unit, but having to swipe
  through too many "markers" with no real course content is not a good
  experience for mobile users.

* Display names are critical for navigation on mobile devices. As you create
  course content, make sure you replace the default display names for every
  component with useful courseware component names.

* Keep display names and labels concise. Long display names and labels
  might wrap on smaller screens, or might not be easily viewable. For example,
  if several components have names that all start with the first five words
  and differ only after that, learners on mobile devices will have a difficult
  time distinguishing between components.

* Learners might be viewing your course materials on screens as large as a
  high-resolution Mac Thunderbolt display, or as small as a 5 inch smartphone
  screen, so it is difficult to size an image so that it displays well at all
  resolutions. In general, edX recommends keeping most images under 0.5MB in
  size so that learners who have low Internet bandwidth will not have trouble
  downloading the images. If you have a large image that requires zooming to
  view the full detail, in addition to providing an image that can be easily
  downloaded, link to a full resolution copy that can be opened separately
  from the courseware.

* When you make choices about the problem types to use for graded and ungraded
  assignments in your course, or which problem types to present in a single
  unit, keep the mobile experience in mind. Whenever possible, use mobile-ready
  assessment types. If you use assessment types that are not supported on mobile
  devices, notify learners in your courseware that they will not be able to
  complete assignments using unsupported assessment types using the edX iPhone
  and Android mobile apps.

* If you make JavaScript or CSS changes to course components using XML, be
  aware that components might not render in the same way on a mobile device as
  they do in the desktop. EdX recommends that you create components in Studio
  without modifying them in XML, to ensure that components render reliably on
  both mobile and desktop.


.. _Testing Your Course For Mobile Devices:

**************************************
Testing Your Course For Mobile Devices
**************************************

If you have included some of the more complex problem types, or have highly
customized the way course content displays, edX recommends that you test your
course for multiple devices and displays.

To test the mobile experience of your course, sign in to your course using the
edX Android or iPhone apps and view each courseware unit to make sure that it
renders as you expect it to.


