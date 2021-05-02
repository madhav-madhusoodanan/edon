# Events

It is the 2nd most fundamental part of Edon
<ol>
  <li> Every activity is an event
  <li> Each event runs on a process thread
  <li> An event (equivalent to async await parts in js) can fork out multiple threads if specified
  <li> However, by default an event can only fork out a single child thread (child thread can fork many tho)
</ol> 
