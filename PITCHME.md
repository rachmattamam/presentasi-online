
@title[Introduction]

# Dis<span class="gold">KominfoST</span>

#### Seksi Pengembangan Aplikasi Informatika.*
<br>
<div class="byline front">[Evaluasi Kegiatan TA 2017]</div>
<div class="byline front">[Rencana Kerja TA 2018]</div>

---

@title[PITCHME.md]

#### Dinas Komunikasi <span class="gold">Informatika</span> Statistik
#### dan Persandian
#### Seksi Pengembangan Aplikasi Informatika.
<br>
<span class="aside">Telah melaksanakan ...</span>

---

### Pengembangan <span class="gray">Dashboard Pimpinan</span>[.](http://dashboard-01.dev.bantenprov.go.id/)
#### Pengembangan <span class="gray">Portal Provinsi Banten</span>[.](http://portal-01.dev.bantenprov.go.id/)
### Pengembangan <span class="gold">BantOS</span>[.](http://linux.dev.bantenprov.go.id/)
#### Pengembangan <span class="gold">Bantenprov API</span>[.](http://api-01.dev.bantenprov.go.id/)


---


### Pengembangan <span class="gray">Banten Satu Data</span>[.](http://satudata-01.dev.bantenprov.go.id/)
#### Pengembangan <span class="gold">Yankes</span>[.](http://yankes-01.dev.bantenprov.go.id/)
### Pengembangan <span class="gold">Simbada</span>[.](http://simbada-01.dev.bantenprov.go.id/)
#### Pengembangan <span class="gold">Epormas</span>[.](http://epormas-01.dev.bantenprov.go.id/)

---


### Pengembangan <span class="gold">Banten SSO</span>[.](https://sso.dev.bantenprov.go.id:9443/cas)
#### Pengembangan <span class="gold">Task Management</span>[.](http://task-01.dev.bantenprov.go.id/)


---


?code=assets/md/hello.md&title=Step 1. PITCHME.md

<br>
#### Create slideshow content using GitHub Flavored Markdown in your favorite editor.

<span class="aside">It's as easy as README.md with simple slide-delimeters (---)</span>

---

@title[Step 2. Git-Commit]

### <span class="gold">Peraturan Gubernur</span>
<br>

```shell
- SOP Pengembangan Aplikasi
- SOP Pengembangan Website
- SOP Kemanan Sistem
- SOP Data center

Menjadi >>>>>>> Pergub Sistem Elektronik Pemerintah Provinsi Banten
```

@[1](Mengatur cara pengajuan pengembangan aplikasi.)
@[2](Mengatur cara mengelola halaman website .)
@[3](Mengatur cara penerapan kemanan sistem jaringan)
@[4](Mengatur cara menyelenggarakan data center.)

---

@title[Step 3. Done!]

### <span class="gold">STEP 3. GET THE WORD OUT!</span>
<br>
![GitPitch Slideshow URLs](assets/images/gp-slideshow-urls.png)
<br>
<br>
#### Instantly use your GitPitch slideshow URL to promote, pitch or present absolutely anything.

---y

@title[Slide Rich]

### <span class="gold">Slide Rich</span>

#### Code Presenting for Blocks, Files, and GISTs
#### Image, Video, Chart, and Math Slides
#### Multiple Themes with Easy Customization
<br>
#### <span class="gold">Plus collaboration is built-in...</span>
#### Your Slideshow is Part of Your Project
#### Under Git Version Control within Your Git Repo

---

@title[Feature Rich]

### <span class="gold">Feature Rich</span>

#### Present Online or Offline
#### With Speaker Notes Support
#### Print Presentation as PDF
#### Auto-Generated Table-of-Contents
#### Share Presentation on Twitter or LinkedIn

---

### <span class="gold">GitPitch Pro - Coming Soon!</span>

<br>
<div class="left">
    <i class="fa fa-user-secret fa-5x" aria-hidden="true"> </i><br>
    <a href="https://gitpitch.com/pro-features" class="pro-link">
    More details here.</a>
</div>
<div class="right">
    <ul>
        <li>Private Repos</li>
        <li>Private URLs</li>
        <li>Password-Protection</li>
        <li>Image Opacity</li>
        <li>SVG Image Support</li>
    </ul>
</div>

---

### Go for it.
### Just add <span class="gold">PITCHME.md</span> ;)
<br>
[Click here to learn more @fa[external-link fa-pad-left]](https://github.com/gitpitch/gitpitch/wiki)
=======

#### Banten Development Presentation Online

##### Menuju Banten Satu Data

---

## Tips!

<br>

@fa[arrows gp-tip](Press F to go Fullscreen)

@fa[microphone gp-tip](Press S for Speaker Notes)

---

## Template Features

- Code Presenting |
- Repo Source, Static Blocks, GIST |
- Custom CSS Styling |
- Slideshow Background Image |
- Slide-specific Background Images |
- Custom Logo, TOC, and Footnotes |

---?code=src/go/server.go&lang=golang&title=Golang File

@[1,3-6](Present code found within any repo source file.)
@[8-18](Without ever leaving your slideshow.)
@[19-28](Using GitPitch code-presenting with (optional) annotations.)

---

@title[JavaScript Block]

<p><span class="slide-title">JavaScript Block</span></p>

```javascript
// Include http module.
var http = require("http");

// Create the server. Function passed as parameter
// is called on every request made.
http.createServer(function (request, response) {
  // Attach listener on end event.  This event is
  // called when client sent, awaiting response.
  request.on("end", function () {
    // Write headers to the response.
    // HTTP 200 status, Content-Type text/plain.
    response.writeHead(200, {
      'Content-Type': 'text/plain'
    });
    // Send data and end response.
    response.end('Hello HTTP!');
  });

// Listen on the 8080 port.
}).listen(8080);
```

@[1,2](You can present code inlined within your slide markdown too.)
@[9-17](Displayed using code-syntax highlighting just like your IDE.)
@[19-20](Again, all of this without ever leaving your slideshow.)

---?gist=onetapbeyond/494e0fecaf0d6a2aa2acadfb8eb9d6e8&lang=scala&title=Scala GIST

@[23](You can even present code found within any GitHub GIST.)
@[41-53](GIST source code is beautifully rendered on any slide.)
@[57-62](And code-presenting works seamlessly for GIST too, both online and offline.)

---

## Template Help

- [Code Presenting](https://github.com/gitpitch/gitpitch/wiki/Code-Presenting)
  + [Repo Source](https://github.com/gitpitch/gitpitch/wiki/Code-Delimiter-Slides), [Static Blocks](https://github.com/gitpitch/gitpitch/wiki/Code-Slides), [GIST](https://github.com/gitpitch/gitpitch/wiki/GIST-Slides) 
- [Custom CSS Styling](https://github.com/gitpitch/gitpitch/wiki/Slideshow-Custom-CSS)
- [Slideshow Background Image](https://github.com/gitpitch/gitpitch/wiki/Background-Setting)
- [Slide-specific Background Images](https://github.com/gitpitch/gitpitch/wiki/Image-Slides#background)
- [Custom Logo](https://github.com/gitpitch/gitpitch/wiki/Logo-Setting), [TOC](https://github.com/gitpitch/gitpitch/wiki/Table-of-Contents), and [Footnotes](https://github.com/gitpitch/gitpitch/wiki/Footnote-Setting)

---

### Template Versions

- #### [Base Template  @fa[external-link gp-download]](https://gitpitch.com/gitpitch/templates/blue)
- #### [Code Maximized @fa[external-link gp-download]](https://gitpitch.com/gitpitch/templates/blue?p=codemax)
- #### [Speaker Notes @fa[external-link gp-download]](https://gitpitch.com/gitpitch/templates/blue?p=speaker)

---

### Questions?

<br>

@fa[twitter gp-contact](@gitpitch)

@fa[github gp-contact](gitpitch)

@fa[medium gp-contact](@gitpitch)

---?image=assets/image/gitpitch-audience.jpg

@title[Download this Template!]

### <span class="white">Get your presentation started!</span>
### [Download this template @fa[external-link gp-download]](https://gitpitch.com/template/download/blue)
