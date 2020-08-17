External users goals:
Site's users are interested in learning how to produce music, how to dj or acquiring new sounds for their own use

Site owners goals:
Acquire students to teach (music production and djing), sell own samples and sounds, and also gain more listeners for my own music

Potential features:
Give personal story and own experience
Give an outline of both production and dj course - Embedded video (example of tutorials)
Embedded music (examples of patches)
Contact form

Advanced features:
Embed soundcloud player
Newsletter subscription service with free tips and tricks

---

Header :
Make it look like a synth

_-Home (intro video embedded)
_-About me (photo, bio)
_-Learn music production (list broken into modules, include photos and sound samples. Short free tutorial video embedded)
_-Learn how to DJ (brief outline, offer some free tips and tricks)
_-Sound design service ('give me the theme, i'll give you the sound' . Include pricing ie £5 for 3 patches, £10 for 10 patches - (custom drum kit counts as 5) or £20 for 30 patches. Can request how many of each sound (i.e bass, lead, pad, arps etc) included in that
_-Contact (form)

Footer - (link to free samples, soundcloud, mixcloud, facebook), sign up to newsletter

** Aesthetics **

- Vertical menu items along left hand side to look like piano keys. Use hover effect to make it look like keys are being played
- Header will be a picture of an amplifier head
- Include musical fontawesome icons such as notes, keys, speakers and turntables
- Use less colours but more shades of said colours for subtle effect

---

chosen (google) text for h1,h2: Lobster (regular 400)
chosen (google) text for h3,h4,h5,h6,p: Open sans (light 300, regular 400, semi-bold 500)

---

15/08/2020
Initial commit:
-created all folders and pages including css stylesheet.
-created boilerplate and header/footer(blank)
-inserted css stylesheet, bootstrap, fontawesome and google fonts into each page.
-added page titles
-insert placeholder text on every page for rough idea of content
-created readme

added navbar, fixed stylesheet:

- added navbar, basic initial styling (font properties and background colour)
- linked pages together
- fixed css stylesheet path (previously forgot to add assets/css/)

Added custom banner:
-created and uploaded custom banner picture, inserted banner into homepage, using bootstrap grid system. started styling banner and nav bar

responsive and compact navbar and image:
-styled menu list items with box-shadow on hover to create effect of pressing piano keys. style nav li with extra padding to make longer 'piano keys'
-changed page titles to make menu more compact
-made navbar and banner image more responsive using bootstrap grid system

removed image and added 4 different images:
-removed banner image due to responsiveness issues
-uploaded 4 new different sized images to add at different resolutions

Wrote html for contact page:
-created contact form on contact page to allow requests/ feedback from visitprs

Fontawesome changes and embedded soundcloud:
-replaced bootstrap fomtawesome cdn with fontawesome javascript cdn to accomodate newer icons **fontawesome icons are still not appearing. need to keep troubleshooting**
-added icons to list of dj tips on dj page
-started replacing placeholder text on dj and about me page
-embedded soundcloud player on about me page to allow visitors to listen to my music

16/08/2020
Created music production curriculum
-Created a curriculum for the music production course. Added all modules and sub-divided with unordered lists

Added DJ tips and mix,
-wrote ordered list of free DJ tips on DJ page
-Uploaded and embedded own mix to DJ page
-Added headline for homepage

Wrote introduction paragraph to DJ page, included external code in readme
-Introduction to DJ course written on DJ page with reference to other elements on the page. Included eternal code used, at the bottom of this readme

Uploaded images for music production page
-Uploaded images matching the modules in the music production course

Updated design page
-Added intro paragraph for design page
-included pricing table on design page using bootstrap

Updated homepage, added new images to images folder
-Added 'Who this website is for' and 'What i can offer you' unordered lists to homepage
-added new images to folder for later use

Updated about me page
-Wrote bio for about me page

17/08/2020
Created footer, intro to music production
-created footer including form for newsletter and social links **fontawesome icons still not displaying**. Keeping footer only on homepage until fontawesome problem is fixed.
-wrote introduction to music production course

Added pricing and special offer
-Added pricing to both production and DJ pages
-Created special offer and link to contact page from homepage
-Slightly adjusted wording on contact page to accomodate visitors coming to the page from the link on the homepage

Added sections, tidied up paragraphs
-added sections to every page with accompanying css selectors
-added line breaks where necessary to break up larger bodies of text

Special offer section
-added extra section for special offer for aesthetic reasons
---------------------------------------------------------------------------------------------------------------------------------
external code used:

-(Bootstrap CDN):  <link
      rel="stylesheet"
      href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css"
      integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T"
      crossorigin="anonymous"
    />
    <script
      src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"
      integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM"
      crossorigin="anonymous"
    ></script>
    <script
      src="https://code.jquery.com/jquery-3.3.1.slim.min.js"
      integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo"
      crossorigin="anonymous"
    ></script>
    <script
      src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"
      integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1"
      crossorigin="anonymous"
    ></script>

-(Fontawesome CDN): <script href="https://use.fontawesome.com/7e63086f43.js"></script>

-(Google fonts CDN): <link
      href="https://fonts.googleapis.com/css2?family=Lobster&family=Open+Sans:wght@300;400;600&display=swap"
      rel="stylesheet"
    />

-(To embed soundcloud player): <iframe
      width="100%"
      height="300"
      scrolling="no"
      frameborder="no"
      allow="autoplay"
      src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/216717155&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"
    ></iframe>

<div
      style="
        font-size: 10px;
        color: #cccccc;
        line-break: anywhere;
        word-break: normal;
        overflow: hidden;
        white-space: nowrap;
        text-overflow: ellipsis;
        font-family: Interstate, Lucida Grande, Lucida Sans Unicode, Lucida Sans,
          Garuda, Verdana, Tahoma, sans-serif;
        font-weight: 100;
      "
    >
<a
        href="https://soundcloud.com/gildy"
        title="gildy"
        target="_blank"
        style="color: #cccccc; text-decoration: none;"
        >gildy</a
      >
·
<a
        href="https://soundcloud.com/gildy/p1003031972014904"
        title="P10/03031972014904"
        target="_blank"
        style="color: #cccccc; text-decoration: none;"
        >P10/03031972014904</a
      >
</div>

-(To embed mixcloud player): <iframe width="100%" height="120" src="https://www.mixcloud.com/widget/iframe/?hide_cover=1&feed=%2FGjgcf5%2Faugust-techno%2F" frameborder="0"></iframe>
