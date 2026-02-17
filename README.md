## **Splunk-Sticky-Flyout-Nav**

For environments that either cannot or do not want to use JS - a pure CSS sticky nav bar with a flyout. Similar to the <a href="https://github.com/lippmanry/Splunk-Sticky-Nav">sticky nav</a> but with a flyout on hover.

To use this, add at the top of your dashbord above your rows. Change the button text to change the first level label then change the page anchor IDs to match your row/panel IDs.

```
      <ul>
        <li class="dropdown-content-li">
          <button class="dropbtn">Row IDs <i class="icon-triangle-right-small"/>
                </button>
          <div class="dropdown-content-list">
            <ul>
              <li><a href="#row1">Row 1</a></li>
              <li><a href="#row4">Row 4</a></li>
              <li><a href="#row6">Row 6</a></li>
              <li><a href="#row8">Row 8</a></li>
              <li><a href="#row9">Row 9</a></li>
            </ul>         
           </div>
        </li>
      </ul>

...

<row id="row1">
...
<row id="row4">
...
```
