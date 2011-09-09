Key input to string
===================

About
-----

This is provides conversion to a string from a key code.
This is an alternate keyIdentifier.

Usage
-----

Executes tests:

::

  // use native
  window.onkeydown = function () {
    if (getKeyChar(event) === 'A') { //< here
      alert('shift + a');
    }
  };
  
  // use jQuery
  $(window).keydown(function (evt) {
    if (evt.keyChar() === 'A') { //< here
      alert('shift + a');
    }
  });
