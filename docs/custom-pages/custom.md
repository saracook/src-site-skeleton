---
title: Custom js
permalink: /custom-pages/index.html
folder: submenu
toc: true
customjs: /assets/js/connect.js
customcss: /assets/css/demo-custom.css
---
<p class="annotation">This page calls a custom js file (via customjs: in front matter) to control the auto-fill feature</p>

<p class="annotation">This page calls a custom css file (via customcss: in front matter) which is changing the color of the boxes in the sidebar for this page only</p>

## Connect to your VM/Project

_optional: enter your VM and Project names below and click the Generate button to generate commands with your variables pre-filled_
<div class="form-row  flex-grow-1">
  <div class="col-auto flex-grow-1 ">
    <label class="sr-only" for="vmName">VM Name</label>
    <input type="text" class="form-control form-control-lg" name="vmName" id="vmName" placeholder="VM Name" />
  </div>
  <div class="col-auto flex-grow-1 ">
    <label class="sr-only" for="projectName">Project Name</label>
    <input type="text" class="form-control form-control-lg" name="projectName" id="projectName" placeholder="Project Name" />
  </div>
  <div class="col-auto">
    <a class="btn btn-info generate" id="generateBtn" title="Generate Commands"><i class="fa-solid fa-wand-magic-sparkles"></i> Generate!</a>
  </div>
</div>

### Power on your VM

This step can be done on the command line, or via your web browser. Click the button to copy the text to your clipboard.

#### Command Line/Terminal


<div class="form-group form-inline">
<div class="form-row  flex-grow-1">
    <div class="col-auto tip-input">
      <label class="sr-only" for="powerVM">Power On Command</label>
      <input type="text" id="powerVM" class="form-control form-control-lg" readonly placeholder="Power On!" />
    </div>
    <div class="col-auto tip-btn">
      <a class="btn btn-info copy" title="Copy to Clipboard" data-target="powerVM"><i class="fa-regular fa-clipboard"></i></a>
    </div>
</div>
</div>

#### Web Browser

<span id="powerUrlLink"></span>
<div class="form-group form-inline">
<div class="form-row flex-grow-1">
    <div class="col-auto tip-input">
      <label class="sr-only" for="powerUrl">Power On Command</label>
      <input type="text" id="powerUrl" class="form-control form-control-lg" readonly placeholder="Power On!" />
    </div>
    <div class="col-auto tip-btn">
      <a class="btn btn-info copy" title="Copy to Clipboard" data-target="powerUrl"><i class="fa-regular fa-clipboard"></i></a>
    </div>
  </div>
</div>

### Connect to localhost

Once powered on, connect to it from the command line with: 

<div class="form-group form-inline">
<div class="form-row flex-grow-1">
    <div class="col-auto tip-input">
      <label class="sr-only" for="connect">Connect Command</label>
      <input type="text" id="connect" class="form-control form-control-lg" readonly placeholder="connect!" />
    </div>
    <div class="col-auto tip-btn">
      <a class="btn btn-info copy" title="Copy to Clipboard" data-target="connect"><i class="fa-regular fa-clipboard"></i></a>
    </div>
</div>
</div>

Then, open a new web browser tab and go to
[localhost:8080][url_localhost].

### Turn It Off

Remember to turn off the instance after you're done working. You can do this via the web console, or from the command line using the text below.

<div class="form-group form-inline">
<div class="form-row  flex-grow-1">
    <div class="col-auto tip-input">
      <label class="sr-only" for="turnItOff">Turn Off Command</label>
      <input type="text" id="turnItOff" class="form-control form-control-lg" readonly placeholder="Power OFF!" />
    </div>
    <div class="col-auto tip-btn">
      <a class="btn btn-info copy" title="Copy to Clipboard" data-target="turnItOff"><i class="fa-regular fa-clipboard"></i></a>
    </div>
</div>
</div>


[comment]: #  (link URLs -----------------------------------------------------)

[url_gsdk]:        https://cloud.google.com/sdk/docs/install
[url_vpn]:         https://uit.stanford.edu/service/vpn
[url_localhost]:   http://localhost:8080


{% include links.html %}
