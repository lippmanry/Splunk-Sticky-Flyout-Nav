## **Splunk-Sticky-Flyout-Nav**

For environments that either cannot or do not want to use JS - a pure CSS sticky nav bar with a flyout. Similar to the <a href="https://github.com/lippmanry/Splunk-Sticky-Nav">sticky nav</a> but with a flyout.

To use this, add at the top of your dashbord above your rows. Change the button text to change the first level label then change the page anchor IDs to match your row/panel IDs.

```
<button class="dropbtn">CHANGE THIS  <i class="icon-triangle-right-small"/></button>

      <div class="dropdown-content-list">
        <ul>
          <li><a href="#CHANGETHIS">CHANGETHIS...</a></li>
          <li><a href="#example">EXAMPLE</a></li>
          <li><a href="#example">EXAMPLE</a></li>
          <li><a href="#example">EXAMPLE</a></li>
          <li><a href="#example">EXAMPLE</a></li>
        </ul>         
       </div>

```
