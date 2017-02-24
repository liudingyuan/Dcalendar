## Dcalendar
A simple calendar

[DEMO](http://liudyuan.com/Dcalendar/index.html)

#Usage
HTML
    
    <div class="dcalendar"></div>

JS

    var app = new Dcalendar();
    app.init();

##API
* app.init(date)
* app.markDay(day)  //mark some day
* app.addEvent(day, type, callback) //add event to some day