#### 04/13/2022: Read 08 - More CSS Layout

#### HTML Chapter 15: “Layout” (repeat of Class 4 reading)
* [Link to Read 4 file](class-04.md)
  
#### Additional Resource: [Learn CSS](https://web.dev/learn/css/layout/)
* [!Image](https://web-dev.imgix.net/image/VbAJIREinuYvovrBzzvEyZOpw5w1/GezxDZXkJgkMevkKg39M.png?auto=format&w=845)

* you can split lists (here's an example):  <ul class="className"> <li> list of stuff </li></ul> the CSS would be: .className { column-count: 2; column-gap: 1em; }

#### Additional Resource: [CSS Podcast](https://traffic.libsyn.com/secure/thecsspodcast/TCP_CSS_Podcast_Episode_009_v1.1.mp3?dest-id=1891556)
* fixed positioning - relative to viewport
* relative positioning - to the nearest ancestor/parent
* it is very common practice to position parent elements with relative positioning and child elements with absolute

* sticky elements maintain a block level layout when not stuck but will stick at viewport edges based on what you instructed. Not sure what they mean by all this but there are links provided for follow-up at a later date. (see podcast recording timestamp ~11:15)

* inline axes change depending on language being used - English axes run left to right, top to bottom (like we read). Some Japanese axes run vertically.

* when you state display block, the element starts on a new line (reiteration)

* inline-block is a combo of the two features: it always stays within the inline axis of the doc but also responds to width/height properties (podcast ~13:50); flexbox does this and more;

* Sub-Grid: anxiously anticipated feature that allows children any number down in the DOM tree to opt into parent grid lines (this can't be done currently with the widely supportted grid tool)

* CSS Whodini - a collection of low & high level APIs that give devs more control than currently available; coming soon


#### `Why this topic matters`
* I enjoyed listening to the podcast and it served as a reminder that things change quickly in tech so its important to incorporate input streams to help you stay on top of relevant problems, solutions, updates and upgrades.
    
#### `Analogy `
* Yesteryear university professionals advocated reading of industry journals for whatever industry you were entering; this is still true today only those snail-mail print journals are now trumped by podcasts and other more immediate digital media sources.
        
#### `Things I want to know more about`
* I'm actually not all that taken with HTML/CSS info, yes it's fun and necessary for web design but I'm definitely more interested in the JS side of things and eager to get back to practicing what we've covered so far.