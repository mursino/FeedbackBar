FeedbackBar
===========

**Purpose**: $.feedbackBar is a jQuery plugin meant to provide unobtrusive feedback to the user via an absolutely positioned bar at the top of your page. The position is absolute to the page because it is meant to provide feedback that can either be automatically closed after a certain length of time or by a user action. It positioning is not meant to alter the existing page content but instead, overlay it.

**Features**
* Takes an HTML string for your feedback message so you can include your own additional markup
* The slide down and slide up durations can be customized (independently)
* The feedback bar can auto-close after a set interval or you can defined a "close" button/element
* A callback can be defined to execute when the feedback bar is closed (e.g. redirect a user to a login page if they're not authenticated)
* The feedback bar contains an outer div and an inner div for maximum CSS styling flexibility 

**Extended Documentation**: http://code.ursino.info/feedbackbar/

**Simple Example**

    $.feedbackBar("Welcome new user!", {
      delay : 500,
      autoClose : 5000
    });
