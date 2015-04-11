# Modern Tables
##A modern approach to laying out websites.

We all know we're not supposed to use tables for layout any more.  The Modern Tables library provides a simple way to lay out a web site using modern `div` tags.  It even includes a polyfill for `center`!

# Basic Layout Example

See how simple it is to use?

```html
<div class="table" style="width: 100%">
  <div class="tr">
    <div class="td" style="width: 20%"><img src="1x1.gif"></div>
    <div class="td" style="width: 60%">
      <!-- Main column -->
      <div class="table" style="width:100%">
        <div class="tr">
          <div class="td">
            <div class="table" style="width:100%">
              <div class="tr">
                <div class="td" style="width:100%">
                  <div class="center">My Site!</div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="tr">
          <div class="td">
            <div class="table" style="width: 100%">
              <div class="tr">
                <div class="td" style="width: 100px">
                  <!-- Navigation -->
                  <div class="table">
                    <div class="tr">
                      <div class="td">Home</div>
                    </div>
                    <div class="tr">
                      <div class="td">Links</div>
                    </div>
                  </div>
                </div>
                <div class="td">
                  <!-- Main column -->
                  <div class="table" style="width:100%">
                    <div class="tr">
                      <div class="td" style="height: 20px"><img src="1x1.gif"></div>
                    </div>
                    <div class="tr">
                      <div class="td">
                        My content
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="td" style="width: 20%"><img src="1x1.gif"></div>
  </div>
</div>
```

Note: `font` polyfill and 1x1 transparent spacer image not provided