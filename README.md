# Glut-stb_image.-installation

<h2>Image Loading with stb_image.h</h2>

<p>
  <strong><code>stb_image.h</code></strong> is a lightweight, header-only image loading library used to load images like PNG and JPEG into your OpenGL projects.
</p>

<h3>Download</h3>
<ul>
  <li>Go to the official repository: 
    <a href="https://github.com/nothings/stb/blob/master/stb_image.h" target="_blank">
      https://github.com/nothings/stb/blob/master/stb_image.h
    </a>
  </li>
  <li>Right-click <code>Raw</code> → Save As → Place it in your project directory (e.g., <code>libs/</code>).</li>
</ul>

<h3>Usage</h3>
<pre><code>#define STB_IMAGE_IMPLEMENTATION
#include "stb_image.h"
</code></pre>

<p>
  This must be written in one (and only one) of your source files to implement the functionality.
</p>


<h3>Compiler Note</h3>
<p>
  No need to link any special libraries for <code>stb_image</code>. It is a self-contained header file.
</p>

<p>
  If you want to learn more, visit the full stb documentation:
  <a href="https://github.com/nothings/stb" target="_blank">
    https://github.com/nothings/stb
  </a>
</p>
