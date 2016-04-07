# js.alertplugin
A simple vanilla JS plugin that creates a custom alert message.

Usage

var alert = new Alert({
  className: 'pop-out',
	positiveMessage: "Ok",
	closeButton: false,
	maxWidth: 600,
	minWidth: 250,
  overlay: true,
	shake: true,
	sound: true,
	soundFile: "audio/alert"
});


Events:

  1. Open
    - alert.open();
  2. Close
    - alert.close();
  3. Shake
    - alert.shake()
