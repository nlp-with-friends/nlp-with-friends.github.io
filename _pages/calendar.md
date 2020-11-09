---
permalink: /calendar/
title: "Series Calendar"
---

[Eventbrite registration links](https://www.eventbrite.co.uk/o/nlp-with-friends-30774024728){:target="_blank"} (to receive zoom details) are listed in both the talk descriptions and their calendar events. 

To add an individual talk below to your (google) calendar, click on the event and then click *<copy to my calendar*>. 

To subscribe to this calendar and view events in your own google calendar, click [here](https://calendar.google.com/calendar/b/0/r/settings/addcalendar?cid=nlpwithfriends%40gmail.com)! All events are available via ics for other calendar formats [here](/assets/ics/nlpwithfriends.ics).

<hr style="height:5pt; visibility:hidden;" />

<div id="calendar-container"></div>

<script type="text/javascript" src="//cdnjs.cloudflare.com/ajax/libs/jstimezonedetect/1.0.4/jstz.min.js"></script>
<script type="text/javascript">
 var timezone = encodeURIComponent(jstz.determine().name()); 
 var pref = '<iframe src="https://calendar.google.com/calendar/embed?src=nlpwithfriends%40gmail.com&ctz=';
 var suff = '" style=" border-width:0 " width="800" height="600" frameborder="0" scrolling="no"></iframe>';
 var iframe_html = pref + timezone + suff;
 document.getElementById('calendar-container').innerHTML = iframe_html;
</script>

