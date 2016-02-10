# THIS PLUGIN HAS BEEN DEPRECATED; PLEASE SEE THE LATEST VERSION HERE: https://github.com/Reflejo/jquery-countdown #



---


Take a look to the [demostration](http://jquery-countdown.googlecode.com/svn/trunk/index.html). This countdown has a great animation.

This project is still at beta stage, soon i'll implement callbacks and stuff.

Basic usage:
```
  $('#counter').countdown({startTime: "01:12:32:55"});
```

Complete usage:
```
  $('#counter').countdown({
    stepTime: 60,
    format: 'hh:mm:ss',
    startTime: "12:32:55",
    digitImages: 6,
    digitWidth: 53,
    digitHeight: 77,
    timerEnd: function() { alert('end!!'); },
    image: "digits.png"
  });
```

Did I mention that js code weighs just 1.7 KB?

See the [demo](http://jquery-countdown.googlecode.com/svn/trunk/index.html)!!.