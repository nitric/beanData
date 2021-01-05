<!DOCTYPE html>
<html>
<head><meta charset="utf-8" />

<title>Final_Project_Nithin_Richard</title>

<script src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.1.10/require.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.0.3/jquery.min.js"></script>



<style type="text/css">
    /*!
*
* Twitter Bootstrap
*
*/
/*!
 * Bootstrap v3.3.7 (http://getbootstrap.com)
 * Copyright 2011-2016 Twitter, Inc.
 * Licensed under MIT (https://github.com/twbs/bootstrap/blob/master/LICENSE)
 */
/*! normalize.css v3.0.3 | MIT License | github.com/necolas/normalize.css */
html {
  font-family: sans-serif;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
}
body {
  margin: 0;
}
article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
main,
menu,
nav,
section,
summary {
  display: block;
}
audio,
canvas,
progress,
video {
  display: inline-block;
  vertical-align: baseline;
}
audio:not([controls]) {
  display: none;
  height: 0;
}
[hidden],
template {
  display: none;
}
a {
  background-color: transparent;
}
a:active,
a:hover {
  outline: 0;
}
abbr[title] {
  border-bottom: 1px dotted;
}
b,
strong {
  font-weight: bold;
}
dfn {
  font-style: italic;
}
h1 {
  font-size: 2em;
  margin: 0.67em 0;
}
mark {
  background: #ff0;
  color: #000;
}
small {
  font-size: 80%;
}
sub,
sup {
  font-size: 75%;
  line-height: 0;
  position: relative;
  vertical-align: baseline;
}
sup {
  top: -0.5em;
}
sub {
  bottom: -0.25em;
}
img {
  border: 0;
}
svg:not(:root) {
  overflow: hidden;
}
figure {
  margin: 1em 40px;
}
hr {
  box-sizing: content-box;
  height: 0;
}
pre {
  overflow: auto;
}
code,
kbd,
pre,
samp {
  font-family: monospace, monospace;
  font-size: 1em;
}
button,
input,
optgroup,
select,
textarea {
  color: inherit;
  font: inherit;
  margin: 0;
}
button {
  overflow: visible;
}
button,
select {
  text-transform: none;
}
button,
html input[type="button"],
input[type="reset"],
input[type="submit"] {
  -webkit-appearance: button;
  cursor: pointer;
}
button[disabled],
html input[disabled] {
  cursor: default;
}
button::-moz-focus-inner,
input::-moz-focus-inner {
  border: 0;
  padding: 0;
}
input {
  line-height: normal;
}
input[type="checkbox"],
input[type="radio"] {
  box-sizing: border-box;
  padding: 0;
}
input[type="number"]::-webkit-inner-spin-button,
input[type="number"]::-webkit-outer-spin-button {
  height: auto;
}
input[type="search"] {
  -webkit-appearance: textfield;
  box-sizing: content-box;
}
input[type="search"]::-webkit-search-cancel-button,
input[type="search"]::-webkit-search-decoration {
  -webkit-appearance: none;
}
fieldset {
  border: 1px solid #c0c0c0;
  margin: 0 2px;
  padding: 0.35em 0.625em 0.75em;
}
legend {
  border: 0;
  padding: 0;
}
textarea {
  overflow: auto;
}
optgroup {
  font-weight: bold;
}
table {
  border-collapse: collapse;
  border-spacing: 0;
}
td,
th {
  padding: 0;
}
/*! Source: https://github.com/h5bp/html5-boilerplate/blob/master/src/css/main.css */
@media print {
  *,
  *:before,
  *:after {
    background: transparent !important;
    box-shadow: none !important;
    text-shadow: none !important;
  }
  a,
  a:visited {
    text-decoration: underline;
  }
  a[href]:after {
    content: " (" attr(href) ")";
  }
  abbr[title]:after {
    content: " (" attr(title) ")";
  }
  a[href^="#"]:after,
  a[href^="javascript:"]:after {
    content: "";
  }
  pre,
  blockquote {
    border: 1px solid #999;
    page-break-inside: avoid;
  }
  thead {
    display: table-header-group;
  }
  tr,
  img {
    page-break-inside: avoid;
  }
  img {
    max-width: 100% !important;
  }
  p,
  h2,
  h3 {
    orphans: 3;
    widows: 3;
  }
  h2,
  h3 {
    page-break-after: avoid;
  }
  .navbar {
    display: none;
  }
  .btn > .caret,
  .dropup > .btn > .caret {
    border-top-color: #000 !important;
  }
  .label {
    border: 1px solid #000;
  }
  .table {
    border-collapse: collapse !important;
  }
  .table td,
  .table th {
    background-color: #fff !important;
  }
  .table-bordered th,
  .table-bordered td {
    border: 1px solid #ddd !important;
  }
}
@font-face {
  font-family: 'Glyphicons Halflings';
  src: url('../components/bootstrap/fonts/glyphicons-halflings-regular.eot');
  src: url('../components/bootstrap/fonts/glyphicons-halflings-regular.eot?#iefix') format('embedded-opentype'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.woff2') format('woff2'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.woff') format('woff'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.ttf') format('truetype'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.svg#glyphicons_halflingsregular') format('svg');
}
.glyphicon {
  position: relative;
  top: 1px;
  display: inline-block;
  font-family: 'Glyphicons Halflings';
  font-style: normal;
  font-weight: normal;
  line-height: 1;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
.glyphicon-asterisk:before {
  content: "\002a";
}
.glyphicon-plus:before {
  content: "\002b";
}
.glyphicon-euro:before,
.glyphicon-eur:before {
  content: "\20ac";
}
.glyphicon-minus:before {
  content: "\2212";
}
.glyphicon-cloud:before {
  content: "\2601";
}
.glyphicon-envelope:before {
  content: "\2709";
}
.glyphicon-pencil:before {
  content: "\270f";
}
.glyphicon-glass:before {
  content: "\e001";
}
.glyphicon-music:before {
  content: "\e002";
}
.glyphicon-search:before {
  content: "\e003";
}
.glyphicon-heart:before {
  content: "\e005";
}
.glyphicon-star:before {
  content: "\e006";
}
.glyphicon-star-empty:before {
  content: "\e007";
}
.glyphicon-user:before {
  content: "\e008";
}
.glyphicon-film:before {
  content: "\e009";
}
.glyphicon-th-large:before {
  content: "\e010";
}
.glyphicon-th:before {
  content: "\e011";
}
.glyphicon-th-list:before {
  content: "\e012";
}
.glyphicon-ok:before {
  content: "\e013";
}
.glyphicon-remove:before {
  content: "\e014";
}
.glyphicon-zoom-in:before {
  content: "\e015";
}
.glyphicon-zoom-out:before {
  content: "\e016";
}
.glyphicon-off:before {
  content: "\e017";
}
.glyphicon-signal:before {
  content: "\e018";
}
.glyphicon-cog:before {
  content: "\e019";
}
.glyphicon-trash:before {
  content: "\e020";
}
.glyphicon-home:before {
  content: "\e021";
}
.glyphicon-file:before {
  content: "\e022";
}
.glyphicon-time:before {
  content: "\e023";
}
.glyphicon-road:before {
  content: "\e024";
}
.glyphicon-download-alt:before {
  content: "\e025";
}
.glyphicon-download:before {
  content: "\e026";
}
.glyphicon-upload:before {
  content: "\e027";
}
.glyphicon-inbox:before {
  content: "\e028";
}
.glyphicon-play-circle:before {
  content: "\e029";
}
.glyphicon-repeat:before {
  content: "\e030";
}
.glyphicon-refresh:before {
  content: "\e031";
}
.glyphicon-list-alt:before {
  content: "\e032";
}
.glyphicon-lock:before {
  content: "\e033";
}
.glyphicon-flag:before {
  content: "\e034";
}
.glyphicon-headphones:before {
  content: "\e035";
}
.glyphicon-volume-off:before {
  content: "\e036";
}
.glyphicon-volume-down:before {
  content: "\e037";
}
.glyphicon-volume-up:before {
  content: "\e038";
}
.glyphicon-qrcode:before {
  content: "\e039";
}
.glyphicon-barcode:before {
  content: "\e040";
}
.glyphicon-tag:before {
  content: "\e041";
}
.glyphicon-tags:before {
  content: "\e042";
}
.glyphicon-book:before {
  content: "\e043";
}
.glyphicon-bookmark:before {
  content: "\e044";
}
.glyphicon-print:before {
  content: "\e045";
}
.glyphicon-camera:before {
  content: "\e046";
}
.glyphicon-font:before {
  content: "\e047";
}
.glyphicon-bold:before {
  content: "\e048";
}
.glyphicon-italic:before {
  content: "\e049";
}
.glyphicon-text-height:before {
  content: "\e050";
}
.glyphicon-text-width:before {
  content: "\e051";
}
.glyphicon-align-left:before {
  content: "\e052";
}
.glyphicon-align-center:before {
  content: "\e053";
}
.glyphicon-align-right:before {
  content: "\e054";
}
.glyphicon-align-justify:before {
  content: "\e055";
}
.glyphicon-list:before {
  content: "\e056";
}
.glyphicon-indent-left:before {
  content: "\e057";
}
.glyphicon-indent-right:before {
  content: "\e058";
}
.glyphicon-facetime-video:before {
  content: "\e059";
}
.glyphicon-picture:before {
  content: "\e060";
}
.glyphicon-map-marker:before {
  content: "\e062";
}
.glyphicon-adjust:before {
  content: "\e063";
}
.glyphicon-tint:before {
  content: "\e064";
}
.glyphicon-edit:before {
  content: "\e065";
}
.glyphicon-share:before {
  content: "\e066";
}
.glyphicon-check:before {
  content: "\e067";
}
.glyphicon-move:before {
  content: "\e068";
}
.glyphicon-step-backward:before {
  content: "\e069";
}
.glyphicon-fast-backward:before {
  content: "\e070";
}
.glyphicon-backward:before {
  content: "\e071";
}
.glyphicon-play:before {
  content: "\e072";
}
.glyphicon-pause:before {
  content: "\e073";
}
.glyphicon-stop:before {
  content: "\e074";
}
.glyphicon-forward:before {
  content: "\e075";
}
.glyphicon-fast-forward:before {
  content: "\e076";
}
.glyphicon-step-forward:before {
  content: "\e077";
}
.glyphicon-eject:before {
  content: "\e078";
}
.glyphicon-chevron-left:before {
  content: "\e079";
}
.glyphicon-chevron-right:before {
  content: "\e080";
}
.glyphicon-plus-sign:before {
  content: "\e081";
}
.glyphicon-minus-sign:before {
  content: "\e082";
}
.glyphicon-remove-sign:before {
  content: "\e083";
}
.glyphicon-ok-sign:before {
  content: "\e084";
}
.glyphicon-question-sign:before {
  content: "\e085";
}
.glyphicon-info-sign:before {
  content: "\e086";
}
.glyphicon-screenshot:before {
  content: "\e087";
}
.glyphicon-remove-circle:before {
  content: "\e088";
}
.glyphicon-ok-circle:before {
  content: "\e089";
}
.glyphicon-ban-circle:before {
  content: "\e090";
}
.glyphicon-arrow-left:before {
  content: "\e091";
}
.glyphicon-arrow-right:before {
  content: "\e092";
}
.glyphicon-arrow-up:before {
  content: "\e093";
}
.glyphicon-arrow-down:before {
  content: "\e094";
}
.glyphicon-share-alt:before {
  content: "\e095";
}
.glyphicon-resize-full:before {
  content: "\e096";
}
.glyphicon-resize-small:before {
  content: "\e097";
}
.glyphicon-exclamation-sign:before {
  content: "\e101";
}
.glyphicon-gift:before {
  content: "\e102";
}
.glyphicon-leaf:before {
  content: "\e103";
}
.glyphicon-fire:before {
  content: "\e104";
}
.glyphicon-eye-open:before {
  content: "\e105";
}
.glyphicon-eye-close:before {
  content: "\e106";
}
.glyphicon-warning-sign:before {
  content: "\e107";
}
.glyphicon-plane:before {
  content: "\e108";
}
.glyphicon-calendar:before {
  content: "\e109";
}
.glyphicon-random:before {
  content: "\e110";
}
.glyphicon-comment:before {
  content: "\e111";
}
.glyphicon-magnet:before {
  content: "\e112";
}
.glyphicon-chevron-up:before {
  content: "\e113";
}
.glyphicon-chevron-down:before {
  content: "\e114";
}
.glyphicon-retweet:before {
  content: "\e115";
}
.glyphicon-shopping-cart:before {
  content: "\e116";
}
.glyphicon-folder-close:before {
  content: "\e117";
}
.glyphicon-folder-open:before {
  content: "\e118";
}
.glyphicon-resize-vertical:before {
  content: "\e119";
}
.glyphicon-resize-horizontal:before {
  content: "\e120";
}
.glyphicon-hdd:before {
  content: "\e121";
}
.glyphicon-bullhorn:before {
  content: "\e122";
}
.glyphicon-bell:before {
  content: "\e123";
}
.glyphicon-certificate:before {
  content: "\e124";
}
.glyphicon-thumbs-up:before {
  content: "\e125";
}
.glyphicon-thumbs-down:before {
  content: "\e126";
}
.glyphicon-hand-right:before {
  content: "\e127";
}
.glyphicon-hand-left:before {
  content: "\e128";
}
.glyphicon-hand-up:before {
  content: "\e129";
}
.glyphicon-hand-down:before {
  content: "\e130";
}
.glyphicon-circle-arrow-right:before {
  content: "\e131";
}
.glyphicon-circle-arrow-left:before {
  content: "\e132";
}
.glyphicon-circle-arrow-up:before {
  content: "\e133";
}
.glyphicon-circle-arrow-down:before {
  content: "\e134";
}
.glyphicon-globe:before {
  content: "\e135";
}
.glyphicon-wrench:before {
  content: "\e136";
}
.glyphicon-tasks:before {
  content: "\e137";
}
.glyphicon-filter:before {
  content: "\e138";
}
.glyphicon-briefcase:before {
  content: "\e139";
}
.glyphicon-fullscreen:before {
  content: "\e140";
}
.glyphicon-dashboard:before {
  content: "\e141";
}
.glyphicon-paperclip:before {
  content: "\e142";
}
.glyphicon-heart-empty:before {
  content: "\e143";
}
.glyphicon-link:before {
  content: "\e144";
}
.glyphicon-phone:before {
  content: "\e145";
}
.glyphicon-pushpin:before {
  content: "\e146";
}
.glyphicon-usd:before {
  content: "\e148";
}
.glyphicon-gbp:before {
  content: "\e149";
}
.glyphicon-sort:before {
  content: "\e150";
}
.glyphicon-sort-by-alphabet:before {
  content: "\e151";
}
.glyphicon-sort-by-alphabet-alt:before {
  content: "\e152";
}
.glyphicon-sort-by-order:before {
  content: "\e153";
}
.glyphicon-sort-by-order-alt:before {
  content: "\e154";
}
.glyphicon-sort-by-attributes:before {
  content: "\e155";
}
.glyphicon-sort-by-attributes-alt:before {
  content: "\e156";
}
.glyphicon-unchecked:before {
  content: "\e157";
}
.glyphicon-expand:before {
  content: "\e158";
}
.glyphicon-collapse-down:before {
  content: "\e159";
}
.glyphicon-collapse-up:before {
  content: "\e160";
}
.glyphicon-log-in:before {
  content: "\e161";
}
.glyphicon-flash:before {
  content: "\e162";
}
.glyphicon-log-out:before {
  content: "\e163";
}
.glyphicon-new-window:before {
  content: "\e164";
}
.glyphicon-record:before {
  content: "\e165";
}
.glyphicon-save:before {
  content: "\e166";
}
.glyphicon-open:before {
  content: "\e167";
}
.glyphicon-saved:before {
  content: "\e168";
}
.glyphicon-import:before {
  content: "\e169";
}
.glyphicon-export:before {
  content: "\e170";
}
.glyphicon-send:before {
  content: "\e171";
}
.glyphicon-floppy-disk:before {
  content: "\e172";
}
.glyphicon-floppy-saved:before {
  content: "\e173";
}
.glyphicon-floppy-remove:before {
  content: "\e174";
}
.glyphicon-floppy-save:before {
  content: "\e175";
}
.glyphicon-floppy-open:before {
  content: "\e176";
}
.glyphicon-credit-card:before {
  content: "\e177";
}
.glyphicon-transfer:before {
  content: "\e178";
}
.glyphicon-cutlery:before {
  content: "\e179";
}
.glyphicon-header:before {
  content: "\e180";
}
.glyphicon-compressed:before {
  content: "\e181";
}
.glyphicon-earphone:before {
  content: "\e182";
}
.glyphicon-phone-alt:before {
  content: "\e183";
}
.glyphicon-tower:before {
  content: "\e184";
}
.glyphicon-stats:before {
  content: "\e185";
}
.glyphicon-sd-video:before {
  content: "\e186";
}
.glyphicon-hd-video:before {
  content: "\e187";
}
.glyphicon-subtitles:before {
  content: "\e188";
}
.glyphicon-sound-stereo:before {
  content: "\e189";
}
.glyphicon-sound-dolby:before {
  content: "\e190";
}
.glyphicon-sound-5-1:before {
  content: "\e191";
}
.glyphicon-sound-6-1:before {
  content: "\e192";
}
.glyphicon-sound-7-1:before {
  content: "\e193";
}
.glyphicon-copyright-mark:before {
  content: "\e194";
}
.glyphicon-registration-mark:before {
  content: "\e195";
}
.glyphicon-cloud-download:before {
  content: "\e197";
}
.glyphicon-cloud-upload:before {
  content: "\e198";
}
.glyphicon-tree-conifer:before {
  content: "\e199";
}
.glyphicon-tree-deciduous:before {
  content: "\e200";
}
.glyphicon-cd:before {
  content: "\e201";
}
.glyphicon-save-file:before {
  content: "\e202";
}
.glyphicon-open-file:before {
  content: "\e203";
}
.glyphicon-level-up:before {
  content: "\e204";
}
.glyphicon-copy:before {
  content: "\e205";
}
.glyphicon-paste:before {
  content: "\e206";
}
.glyphicon-alert:before {
  content: "\e209";
}
.glyphicon-equalizer:before {
  content: "\e210";
}
.glyphicon-king:before {
  content: "\e211";
}
.glyphicon-queen:before {
  content: "\e212";
}
.glyphicon-pawn:before {
  content: "\e213";
}
.glyphicon-bishop:before {
  content: "\e214";
}
.glyphicon-knight:before {
  content: "\e215";
}
.glyphicon-baby-formula:before {
  content: "\e216";
}
.glyphicon-tent:before {
  content: "\26fa";
}
.glyphicon-blackboard:before {
  content: "\e218";
}
.glyphicon-bed:before {
  content: "\e219";
}
.glyphicon-apple:before {
  content: "\f8ff";
}
.glyphicon-erase:before {
  content: "\e221";
}
.glyphicon-hourglass:before {
  content: "\231b";
}
.glyphicon-lamp:before {
  content: "\e223";
}
.glyphicon-duplicate:before {
  content: "\e224";
}
.glyphicon-piggy-bank:before {
  content: "\e225";
}
.glyphicon-scissors:before {
  content: "\e226";
}
.glyphicon-bitcoin:before {
  content: "\e227";
}
.glyphicon-btc:before {
  content: "\e227";
}
.glyphicon-xbt:before {
  content: "\e227";
}
.glyphicon-yen:before {
  content: "\00a5";
}
.glyphicon-jpy:before {
  content: "\00a5";
}
.glyphicon-ruble:before {
  content: "\20bd";
}
.glyphicon-rub:before {
  content: "\20bd";
}
.glyphicon-scale:before {
  content: "\e230";
}
.glyphicon-ice-lolly:before {
  content: "\e231";
}
.glyphicon-ice-lolly-tasted:before {
  content: "\e232";
}
.glyphicon-education:before {
  content: "\e233";
}
.glyphicon-option-horizontal:before {
  content: "\e234";
}
.glyphicon-option-vertical:before {
  content: "\e235";
}
.glyphicon-menu-hamburger:before {
  content: "\e236";
}
.glyphicon-modal-window:before {
  content: "\e237";
}
.glyphicon-oil:before {
  content: "\e238";
}
.glyphicon-grain:before {
  content: "\e239";
}
.glyphicon-sunglasses:before {
  content: "\e240";
}
.glyphicon-text-size:before {
  content: "\e241";
}
.glyphicon-text-color:before {
  content: "\e242";
}
.glyphicon-text-background:before {
  content: "\e243";
}
.glyphicon-object-align-top:before {
  content: "\e244";
}
.glyphicon-object-align-bottom:before {
  content: "\e245";
}
.glyphicon-object-align-horizontal:before {
  content: "\e246";
}
.glyphicon-object-align-left:before {
  content: "\e247";
}
.glyphicon-object-align-vertical:before {
  content: "\e248";
}
.glyphicon-object-align-right:before {
  content: "\e249";
}
.glyphicon-triangle-right:before {
  content: "\e250";
}
.glyphicon-triangle-left:before {
  content: "\e251";
}
.glyphicon-triangle-bottom:before {
  content: "\e252";
}
.glyphicon-triangle-top:before {
  content: "\e253";
}
.glyphicon-console:before {
  content: "\e254";
}
.glyphicon-superscript:before {
  content: "\e255";
}
.glyphicon-subscript:before {
  content: "\e256";
}
.glyphicon-menu-left:before {
  content: "\e257";
}
.glyphicon-menu-right:before {
  content: "\e258";
}
.glyphicon-menu-down:before {
  content: "\e259";
}
.glyphicon-menu-up:before {
  content: "\e260";
}
* {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
*:before,
*:after {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
html {
  font-size: 10px;
  -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
}
body {
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-size: 13px;
  line-height: 1.42857143;
  color: #000;
  background-color: #fff;
}
input,
button,
select,
textarea {
  font-family: inherit;
  font-size: inherit;
  line-height: inherit;
}
a {
  color: #337ab7;
  text-decoration: none;
}
a:hover,
a:focus {
  color: #23527c;
  text-decoration: underline;
}
a:focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
figure {
  margin: 0;
}
img {
  vertical-align: middle;
}
.img-responsive,
.thumbnail > img,
.thumbnail a > img,
.carousel-inner > .item > img,
.carousel-inner > .item > a > img {
  display: block;
  max-width: 100%;
  height: auto;
}
.img-rounded {
  border-radius: 3px;
}
.img-thumbnail {
  padding: 4px;
  line-height: 1.42857143;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 2px;
  -webkit-transition: all 0.2s ease-in-out;
  -o-transition: all 0.2s ease-in-out;
  transition: all 0.2s ease-in-out;
  display: inline-block;
  max-width: 100%;
  height: auto;
}
.img-circle {
  border-radius: 50%;
}
hr {
  margin-top: 18px;
  margin-bottom: 18px;
  border: 0;
  border-top: 1px solid #eeeeee;
}
.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  margin: -1px;
  padding: 0;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}
[role="button"] {
  cursor: pointer;
}
h1,
h2,
h3,
h4,
h5,
h6,
.h1,
.h2,
.h3,
.h4,
.h5,
.h6 {
  font-family: inherit;
  font-weight: 500;
  line-height: 1.1;
  color: inherit;
}
h1 small,
h2 small,
h3 small,
h4 small,
h5 small,
h6 small,
.h1 small,
.h2 small,
.h3 small,
.h4 small,
.h5 small,
.h6 small,
h1 .small,
h2 .small,
h3 .small,
h4 .small,
h5 .small,
h6 .small,
.h1 .small,
.h2 .small,
.h3 .small,
.h4 .small,
.h5 .small,
.h6 .small {
  font-weight: normal;
  line-height: 1;
  color: #777777;
}
h1,
.h1,
h2,
.h2,
h3,
.h3 {
  margin-top: 18px;
  margin-bottom: 9px;
}
h1 small,
.h1 small,
h2 small,
.h2 small,
h3 small,
.h3 small,
h1 .small,
.h1 .small,
h2 .small,
.h2 .small,
h3 .small,
.h3 .small {
  font-size: 65%;
}
h4,
.h4,
h5,
.h5,
h6,
.h6 {
  margin-top: 9px;
  margin-bottom: 9px;
}
h4 small,
.h4 small,
h5 small,
.h5 small,
h6 small,
.h6 small,
h4 .small,
.h4 .small,
h5 .small,
.h5 .small,
h6 .small,
.h6 .small {
  font-size: 75%;
}
h1,
.h1 {
  font-size: 33px;
}
h2,
.h2 {
  font-size: 27px;
}
h3,
.h3 {
  font-size: 23px;
}
h4,
.h4 {
  font-size: 17px;
}
h5,
.h5 {
  font-size: 13px;
}
h6,
.h6 {
  font-size: 12px;
}
p {
  margin: 0 0 9px;
}
.lead {
  margin-bottom: 18px;
  font-size: 14px;
  font-weight: 300;
  line-height: 1.4;
}
@media (min-width: 768px) {
  .lead {
    font-size: 19.5px;
  }
}
small,
.small {
  font-size: 92%;
}
mark,
.mark {
  background-color: #fcf8e3;
  padding: .2em;
}
.text-left {
  text-align: left;
}
.text-right {
  text-align: right;
}
.text-center {
  text-align: center;
}
.text-justify {
  text-align: justify;
}
.text-nowrap {
  white-space: nowrap;
}
.text-lowercase {
  text-transform: lowercase;
}
.text-uppercase {
  text-transform: uppercase;
}
.text-capitalize {
  text-transform: capitalize;
}
.text-muted {
  color: #777777;
}
.text-primary {
  color: #337ab7;
}
a.text-primary:hover,
a.text-primary:focus {
  color: #286090;
}
.text-success {
  color: #3c763d;
}
a.text-success:hover,
a.text-success:focus {
  color: #2b542c;
}
.text-info {
  color: #31708f;
}
a.text-info:hover,
a.text-info:focus {
  color: #245269;
}
.text-warning {
  color: #8a6d3b;
}
a.text-warning:hover,
a.text-warning:focus {
  color: #66512c;
}
.text-danger {
  color: #a94442;
}
a.text-danger:hover,
a.text-danger:focus {
  color: #843534;
}
.bg-primary {
  color: #fff;
  background-color: #337ab7;
}
a.bg-primary:hover,
a.bg-primary:focus {
  background-color: #286090;
}
.bg-success {
  background-color: #dff0d8;
}
a.bg-success:hover,
a.bg-success:focus {
  background-color: #c1e2b3;
}
.bg-info {
  background-color: #d9edf7;
}
a.bg-info:hover,
a.bg-info:focus {
  background-color: #afd9ee;
}
.bg-warning {
  background-color: #fcf8e3;
}
a.bg-warning:hover,
a.bg-warning:focus {
  background-color: #f7ecb5;
}
.bg-danger {
  background-color: #f2dede;
}
a.bg-danger:hover,
a.bg-danger:focus {
  background-color: #e4b9b9;
}
.page-header {
  padding-bottom: 8px;
  margin: 36px 0 18px;
  border-bottom: 1px solid #eeeeee;
}
ul,
ol {
  margin-top: 0;
  margin-bottom: 9px;
}
ul ul,
ol ul,
ul ol,
ol ol {
  margin-bottom: 0;
}
.list-unstyled {
  padding-left: 0;
  list-style: none;
}
.list-inline {
  padding-left: 0;
  list-style: none;
  margin-left: -5px;
}
.list-inline > li {
  display: inline-block;
  padding-left: 5px;
  padding-right: 5px;
}
dl {
  margin-top: 0;
  margin-bottom: 18px;
}
dt,
dd {
  line-height: 1.42857143;
}
dt {
  font-weight: bold;
}
dd {
  margin-left: 0;
}
@media (min-width: 541px) {
  .dl-horizontal dt {
    float: left;
    width: 160px;
    clear: left;
    text-align: right;
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
  }
  .dl-horizontal dd {
    margin-left: 180px;
  }
}
abbr[title],
abbr[data-original-title] {
  cursor: help;
  border-bottom: 1px dotted #777777;
}
.initialism {
  font-size: 90%;
  text-transform: uppercase;
}
blockquote {
  padding: 9px 18px;
  margin: 0 0 18px;
  font-size: inherit;
  border-left: 5px solid #eeeeee;
}
blockquote p:last-child,
blockquote ul:last-child,
blockquote ol:last-child {
  margin-bottom: 0;
}
blockquote footer,
blockquote small,
blockquote .small {
  display: block;
  font-size: 80%;
  line-height: 1.42857143;
  color: #777777;
}
blockquote footer:before,
blockquote small:before,
blockquote .small:before {
  content: '\2014 \00A0';
}
.blockquote-reverse,
blockquote.pull-right {
  padding-right: 15px;
  padding-left: 0;
  border-right: 5px solid #eeeeee;
  border-left: 0;
  text-align: right;
}
.blockquote-reverse footer:before,
blockquote.pull-right footer:before,
.blockquote-reverse small:before,
blockquote.pull-right small:before,
.blockquote-reverse .small:before,
blockquote.pull-right .small:before {
  content: '';
}
.blockquote-reverse footer:after,
blockquote.pull-right footer:after,
.blockquote-reverse small:after,
blockquote.pull-right small:after,
.blockquote-reverse .small:after,
blockquote.pull-right .small:after {
  content: '\00A0 \2014';
}
address {
  margin-bottom: 18px;
  font-style: normal;
  line-height: 1.42857143;
}
code,
kbd,
pre,
samp {
  font-family: monospace;
}
code {
  padding: 2px 4px;
  font-size: 90%;
  color: #c7254e;
  background-color: #f9f2f4;
  border-radius: 2px;
}
kbd {
  padding: 2px 4px;
  font-size: 90%;
  color: #888;
  background-color: transparent;
  border-radius: 1px;
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.25);
}
kbd kbd {
  padding: 0;
  font-size: 100%;
  font-weight: bold;
  box-shadow: none;
}
pre {
  display: block;
  padding: 8.5px;
  margin: 0 0 9px;
  font-size: 12px;
  line-height: 1.42857143;
  word-break: break-all;
  word-wrap: break-word;
  color: #333333;
  background-color: #f5f5f5;
  border: 1px solid #ccc;
  border-radius: 2px;
}
pre code {
  padding: 0;
  font-size: inherit;
  color: inherit;
  white-space: pre-wrap;
  background-color: transparent;
  border-radius: 0;
}
.pre-scrollable {
  max-height: 340px;
  overflow-y: scroll;
}
.container {
  margin-right: auto;
  margin-left: auto;
  padding-left: 0px;
  padding-right: 0px;
}
@media (min-width: 768px) {
  .container {
    width: 768px;
  }
}
@media (min-width: 992px) {
  .container {
    width: 940px;
  }
}
@media (min-width: 1200px) {
  .container {
    width: 1140px;
  }
}
.container-fluid {
  margin-right: auto;
  margin-left: auto;
  padding-left: 0px;
  padding-right: 0px;
}
.row {
  margin-left: 0px;
  margin-right: 0px;
}
.col-xs-1, .col-sm-1, .col-md-1, .col-lg-1, .col-xs-2, .col-sm-2, .col-md-2, .col-lg-2, .col-xs-3, .col-sm-3, .col-md-3, .col-lg-3, .col-xs-4, .col-sm-4, .col-md-4, .col-lg-4, .col-xs-5, .col-sm-5, .col-md-5, .col-lg-5, .col-xs-6, .col-sm-6, .col-md-6, .col-lg-6, .col-xs-7, .col-sm-7, .col-md-7, .col-lg-7, .col-xs-8, .col-sm-8, .col-md-8, .col-lg-8, .col-xs-9, .col-sm-9, .col-md-9, .col-lg-9, .col-xs-10, .col-sm-10, .col-md-10, .col-lg-10, .col-xs-11, .col-sm-11, .col-md-11, .col-lg-11, .col-xs-12, .col-sm-12, .col-md-12, .col-lg-12 {
  position: relative;
  min-height: 1px;
  padding-left: 0px;
  padding-right: 0px;
}
.col-xs-1, .col-xs-2, .col-xs-3, .col-xs-4, .col-xs-5, .col-xs-6, .col-xs-7, .col-xs-8, .col-xs-9, .col-xs-10, .col-xs-11, .col-xs-12 {
  float: left;
}
.col-xs-12 {
  width: 100%;
}
.col-xs-11 {
  width: 91.66666667%;
}
.col-xs-10 {
  width: 83.33333333%;
}
.col-xs-9 {
  width: 75%;
}
.col-xs-8 {
  width: 66.66666667%;
}
.col-xs-7 {
  width: 58.33333333%;
}
.col-xs-6 {
  width: 50%;
}
.col-xs-5 {
  width: 41.66666667%;
}
.col-xs-4 {
  width: 33.33333333%;
}
.col-xs-3 {
  width: 25%;
}
.col-xs-2 {
  width: 16.66666667%;
}
.col-xs-1 {
  width: 8.33333333%;
}
.col-xs-pull-12 {
  right: 100%;
}
.col-xs-pull-11 {
  right: 91.66666667%;
}
.col-xs-pull-10 {
  right: 83.33333333%;
}
.col-xs-pull-9 {
  right: 75%;
}
.col-xs-pull-8 {
  right: 66.66666667%;
}
.col-xs-pull-7 {
  right: 58.33333333%;
}
.col-xs-pull-6 {
  right: 50%;
}
.col-xs-pull-5 {
  right: 41.66666667%;
}
.col-xs-pull-4 {
  right: 33.33333333%;
}
.col-xs-pull-3 {
  right: 25%;
}
.col-xs-pull-2 {
  right: 16.66666667%;
}
.col-xs-pull-1 {
  right: 8.33333333%;
}
.col-xs-pull-0 {
  right: auto;
}
.col-xs-push-12 {
  left: 100%;
}
.col-xs-push-11 {
  left: 91.66666667%;
}
.col-xs-push-10 {
  left: 83.33333333%;
}
.col-xs-push-9 {
  left: 75%;
}
.col-xs-push-8 {
  left: 66.66666667%;
}
.col-xs-push-7 {
  left: 58.33333333%;
}
.col-xs-push-6 {
  left: 50%;
}
.col-xs-push-5 {
  left: 41.66666667%;
}
.col-xs-push-4 {
  left: 33.33333333%;
}
.col-xs-push-3 {
  left: 25%;
}
.col-xs-push-2 {
  left: 16.66666667%;
}
.col-xs-push-1 {
  left: 8.33333333%;
}
.col-xs-push-0 {
  left: auto;
}
.col-xs-offset-12 {
  margin-left: 100%;
}
.col-xs-offset-11 {
  margin-left: 91.66666667%;
}
.col-xs-offset-10 {
  margin-left: 83.33333333%;
}
.col-xs-offset-9 {
  margin-left: 75%;
}
.col-xs-offset-8 {
  margin-left: 66.66666667%;
}
.col-xs-offset-7 {
  margin-left: 58.33333333%;
}
.col-xs-offset-6 {
  margin-left: 50%;
}
.col-xs-offset-5 {
  margin-left: 41.66666667%;
}
.col-xs-offset-4 {
  margin-left: 33.33333333%;
}
.col-xs-offset-3 {
  margin-left: 25%;
}
.col-xs-offset-2 {
  margin-left: 16.66666667%;
}
.col-xs-offset-1 {
  margin-left: 8.33333333%;
}
.col-xs-offset-0 {
  margin-left: 0%;
}
@media (min-width: 768px) {
  .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12 {
    float: left;
  }
  .col-sm-12 {
    width: 100%;
  }
  .col-sm-11 {
    width: 91.66666667%;
  }
  .col-sm-10 {
    width: 83.33333333%;
  }
  .col-sm-9 {
    width: 75%;
  }
  .col-sm-8 {
    width: 66.66666667%;
  }
  .col-sm-7 {
    width: 58.33333333%;
  }
  .col-sm-6 {
    width: 50%;
  }
  .col-sm-5 {
    width: 41.66666667%;
  }
  .col-sm-4 {
    width: 33.33333333%;
  }
  .col-sm-3 {
    width: 25%;
  }
  .col-sm-2 {
    width: 16.66666667%;
  }
  .col-sm-1 {
    width: 8.33333333%;
  }
  .col-sm-pull-12 {
    right: 100%;
  }
  .col-sm-pull-11 {
    right: 91.66666667%;
  }
  .col-sm-pull-10 {
    right: 83.33333333%;
  }
  .col-sm-pull-9 {
    right: 75%;
  }
  .col-sm-pull-8 {
    right: 66.66666667%;
  }
  .col-sm-pull-7 {
    right: 58.33333333%;
  }
  .col-sm-pull-6 {
    right: 50%;
  }
  .col-sm-pull-5 {
    right: 41.66666667%;
  }
  .col-sm-pull-4 {
    right: 33.33333333%;
  }
  .col-sm-pull-3 {
    right: 25%;
  }
  .col-sm-pull-2 {
    right: 16.66666667%;
  }
  .col-sm-pull-1 {
    right: 8.33333333%;
  }
  .col-sm-pull-0 {
    right: auto;
  }
  .col-sm-push-12 {
    left: 100%;
  }
  .col-sm-push-11 {
    left: 91.66666667%;
  }
  .col-sm-push-10 {
    left: 83.33333333%;
  }
  .col-sm-push-9 {
    left: 75%;
  }
  .col-sm-push-8 {
    left: 66.66666667%;
  }
  .col-sm-push-7 {
    left: 58.33333333%;
  }
  .col-sm-push-6 {
    left: 50%;
  }
  .col-sm-push-5 {
    left: 41.66666667%;
  }
  .col-sm-push-4 {
    left: 33.33333333%;
  }
  .col-sm-push-3 {
    left: 25%;
  }
  .col-sm-push-2 {
    left: 16.66666667%;
  }
  .col-sm-push-1 {
    left: 8.33333333%;
  }
  .col-sm-push-0 {
    left: auto;
  }
  .col-sm-offset-12 {
    margin-left: 100%;
  }
  .col-sm-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-sm-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-sm-offset-9 {
    margin-left: 75%;
  }
  .col-sm-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-sm-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-sm-offset-6 {
    margin-left: 50%;
  }
  .col-sm-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-sm-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-sm-offset-3 {
    margin-left: 25%;
  }
  .col-sm-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-sm-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-sm-offset-0 {
    margin-left: 0%;
  }
}
@media (min-width: 992px) {
  .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
    float: left;
  }
  .col-md-12 {
    width: 100%;
  }
  .col-md-11 {
    width: 91.66666667%;
  }
  .col-md-10 {
    width: 83.33333333%;
  }
  .col-md-9 {
    width: 75%;
  }
  .col-md-8 {
    width: 66.66666667%;
  }
  .col-md-7 {
    width: 58.33333333%;
  }
  .col-md-6 {
    width: 50%;
  }
  .col-md-5 {
    width: 41.66666667%;
  }
  .col-md-4 {
    width: 33.33333333%;
  }
  .col-md-3 {
    width: 25%;
  }
  .col-md-2 {
    width: 16.66666667%;
  }
  .col-md-1 {
    width: 8.33333333%;
  }
  .col-md-pull-12 {
    right: 100%;
  }
  .col-md-pull-11 {
    right: 91.66666667%;
  }
  .col-md-pull-10 {
    right: 83.33333333%;
  }
  .col-md-pull-9 {
    right: 75%;
  }
  .col-md-pull-8 {
    right: 66.66666667%;
  }
  .col-md-pull-7 {
    right: 58.33333333%;
  }
  .col-md-pull-6 {
    right: 50%;
  }
  .col-md-pull-5 {
    right: 41.66666667%;
  }
  .col-md-pull-4 {
    right: 33.33333333%;
  }
  .col-md-pull-3 {
    right: 25%;
  }
  .col-md-pull-2 {
    right: 16.66666667%;
  }
  .col-md-pull-1 {
    right: 8.33333333%;
  }
  .col-md-pull-0 {
    right: auto;
  }
  .col-md-push-12 {
    left: 100%;
  }
  .col-md-push-11 {
    left: 91.66666667%;
  }
  .col-md-push-10 {
    left: 83.33333333%;
  }
  .col-md-push-9 {
    left: 75%;
  }
  .col-md-push-8 {
    left: 66.66666667%;
  }
  .col-md-push-7 {
    left: 58.33333333%;
  }
  .col-md-push-6 {
    left: 50%;
  }
  .col-md-push-5 {
    left: 41.66666667%;
  }
  .col-md-push-4 {
    left: 33.33333333%;
  }
  .col-md-push-3 {
    left: 25%;
  }
  .col-md-push-2 {
    left: 16.66666667%;
  }
  .col-md-push-1 {
    left: 8.33333333%;
  }
  .col-md-push-0 {
    left: auto;
  }
  .col-md-offset-12 {
    margin-left: 100%;
  }
  .col-md-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-md-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-md-offset-9 {
    margin-left: 75%;
  }
  .col-md-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-md-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-md-offset-6 {
    margin-left: 50%;
  }
  .col-md-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-md-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-md-offset-3 {
    margin-left: 25%;
  }
  .col-md-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-md-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-md-offset-0 {
    margin-left: 0%;
  }
}
@media (min-width: 1200px) {
  .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
    float: left;
  }
  .col-lg-12 {
    width: 100%;
  }
  .col-lg-11 {
    width: 91.66666667%;
  }
  .col-lg-10 {
    width: 83.33333333%;
  }
  .col-lg-9 {
    width: 75%;
  }
  .col-lg-8 {
    width: 66.66666667%;
  }
  .col-lg-7 {
    width: 58.33333333%;
  }
  .col-lg-6 {
    width: 50%;
  }
  .col-lg-5 {
    width: 41.66666667%;
  }
  .col-lg-4 {
    width: 33.33333333%;
  }
  .col-lg-3 {
    width: 25%;
  }
  .col-lg-2 {
    width: 16.66666667%;
  }
  .col-lg-1 {
    width: 8.33333333%;
  }
  .col-lg-pull-12 {
    right: 100%;
  }
  .col-lg-pull-11 {
    right: 91.66666667%;
  }
  .col-lg-pull-10 {
    right: 83.33333333%;
  }
  .col-lg-pull-9 {
    right: 75%;
  }
  .col-lg-pull-8 {
    right: 66.66666667%;
  }
  .col-lg-pull-7 {
    right: 58.33333333%;
  }
  .col-lg-pull-6 {
    right: 50%;
  }
  .col-lg-pull-5 {
    right: 41.66666667%;
  }
  .col-lg-pull-4 {
    right: 33.33333333%;
  }
  .col-lg-pull-3 {
    right: 25%;
  }
  .col-lg-pull-2 {
    right: 16.66666667%;
  }
  .col-lg-pull-1 {
    right: 8.33333333%;
  }
  .col-lg-pull-0 {
    right: auto;
  }
  .col-lg-push-12 {
    left: 100%;
  }
  .col-lg-push-11 {
    left: 91.66666667%;
  }
  .col-lg-push-10 {
    left: 83.33333333%;
  }
  .col-lg-push-9 {
    left: 75%;
  }
  .col-lg-push-8 {
    left: 66.66666667%;
  }
  .col-lg-push-7 {
    left: 58.33333333%;
  }
  .col-lg-push-6 {
    left: 50%;
  }
  .col-lg-push-5 {
    left: 41.66666667%;
  }
  .col-lg-push-4 {
    left: 33.33333333%;
  }
  .col-lg-push-3 {
    left: 25%;
  }
  .col-lg-push-2 {
    left: 16.66666667%;
  }
  .col-lg-push-1 {
    left: 8.33333333%;
  }
  .col-lg-push-0 {
    left: auto;
  }
  .col-lg-offset-12 {
    margin-left: 100%;
  }
  .col-lg-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-lg-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-lg-offset-9 {
    margin-left: 75%;
  }
  .col-lg-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-lg-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-lg-offset-6 {
    margin-left: 50%;
  }
  .col-lg-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-lg-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-lg-offset-3 {
    margin-left: 25%;
  }
  .col-lg-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-lg-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-lg-offset-0 {
    margin-left: 0%;
  }
}
table {
  background-color: transparent;
}
caption {
  padding-top: 8px;
  padding-bottom: 8px;
  color: #777777;
  text-align: left;
}
th {
  text-align: left;
}
.table {
  width: 100%;
  max-width: 100%;
  margin-bottom: 18px;
}
.table > thead > tr > th,
.table > tbody > tr > th,
.table > tfoot > tr > th,
.table > thead > tr > td,
.table > tbody > tr > td,
.table > tfoot > tr > td {
  padding: 8px;
  line-height: 1.42857143;
  vertical-align: top;
  border-top: 1px solid #ddd;
}
.table > thead > tr > th {
  vertical-align: bottom;
  border-bottom: 2px solid #ddd;
}
.table > caption + thead > tr:first-child > th,
.table > colgroup + thead > tr:first-child > th,
.table > thead:first-child > tr:first-child > th,
.table > caption + thead > tr:first-child > td,
.table > colgroup + thead > tr:first-child > td,
.table > thead:first-child > tr:first-child > td {
  border-top: 0;
}
.table > tbody + tbody {
  border-top: 2px solid #ddd;
}
.table .table {
  background-color: #fff;
}
.table-condensed > thead > tr > th,
.table-condensed > tbody > tr > th,
.table-condensed > tfoot > tr > th,
.table-condensed > thead > tr > td,
.table-condensed > tbody > tr > td,
.table-condensed > tfoot > tr > td {
  padding: 5px;
}
.table-bordered {
  border: 1px solid #ddd;
}
.table-bordered > thead > tr > th,
.table-bordered > tbody > tr > th,
.table-bordered > tfoot > tr > th,
.table-bordered > thead > tr > td,
.table-bordered > tbody > tr > td,
.table-bordered > tfoot > tr > td {
  border: 1px solid #ddd;
}
.table-bordered > thead > tr > th,
.table-bordered > thead > tr > td {
  border-bottom-width: 2px;
}
.table-striped > tbody > tr:nth-of-type(odd) {
  background-color: #f9f9f9;
}
.table-hover > tbody > tr:hover {
  background-color: #f5f5f5;
}
table col[class*="col-"] {
  position: static;
  float: none;
  display: table-column;
}
table td[class*="col-"],
table th[class*="col-"] {
  position: static;
  float: none;
  display: table-cell;
}
.table > thead > tr > td.active,
.table > tbody > tr > td.active,
.table > tfoot > tr > td.active,
.table > thead > tr > th.active,
.table > tbody > tr > th.active,
.table > tfoot > tr > th.active,
.table > thead > tr.active > td,
.table > tbody > tr.active > td,
.table > tfoot > tr.active > td,
.table > thead > tr.active > th,
.table > tbody > tr.active > th,
.table > tfoot > tr.active > th {
  background-color: #f5f5f5;
}
.table-hover > tbody > tr > td.active:hover,
.table-hover > tbody > tr > th.active:hover,
.table-hover > tbody > tr.active:hover > td,
.table-hover > tbody > tr:hover > .active,
.table-hover > tbody > tr.active:hover > th {
  background-color: #e8e8e8;
}
.table > thead > tr > td.success,
.table > tbody > tr > td.success,
.table > tfoot > tr > td.success,
.table > thead > tr > th.success,
.table > tbody > tr > th.success,
.table > tfoot > tr > th.success,
.table > thead > tr.success > td,
.table > tbody > tr.success > td,
.table > tfoot > tr.success > td,
.table > thead > tr.success > th,
.table > tbody > tr.success > th,
.table > tfoot > tr.success > th {
  background-color: #dff0d8;
}
.table-hover > tbody > tr > td.success:hover,
.table-hover > tbody > tr > th.success:hover,
.table-hover > tbody > tr.success:hover > td,
.table-hover > tbody > tr:hover > .success,
.table-hover > tbody > tr.success:hover > th {
  background-color: #d0e9c6;
}
.table > thead > tr > td.info,
.table > tbody > tr > td.info,
.table > tfoot > tr > td.info,
.table > thead > tr > th.info,
.table > tbody > tr > th.info,
.table > tfoot > tr > th.info,
.table > thead > tr.info > td,
.table > tbody > tr.info > td,
.table > tfoot > tr.info > td,
.table > thead > tr.info > th,
.table > tbody > tr.info > th,
.table > tfoot > tr.info > th {
  background-color: #d9edf7;
}
.table-hover > tbody > tr > td.info:hover,
.table-hover > tbody > tr > th.info:hover,
.table-hover > tbody > tr.info:hover > td,
.table-hover > tbody > tr:hover > .info,
.table-hover > tbody > tr.info:hover > th {
  background-color: #c4e3f3;
}
.table > thead > tr > td.warning,
.table > tbody > tr > td.warning,
.table > tfoot > tr > td.warning,
.table > thead > tr > th.warning,
.table > tbody > tr > th.warning,
.table > tfoot > tr > th.warning,
.table > thead > tr.warning > td,
.table > tbody > tr.warning > td,
.table > tfoot > tr.warning > td,
.table > thead > tr.warning > th,
.table > tbody > tr.warning > th,
.table > tfoot > tr.warning > th {
  background-color: #fcf8e3;
}
.table-hover > tbody > tr > td.warning:hover,
.table-hover > tbody > tr > th.warning:hover,
.table-hover > tbody > tr.warning:hover > td,
.table-hover > tbody > tr:hover > .warning,
.table-hover > tbody > tr.warning:hover > th {
  background-color: #faf2cc;
}
.table > thead > tr > td.danger,
.table > tbody > tr > td.danger,
.table > tfoot > tr > td.danger,
.table > thead > tr > th.danger,
.table > tbody > tr > th.danger,
.table > tfoot > tr > th.danger,
.table > thead > tr.danger > td,
.table > tbody > tr.danger > td,
.table > tfoot > tr.danger > td,
.table > thead > tr.danger > th,
.table > tbody > tr.danger > th,
.table > tfoot > tr.danger > th {
  background-color: #f2dede;
}
.table-hover > tbody > tr > td.danger:hover,
.table-hover > tbody > tr > th.danger:hover,
.table-hover > tbody > tr.danger:hover > td,
.table-hover > tbody > tr:hover > .danger,
.table-hover > tbody > tr.danger:hover > th {
  background-color: #ebcccc;
}
.table-responsive {
  overflow-x: auto;
  min-height: 0.01%;
}
@media screen and (max-width: 767px) {
  .table-responsive {
    width: 100%;
    margin-bottom: 13.5px;
    overflow-y: hidden;
    -ms-overflow-style: -ms-autohiding-scrollbar;
    border: 1px solid #ddd;
  }
  .table-responsive > .table {
    margin-bottom: 0;
  }
  .table-responsive > .table > thead > tr > th,
  .table-responsive > .table > tbody > tr > th,
  .table-responsive > .table > tfoot > tr > th,
  .table-responsive > .table > thead > tr > td,
  .table-responsive > .table > tbody > tr > td,
  .table-responsive > .table > tfoot > tr > td {
    white-space: nowrap;
  }
  .table-responsive > .table-bordered {
    border: 0;
  }
  .table-responsive > .table-bordered > thead > tr > th:first-child,
  .table-responsive > .table-bordered > tbody > tr > th:first-child,
  .table-responsive > .table-bordered > tfoot > tr > th:first-child,
  .table-responsive > .table-bordered > thead > tr > td:first-child,
  .table-responsive > .table-bordered > tbody > tr > td:first-child,
  .table-responsive > .table-bordered > tfoot > tr > td:first-child {
    border-left: 0;
  }
  .table-responsive > .table-bordered > thead > tr > th:last-child,
  .table-responsive > .table-bordered > tbody > tr > th:last-child,
  .table-responsive > .table-bordered > tfoot > tr > th:last-child,
  .table-responsive > .table-bordered > thead > tr > td:last-child,
  .table-responsive > .table-bordered > tbody > tr > td:last-child,
  .table-responsive > .table-bordered > tfoot > tr > td:last-child {
    border-right: 0;
  }
  .table-responsive > .table-bordered > tbody > tr:last-child > th,
  .table-responsive > .table-bordered > tfoot > tr:last-child > th,
  .table-responsive > .table-bordered > tbody > tr:last-child > td,
  .table-responsive > .table-bordered > tfoot > tr:last-child > td {
    border-bottom: 0;
  }
}
fieldset {
  padding: 0;
  margin: 0;
  border: 0;
  min-width: 0;
}
legend {
  display: block;
  width: 100%;
  padding: 0;
  margin-bottom: 18px;
  font-size: 19.5px;
  line-height: inherit;
  color: #333333;
  border: 0;
  border-bottom: 1px solid #e5e5e5;
}
label {
  display: inline-block;
  max-width: 100%;
  margin-bottom: 5px;
  font-weight: bold;
}
input[type="search"] {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
input[type="radio"],
input[type="checkbox"] {
  margin: 4px 0 0;
  margin-top: 1px \9;
  line-height: normal;
}
input[type="file"] {
  display: block;
}
input[type="range"] {
  display: block;
  width: 100%;
}
select[multiple],
select[size] {
  height: auto;
}
input[type="file"]:focus,
input[type="radio"]:focus,
input[type="checkbox"]:focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
output {
  display: block;
  padding-top: 7px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
}
.form-control {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
}
.form-control:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.form-control::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.form-control:-ms-input-placeholder {
  color: #999;
}
.form-control::-webkit-input-placeholder {
  color: #999;
}
.form-control::-ms-expand {
  border: 0;
  background-color: transparent;
}
.form-control[disabled],
.form-control[readonly],
fieldset[disabled] .form-control {
  background-color: #eeeeee;
  opacity: 1;
}
.form-control[disabled],
fieldset[disabled] .form-control {
  cursor: not-allowed;
}
textarea.form-control {
  height: auto;
}
input[type="search"] {
  -webkit-appearance: none;
}
@media screen and (-webkit-min-device-pixel-ratio: 0) {
  input[type="date"].form-control,
  input[type="time"].form-control,
  input[type="datetime-local"].form-control,
  input[type="month"].form-control {
    line-height: 32px;
  }
  input[type="date"].input-sm,
  input[type="time"].input-sm,
  input[type="datetime-local"].input-sm,
  input[type="month"].input-sm,
  .input-group-sm input[type="date"],
  .input-group-sm input[type="time"],
  .input-group-sm input[type="datetime-local"],
  .input-group-sm input[type="month"] {
    line-height: 30px;
  }
  input[type="date"].input-lg,
  input[type="time"].input-lg,
  input[type="datetime-local"].input-lg,
  input[type="month"].input-lg,
  .input-group-lg input[type="date"],
  .input-group-lg input[type="time"],
  .input-group-lg input[type="datetime-local"],
  .input-group-lg input[type="month"] {
    line-height: 45px;
  }
}
.form-group {
  margin-bottom: 15px;
}
.radio,
.checkbox {
  position: relative;
  display: block;
  margin-top: 10px;
  margin-bottom: 10px;
}
.radio label,
.checkbox label {
  min-height: 18px;
  padding-left: 20px;
  margin-bottom: 0;
  font-weight: normal;
  cursor: pointer;
}
.radio input[type="radio"],
.radio-inline input[type="radio"],
.checkbox input[type="checkbox"],
.checkbox-inline input[type="checkbox"] {
  position: absolute;
  margin-left: -20px;
  margin-top: 4px \9;
}
.radio + .radio,
.checkbox + .checkbox {
  margin-top: -5px;
}
.radio-inline,
.checkbox-inline {
  position: relative;
  display: inline-block;
  padding-left: 20px;
  margin-bottom: 0;
  vertical-align: middle;
  font-weight: normal;
  cursor: pointer;
}
.radio-inline + .radio-inline,
.checkbox-inline + .checkbox-inline {
  margin-top: 0;
  margin-left: 10px;
}
input[type="radio"][disabled],
input[type="checkbox"][disabled],
input[type="radio"].disabled,
input[type="checkbox"].disabled,
fieldset[disabled] input[type="radio"],
fieldset[disabled] input[type="checkbox"] {
  cursor: not-allowed;
}
.radio-inline.disabled,
.checkbox-inline.disabled,
fieldset[disabled] .radio-inline,
fieldset[disabled] .checkbox-inline {
  cursor: not-allowed;
}
.radio.disabled label,
.checkbox.disabled label,
fieldset[disabled] .radio label,
fieldset[disabled] .checkbox label {
  cursor: not-allowed;
}
.form-control-static {
  padding-top: 7px;
  padding-bottom: 7px;
  margin-bottom: 0;
  min-height: 31px;
}
.form-control-static.input-lg,
.form-control-static.input-sm {
  padding-left: 0;
  padding-right: 0;
}
.input-sm {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
select.input-sm {
  height: 30px;
  line-height: 30px;
}
textarea.input-sm,
select[multiple].input-sm {
  height: auto;
}
.form-group-sm .form-control {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.form-group-sm select.form-control {
  height: 30px;
  line-height: 30px;
}
.form-group-sm textarea.form-control,
.form-group-sm select[multiple].form-control {
  height: auto;
}
.form-group-sm .form-control-static {
  height: 30px;
  min-height: 30px;
  padding: 6px 10px;
  font-size: 12px;
  line-height: 1.5;
}
.input-lg {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
select.input-lg {
  height: 45px;
  line-height: 45px;
}
textarea.input-lg,
select[multiple].input-lg {
  height: auto;
}
.form-group-lg .form-control {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
.form-group-lg select.form-control {
  height: 45px;
  line-height: 45px;
}
.form-group-lg textarea.form-control,
.form-group-lg select[multiple].form-control {
  height: auto;
}
.form-group-lg .form-control-static {
  height: 45px;
  min-height: 35px;
  padding: 11px 16px;
  font-size: 17px;
  line-height: 1.3333333;
}
.has-feedback {
  position: relative;
}
.has-feedback .form-control {
  padding-right: 40px;
}
.form-control-feedback {
  position: absolute;
  top: 0;
  right: 0;
  z-index: 2;
  display: block;
  width: 32px;
  height: 32px;
  line-height: 32px;
  text-align: center;
  pointer-events: none;
}
.input-lg + .form-control-feedback,
.input-group-lg + .form-control-feedback,
.form-group-lg .form-control + .form-control-feedback {
  width: 45px;
  height: 45px;
  line-height: 45px;
}
.input-sm + .form-control-feedback,
.input-group-sm + .form-control-feedback,
.form-group-sm .form-control + .form-control-feedback {
  width: 30px;
  height: 30px;
  line-height: 30px;
}
.has-success .help-block,
.has-success .control-label,
.has-success .radio,
.has-success .checkbox,
.has-success .radio-inline,
.has-success .checkbox-inline,
.has-success.radio label,
.has-success.checkbox label,
.has-success.radio-inline label,
.has-success.checkbox-inline label {
  color: #3c763d;
}
.has-success .form-control {
  border-color: #3c763d;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-success .form-control:focus {
  border-color: #2b542c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
}
.has-success .input-group-addon {
  color: #3c763d;
  border-color: #3c763d;
  background-color: #dff0d8;
}
.has-success .form-control-feedback {
  color: #3c763d;
}
.has-warning .help-block,
.has-warning .control-label,
.has-warning .radio,
.has-warning .checkbox,
.has-warning .radio-inline,
.has-warning .checkbox-inline,
.has-warning.radio label,
.has-warning.checkbox label,
.has-warning.radio-inline label,
.has-warning.checkbox-inline label {
  color: #8a6d3b;
}
.has-warning .form-control {
  border-color: #8a6d3b;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-warning .form-control:focus {
  border-color: #66512c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
}
.has-warning .input-group-addon {
  color: #8a6d3b;
  border-color: #8a6d3b;
  background-color: #fcf8e3;
}
.has-warning .form-control-feedback {
  color: #8a6d3b;
}
.has-error .help-block,
.has-error .control-label,
.has-error .radio,
.has-error .checkbox,
.has-error .radio-inline,
.has-error .checkbox-inline,
.has-error.radio label,
.has-error.checkbox label,
.has-error.radio-inline label,
.has-error.checkbox-inline label {
  color: #a94442;
}
.has-error .form-control {
  border-color: #a94442;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-error .form-control:focus {
  border-color: #843534;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
}
.has-error .input-group-addon {
  color: #a94442;
  border-color: #a94442;
  background-color: #f2dede;
}
.has-error .form-control-feedback {
  color: #a94442;
}
.has-feedback label ~ .form-control-feedback {
  top: 23px;
}
.has-feedback label.sr-only ~ .form-control-feedback {
  top: 0;
}
.help-block {
  display: block;
  margin-top: 5px;
  margin-bottom: 10px;
  color: #404040;
}
@media (min-width: 768px) {
  .form-inline .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle;
  }
  .form-inline .form-control-static {
    display: inline-block;
  }
  .form-inline .input-group {
    display: inline-table;
    vertical-align: middle;
  }
  .form-inline .input-group .input-group-addon,
  .form-inline .input-group .input-group-btn,
  .form-inline .input-group .form-control {
    width: auto;
  }
  .form-inline .input-group > .form-control {
    width: 100%;
  }
  .form-inline .control-label {
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .radio,
  .form-inline .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .radio label,
  .form-inline .checkbox label {
    padding-left: 0;
  }
  .form-inline .radio input[type="radio"],
  .form-inline .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0;
  }
  .form-inline .has-feedback .form-control-feedback {
    top: 0;
  }
}
.form-horizontal .radio,
.form-horizontal .checkbox,
.form-horizontal .radio-inline,
.form-horizontal .checkbox-inline {
  margin-top: 0;
  margin-bottom: 0;
  padding-top: 7px;
}
.form-horizontal .radio,
.form-horizontal .checkbox {
  min-height: 25px;
}
.form-horizontal .form-group {
  margin-left: 0px;
  margin-right: 0px;
}
@media (min-width: 768px) {
  .form-horizontal .control-label {
    text-align: right;
    margin-bottom: 0;
    padding-top: 7px;
  }
}
.form-horizontal .has-feedback .form-control-feedback {
  right: 0px;
}
@media (min-width: 768px) {
  .form-horizontal .form-group-lg .control-label {
    padding-top: 11px;
    font-size: 17px;
  }
}
@media (min-width: 768px) {
  .form-horizontal .form-group-sm .control-label {
    padding-top: 6px;
    font-size: 12px;
  }
}
.btn {
  display: inline-block;
  margin-bottom: 0;
  font-weight: normal;
  text-align: center;
  vertical-align: middle;
  touch-action: manipulation;
  cursor: pointer;
  background-image: none;
  border: 1px solid transparent;
  white-space: nowrap;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  border-radius: 2px;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}
.btn:focus,
.btn:active:focus,
.btn.active:focus,
.btn.focus,
.btn:active.focus,
.btn.active.focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
.btn:hover,
.btn:focus,
.btn.focus {
  color: #333;
  text-decoration: none;
}
.btn:active,
.btn.active {
  outline: 0;
  background-image: none;
  -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
}
.btn.disabled,
.btn[disabled],
fieldset[disabled] .btn {
  cursor: not-allowed;
  opacity: 0.65;
  filter: alpha(opacity=65);
  -webkit-box-shadow: none;
  box-shadow: none;
}
a.btn.disabled,
fieldset[disabled] a.btn {
  pointer-events: none;
}
.btn-default {
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
.btn-default:focus,
.btn-default.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
.btn-default:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.btn-default:active,
.btn-default.active,
.open > .dropdown-toggle.btn-default {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.btn-default:active:hover,
.btn-default.active:hover,
.open > .dropdown-toggle.btn-default:hover,
.btn-default:active:focus,
.btn-default.active:focus,
.open > .dropdown-toggle.btn-default:focus,
.btn-default:active.focus,
.btn-default.active.focus,
.open > .dropdown-toggle.btn-default.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
.btn-default:active,
.btn-default.active,
.open > .dropdown-toggle.btn-default {
  background-image: none;
}
.btn-default.disabled:hover,
.btn-default[disabled]:hover,
fieldset[disabled] .btn-default:hover,
.btn-default.disabled:focus,
.btn-default[disabled]:focus,
fieldset[disabled] .btn-default:focus,
.btn-default.disabled.focus,
.btn-default[disabled].focus,
fieldset[disabled] .btn-default.focus {
  background-color: #fff;
  border-color: #ccc;
}
.btn-default .badge {
  color: #fff;
  background-color: #333;
}
.btn-primary {
  color: #fff;
  background-color: #337ab7;
  border-color: #2e6da4;
}
.btn-primary:focus,
.btn-primary.focus {
  color: #fff;
  background-color: #286090;
  border-color: #122b40;
}
.btn-primary:hover {
  color: #fff;
  background-color: #286090;
  border-color: #204d74;
}
.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
  color: #fff;
  background-color: #286090;
  border-color: #204d74;
}
.btn-primary:active:hover,
.btn-primary.active:hover,
.open > .dropdown-toggle.btn-primary:hover,
.btn-primary:active:focus,
.btn-primary.active:focus,
.open > .dropdown-toggle.btn-primary:focus,
.btn-primary:active.focus,
.btn-primary.active.focus,
.open > .dropdown-toggle.btn-primary.focus {
  color: #fff;
  background-color: #204d74;
  border-color: #122b40;
}
.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
  background-image: none;
}
.btn-primary.disabled:hover,
.btn-primary[disabled]:hover,
fieldset[disabled] .btn-primary:hover,
.btn-primary.disabled:focus,
.btn-primary[disabled]:focus,
fieldset[disabled] .btn-primary:focus,
.btn-primary.disabled.focus,
.btn-primary[disabled].focus,
fieldset[disabled] .btn-primary.focus {
  background-color: #337ab7;
  border-color: #2e6da4;
}
.btn-primary .badge {
  color: #337ab7;
  background-color: #fff;
}
.btn-success {
  color: #fff;
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.btn-success:focus,
.btn-success.focus {
  color: #fff;
  background-color: #449d44;
  border-color: #255625;
}
.btn-success:hover {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.btn-success:active,
.btn-success.active,
.open > .dropdown-toggle.btn-success {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.btn-success:active:hover,
.btn-success.active:hover,
.open > .dropdown-toggle.btn-success:hover,
.btn-success:active:focus,
.btn-success.active:focus,
.open > .dropdown-toggle.btn-success:focus,
.btn-success:active.focus,
.btn-success.active.focus,
.open > .dropdown-toggle.btn-success.focus {
  color: #fff;
  background-color: #398439;
  border-color: #255625;
}
.btn-success:active,
.btn-success.active,
.open > .dropdown-toggle.btn-success {
  background-image: none;
}
.btn-success.disabled:hover,
.btn-success[disabled]:hover,
fieldset[disabled] .btn-success:hover,
.btn-success.disabled:focus,
.btn-success[disabled]:focus,
fieldset[disabled] .btn-success:focus,
.btn-success.disabled.focus,
.btn-success[disabled].focus,
fieldset[disabled] .btn-success.focus {
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.btn-success .badge {
  color: #5cb85c;
  background-color: #fff;
}
.btn-info {
  color: #fff;
  background-color: #5bc0de;
  border-color: #46b8da;
}
.btn-info:focus,
.btn-info.focus {
  color: #fff;
  background-color: #31b0d5;
  border-color: #1b6d85;
}
.btn-info:hover {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.btn-info:active,
.btn-info.active,
.open > .dropdown-toggle.btn-info {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.btn-info:active:hover,
.btn-info.active:hover,
.open > .dropdown-toggle.btn-info:hover,
.btn-info:active:focus,
.btn-info.active:focus,
.open > .dropdown-toggle.btn-info:focus,
.btn-info:active.focus,
.btn-info.active.focus,
.open > .dropdown-toggle.btn-info.focus {
  color: #fff;
  background-color: #269abc;
  border-color: #1b6d85;
}
.btn-info:active,
.btn-info.active,
.open > .dropdown-toggle.btn-info {
  background-image: none;
}
.btn-info.disabled:hover,
.btn-info[disabled]:hover,
fieldset[disabled] .btn-info:hover,
.btn-info.disabled:focus,
.btn-info[disabled]:focus,
fieldset[disabled] .btn-info:focus,
.btn-info.disabled.focus,
.btn-info[disabled].focus,
fieldset[disabled] .btn-info.focus {
  background-color: #5bc0de;
  border-color: #46b8da;
}
.btn-info .badge {
  color: #5bc0de;
  background-color: #fff;
}
.btn-warning {
  color: #fff;
  background-color: #f0ad4e;
  border-color: #eea236;
}
.btn-warning:focus,
.btn-warning.focus {
  color: #fff;
  background-color: #ec971f;
  border-color: #985f0d;
}
.btn-warning:hover {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.btn-warning:active,
.btn-warning.active,
.open > .dropdown-toggle.btn-warning {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.btn-warning:active:hover,
.btn-warning.active:hover,
.open > .dropdown-toggle.btn-warning:hover,
.btn-warning:active:focus,
.btn-warning.active:focus,
.open > .dropdown-toggle.btn-warning:focus,
.btn-warning:active.focus,
.btn-warning.active.focus,
.open > .dropdown-toggle.btn-warning.focus {
  color: #fff;
  background-color: #d58512;
  border-color: #985f0d;
}
.btn-warning:active,
.btn-warning.active,
.open > .dropdown-toggle.btn-warning {
  background-image: none;
}
.btn-warning.disabled:hover,
.btn-warning[disabled]:hover,
fieldset[disabled] .btn-warning:hover,
.btn-warning.disabled:focus,
.btn-warning[disabled]:focus,
fieldset[disabled] .btn-warning:focus,
.btn-warning.disabled.focus,
.btn-warning[disabled].focus,
fieldset[disabled] .btn-warning.focus {
  background-color: #f0ad4e;
  border-color: #eea236;
}
.btn-warning .badge {
  color: #f0ad4e;
  background-color: #fff;
}
.btn-danger {
  color: #fff;
  background-color: #d9534f;
  border-color: #d43f3a;
}
.btn-danger:focus,
.btn-danger.focus {
  color: #fff;
  background-color: #c9302c;
  border-color: #761c19;
}
.btn-danger:hover {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.btn-danger:active,
.btn-danger.active,
.open > .dropdown-toggle.btn-danger {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.btn-danger:active:hover,
.btn-danger.active:hover,
.open > .dropdown-toggle.btn-danger:hover,
.btn-danger:active:focus,
.btn-danger.active:focus,
.open > .dropdown-toggle.btn-danger:focus,
.btn-danger:active.focus,
.btn-danger.active.focus,
.open > .dropdown-toggle.btn-danger.focus {
  color: #fff;
  background-color: #ac2925;
  border-color: #761c19;
}
.btn-danger:active,
.btn-danger.active,
.open > .dropdown-toggle.btn-danger {
  background-image: none;
}
.btn-danger.disabled:hover,
.btn-danger[disabled]:hover,
fieldset[disabled] .btn-danger:hover,
.btn-danger.disabled:focus,
.btn-danger[disabled]:focus,
fieldset[disabled] .btn-danger:focus,
.btn-danger.disabled.focus,
.btn-danger[disabled].focus,
fieldset[disabled] .btn-danger.focus {
  background-color: #d9534f;
  border-color: #d43f3a;
}
.btn-danger .badge {
  color: #d9534f;
  background-color: #fff;
}
.btn-link {
  color: #337ab7;
  font-weight: normal;
  border-radius: 0;
}
.btn-link,
.btn-link:active,
.btn-link.active,
.btn-link[disabled],
fieldset[disabled] .btn-link {
  background-color: transparent;
  -webkit-box-shadow: none;
  box-shadow: none;
}
.btn-link,
.btn-link:hover,
.btn-link:focus,
.btn-link:active {
  border-color: transparent;
}
.btn-link:hover,
.btn-link:focus {
  color: #23527c;
  text-decoration: underline;
  background-color: transparent;
}
.btn-link[disabled]:hover,
fieldset[disabled] .btn-link:hover,
.btn-link[disabled]:focus,
fieldset[disabled] .btn-link:focus {
  color: #777777;
  text-decoration: none;
}
.btn-lg,
.btn-group-lg > .btn {
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
.btn-sm,
.btn-group-sm > .btn {
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.btn-xs,
.btn-group-xs > .btn {
  padding: 1px 5px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.btn-block {
  display: block;
  width: 100%;
}
.btn-block + .btn-block {
  margin-top: 5px;
}
input[type="submit"].btn-block,
input[type="reset"].btn-block,
input[type="button"].btn-block {
  width: 100%;
}
.fade {
  opacity: 0;
  -webkit-transition: opacity 0.15s linear;
  -o-transition: opacity 0.15s linear;
  transition: opacity 0.15s linear;
}
.fade.in {
  opacity: 1;
}
.collapse {
  display: none;
}
.collapse.in {
  display: block;
}
tr.collapse.in {
  display: table-row;
}
tbody.collapse.in {
  display: table-row-group;
}
.collapsing {
  position: relative;
  height: 0;
  overflow: hidden;
  -webkit-transition-property: height, visibility;
  transition-property: height, visibility;
  -webkit-transition-duration: 0.35s;
  transition-duration: 0.35s;
  -webkit-transition-timing-function: ease;
  transition-timing-function: ease;
}
.caret {
  display: inline-block;
  width: 0;
  height: 0;
  margin-left: 2px;
  vertical-align: middle;
  border-top: 4px dashed;
  border-top: 4px solid \9;
  border-right: 4px solid transparent;
  border-left: 4px solid transparent;
}
.dropup,
.dropdown {
  position: relative;
}
.dropdown-toggle:focus {
  outline: 0;
}
.dropdown-menu {
  position: absolute;
  top: 100%;
  left: 0;
  z-index: 1000;
  display: none;
  float: left;
  min-width: 160px;
  padding: 5px 0;
  margin: 2px 0 0;
  list-style: none;
  font-size: 13px;
  text-align: left;
  background-color: #fff;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.15);
  border-radius: 2px;
  -webkit-box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  background-clip: padding-box;
}
.dropdown-menu.pull-right {
  right: 0;
  left: auto;
}
.dropdown-menu .divider {
  height: 1px;
  margin: 8px 0;
  overflow: hidden;
  background-color: #e5e5e5;
}
.dropdown-menu > li > a {
  display: block;
  padding: 3px 20px;
  clear: both;
  font-weight: normal;
  line-height: 1.42857143;
  color: #333333;
  white-space: nowrap;
}
.dropdown-menu > li > a:hover,
.dropdown-menu > li > a:focus {
  text-decoration: none;
  color: #262626;
  background-color: #f5f5f5;
}
.dropdown-menu > .active > a,
.dropdown-menu > .active > a:hover,
.dropdown-menu > .active > a:focus {
  color: #fff;
  text-decoration: none;
  outline: 0;
  background-color: #337ab7;
}
.dropdown-menu > .disabled > a,
.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  color: #777777;
}
.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  text-decoration: none;
  background-color: transparent;
  background-image: none;
  filter: progid:DXImageTransform.Microsoft.gradient(enabled = false);
  cursor: not-allowed;
}
.open > .dropdown-menu {
  display: block;
}
.open > a {
  outline: 0;
}
.dropdown-menu-right {
  left: auto;
  right: 0;
}
.dropdown-menu-left {
  left: 0;
  right: auto;
}
.dropdown-header {
  display: block;
  padding: 3px 20px;
  font-size: 12px;
  line-height: 1.42857143;
  color: #777777;
  white-space: nowrap;
}
.dropdown-backdrop {
  position: fixed;
  left: 0;
  right: 0;
  bottom: 0;
  top: 0;
  z-index: 990;
}
.pull-right > .dropdown-menu {
  right: 0;
  left: auto;
}
.dropup .caret,
.navbar-fixed-bottom .dropdown .caret {
  border-top: 0;
  border-bottom: 4px dashed;
  border-bottom: 4px solid \9;
  content: "";
}
.dropup .dropdown-menu,
.navbar-fixed-bottom .dropdown .dropdown-menu {
  top: auto;
  bottom: 100%;
  margin-bottom: 2px;
}
@media (min-width: 541px) {
  .navbar-right .dropdown-menu {
    left: auto;
    right: 0;
  }
  .navbar-right .dropdown-menu-left {
    left: 0;
    right: auto;
  }
}
.btn-group,
.btn-group-vertical {
  position: relative;
  display: inline-block;
  vertical-align: middle;
}
.btn-group > .btn,
.btn-group-vertical > .btn {
  position: relative;
  float: left;
}
.btn-group > .btn:hover,
.btn-group-vertical > .btn:hover,
.btn-group > .btn:focus,
.btn-group-vertical > .btn:focus,
.btn-group > .btn:active,
.btn-group-vertical > .btn:active,
.btn-group > .btn.active,
.btn-group-vertical > .btn.active {
  z-index: 2;
}
.btn-group .btn + .btn,
.btn-group .btn + .btn-group,
.btn-group .btn-group + .btn,
.btn-group .btn-group + .btn-group {
  margin-left: -1px;
}
.btn-toolbar {
  margin-left: -5px;
}
.btn-toolbar .btn,
.btn-toolbar .btn-group,
.btn-toolbar .input-group {
  float: left;
}
.btn-toolbar > .btn,
.btn-toolbar > .btn-group,
.btn-toolbar > .input-group {
  margin-left: 5px;
}
.btn-group > .btn:not(:first-child):not(:last-child):not(.dropdown-toggle) {
  border-radius: 0;
}
.btn-group > .btn:first-child {
  margin-left: 0;
}
.btn-group > .btn:first-child:not(:last-child):not(.dropdown-toggle) {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.btn-group > .btn:last-child:not(:first-child),
.btn-group > .dropdown-toggle:not(:first-child) {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.btn-group > .btn-group {
  float: left;
}
.btn-group > .btn-group:not(:first-child):not(:last-child) > .btn {
  border-radius: 0;
}
.btn-group > .btn-group:first-child:not(:last-child) > .btn:last-child,
.btn-group > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.btn-group > .btn-group:last-child:not(:first-child) > .btn:first-child {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.btn-group .dropdown-toggle:active,
.btn-group.open .dropdown-toggle {
  outline: 0;
}
.btn-group > .btn + .dropdown-toggle {
  padding-left: 8px;
  padding-right: 8px;
}
.btn-group > .btn-lg + .dropdown-toggle {
  padding-left: 12px;
  padding-right: 12px;
}
.btn-group.open .dropdown-toggle {
  -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
}
.btn-group.open .dropdown-toggle.btn-link {
  -webkit-box-shadow: none;
  box-shadow: none;
}
.btn .caret {
  margin-left: 0;
}
.btn-lg .caret {
  border-width: 5px 5px 0;
  border-bottom-width: 0;
}
.dropup .btn-lg .caret {
  border-width: 0 5px 5px;
}
.btn-group-vertical > .btn,
.btn-group-vertical > .btn-group,
.btn-group-vertical > .btn-group > .btn {
  display: block;
  float: none;
  width: 100%;
  max-width: 100%;
}
.btn-group-vertical > .btn-group > .btn {
  float: none;
}
.btn-group-vertical > .btn + .btn,
.btn-group-vertical > .btn + .btn-group,
.btn-group-vertical > .btn-group + .btn,
.btn-group-vertical > .btn-group + .btn-group {
  margin-top: -1px;
  margin-left: 0;
}
.btn-group-vertical > .btn:not(:first-child):not(:last-child) {
  border-radius: 0;
}
.btn-group-vertical > .btn:first-child:not(:last-child) {
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.btn-group-vertical > .btn:last-child:not(:first-child) {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
  border-bottom-right-radius: 2px;
  border-bottom-left-radius: 2px;
}
.btn-group-vertical > .btn-group:not(:first-child):not(:last-child) > .btn {
  border-radius: 0;
}
.btn-group-vertical > .btn-group:first-child:not(:last-child) > .btn:last-child,
.btn-group-vertical > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.btn-group-vertical > .btn-group:last-child:not(:first-child) > .btn:first-child {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.btn-group-justified {
  display: table;
  width: 100%;
  table-layout: fixed;
  border-collapse: separate;
}
.btn-group-justified > .btn,
.btn-group-justified > .btn-group {
  float: none;
  display: table-cell;
  width: 1%;
}
.btn-group-justified > .btn-group .btn {
  width: 100%;
}
.btn-group-justified > .btn-group .dropdown-menu {
  left: auto;
}
[data-toggle="buttons"] > .btn input[type="radio"],
[data-toggle="buttons"] > .btn-group > .btn input[type="radio"],
[data-toggle="buttons"] > .btn input[type="checkbox"],
[data-toggle="buttons"] > .btn-group > .btn input[type="checkbox"] {
  position: absolute;
  clip: rect(0, 0, 0, 0);
  pointer-events: none;
}
.input-group {
  position: relative;
  display: table;
  border-collapse: separate;
}
.input-group[class*="col-"] {
  float: none;
  padding-left: 0;
  padding-right: 0;
}
.input-group .form-control {
  position: relative;
  z-index: 2;
  float: left;
  width: 100%;
  margin-bottom: 0;
}
.input-group .form-control:focus {
  z-index: 3;
}
.input-group-lg > .form-control,
.input-group-lg > .input-group-addon,
.input-group-lg > .input-group-btn > .btn {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
select.input-group-lg > .form-control,
select.input-group-lg > .input-group-addon,
select.input-group-lg > .input-group-btn > .btn {
  height: 45px;
  line-height: 45px;
}
textarea.input-group-lg > .form-control,
textarea.input-group-lg > .input-group-addon,
textarea.input-group-lg > .input-group-btn > .btn,
select[multiple].input-group-lg > .form-control,
select[multiple].input-group-lg > .input-group-addon,
select[multiple].input-group-lg > .input-group-btn > .btn {
  height: auto;
}
.input-group-sm > .form-control,
.input-group-sm > .input-group-addon,
.input-group-sm > .input-group-btn > .btn {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
select.input-group-sm > .form-control,
select.input-group-sm > .input-group-addon,
select.input-group-sm > .input-group-btn > .btn {
  height: 30px;
  line-height: 30px;
}
textarea.input-group-sm > .form-control,
textarea.input-group-sm > .input-group-addon,
textarea.input-group-sm > .input-group-btn > .btn,
select[multiple].input-group-sm > .form-control,
select[multiple].input-group-sm > .input-group-addon,
select[multiple].input-group-sm > .input-group-btn > .btn {
  height: auto;
}
.input-group-addon,
.input-group-btn,
.input-group .form-control {
  display: table-cell;
}
.input-group-addon:not(:first-child):not(:last-child),
.input-group-btn:not(:first-child):not(:last-child),
.input-group .form-control:not(:first-child):not(:last-child) {
  border-radius: 0;
}
.input-group-addon,
.input-group-btn {
  width: 1%;
  white-space: nowrap;
  vertical-align: middle;
}
.input-group-addon {
  padding: 6px 12px;
  font-size: 13px;
  font-weight: normal;
  line-height: 1;
  color: #555555;
  text-align: center;
  background-color: #eeeeee;
  border: 1px solid #ccc;
  border-radius: 2px;
}
.input-group-addon.input-sm {
  padding: 5px 10px;
  font-size: 12px;
  border-radius: 1px;
}
.input-group-addon.input-lg {
  padding: 10px 16px;
  font-size: 17px;
  border-radius: 3px;
}
.input-group-addon input[type="radio"],
.input-group-addon input[type="checkbox"] {
  margin-top: 0;
}
.input-group .form-control:first-child,
.input-group-addon:first-child,
.input-group-btn:first-child > .btn,
.input-group-btn:first-child > .btn-group > .btn,
.input-group-btn:first-child > .dropdown-toggle,
.input-group-btn:last-child > .btn:not(:last-child):not(.dropdown-toggle),
.input-group-btn:last-child > .btn-group:not(:last-child) > .btn {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.input-group-addon:first-child {
  border-right: 0;
}
.input-group .form-control:last-child,
.input-group-addon:last-child,
.input-group-btn:last-child > .btn,
.input-group-btn:last-child > .btn-group > .btn,
.input-group-btn:last-child > .dropdown-toggle,
.input-group-btn:first-child > .btn:not(:first-child),
.input-group-btn:first-child > .btn-group:not(:first-child) > .btn {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.input-group-addon:last-child {
  border-left: 0;
}
.input-group-btn {
  position: relative;
  font-size: 0;
  white-space: nowrap;
}
.input-group-btn > .btn {
  position: relative;
}
.input-group-btn > .btn + .btn {
  margin-left: -1px;
}
.input-group-btn > .btn:hover,
.input-group-btn > .btn:focus,
.input-group-btn > .btn:active {
  z-index: 2;
}
.input-group-btn:first-child > .btn,
.input-group-btn:first-child > .btn-group {
  margin-right: -1px;
}
.input-group-btn:last-child > .btn,
.input-group-btn:last-child > .btn-group {
  z-index: 2;
  margin-left: -1px;
}
.nav {
  margin-bottom: 0;
  padding-left: 0;
  list-style: none;
}
.nav > li {
  position: relative;
  display: block;
}
.nav > li > a {
  position: relative;
  display: block;
  padding: 10px 15px;
}
.nav > li > a:hover,
.nav > li > a:focus {
  text-decoration: none;
  background-color: #eeeeee;
}
.nav > li.disabled > a {
  color: #777777;
}
.nav > li.disabled > a:hover,
.nav > li.disabled > a:focus {
  color: #777777;
  text-decoration: none;
  background-color: transparent;
  cursor: not-allowed;
}
.nav .open > a,
.nav .open > a:hover,
.nav .open > a:focus {
  background-color: #eeeeee;
  border-color: #337ab7;
}
.nav .nav-divider {
  height: 1px;
  margin: 8px 0;
  overflow: hidden;
  background-color: #e5e5e5;
}
.nav > li > a > img {
  max-width: none;
}
.nav-tabs {
  border-bottom: 1px solid #ddd;
}
.nav-tabs > li {
  float: left;
  margin-bottom: -1px;
}
.nav-tabs > li > a {
  margin-right: 2px;
  line-height: 1.42857143;
  border: 1px solid transparent;
  border-radius: 2px 2px 0 0;
}
.nav-tabs > li > a:hover {
  border-color: #eeeeee #eeeeee #ddd;
}
.nav-tabs > li.active > a,
.nav-tabs > li.active > a:hover,
.nav-tabs > li.active > a:focus {
  color: #555555;
  background-color: #fff;
  border: 1px solid #ddd;
  border-bottom-color: transparent;
  cursor: default;
}
.nav-tabs.nav-justified {
  width: 100%;
  border-bottom: 0;
}
.nav-tabs.nav-justified > li {
  float: none;
}
.nav-tabs.nav-justified > li > a {
  text-align: center;
  margin-bottom: 5px;
}
.nav-tabs.nav-justified > .dropdown .dropdown-menu {
  top: auto;
  left: auto;
}
@media (min-width: 768px) {
  .nav-tabs.nav-justified > li {
    display: table-cell;
    width: 1%;
  }
  .nav-tabs.nav-justified > li > a {
    margin-bottom: 0;
  }
}
.nav-tabs.nav-justified > li > a {
  margin-right: 0;
  border-radius: 2px;
}
.nav-tabs.nav-justified > .active > a,
.nav-tabs.nav-justified > .active > a:hover,
.nav-tabs.nav-justified > .active > a:focus {
  border: 1px solid #ddd;
}
@media (min-width: 768px) {
  .nav-tabs.nav-justified > li > a {
    border-bottom: 1px solid #ddd;
    border-radius: 2px 2px 0 0;
  }
  .nav-tabs.nav-justified > .active > a,
  .nav-tabs.nav-justified > .active > a:hover,
  .nav-tabs.nav-justified > .active > a:focus {
    border-bottom-color: #fff;
  }
}
.nav-pills > li {
  float: left;
}
.nav-pills > li > a {
  border-radius: 2px;
}
.nav-pills > li + li {
  margin-left: 2px;
}
.nav-pills > li.active > a,
.nav-pills > li.active > a:hover,
.nav-pills > li.active > a:focus {
  color: #fff;
  background-color: #337ab7;
}
.nav-stacked > li {
  float: none;
}
.nav-stacked > li + li {
  margin-top: 2px;
  margin-left: 0;
}
.nav-justified {
  width: 100%;
}
.nav-justified > li {
  float: none;
}
.nav-justified > li > a {
  text-align: center;
  margin-bottom: 5px;
}
.nav-justified > .dropdown .dropdown-menu {
  top: auto;
  left: auto;
}
@media (min-width: 768px) {
  .nav-justified > li {
    display: table-cell;
    width: 1%;
  }
  .nav-justified > li > a {
    margin-bottom: 0;
  }
}
.nav-tabs-justified {
  border-bottom: 0;
}
.nav-tabs-justified > li > a {
  margin-right: 0;
  border-radius: 2px;
}
.nav-tabs-justified > .active > a,
.nav-tabs-justified > .active > a:hover,
.nav-tabs-justified > .active > a:focus {
  border: 1px solid #ddd;
}
@media (min-width: 768px) {
  .nav-tabs-justified > li > a {
    border-bottom: 1px solid #ddd;
    border-radius: 2px 2px 0 0;
  }
  .nav-tabs-justified > .active > a,
  .nav-tabs-justified > .active > a:hover,
  .nav-tabs-justified > .active > a:focus {
    border-bottom-color: #fff;
  }
}
.tab-content > .tab-pane {
  display: none;
}
.tab-content > .active {
  display: block;
}
.nav-tabs .dropdown-menu {
  margin-top: -1px;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.navbar {
  position: relative;
  min-height: 30px;
  margin-bottom: 18px;
  border: 1px solid transparent;
}
@media (min-width: 541px) {
  .navbar {
    border-radius: 2px;
  }
}
@media (min-width: 541px) {
  .navbar-header {
    float: left;
  }
}
.navbar-collapse {
  overflow-x: visible;
  padding-right: 0px;
  padding-left: 0px;
  border-top: 1px solid transparent;
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1);
  -webkit-overflow-scrolling: touch;
}
.navbar-collapse.in {
  overflow-y: auto;
}
@media (min-width: 541px) {
  .navbar-collapse {
    width: auto;
    border-top: 0;
    box-shadow: none;
  }
  .navbar-collapse.collapse {
    display: block !important;
    height: auto !important;
    padding-bottom: 0;
    overflow: visible !important;
  }
  .navbar-collapse.in {
    overflow-y: visible;
  }
  .navbar-fixed-top .navbar-collapse,
  .navbar-static-top .navbar-collapse,
  .navbar-fixed-bottom .navbar-collapse {
    padding-left: 0;
    padding-right: 0;
  }
}
.navbar-fixed-top .navbar-collapse,
.navbar-fixed-bottom .navbar-collapse {
  max-height: 340px;
}
@media (max-device-width: 540px) and (orientation: landscape) {
  .navbar-fixed-top .navbar-collapse,
  .navbar-fixed-bottom .navbar-collapse {
    max-height: 200px;
  }
}
.container > .navbar-header,
.container-fluid > .navbar-header,
.container > .navbar-collapse,
.container-fluid > .navbar-collapse {
  margin-right: 0px;
  margin-left: 0px;
}
@media (min-width: 541px) {
  .container > .navbar-header,
  .container-fluid > .navbar-header,
  .container > .navbar-collapse,
  .container-fluid > .navbar-collapse {
    margin-right: 0;
    margin-left: 0;
  }
}
.navbar-static-top {
  z-index: 1000;
  border-width: 0 0 1px;
}
@media (min-width: 541px) {
  .navbar-static-top {
    border-radius: 0;
  }
}
.navbar-fixed-top,
.navbar-fixed-bottom {
  position: fixed;
  right: 0;
  left: 0;
  z-index: 1030;
}
@media (min-width: 541px) {
  .navbar-fixed-top,
  .navbar-fixed-bottom {
    border-radius: 0;
  }
}
.navbar-fixed-top {
  top: 0;
  border-width: 0 0 1px;
}
.navbar-fixed-bottom {
  bottom: 0;
  margin-bottom: 0;
  border-width: 1px 0 0;
}
.navbar-brand {
  float: left;
  padding: 6px 0px;
  font-size: 17px;
  line-height: 18px;
  height: 30px;
}
.navbar-brand:hover,
.navbar-brand:focus {
  text-decoration: none;
}
.navbar-brand > img {
  display: block;
}
@media (min-width: 541px) {
  .navbar > .container .navbar-brand,
  .navbar > .container-fluid .navbar-brand {
    margin-left: 0px;
  }
}
.navbar-toggle {
  position: relative;
  float: right;
  margin-right: 0px;
  padding: 9px 10px;
  margin-top: -2px;
  margin-bottom: -2px;
  background-color: transparent;
  background-image: none;
  border: 1px solid transparent;
  border-radius: 2px;
}
.navbar-toggle:focus {
  outline: 0;
}
.navbar-toggle .icon-bar {
  display: block;
  width: 22px;
  height: 2px;
  border-radius: 1px;
}
.navbar-toggle .icon-bar + .icon-bar {
  margin-top: 4px;
}
@media (min-width: 541px) {
  .navbar-toggle {
    display: none;
  }
}
.navbar-nav {
  margin: 3px 0px;
}
.navbar-nav > li > a {
  padding-top: 10px;
  padding-bottom: 10px;
  line-height: 18px;
}
@media (max-width: 540px) {
  .navbar-nav .open .dropdown-menu {
    position: static;
    float: none;
    width: auto;
    margin-top: 0;
    background-color: transparent;
    border: 0;
    box-shadow: none;
  }
  .navbar-nav .open .dropdown-menu > li > a,
  .navbar-nav .open .dropdown-menu .dropdown-header {
    padding: 5px 15px 5px 25px;
  }
  .navbar-nav .open .dropdown-menu > li > a {
    line-height: 18px;
  }
  .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-nav .open .dropdown-menu > li > a:focus {
    background-image: none;
  }
}
@media (min-width: 541px) {
  .navbar-nav {
    float: left;
    margin: 0;
  }
  .navbar-nav > li {
    float: left;
  }
  .navbar-nav > li > a {
    padding-top: 6px;
    padding-bottom: 6px;
  }
}
.navbar-form {
  margin-left: 0px;
  margin-right: 0px;
  padding: 10px 0px;
  border-top: 1px solid transparent;
  border-bottom: 1px solid transparent;
  -webkit-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  margin-top: -1px;
  margin-bottom: -1px;
}
@media (min-width: 768px) {
  .navbar-form .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle;
  }
  .navbar-form .form-control-static {
    display: inline-block;
  }
  .navbar-form .input-group {
    display: inline-table;
    vertical-align: middle;
  }
  .navbar-form .input-group .input-group-addon,
  .navbar-form .input-group .input-group-btn,
  .navbar-form .input-group .form-control {
    width: auto;
  }
  .navbar-form .input-group > .form-control {
    width: 100%;
  }
  .navbar-form .control-label {
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .radio,
  .navbar-form .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .radio label,
  .navbar-form .checkbox label {
    padding-left: 0;
  }
  .navbar-form .radio input[type="radio"],
  .navbar-form .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0;
  }
  .navbar-form .has-feedback .form-control-feedback {
    top: 0;
  }
}
@media (max-width: 540px) {
  .navbar-form .form-group {
    margin-bottom: 5px;
  }
  .navbar-form .form-group:last-child {
    margin-bottom: 0;
  }
}
@media (min-width: 541px) {
  .navbar-form {
    width: auto;
    border: 0;
    margin-left: 0;
    margin-right: 0;
    padding-top: 0;
    padding-bottom: 0;
    -webkit-box-shadow: none;
    box-shadow: none;
  }
}
.navbar-nav > li > .dropdown-menu {
  margin-top: 0;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.navbar-fixed-bottom .navbar-nav > li > .dropdown-menu {
  margin-bottom: 0;
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.navbar-btn {
  margin-top: -1px;
  margin-bottom: -1px;
}
.navbar-btn.btn-sm {
  margin-top: 0px;
  margin-bottom: 0px;
}
.navbar-btn.btn-xs {
  margin-top: 4px;
  margin-bottom: 4px;
}
.navbar-text {
  margin-top: 6px;
  margin-bottom: 6px;
}
@media (min-width: 541px) {
  .navbar-text {
    float: left;
    margin-left: 0px;
    margin-right: 0px;
  }
}
@media (min-width: 541px) {
  .navbar-left {
    float: left !important;
    float: left;
  }
  .navbar-right {
    float: right !important;
    float: right;
    margin-right: 0px;
  }
  .navbar-right ~ .navbar-right {
    margin-right: 0;
  }
}
.navbar-default {
  background-color: #f8f8f8;
  border-color: #e7e7e7;
}
.navbar-default .navbar-brand {
  color: #777;
}
.navbar-default .navbar-brand:hover,
.navbar-default .navbar-brand:focus {
  color: #5e5e5e;
  background-color: transparent;
}
.navbar-default .navbar-text {
  color: #777;
}
.navbar-default .navbar-nav > li > a {
  color: #777;
}
.navbar-default .navbar-nav > li > a:hover,
.navbar-default .navbar-nav > li > a:focus {
  color: #333;
  background-color: transparent;
}
.navbar-default .navbar-nav > .active > a,
.navbar-default .navbar-nav > .active > a:hover,
.navbar-default .navbar-nav > .active > a:focus {
  color: #555;
  background-color: #e7e7e7;
}
.navbar-default .navbar-nav > .disabled > a,
.navbar-default .navbar-nav > .disabled > a:hover,
.navbar-default .navbar-nav > .disabled > a:focus {
  color: #ccc;
  background-color: transparent;
}
.navbar-default .navbar-toggle {
  border-color: #ddd;
}
.navbar-default .navbar-toggle:hover,
.navbar-default .navbar-toggle:focus {
  background-color: #ddd;
}
.navbar-default .navbar-toggle .icon-bar {
  background-color: #888;
}
.navbar-default .navbar-collapse,
.navbar-default .navbar-form {
  border-color: #e7e7e7;
}
.navbar-default .navbar-nav > .open > a,
.navbar-default .navbar-nav > .open > a:hover,
.navbar-default .navbar-nav > .open > a:focus {
  background-color: #e7e7e7;
  color: #555;
}
@media (max-width: 540px) {
  .navbar-default .navbar-nav .open .dropdown-menu > li > a {
    color: #777;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > li > a:focus {
    color: #333;
    background-color: transparent;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a,
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a:focus {
    color: #555;
    background-color: #e7e7e7;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a,
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:focus {
    color: #ccc;
    background-color: transparent;
  }
}
.navbar-default .navbar-link {
  color: #777;
}
.navbar-default .navbar-link:hover {
  color: #333;
}
.navbar-default .btn-link {
  color: #777;
}
.navbar-default .btn-link:hover,
.navbar-default .btn-link:focus {
  color: #333;
}
.navbar-default .btn-link[disabled]:hover,
fieldset[disabled] .navbar-default .btn-link:hover,
.navbar-default .btn-link[disabled]:focus,
fieldset[disabled] .navbar-default .btn-link:focus {
  color: #ccc;
}
.navbar-inverse {
  background-color: #222;
  border-color: #080808;
}
.navbar-inverse .navbar-brand {
  color: #9d9d9d;
}
.navbar-inverse .navbar-brand:hover,
.navbar-inverse .navbar-brand:focus {
  color: #fff;
  background-color: transparent;
}
.navbar-inverse .navbar-text {
  color: #9d9d9d;
}
.navbar-inverse .navbar-nav > li > a {
  color: #9d9d9d;
}
.navbar-inverse .navbar-nav > li > a:hover,
.navbar-inverse .navbar-nav > li > a:focus {
  color: #fff;
  background-color: transparent;
}
.navbar-inverse .navbar-nav > .active > a,
.navbar-inverse .navbar-nav > .active > a:hover,
.navbar-inverse .navbar-nav > .active > a:focus {
  color: #fff;
  background-color: #080808;
}
.navbar-inverse .navbar-nav > .disabled > a,
.navbar-inverse .navbar-nav > .disabled > a:hover,
.navbar-inverse .navbar-nav > .disabled > a:focus {
  color: #444;
  background-color: transparent;
}
.navbar-inverse .navbar-toggle {
  border-color: #333;
}
.navbar-inverse .navbar-toggle:hover,
.navbar-inverse .navbar-toggle:focus {
  background-color: #333;
}
.navbar-inverse .navbar-toggle .icon-bar {
  background-color: #fff;
}
.navbar-inverse .navbar-collapse,
.navbar-inverse .navbar-form {
  border-color: #101010;
}
.navbar-inverse .navbar-nav > .open > a,
.navbar-inverse .navbar-nav > .open > a:hover,
.navbar-inverse .navbar-nav > .open > a:focus {
  background-color: #080808;
  color: #fff;
}
@media (max-width: 540px) {
  .navbar-inverse .navbar-nav .open .dropdown-menu > .dropdown-header {
    border-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu .divider {
    background-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a {
    color: #9d9d9d;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:focus {
    color: #fff;
    background-color: transparent;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:focus {
    color: #fff;
    background-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:focus {
    color: #444;
    background-color: transparent;
  }
}
.navbar-inverse .navbar-link {
  color: #9d9d9d;
}
.navbar-inverse .navbar-link:hover {
  color: #fff;
}
.navbar-inverse .btn-link {
  color: #9d9d9d;
}
.navbar-inverse .btn-link:hover,
.navbar-inverse .btn-link:focus {
  color: #fff;
}
.navbar-inverse .btn-link[disabled]:hover,
fieldset[disabled] .navbar-inverse .btn-link:hover,
.navbar-inverse .btn-link[disabled]:focus,
fieldset[disabled] .navbar-inverse .btn-link:focus {
  color: #444;
}
.breadcrumb {
  padding: 8px 15px;
  margin-bottom: 18px;
  list-style: none;
  background-color: #f5f5f5;
  border-radius: 2px;
}
.breadcrumb > li {
  display: inline-block;
}
.breadcrumb > li + li:before {
  content: "/\00a0";
  padding: 0 5px;
  color: #5e5e5e;
}
.breadcrumb > .active {
  color: #777777;
}
.pagination {
  display: inline-block;
  padding-left: 0;
  margin: 18px 0;
  border-radius: 2px;
}
.pagination > li {
  display: inline;
}
.pagination > li > a,
.pagination > li > span {
  position: relative;
  float: left;
  padding: 6px 12px;
  line-height: 1.42857143;
  text-decoration: none;
  color: #337ab7;
  background-color: #fff;
  border: 1px solid #ddd;
  margin-left: -1px;
}
.pagination > li:first-child > a,
.pagination > li:first-child > span {
  margin-left: 0;
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}
.pagination > li:last-child > a,
.pagination > li:last-child > span {
  border-bottom-right-radius: 2px;
  border-top-right-radius: 2px;
}
.pagination > li > a:hover,
.pagination > li > span:hover,
.pagination > li > a:focus,
.pagination > li > span:focus {
  z-index: 2;
  color: #23527c;
  background-color: #eeeeee;
  border-color: #ddd;
}
.pagination > .active > a,
.pagination > .active > span,
.pagination > .active > a:hover,
.pagination > .active > span:hover,
.pagination > .active > a:focus,
.pagination > .active > span:focus {
  z-index: 3;
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
  cursor: default;
}
.pagination > .disabled > span,
.pagination > .disabled > span:hover,
.pagination > .disabled > span:focus,
.pagination > .disabled > a,
.pagination > .disabled > a:hover,
.pagination > .disabled > a:focus {
  color: #777777;
  background-color: #fff;
  border-color: #ddd;
  cursor: not-allowed;
}
.pagination-lg > li > a,
.pagination-lg > li > span {
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
}
.pagination-lg > li:first-child > a,
.pagination-lg > li:first-child > span {
  border-bottom-left-radius: 3px;
  border-top-left-radius: 3px;
}
.pagination-lg > li:last-child > a,
.pagination-lg > li:last-child > span {
  border-bottom-right-radius: 3px;
  border-top-right-radius: 3px;
}
.pagination-sm > li > a,
.pagination-sm > li > span {
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
}
.pagination-sm > li:first-child > a,
.pagination-sm > li:first-child > span {
  border-bottom-left-radius: 1px;
  border-top-left-radius: 1px;
}
.pagination-sm > li:last-child > a,
.pagination-sm > li:last-child > span {
  border-bottom-right-radius: 1px;
  border-top-right-radius: 1px;
}
.pager {
  padding-left: 0;
  margin: 18px 0;
  list-style: none;
  text-align: center;
}
.pager li {
  display: inline;
}
.pager li > a,
.pager li > span {
  display: inline-block;
  padding: 5px 14px;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 15px;
}
.pager li > a:hover,
.pager li > a:focus {
  text-decoration: none;
  background-color: #eeeeee;
}
.pager .next > a,
.pager .next > span {
  float: right;
}
.pager .previous > a,
.pager .previous > span {
  float: left;
}
.pager .disabled > a,
.pager .disabled > a:hover,
.pager .disabled > a:focus,
.pager .disabled > span {
  color: #777777;
  background-color: #fff;
  cursor: not-allowed;
}
.label {
  display: inline;
  padding: .2em .6em .3em;
  font-size: 75%;
  font-weight: bold;
  line-height: 1;
  color: #fff;
  text-align: center;
  white-space: nowrap;
  vertical-align: baseline;
  border-radius: .25em;
}
a.label:hover,
a.label:focus {
  color: #fff;
  text-decoration: none;
  cursor: pointer;
}
.label:empty {
  display: none;
}
.btn .label {
  position: relative;
  top: -1px;
}
.label-default {
  background-color: #777777;
}
.label-default[href]:hover,
.label-default[href]:focus {
  background-color: #5e5e5e;
}
.label-primary {
  background-color: #337ab7;
}
.label-primary[href]:hover,
.label-primary[href]:focus {
  background-color: #286090;
}
.label-success {
  background-color: #5cb85c;
}
.label-success[href]:hover,
.label-success[href]:focus {
  background-color: #449d44;
}
.label-info {
  background-color: #5bc0de;
}
.label-info[href]:hover,
.label-info[href]:focus {
  background-color: #31b0d5;
}
.label-warning {
  background-color: #f0ad4e;
}
.label-warning[href]:hover,
.label-warning[href]:focus {
  background-color: #ec971f;
}
.label-danger {
  background-color: #d9534f;
}
.label-danger[href]:hover,
.label-danger[href]:focus {
  background-color: #c9302c;
}
.badge {
  display: inline-block;
  min-width: 10px;
  padding: 3px 7px;
  font-size: 12px;
  font-weight: bold;
  color: #fff;
  line-height: 1;
  vertical-align: middle;
  white-space: nowrap;
  text-align: center;
  background-color: #777777;
  border-radius: 10px;
}
.badge:empty {
  display: none;
}
.btn .badge {
  position: relative;
  top: -1px;
}
.btn-xs .badge,
.btn-group-xs > .btn .badge {
  top: 0;
  padding: 1px 5px;
}
a.badge:hover,
a.badge:focus {
  color: #fff;
  text-decoration: none;
  cursor: pointer;
}
.list-group-item.active > .badge,
.nav-pills > .active > a > .badge {
  color: #337ab7;
  background-color: #fff;
}
.list-group-item > .badge {
  float: right;
}
.list-group-item > .badge + .badge {
  margin-right: 5px;
}
.nav-pills > li > a > .badge {
  margin-left: 3px;
}
.jumbotron {
  padding-top: 30px;
  padding-bottom: 30px;
  margin-bottom: 30px;
  color: inherit;
  background-color: #eeeeee;
}
.jumbotron h1,
.jumbotron .h1 {
  color: inherit;
}
.jumbotron p {
  margin-bottom: 15px;
  font-size: 20px;
  font-weight: 200;
}
.jumbotron > hr {
  border-top-color: #d5d5d5;
}
.container .jumbotron,
.container-fluid .jumbotron {
  border-radius: 3px;
  padding-left: 0px;
  padding-right: 0px;
}
.jumbotron .container {
  max-width: 100%;
}
@media screen and (min-width: 768px) {
  .jumbotron {
    padding-top: 48px;
    padding-bottom: 48px;
  }
  .container .jumbotron,
  .container-fluid .jumbotron {
    padding-left: 60px;
    padding-right: 60px;
  }
  .jumbotron h1,
  .jumbotron .h1 {
    font-size: 59px;
  }
}
.thumbnail {
  display: block;
  padding: 4px;
  margin-bottom: 18px;
  line-height: 1.42857143;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 2px;
  -webkit-transition: border 0.2s ease-in-out;
  -o-transition: border 0.2s ease-in-out;
  transition: border 0.2s ease-in-out;
}
.thumbnail > img,
.thumbnail a > img {
  margin-left: auto;
  margin-right: auto;
}
a.thumbnail:hover,
a.thumbnail:focus,
a.thumbnail.active {
  border-color: #337ab7;
}
.thumbnail .caption {
  padding: 9px;
  color: #000;
}
.alert {
  padding: 15px;
  margin-bottom: 18px;
  border: 1px solid transparent;
  border-radius: 2px;
}
.alert h4 {
  margin-top: 0;
  color: inherit;
}
.alert .alert-link {
  font-weight: bold;
}
.alert > p,
.alert > ul {
  margin-bottom: 0;
}
.alert > p + p {
  margin-top: 5px;
}
.alert-dismissable,
.alert-dismissible {
  padding-right: 35px;
}
.alert-dismissable .close,
.alert-dismissible .close {
  position: relative;
  top: -2px;
  right: -21px;
  color: inherit;
}
.alert-success {
  background-color: #dff0d8;
  border-color: #d6e9c6;
  color: #3c763d;
}
.alert-success hr {
  border-top-color: #c9e2b3;
}
.alert-success .alert-link {
  color: #2b542c;
}
.alert-info {
  background-color: #d9edf7;
  border-color: #bce8f1;
  color: #31708f;
}
.alert-info hr {
  border-top-color: #a6e1ec;
}
.alert-info .alert-link {
  color: #245269;
}
.alert-warning {
  background-color: #fcf8e3;
  border-color: #faebcc;
  color: #8a6d3b;
}
.alert-warning hr {
  border-top-color: #f7e1b5;
}
.alert-warning .alert-link {
  color: #66512c;
}
.alert-danger {
  background-color: #f2dede;
  border-color: #ebccd1;
  color: #a94442;
}
.alert-danger hr {
  border-top-color: #e4b9c0;
}
.alert-danger .alert-link {
  color: #843534;
}
@-webkit-keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}
@keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}
.progress {
  overflow: hidden;
  height: 18px;
  margin-bottom: 18px;
  background-color: #f5f5f5;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
  box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
}
.progress-bar {
  float: left;
  width: 0%;
  height: 100%;
  font-size: 12px;
  line-height: 18px;
  color: #fff;
  text-align: center;
  background-color: #337ab7;
  -webkit-box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  -webkit-transition: width 0.6s ease;
  -o-transition: width 0.6s ease;
  transition: width 0.6s ease;
}
.progress-striped .progress-bar,
.progress-bar-striped {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-size: 40px 40px;
}
.progress.active .progress-bar,
.progress-bar.active {
  -webkit-animation: progress-bar-stripes 2s linear infinite;
  -o-animation: progress-bar-stripes 2s linear infinite;
  animation: progress-bar-stripes 2s linear infinite;
}
.progress-bar-success {
  background-color: #5cb85c;
}
.progress-striped .progress-bar-success {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-info {
  background-color: #5bc0de;
}
.progress-striped .progress-bar-info {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-warning {
  background-color: #f0ad4e;
}
.progress-striped .progress-bar-warning {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-danger {
  background-color: #d9534f;
}
.progress-striped .progress-bar-danger {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.media {
  margin-top: 15px;
}
.media:first-child {
  margin-top: 0;
}
.media,
.media-body {
  zoom: 1;
  overflow: hidden;
}
.media-body {
  width: 10000px;
}
.media-object {
  display: block;
}
.media-object.img-thumbnail {
  max-width: none;
}
.media-right,
.media > .pull-right {
  padding-left: 10px;
}
.media-left,
.media > .pull-left {
  padding-right: 10px;
}
.media-left,
.media-right,
.media-body {
  display: table-cell;
  vertical-align: top;
}
.media-middle {
  vertical-align: middle;
}
.media-bottom {
  vertical-align: bottom;
}
.media-heading {
  margin-top: 0;
  margin-bottom: 5px;
}
.media-list {
  padding-left: 0;
  list-style: none;
}
.list-group {
  margin-bottom: 20px;
  padding-left: 0;
}
.list-group-item {
  position: relative;
  display: block;
  padding: 10px 15px;
  margin-bottom: -1px;
  background-color: #fff;
  border: 1px solid #ddd;
}
.list-group-item:first-child {
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
}
.list-group-item:last-child {
  margin-bottom: 0;
  border-bottom-right-radius: 2px;
  border-bottom-left-radius: 2px;
}
a.list-group-item,
button.list-group-item {
  color: #555;
}
a.list-group-item .list-group-item-heading,
button.list-group-item .list-group-item-heading {
  color: #333;
}
a.list-group-item:hover,
button.list-group-item:hover,
a.list-group-item:focus,
button.list-group-item:focus {
  text-decoration: none;
  color: #555;
  background-color: #f5f5f5;
}
button.list-group-item {
  width: 100%;
  text-align: left;
}
.list-group-item.disabled,
.list-group-item.disabled:hover,
.list-group-item.disabled:focus {
  background-color: #eeeeee;
  color: #777777;
  cursor: not-allowed;
}
.list-group-item.disabled .list-group-item-heading,
.list-group-item.disabled:hover .list-group-item-heading,
.list-group-item.disabled:focus .list-group-item-heading {
  color: inherit;
}
.list-group-item.disabled .list-group-item-text,
.list-group-item.disabled:hover .list-group-item-text,
.list-group-item.disabled:focus .list-group-item-text {
  color: #777777;
}
.list-group-item.active,
.list-group-item.active:hover,
.list-group-item.active:focus {
  z-index: 2;
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
}
.list-group-item.active .list-group-item-heading,
.list-group-item.active:hover .list-group-item-heading,
.list-group-item.active:focus .list-group-item-heading,
.list-group-item.active .list-group-item-heading > small,
.list-group-item.active:hover .list-group-item-heading > small,
.list-group-item.active:focus .list-group-item-heading > small,
.list-group-item.active .list-group-item-heading > .small,
.list-group-item.active:hover .list-group-item-heading > .small,
.list-group-item.active:focus .list-group-item-heading > .small {
  color: inherit;
}
.list-group-item.active .list-group-item-text,
.list-group-item.active:hover .list-group-item-text,
.list-group-item.active:focus .list-group-item-text {
  color: #c7ddef;
}
.list-group-item-success {
  color: #3c763d;
  background-color: #dff0d8;
}
a.list-group-item-success,
button.list-group-item-success {
  color: #3c763d;
}
a.list-group-item-success .list-group-item-heading,
button.list-group-item-success .list-group-item-heading {
  color: inherit;
}
a.list-group-item-success:hover,
button.list-group-item-success:hover,
a.list-group-item-success:focus,
button.list-group-item-success:focus {
  color: #3c763d;
  background-color: #d0e9c6;
}
a.list-group-item-success.active,
button.list-group-item-success.active,
a.list-group-item-success.active:hover,
button.list-group-item-success.active:hover,
a.list-group-item-success.active:focus,
button.list-group-item-success.active:focus {
  color: #fff;
  background-color: #3c763d;
  border-color: #3c763d;
}
.list-group-item-info {
  color: #31708f;
  background-color: #d9edf7;
}
a.list-group-item-info,
button.list-group-item-info {
  color: #31708f;
}
a.list-group-item-info .list-group-item-heading,
button.list-group-item-info .list-group-item-heading {
  color: inherit;
}
a.list-group-item-info:hover,
button.list-group-item-info:hover,
a.list-group-item-info:focus,
button.list-group-item-info:focus {
  color: #31708f;
  background-color: #c4e3f3;
}
a.list-group-item-info.active,
button.list-group-item-info.active,
a.list-group-item-info.active:hover,
button.list-group-item-info.active:hover,
a.list-group-item-info.active:focus,
button.list-group-item-info.active:focus {
  color: #fff;
  background-color: #31708f;
  border-color: #31708f;
}
.list-group-item-warning {
  color: #8a6d3b;
  background-color: #fcf8e3;
}
a.list-group-item-warning,
button.list-group-item-warning {
  color: #8a6d3b;
}
a.list-group-item-warning .list-group-item-heading,
button.list-group-item-warning .list-group-item-heading {
  color: inherit;
}
a.list-group-item-warning:hover,
button.list-group-item-warning:hover,
a.list-group-item-warning:focus,
button.list-group-item-warning:focus {
  color: #8a6d3b;
  background-color: #faf2cc;
}
a.list-group-item-warning.active,
button.list-group-item-warning.active,
a.list-group-item-warning.active:hover,
button.list-group-item-warning.active:hover,
a.list-group-item-warning.active:focus,
button.list-group-item-warning.active:focus {
  color: #fff;
  background-color: #8a6d3b;
  border-color: #8a6d3b;
}
.list-group-item-danger {
  color: #a94442;
  background-color: #f2dede;
}
a.list-group-item-danger,
button.list-group-item-danger {
  color: #a94442;
}
a.list-group-item-danger .list-group-item-heading,
button.list-group-item-danger .list-group-item-heading {
  color: inherit;
}
a.list-group-item-danger:hover,
button.list-group-item-danger:hover,
a.list-group-item-danger:focus,
button.list-group-item-danger:focus {
  color: #a94442;
  background-color: #ebcccc;
}
a.list-group-item-danger.active,
button.list-group-item-danger.active,
a.list-group-item-danger.active:hover,
button.list-group-item-danger.active:hover,
a.list-group-item-danger.active:focus,
button.list-group-item-danger.active:focus {
  color: #fff;
  background-color: #a94442;
  border-color: #a94442;
}
.list-group-item-heading {
  margin-top: 0;
  margin-bottom: 5px;
}
.list-group-item-text {
  margin-bottom: 0;
  line-height: 1.3;
}
.panel {
  margin-bottom: 18px;
  background-color: #fff;
  border: 1px solid transparent;
  border-radius: 2px;
  -webkit-box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
  box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
}
.panel-body {
  padding: 15px;
}
.panel-heading {
  padding: 10px 15px;
  border-bottom: 1px solid transparent;
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel-heading > .dropdown .dropdown-toggle {
  color: inherit;
}
.panel-title {
  margin-top: 0;
  margin-bottom: 0;
  font-size: 15px;
  color: inherit;
}
.panel-title > a,
.panel-title > small,
.panel-title > .small,
.panel-title > small > a,
.panel-title > .small > a {
  color: inherit;
}
.panel-footer {
  padding: 10px 15px;
  background-color: #f5f5f5;
  border-top: 1px solid #ddd;
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .list-group,
.panel > .panel-collapse > .list-group {
  margin-bottom: 0;
}
.panel > .list-group .list-group-item,
.panel > .panel-collapse > .list-group .list-group-item {
  border-width: 1px 0;
  border-radius: 0;
}
.panel > .list-group:first-child .list-group-item:first-child,
.panel > .panel-collapse > .list-group:first-child .list-group-item:first-child {
  border-top: 0;
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel > .list-group:last-child .list-group-item:last-child,
.panel > .panel-collapse > .list-group:last-child .list-group-item:last-child {
  border-bottom: 0;
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .panel-heading + .panel-collapse > .list-group .list-group-item:first-child {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.panel-heading + .list-group .list-group-item:first-child {
  border-top-width: 0;
}
.list-group + .panel-footer {
  border-top-width: 0;
}
.panel > .table,
.panel > .table-responsive > .table,
.panel > .panel-collapse > .table {
  margin-bottom: 0;
}
.panel > .table caption,
.panel > .table-responsive > .table caption,
.panel > .panel-collapse > .table caption {
  padding-left: 15px;
  padding-right: 15px;
}
.panel > .table:first-child,
.panel > .table-responsive:first-child > .table:first-child {
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child {
  border-top-left-radius: 1px;
  border-top-right-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child td:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child td:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:first-child,
.panel > .table:first-child > thead:first-child > tr:first-child th:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child th:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:first-child {
  border-top-left-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child td:last-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:last-child,
.panel > .table:first-child > tbody:first-child > tr:first-child td:last-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:last-child,
.panel > .table:first-child > thead:first-child > tr:first-child th:last-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:last-child,
.panel > .table:first-child > tbody:first-child > tr:first-child th:last-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:last-child {
  border-top-right-radius: 1px;
}
.panel > .table:last-child,
.panel > .table-responsive:last-child > .table:last-child {
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child {
  border-bottom-left-radius: 1px;
  border-bottom-right-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child td:first-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:first-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child td:first-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:first-child,
.panel > .table:last-child > tbody:last-child > tr:last-child th:first-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:first-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child th:first-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:first-child {
  border-bottom-left-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child td:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child td:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:last-child,
.panel > .table:last-child > tbody:last-child > tr:last-child th:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child th:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:last-child {
  border-bottom-right-radius: 1px;
}
.panel > .panel-body + .table,
.panel > .panel-body + .table-responsive,
.panel > .table + .panel-body,
.panel > .table-responsive + .panel-body {
  border-top: 1px solid #ddd;
}
.panel > .table > tbody:first-child > tr:first-child th,
.panel > .table > tbody:first-child > tr:first-child td {
  border-top: 0;
}
.panel > .table-bordered,
.panel > .table-responsive > .table-bordered {
  border: 0;
}
.panel > .table-bordered > thead > tr > th:first-child,
.panel > .table-responsive > .table-bordered > thead > tr > th:first-child,
.panel > .table-bordered > tbody > tr > th:first-child,
.panel > .table-responsive > .table-bordered > tbody > tr > th:first-child,
.panel > .table-bordered > tfoot > tr > th:first-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > th:first-child,
.panel > .table-bordered > thead > tr > td:first-child,
.panel > .table-responsive > .table-bordered > thead > tr > td:first-child,
.panel > .table-bordered > tbody > tr > td:first-child,
.panel > .table-responsive > .table-bordered > tbody > tr > td:first-child,
.panel > .table-bordered > tfoot > tr > td:first-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > td:first-child {
  border-left: 0;
}
.panel > .table-bordered > thead > tr > th:last-child,
.panel > .table-responsive > .table-bordered > thead > tr > th:last-child,
.panel > .table-bordered > tbody > tr > th:last-child,
.panel > .table-responsive > .table-bordered > tbody > tr > th:last-child,
.panel > .table-bordered > tfoot > tr > th:last-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > th:last-child,
.panel > .table-bordered > thead > tr > td:last-child,
.panel > .table-responsive > .table-bordered > thead > tr > td:last-child,
.panel > .table-bordered > tbody > tr > td:last-child,
.panel > .table-responsive > .table-bordered > tbody > tr > td:last-child,
.panel > .table-bordered > tfoot > tr > td:last-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > td:last-child {
  border-right: 0;
}
.panel > .table-bordered > thead > tr:first-child > td,
.panel > .table-responsive > .table-bordered > thead > tr:first-child > td,
.panel > .table-bordered > tbody > tr:first-child > td,
.panel > .table-responsive > .table-bordered > tbody > tr:first-child > td,
.panel > .table-bordered > thead > tr:first-child > th,
.panel > .table-responsive > .table-bordered > thead > tr:first-child > th,
.panel > .table-bordered > tbody > tr:first-child > th,
.panel > .table-responsive > .table-bordered > tbody > tr:first-child > th {
  border-bottom: 0;
}
.panel > .table-bordered > tbody > tr:last-child > td,
.panel > .table-responsive > .table-bordered > tbody > tr:last-child > td,
.panel > .table-bordered > tfoot > tr:last-child > td,
.panel > .table-responsive > .table-bordered > tfoot > tr:last-child > td,
.panel > .table-bordered > tbody > tr:last-child > th,
.panel > .table-responsive > .table-bordered > tbody > tr:last-child > th,
.panel > .table-bordered > tfoot > tr:last-child > th,
.panel > .table-responsive > .table-bordered > tfoot > tr:last-child > th {
  border-bottom: 0;
}
.panel > .table-responsive {
  border: 0;
  margin-bottom: 0;
}
.panel-group {
  margin-bottom: 18px;
}
.panel-group .panel {
  margin-bottom: 0;
  border-radius: 2px;
}
.panel-group .panel + .panel {
  margin-top: 5px;
}
.panel-group .panel-heading {
  border-bottom: 0;
}
.panel-group .panel-heading + .panel-collapse > .panel-body,
.panel-group .panel-heading + .panel-collapse > .list-group {
  border-top: 1px solid #ddd;
}
.panel-group .panel-footer {
  border-top: 0;
}
.panel-group .panel-footer + .panel-collapse .panel-body {
  border-bottom: 1px solid #ddd;
}
.panel-default {
  border-color: #ddd;
}
.panel-default > .panel-heading {
  color: #333333;
  background-color: #f5f5f5;
  border-color: #ddd;
}
.panel-default > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #ddd;
}
.panel-default > .panel-heading .badge {
  color: #f5f5f5;
  background-color: #333333;
}
.panel-default > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #ddd;
}
.panel-primary {
  border-color: #337ab7;
}
.panel-primary > .panel-heading {
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
}
.panel-primary > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #337ab7;
}
.panel-primary > .panel-heading .badge {
  color: #337ab7;
  background-color: #fff;
}
.panel-primary > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #337ab7;
}
.panel-success {
  border-color: #d6e9c6;
}
.panel-success > .panel-heading {
  color: #3c763d;
  background-color: #dff0d8;
  border-color: #d6e9c6;
}
.panel-success > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #d6e9c6;
}
.panel-success > .panel-heading .badge {
  color: #dff0d8;
  background-color: #3c763d;
}
.panel-success > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #d6e9c6;
}
.panel-info {
  border-color: #bce8f1;
}
.panel-info > .panel-heading {
  color: #31708f;
  background-color: #d9edf7;
  border-color: #bce8f1;
}
.panel-info > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #bce8f1;
}
.panel-info > .panel-heading .badge {
  color: #d9edf7;
  background-color: #31708f;
}
.panel-info > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #bce8f1;
}
.panel-warning {
  border-color: #faebcc;
}
.panel-warning > .panel-heading {
  color: #8a6d3b;
  background-color: #fcf8e3;
  border-color: #faebcc;
}
.panel-warning > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #faebcc;
}
.panel-warning > .panel-heading .badge {
  color: #fcf8e3;
  background-color: #8a6d3b;
}
.panel-warning > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #faebcc;
}
.panel-danger {
  border-color: #ebccd1;
}
.panel-danger > .panel-heading {
  color: #a94442;
  background-color: #f2dede;
  border-color: #ebccd1;
}
.panel-danger > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #ebccd1;
}
.panel-danger > .panel-heading .badge {
  color: #f2dede;
  background-color: #a94442;
}
.panel-danger > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #ebccd1;
}
.embed-responsive {
  position: relative;
  display: block;
  height: 0;
  padding: 0;
  overflow: hidden;
}
.embed-responsive .embed-responsive-item,
.embed-responsive iframe,
.embed-responsive embed,
.embed-responsive object,
.embed-responsive video {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  height: 100%;
  width: 100%;
  border: 0;
}
.embed-responsive-16by9 {
  padding-bottom: 56.25%;
}
.embed-responsive-4by3 {
  padding-bottom: 75%;
}
.well {
  min-height: 20px;
  padding: 19px;
  margin-bottom: 20px;
  background-color: #f5f5f5;
  border: 1px solid #e3e3e3;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
}
.well blockquote {
  border-color: #ddd;
  border-color: rgba(0, 0, 0, 0.15);
}
.well-lg {
  padding: 24px;
  border-radius: 3px;
}
.well-sm {
  padding: 9px;
  border-radius: 1px;
}
.close {
  float: right;
  font-size: 19.5px;
  font-weight: bold;
  line-height: 1;
  color: #000;
  text-shadow: 0 1px 0 #fff;
  opacity: 0.2;
  filter: alpha(opacity=20);
}
.close:hover,
.close:focus {
  color: #000;
  text-decoration: none;
  cursor: pointer;
  opacity: 0.5;
  filter: alpha(opacity=50);
}
button.close {
  padding: 0;
  cursor: pointer;
  background: transparent;
  border: 0;
  -webkit-appearance: none;
}
.modal-open {
  overflow: hidden;
}
.modal {
  display: none;
  overflow: hidden;
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1050;
  -webkit-overflow-scrolling: touch;
  outline: 0;
}
.modal.fade .modal-dialog {
  -webkit-transform: translate(0, -25%);
  -ms-transform: translate(0, -25%);
  -o-transform: translate(0, -25%);
  transform: translate(0, -25%);
  -webkit-transition: -webkit-transform 0.3s ease-out;
  -moz-transition: -moz-transform 0.3s ease-out;
  -o-transition: -o-transform 0.3s ease-out;
  transition: transform 0.3s ease-out;
}
.modal.in .modal-dialog {
  -webkit-transform: translate(0, 0);
  -ms-transform: translate(0, 0);
  -o-transform: translate(0, 0);
  transform: translate(0, 0);
}
.modal-open .modal {
  overflow-x: hidden;
  overflow-y: auto;
}
.modal-dialog {
  position: relative;
  width: auto;
  margin: 10px;
}
.modal-content {
  position: relative;
  background-color: #fff;
  border: 1px solid #999;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 3px;
  -webkit-box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  background-clip: padding-box;
  outline: 0;
}
.modal-backdrop {
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1040;
  background-color: #000;
}
.modal-backdrop.fade {
  opacity: 0;
  filter: alpha(opacity=0);
}
.modal-backdrop.in {
  opacity: 0.5;
  filter: alpha(opacity=50);
}
.modal-header {
  padding: 15px;
  border-bottom: 1px solid #e5e5e5;
}
.modal-header .close {
  margin-top: -2px;
}
.modal-title {
  margin: 0;
  line-height: 1.42857143;
}
.modal-body {
  position: relative;
  padding: 15px;
}
.modal-footer {
  padding: 15px;
  text-align: right;
  border-top: 1px solid #e5e5e5;
}
.modal-footer .btn + .btn {
  margin-left: 5px;
  margin-bottom: 0;
}
.modal-footer .btn-group .btn + .btn {
  margin-left: -1px;
}
.modal-footer .btn-block + .btn-block {
  margin-left: 0;
}
.modal-scrollbar-measure {
  position: absolute;
  top: -9999px;
  width: 50px;
  height: 50px;
  overflow: scroll;
}
@media (min-width: 768px) {
  .modal-dialog {
    width: 600px;
    margin: 30px auto;
  }
  .modal-content {
    -webkit-box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
  }
  .modal-sm {
    width: 300px;
  }
}
@media (min-width: 992px) {
  .modal-lg {
    width: 900px;
  }
}
.tooltip {
  position: absolute;
  z-index: 1070;
  display: block;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.42857143;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 12px;
  opacity: 0;
  filter: alpha(opacity=0);
}
.tooltip.in {
  opacity: 0.9;
  filter: alpha(opacity=90);
}
.tooltip.top {
  margin-top: -3px;
  padding: 5px 0;
}
.tooltip.right {
  margin-left: 3px;
  padding: 0 5px;
}
.tooltip.bottom {
  margin-top: 3px;
  padding: 5px 0;
}
.tooltip.left {
  margin-left: -3px;
  padding: 0 5px;
}
.tooltip-inner {
  max-width: 200px;
  padding: 3px 8px;
  color: #fff;
  text-align: center;
  background-color: #000;
  border-radius: 2px;
}
.tooltip-arrow {
  position: absolute;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}
.tooltip.top .tooltip-arrow {
  bottom: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.top-left .tooltip-arrow {
  bottom: 0;
  right: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.top-right .tooltip-arrow {
  bottom: 0;
  left: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.right .tooltip-arrow {
  top: 50%;
  left: 0;
  margin-top: -5px;
  border-width: 5px 5px 5px 0;
  border-right-color: #000;
}
.tooltip.left .tooltip-arrow {
  top: 50%;
  right: 0;
  margin-top: -5px;
  border-width: 5px 0 5px 5px;
  border-left-color: #000;
}
.tooltip.bottom .tooltip-arrow {
  top: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.tooltip.bottom-left .tooltip-arrow {
  top: 0;
  right: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.tooltip.bottom-right .tooltip-arrow {
  top: 0;
  left: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.popover {
  position: absolute;
  top: 0;
  left: 0;
  z-index: 1060;
  display: none;
  max-width: 276px;
  padding: 1px;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.42857143;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 13px;
  background-color: #fff;
  background-clip: padding-box;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 3px;
  -webkit-box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
}
.popover.top {
  margin-top: -10px;
}
.popover.right {
  margin-left: 10px;
}
.popover.bottom {
  margin-top: 10px;
}
.popover.left {
  margin-left: -10px;
}
.popover-title {
  margin: 0;
  padding: 8px 14px;
  font-size: 13px;
  background-color: #f7f7f7;
  border-bottom: 1px solid #ebebeb;
  border-radius: 2px 2px 0 0;
}
.popover-content {
  padding: 9px 14px;
}
.popover > .arrow,
.popover > .arrow:after {
  position: absolute;
  display: block;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}
.popover > .arrow {
  border-width: 11px;
}
.popover > .arrow:after {
  border-width: 10px;
  content: "";
}
.popover.top > .arrow {
  left: 50%;
  margin-left: -11px;
  border-bottom-width: 0;
  border-top-color: #999999;
  border-top-color: rgba(0, 0, 0, 0.25);
  bottom: -11px;
}
.popover.top > .arrow:after {
  content: " ";
  bottom: 1px;
  margin-left: -10px;
  border-bottom-width: 0;
  border-top-color: #fff;
}
.popover.right > .arrow {
  top: 50%;
  left: -11px;
  margin-top: -11px;
  border-left-width: 0;
  border-right-color: #999999;
  border-right-color: rgba(0, 0, 0, 0.25);
}
.popover.right > .arrow:after {
  content: " ";
  left: 1px;
  bottom: -10px;
  border-left-width: 0;
  border-right-color: #fff;
}
.popover.bottom > .arrow {
  left: 50%;
  margin-left: -11px;
  border-top-width: 0;
  border-bottom-color: #999999;
  border-bottom-color: rgba(0, 0, 0, 0.25);
  top: -11px;
}
.popover.bottom > .arrow:after {
  content: " ";
  top: 1px;
  margin-left: -10px;
  border-top-width: 0;
  border-bottom-color: #fff;
}
.popover.left > .arrow {
  top: 50%;
  right: -11px;
  margin-top: -11px;
  border-right-width: 0;
  border-left-color: #999999;
  border-left-color: rgba(0, 0, 0, 0.25);
}
.popover.left > .arrow:after {
  content: " ";
  right: 1px;
  border-right-width: 0;
  border-left-color: #fff;
  bottom: -10px;
}
.carousel {
  position: relative;
}
.carousel-inner {
  position: relative;
  overflow: hidden;
  width: 100%;
}
.carousel-inner > .item {
  display: none;
  position: relative;
  -webkit-transition: 0.6s ease-in-out left;
  -o-transition: 0.6s ease-in-out left;
  transition: 0.6s ease-in-out left;
}
.carousel-inner > .item > img,
.carousel-inner > .item > a > img {
  line-height: 1;
}
@media all and (transform-3d), (-webkit-transform-3d) {
  .carousel-inner > .item {
    -webkit-transition: -webkit-transform 0.6s ease-in-out;
    -moz-transition: -moz-transform 0.6s ease-in-out;
    -o-transition: -o-transform 0.6s ease-in-out;
    transition: transform 0.6s ease-in-out;
    -webkit-backface-visibility: hidden;
    -moz-backface-visibility: hidden;
    backface-visibility: hidden;
    -webkit-perspective: 1000px;
    -moz-perspective: 1000px;
    perspective: 1000px;
  }
  .carousel-inner > .item.next,
  .carousel-inner > .item.active.right {
    -webkit-transform: translate3d(100%, 0, 0);
    transform: translate3d(100%, 0, 0);
    left: 0;
  }
  .carousel-inner > .item.prev,
  .carousel-inner > .item.active.left {
    -webkit-transform: translate3d(-100%, 0, 0);
    transform: translate3d(-100%, 0, 0);
    left: 0;
  }
  .carousel-inner > .item.next.left,
  .carousel-inner > .item.prev.right,
  .carousel-inner > .item.active {
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
    left: 0;
  }
}
.carousel-inner > .active,
.carousel-inner > .next,
.carousel-inner > .prev {
  display: block;
}
.carousel-inner > .active {
  left: 0;
}
.carousel-inner > .next,
.carousel-inner > .prev {
  position: absolute;
  top: 0;
  width: 100%;
}
.carousel-inner > .next {
  left: 100%;
}
.carousel-inner > .prev {
  left: -100%;
}
.carousel-inner > .next.left,
.carousel-inner > .prev.right {
  left: 0;
}
.carousel-inner > .active.left {
  left: -100%;
}
.carousel-inner > .active.right {
  left: 100%;
}
.carousel-control {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  width: 15%;
  opacity: 0.5;
  filter: alpha(opacity=50);
  font-size: 20px;
  color: #fff;
  text-align: center;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
  background-color: rgba(0, 0, 0, 0);
}
.carousel-control.left {
  background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-image: linear-gradient(to right, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#80000000', endColorstr='#00000000', GradientType=1);
}
.carousel-control.right {
  left: auto;
  right: 0;
  background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-image: linear-gradient(to right, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#00000000', endColorstr='#80000000', GradientType=1);
}
.carousel-control:hover,
.carousel-control:focus {
  outline: 0;
  color: #fff;
  text-decoration: none;
  opacity: 0.9;
  filter: alpha(opacity=90);
}
.carousel-control .icon-prev,
.carousel-control .icon-next,
.carousel-control .glyphicon-chevron-left,
.carousel-control .glyphicon-chevron-right {
  position: absolute;
  top: 50%;
  margin-top: -10px;
  z-index: 5;
  display: inline-block;
}
.carousel-control .icon-prev,
.carousel-control .glyphicon-chevron-left {
  left: 50%;
  margin-left: -10px;
}
.carousel-control .icon-next,
.carousel-control .glyphicon-chevron-right {
  right: 50%;
  margin-right: -10px;
}
.carousel-control .icon-prev,
.carousel-control .icon-next {
  width: 20px;
  height: 20px;
  line-height: 1;
  font-family: serif;
}
.carousel-control .icon-prev:before {
  content: '\2039';
}
.carousel-control .icon-next:before {
  content: '\203a';
}
.carousel-indicators {
  position: absolute;
  bottom: 10px;
  left: 50%;
  z-index: 15;
  width: 60%;
  margin-left: -30%;
  padding-left: 0;
  list-style: none;
  text-align: center;
}
.carousel-indicators li {
  display: inline-block;
  width: 10px;
  height: 10px;
  margin: 1px;
  text-indent: -999px;
  border: 1px solid #fff;
  border-radius: 10px;
  cursor: pointer;
  background-color: #000 \9;
  background-color: rgba(0, 0, 0, 0);
}
.carousel-indicators .active {
  margin: 0;
  width: 12px;
  height: 12px;
  background-color: #fff;
}
.carousel-caption {
  position: absolute;
  left: 15%;
  right: 15%;
  bottom: 20px;
  z-index: 10;
  padding-top: 20px;
  padding-bottom: 20px;
  color: #fff;
  text-align: center;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
}
.carousel-caption .btn {
  text-shadow: none;
}
@media screen and (min-width: 768px) {
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .glyphicon-chevron-right,
  .carousel-control .icon-prev,
  .carousel-control .icon-next {
    width: 30px;
    height: 30px;
    margin-top: -10px;
    font-size: 30px;
  }
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .icon-prev {
    margin-left: -10px;
  }
  .carousel-control .glyphicon-chevron-right,
  .carousel-control .icon-next {
    margin-right: -10px;
  }
  .carousel-caption {
    left: 20%;
    right: 20%;
    padding-bottom: 30px;
  }
  .carousel-indicators {
    bottom: 20px;
  }
}
.clearfix:before,
.clearfix:after,
.dl-horizontal dd:before,
.dl-horizontal dd:after,
.container:before,
.container:after,
.container-fluid:before,
.container-fluid:after,
.row:before,
.row:after,
.form-horizontal .form-group:before,
.form-horizontal .form-group:after,
.btn-toolbar:before,
.btn-toolbar:after,
.btn-group-vertical > .btn-group:before,
.btn-group-vertical > .btn-group:after,
.nav:before,
.nav:after,
.navbar:before,
.navbar:after,
.navbar-header:before,
.navbar-header:after,
.navbar-collapse:before,
.navbar-collapse:after,
.pager:before,
.pager:after,
.panel-body:before,
.panel-body:after,
.modal-header:before,
.modal-header:after,
.modal-footer:before,
.modal-footer:after,
.item_buttons:before,
.item_buttons:after {
  content: " ";
  display: table;
}
.clearfix:after,
.dl-horizontal dd:after,
.container:after,
.container-fluid:after,
.row:after,
.form-horizontal .form-group:after,
.btn-toolbar:after,
.btn-group-vertical > .btn-group:after,
.nav:after,
.navbar:after,
.navbar-header:after,
.navbar-collapse:after,
.pager:after,
.panel-body:after,
.modal-header:after,
.modal-footer:after,
.item_buttons:after {
  clear: both;
}
.center-block {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.pull-right {
  float: right !important;
}
.pull-left {
  float: left !important;
}
.hide {
  display: none !important;
}
.show {
  display: block !important;
}
.invisible {
  visibility: hidden;
}
.text-hide {
  font: 0/0 a;
  color: transparent;
  text-shadow: none;
  background-color: transparent;
  border: 0;
}
.hidden {
  display: none !important;
}
.affix {
  position: fixed;
}
@-ms-viewport {
  width: device-width;
}
.visible-xs,
.visible-sm,
.visible-md,
.visible-lg {
  display: none !important;
}
.visible-xs-block,
.visible-xs-inline,
.visible-xs-inline-block,
.visible-sm-block,
.visible-sm-inline,
.visible-sm-inline-block,
.visible-md-block,
.visible-md-inline,
.visible-md-inline-block,
.visible-lg-block,
.visible-lg-inline,
.visible-lg-inline-block {
  display: none !important;
}
@media (max-width: 767px) {
  .visible-xs {
    display: block !important;
  }
  table.visible-xs {
    display: table !important;
  }
  tr.visible-xs {
    display: table-row !important;
  }
  th.visible-xs,
  td.visible-xs {
    display: table-cell !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-block {
    display: block !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-inline {
    display: inline !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm {
    display: block !important;
  }
  table.visible-sm {
    display: table !important;
  }
  tr.visible-sm {
    display: table-row !important;
  }
  th.visible-sm,
  td.visible-sm {
    display: table-cell !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-block {
    display: block !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline {
    display: inline !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md {
    display: block !important;
  }
  table.visible-md {
    display: table !important;
  }
  tr.visible-md {
    display: table-row !important;
  }
  th.visible-md,
  td.visible-md {
    display: table-cell !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-block {
    display: block !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline {
    display: inline !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg {
    display: block !important;
  }
  table.visible-lg {
    display: table !important;
  }
  tr.visible-lg {
    display: table-row !important;
  }
  th.visible-lg,
  td.visible-lg {
    display: table-cell !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-block {
    display: block !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-inline {
    display: inline !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-inline-block {
    display: inline-block !important;
  }
}
@media (max-width: 767px) {
  .hidden-xs {
    display: none !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .hidden-sm {
    display: none !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .hidden-md {
    display: none !important;
  }
}
@media (min-width: 1200px) {
  .hidden-lg {
    display: none !important;
  }
}
.visible-print {
  display: none !important;
}
@media print {
  .visible-print {
    display: block !important;
  }
  table.visible-print {
    display: table !important;
  }
  tr.visible-print {
    display: table-row !important;
  }
  th.visible-print,
  td.visible-print {
    display: table-cell !important;
  }
}
.visible-print-block {
  display: none !important;
}
@media print {
  .visible-print-block {
    display: block !important;
  }
}
.visible-print-inline {
  display: none !important;
}
@media print {
  .visible-print-inline {
    display: inline !important;
  }
}
.visible-print-inline-block {
  display: none !important;
}
@media print {
  .visible-print-inline-block {
    display: inline-block !important;
  }
}
@media print {
  .hidden-print {
    display: none !important;
  }
}
/*!
*
* Font Awesome
*
*/
/*!
 *  Font Awesome 4.7.0 by @davegandy - http://fontawesome.io - @fontawesome
 *  License - http://fontawesome.io/license (Font: SIL OFL 1.1, CSS: MIT License)
 */
/* FONT PATH
 * -------------------------- */
@font-face {
  font-family: 'FontAwesome';
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?v=4.7.0');
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?#iefix&v=4.7.0') format('embedded-opentype'), url('../components/font-awesome/fonts/fontawesome-webfont.woff2?v=4.7.0') format('woff2'), url('../components/font-awesome/fonts/fontawesome-webfont.woff?v=4.7.0') format('woff'), url('../components/font-awesome/fonts/fontawesome-webfont.ttf?v=4.7.0') format('truetype'), url('../components/font-awesome/fonts/fontawesome-webfont.svg?v=4.7.0#fontawesomeregular') format('svg');
  font-weight: normal;
  font-style: normal;
}
.fa {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
/* makes the font 33% larger relative to the icon container */
.fa-lg {
  font-size: 1.33333333em;
  line-height: 0.75em;
  vertical-align: -15%;
}
.fa-2x {
  font-size: 2em;
}
.fa-3x {
  font-size: 3em;
}
.fa-4x {
  font-size: 4em;
}
.fa-5x {
  font-size: 5em;
}
.fa-fw {
  width: 1.28571429em;
  text-align: center;
}
.fa-ul {
  padding-left: 0;
  margin-left: 2.14285714em;
  list-style-type: none;
}
.fa-ul > li {
  position: relative;
}
.fa-li {
  position: absolute;
  left: -2.14285714em;
  width: 2.14285714em;
  top: 0.14285714em;
  text-align: center;
}
.fa-li.fa-lg {
  left: -1.85714286em;
}
.fa-border {
  padding: .2em .25em .15em;
  border: solid 0.08em #eee;
  border-radius: .1em;
}
.fa-pull-left {
  float: left;
}
.fa-pull-right {
  float: right;
}
.fa.fa-pull-left {
  margin-right: .3em;
}
.fa.fa-pull-right {
  margin-left: .3em;
}
/* Deprecated as of 4.4.0 */
.pull-right {
  float: right;
}
.pull-left {
  float: left;
}
.fa.pull-left {
  margin-right: .3em;
}
.fa.pull-right {
  margin-left: .3em;
}
.fa-spin {
  -webkit-animation: fa-spin 2s infinite linear;
  animation: fa-spin 2s infinite linear;
}
.fa-pulse {
  -webkit-animation: fa-spin 1s infinite steps(8);
  animation: fa-spin 1s infinite steps(8);
}
@-webkit-keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg);
  }
}
@keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg);
  }
}
.fa-rotate-90 {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=1)";
  -webkit-transform: rotate(90deg);
  -ms-transform: rotate(90deg);
  transform: rotate(90deg);
}
.fa-rotate-180 {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=2)";
  -webkit-transform: rotate(180deg);
  -ms-transform: rotate(180deg);
  transform: rotate(180deg);
}
.fa-rotate-270 {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=3)";
  -webkit-transform: rotate(270deg);
  -ms-transform: rotate(270deg);
  transform: rotate(270deg);
}
.fa-flip-horizontal {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=0, mirror=1)";
  -webkit-transform: scale(-1, 1);
  -ms-transform: scale(-1, 1);
  transform: scale(-1, 1);
}
.fa-flip-vertical {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=2, mirror=1)";
  -webkit-transform: scale(1, -1);
  -ms-transform: scale(1, -1);
  transform: scale(1, -1);
}
:root .fa-rotate-90,
:root .fa-rotate-180,
:root .fa-rotate-270,
:root .fa-flip-horizontal,
:root .fa-flip-vertical {
  filter: none;
}
.fa-stack {
  position: relative;
  display: inline-block;
  width: 2em;
  height: 2em;
  line-height: 2em;
  vertical-align: middle;
}
.fa-stack-1x,
.fa-stack-2x {
  position: absolute;
  left: 0;
  width: 100%;
  text-align: center;
}
.fa-stack-1x {
  line-height: inherit;
}
.fa-stack-2x {
  font-size: 2em;
}
.fa-inverse {
  color: #fff;
}
/* Font Awesome uses the Unicode Private Use Area (PUA) to ensure screen
   readers do not read off random characters that represent icons */
.fa-glass:before {
  content: "\f000";
}
.fa-music:before {
  content: "\f001";
}
.fa-search:before {
  content: "\f002";
}
.fa-envelope-o:before {
  content: "\f003";
}
.fa-heart:before {
  content: "\f004";
}
.fa-star:before {
  content: "\f005";
}
.fa-star-o:before {
  content: "\f006";
}
.fa-user:before {
  content: "\f007";
}
.fa-film:before {
  content: "\f008";
}
.fa-th-large:before {
  content: "\f009";
}
.fa-th:before {
  content: "\f00a";
}
.fa-th-list:before {
  content: "\f00b";
}
.fa-check:before {
  content: "\f00c";
}
.fa-remove:before,
.fa-close:before,
.fa-times:before {
  content: "\f00d";
}
.fa-search-plus:before {
  content: "\f00e";
}
.fa-search-minus:before {
  content: "\f010";
}
.fa-power-off:before {
  content: "\f011";
}
.fa-signal:before {
  content: "\f012";
}
.fa-gear:before,
.fa-cog:before {
  content: "\f013";
}
.fa-trash-o:before {
  content: "\f014";
}
.fa-home:before {
  content: "\f015";
}
.fa-file-o:before {
  content: "\f016";
}
.fa-clock-o:before {
  content: "\f017";
}
.fa-road:before {
  content: "\f018";
}
.fa-download:before {
  content: "\f019";
}
.fa-arrow-circle-o-down:before {
  content: "\f01a";
}
.fa-arrow-circle-o-up:before {
  content: "\f01b";
}
.fa-inbox:before {
  content: "\f01c";
}
.fa-play-circle-o:before {
  content: "\f01d";
}
.fa-rotate-right:before,
.fa-repeat:before {
  content: "\f01e";
}
.fa-refresh:before {
  content: "\f021";
}
.fa-list-alt:before {
  content: "\f022";
}
.fa-lock:before {
  content: "\f023";
}
.fa-flag:before {
  content: "\f024";
}
.fa-headphones:before {
  content: "\f025";
}
.fa-volume-off:before {
  content: "\f026";
}
.fa-volume-down:before {
  content: "\f027";
}
.fa-volume-up:before {
  content: "\f028";
}
.fa-qrcode:before {
  content: "\f029";
}
.fa-barcode:before {
  content: "\f02a";
}
.fa-tag:before {
  content: "\f02b";
}
.fa-tags:before {
  content: "\f02c";
}
.fa-book:before {
  content: "\f02d";
}
.fa-bookmark:before {
  content: "\f02e";
}
.fa-print:before {
  content: "\f02f";
}
.fa-camera:before {
  content: "\f030";
}
.fa-font:before {
  content: "\f031";
}
.fa-bold:before {
  content: "\f032";
}
.fa-italic:before {
  content: "\f033";
}
.fa-text-height:before {
  content: "\f034";
}
.fa-text-width:before {
  content: "\f035";
}
.fa-align-left:before {
  content: "\f036";
}
.fa-align-center:before {
  content: "\f037";
}
.fa-align-right:before {
  content: "\f038";
}
.fa-align-justify:before {
  content: "\f039";
}
.fa-list:before {
  content: "\f03a";
}
.fa-dedent:before,
.fa-outdent:before {
  content: "\f03b";
}
.fa-indent:before {
  content: "\f03c";
}
.fa-video-camera:before {
  content: "\f03d";
}
.fa-photo:before,
.fa-image:before,
.fa-picture-o:before {
  content: "\f03e";
}
.fa-pencil:before {
  content: "\f040";
}
.fa-map-marker:before {
  content: "\f041";
}
.fa-adjust:before {
  content: "\f042";
}
.fa-tint:before {
  content: "\f043";
}
.fa-edit:before,
.fa-pencil-square-o:before {
  content: "\f044";
}
.fa-share-square-o:before {
  content: "\f045";
}
.fa-check-square-o:before {
  content: "\f046";
}
.fa-arrows:before {
  content: "\f047";
}
.fa-step-backward:before {
  content: "\f048";
}
.fa-fast-backward:before {
  content: "\f049";
}
.fa-backward:before {
  content: "\f04a";
}
.fa-play:before {
  content: "\f04b";
}
.fa-pause:before {
  content: "\f04c";
}
.fa-stop:before {
  content: "\f04d";
}
.fa-forward:before {
  content: "\f04e";
}
.fa-fast-forward:before {
  content: "\f050";
}
.fa-step-forward:before {
  content: "\f051";
}
.fa-eject:before {
  content: "\f052";
}
.fa-chevron-left:before {
  content: "\f053";
}
.fa-chevron-right:before {
  content: "\f054";
}
.fa-plus-circle:before {
  content: "\f055";
}
.fa-minus-circle:before {
  content: "\f056";
}
.fa-times-circle:before {
  content: "\f057";
}
.fa-check-circle:before {
  content: "\f058";
}
.fa-question-circle:before {
  content: "\f059";
}
.fa-info-circle:before {
  content: "\f05a";
}
.fa-crosshairs:before {
  content: "\f05b";
}
.fa-times-circle-o:before {
  content: "\f05c";
}
.fa-check-circle-o:before {
  content: "\f05d";
}
.fa-ban:before {
  content: "\f05e";
}
.fa-arrow-left:before {
  content: "\f060";
}
.fa-arrow-right:before {
  content: "\f061";
}
.fa-arrow-up:before {
  content: "\f062";
}
.fa-arrow-down:before {
  content: "\f063";
}
.fa-mail-forward:before,
.fa-share:before {
  content: "\f064";
}
.fa-expand:before {
  content: "\f065";
}
.fa-compress:before {
  content: "\f066";
}
.fa-plus:before {
  content: "\f067";
}
.fa-minus:before {
  content: "\f068";
}
.fa-asterisk:before {
  content: "\f069";
}
.fa-exclamation-circle:before {
  content: "\f06a";
}
.fa-gift:before {
  content: "\f06b";
}
.fa-leaf:before {
  content: "\f06c";
}
.fa-fire:before {
  content: "\f06d";
}
.fa-eye:before {
  content: "\f06e";
}
.fa-eye-slash:before {
  content: "\f070";
}
.fa-warning:before,
.fa-exclamation-triangle:before {
  content: "\f071";
}
.fa-plane:before {
  content: "\f072";
}
.fa-calendar:before {
  content: "\f073";
}
.fa-random:before {
  content: "\f074";
}
.fa-comment:before {
  content: "\f075";
}
.fa-magnet:before {
  content: "\f076";
}
.fa-chevron-up:before {
  content: "\f077";
}
.fa-chevron-down:before {
  content: "\f078";
}
.fa-retweet:before {
  content: "\f079";
}
.fa-shopping-cart:before {
  content: "\f07a";
}
.fa-folder:before {
  content: "\f07b";
}
.fa-folder-open:before {
  content: "\f07c";
}
.fa-arrows-v:before {
  content: "\f07d";
}
.fa-arrows-h:before {
  content: "\f07e";
}
.fa-bar-chart-o:before,
.fa-bar-chart:before {
  content: "\f080";
}
.fa-twitter-square:before {
  content: "\f081";
}
.fa-facebook-square:before {
  content: "\f082";
}
.fa-camera-retro:before {
  content: "\f083";
}
.fa-key:before {
  content: "\f084";
}
.fa-gears:before,
.fa-cogs:before {
  content: "\f085";
}
.fa-comments:before {
  content: "\f086";
}
.fa-thumbs-o-up:before {
  content: "\f087";
}
.fa-thumbs-o-down:before {
  content: "\f088";
}
.fa-star-half:before {
  content: "\f089";
}
.fa-heart-o:before {
  content: "\f08a";
}
.fa-sign-out:before {
  content: "\f08b";
}
.fa-linkedin-square:before {
  content: "\f08c";
}
.fa-thumb-tack:before {
  content: "\f08d";
}
.fa-external-link:before {
  content: "\f08e";
}
.fa-sign-in:before {
  content: "\f090";
}
.fa-trophy:before {
  content: "\f091";
}
.fa-github-square:before {
  content: "\f092";
}
.fa-upload:before {
  content: "\f093";
}
.fa-lemon-o:before {
  content: "\f094";
}
.fa-phone:before {
  content: "\f095";
}
.fa-square-o:before {
  content: "\f096";
}
.fa-bookmark-o:before {
  content: "\f097";
}
.fa-phone-square:before {
  content: "\f098";
}
.fa-twitter:before {
  content: "\f099";
}
.fa-facebook-f:before,
.fa-facebook:before {
  content: "\f09a";
}
.fa-github:before {
  content: "\f09b";
}
.fa-unlock:before {
  content: "\f09c";
}
.fa-credit-card:before {
  content: "\f09d";
}
.fa-feed:before,
.fa-rss:before {
  content: "\f09e";
}
.fa-hdd-o:before {
  content: "\f0a0";
}
.fa-bullhorn:before {
  content: "\f0a1";
}
.fa-bell:before {
  content: "\f0f3";
}
.fa-certificate:before {
  content: "\f0a3";
}
.fa-hand-o-right:before {
  content: "\f0a4";
}
.fa-hand-o-left:before {
  content: "\f0a5";
}
.fa-hand-o-up:before {
  content: "\f0a6";
}
.fa-hand-o-down:before {
  content: "\f0a7";
}
.fa-arrow-circle-left:before {
  content: "\f0a8";
}
.fa-arrow-circle-right:before {
  content: "\f0a9";
}
.fa-arrow-circle-up:before {
  content: "\f0aa";
}
.fa-arrow-circle-down:before {
  content: "\f0ab";
}
.fa-globe:before {
  content: "\f0ac";
}
.fa-wrench:before {
  content: "\f0ad";
}
.fa-tasks:before {
  content: "\f0ae";
}
.fa-filter:before {
  content: "\f0b0";
}
.fa-briefcase:before {
  content: "\f0b1";
}
.fa-arrows-alt:before {
  content: "\f0b2";
}
.fa-group:before,
.fa-users:before {
  content: "\f0c0";
}
.fa-chain:before,
.fa-link:before {
  content: "\f0c1";
}
.fa-cloud:before {
  content: "\f0c2";
}
.fa-flask:before {
  content: "\f0c3";
}
.fa-cut:before,
.fa-scissors:before {
  content: "\f0c4";
}
.fa-copy:before,
.fa-files-o:before {
  content: "\f0c5";
}
.fa-paperclip:before {
  content: "\f0c6";
}
.fa-save:before,
.fa-floppy-o:before {
  content: "\f0c7";
}
.fa-square:before {
  content: "\f0c8";
}
.fa-navicon:before,
.fa-reorder:before,
.fa-bars:before {
  content: "\f0c9";
}
.fa-list-ul:before {
  content: "\f0ca";
}
.fa-list-ol:before {
  content: "\f0cb";
}
.fa-strikethrough:before {
  content: "\f0cc";
}
.fa-underline:before {
  content: "\f0cd";
}
.fa-table:before {
  content: "\f0ce";
}
.fa-magic:before {
  content: "\f0d0";
}
.fa-truck:before {
  content: "\f0d1";
}
.fa-pinterest:before {
  content: "\f0d2";
}
.fa-pinterest-square:before {
  content: "\f0d3";
}
.fa-google-plus-square:before {
  content: "\f0d4";
}
.fa-google-plus:before {
  content: "\f0d5";
}
.fa-money:before {
  content: "\f0d6";
}
.fa-caret-down:before {
  content: "\f0d7";
}
.fa-caret-up:before {
  content: "\f0d8";
}
.fa-caret-left:before {
  content: "\f0d9";
}
.fa-caret-right:before {
  content: "\f0da";
}
.fa-columns:before {
  content: "\f0db";
}
.fa-unsorted:before,
.fa-sort:before {
  content: "\f0dc";
}
.fa-sort-down:before,
.fa-sort-desc:before {
  content: "\f0dd";
}
.fa-sort-up:before,
.fa-sort-asc:before {
  content: "\f0de";
}
.fa-envelope:before {
  content: "\f0e0";
}
.fa-linkedin:before {
  content: "\f0e1";
}
.fa-rotate-left:before,
.fa-undo:before {
  content: "\f0e2";
}
.fa-legal:before,
.fa-gavel:before {
  content: "\f0e3";
}
.fa-dashboard:before,
.fa-tachometer:before {
  content: "\f0e4";
}
.fa-comment-o:before {
  content: "\f0e5";
}
.fa-comments-o:before {
  content: "\f0e6";
}
.fa-flash:before,
.fa-bolt:before {
  content: "\f0e7";
}
.fa-sitemap:before {
  content: "\f0e8";
}
.fa-umbrella:before {
  content: "\f0e9";
}
.fa-paste:before,
.fa-clipboard:before {
  content: "\f0ea";
}
.fa-lightbulb-o:before {
  content: "\f0eb";
}
.fa-exchange:before {
  content: "\f0ec";
}
.fa-cloud-download:before {
  content: "\f0ed";
}
.fa-cloud-upload:before {
  content: "\f0ee";
}
.fa-user-md:before {
  content: "\f0f0";
}
.fa-stethoscope:before {
  content: "\f0f1";
}
.fa-suitcase:before {
  content: "\f0f2";
}
.fa-bell-o:before {
  content: "\f0a2";
}
.fa-coffee:before {
  content: "\f0f4";
}
.fa-cutlery:before {
  content: "\f0f5";
}
.fa-file-text-o:before {
  content: "\f0f6";
}
.fa-building-o:before {
  content: "\f0f7";
}
.fa-hospital-o:before {
  content: "\f0f8";
}
.fa-ambulance:before {
  content: "\f0f9";
}
.fa-medkit:before {
  content: "\f0fa";
}
.fa-fighter-jet:before {
  content: "\f0fb";
}
.fa-beer:before {
  content: "\f0fc";
}
.fa-h-square:before {
  content: "\f0fd";
}
.fa-plus-square:before {
  content: "\f0fe";
}
.fa-angle-double-left:before {
  content: "\f100";
}
.fa-angle-double-right:before {
  content: "\f101";
}
.fa-angle-double-up:before {
  content: "\f102";
}
.fa-angle-double-down:before {
  content: "\f103";
}
.fa-angle-left:before {
  content: "\f104";
}
.fa-angle-right:before {
  content: "\f105";
}
.fa-angle-up:before {
  content: "\f106";
}
.fa-angle-down:before {
  content: "\f107";
}
.fa-desktop:before {
  content: "\f108";
}
.fa-laptop:before {
  content: "\f109";
}
.fa-tablet:before {
  content: "\f10a";
}
.fa-mobile-phone:before,
.fa-mobile:before {
  content: "\f10b";
}
.fa-circle-o:before {
  content: "\f10c";
}
.fa-quote-left:before {
  content: "\f10d";
}
.fa-quote-right:before {
  content: "\f10e";
}
.fa-spinner:before {
  content: "\f110";
}
.fa-circle:before {
  content: "\f111";
}
.fa-mail-reply:before,
.fa-reply:before {
  content: "\f112";
}
.fa-github-alt:before {
  content: "\f113";
}
.fa-folder-o:before {
  content: "\f114";
}
.fa-folder-open-o:before {
  content: "\f115";
}
.fa-smile-o:before {
  content: "\f118";
}
.fa-frown-o:before {
  content: "\f119";
}
.fa-meh-o:before {
  content: "\f11a";
}
.fa-gamepad:before {
  content: "\f11b";
}
.fa-keyboard-o:before {
  content: "\f11c";
}
.fa-flag-o:before {
  content: "\f11d";
}
.fa-flag-checkered:before {
  content: "\f11e";
}
.fa-terminal:before {
  content: "\f120";
}
.fa-code:before {
  content: "\f121";
}
.fa-mail-reply-all:before,
.fa-reply-all:before {
  content: "\f122";
}
.fa-star-half-empty:before,
.fa-star-half-full:before,
.fa-star-half-o:before {
  content: "\f123";
}
.fa-location-arrow:before {
  content: "\f124";
}
.fa-crop:before {
  content: "\f125";
}
.fa-code-fork:before {
  content: "\f126";
}
.fa-unlink:before,
.fa-chain-broken:before {
  content: "\f127";
}
.fa-question:before {
  content: "\f128";
}
.fa-info:before {
  content: "\f129";
}
.fa-exclamation:before {
  content: "\f12a";
}
.fa-superscript:before {
  content: "\f12b";
}
.fa-subscript:before {
  content: "\f12c";
}
.fa-eraser:before {
  content: "\f12d";
}
.fa-puzzle-piece:before {
  content: "\f12e";
}
.fa-microphone:before {
  content: "\f130";
}
.fa-microphone-slash:before {
  content: "\f131";
}
.fa-shield:before {
  content: "\f132";
}
.fa-calendar-o:before {
  content: "\f133";
}
.fa-fire-extinguisher:before {
  content: "\f134";
}
.fa-rocket:before {
  content: "\f135";
}
.fa-maxcdn:before {
  content: "\f136";
}
.fa-chevron-circle-left:before {
  content: "\f137";
}
.fa-chevron-circle-right:before {
  content: "\f138";
}
.fa-chevron-circle-up:before {
  content: "\f139";
}
.fa-chevron-circle-down:before {
  content: "\f13a";
}
.fa-html5:before {
  content: "\f13b";
}
.fa-css3:before {
  content: "\f13c";
}
.fa-anchor:before {
  content: "\f13d";
}
.fa-unlock-alt:before {
  content: "\f13e";
}
.fa-bullseye:before {
  content: "\f140";
}
.fa-ellipsis-h:before {
  content: "\f141";
}
.fa-ellipsis-v:before {
  content: "\f142";
}
.fa-rss-square:before {
  content: "\f143";
}
.fa-play-circle:before {
  content: "\f144";
}
.fa-ticket:before {
  content: "\f145";
}
.fa-minus-square:before {
  content: "\f146";
}
.fa-minus-square-o:before {
  content: "\f147";
}
.fa-level-up:before {
  content: "\f148";
}
.fa-level-down:before {
  content: "\f149";
}
.fa-check-square:before {
  content: "\f14a";
}
.fa-pencil-square:before {
  content: "\f14b";
}
.fa-external-link-square:before {
  content: "\f14c";
}
.fa-share-square:before {
  content: "\f14d";
}
.fa-compass:before {
  content: "\f14e";
}
.fa-toggle-down:before,
.fa-caret-square-o-down:before {
  content: "\f150";
}
.fa-toggle-up:before,
.fa-caret-square-o-up:before {
  content: "\f151";
}
.fa-toggle-right:before,
.fa-caret-square-o-right:before {
  content: "\f152";
}
.fa-euro:before,
.fa-eur:before {
  content: "\f153";
}
.fa-gbp:before {
  content: "\f154";
}
.fa-dollar:before,
.fa-usd:before {
  content: "\f155";
}
.fa-rupee:before,
.fa-inr:before {
  content: "\f156";
}
.fa-cny:before,
.fa-rmb:before,
.fa-yen:before,
.fa-jpy:before {
  content: "\f157";
}
.fa-ruble:before,
.fa-rouble:before,
.fa-rub:before {
  content: "\f158";
}
.fa-won:before,
.fa-krw:before {
  content: "\f159";
}
.fa-bitcoin:before,
.fa-btc:before {
  content: "\f15a";
}
.fa-file:before {
  content: "\f15b";
}
.fa-file-text:before {
  content: "\f15c";
}
.fa-sort-alpha-asc:before {
  content: "\f15d";
}
.fa-sort-alpha-desc:before {
  content: "\f15e";
}
.fa-sort-amount-asc:before {
  content: "\f160";
}
.fa-sort-amount-desc:before {
  content: "\f161";
}
.fa-sort-numeric-asc:before {
  content: "\f162";
}
.fa-sort-numeric-desc:before {
  content: "\f163";
}
.fa-thumbs-up:before {
  content: "\f164";
}
.fa-thumbs-down:before {
  content: "\f165";
}
.fa-youtube-square:before {
  content: "\f166";
}
.fa-youtube:before {
  content: "\f167";
}
.fa-xing:before {
  content: "\f168";
}
.fa-xing-square:before {
  content: "\f169";
}
.fa-youtube-play:before {
  content: "\f16a";
}
.fa-dropbox:before {
  content: "\f16b";
}
.fa-stack-overflow:before {
  content: "\f16c";
}
.fa-instagram:before {
  content: "\f16d";
}
.fa-flickr:before {
  content: "\f16e";
}
.fa-adn:before {
  content: "\f170";
}
.fa-bitbucket:before {
  content: "\f171";
}
.fa-bitbucket-square:before {
  content: "\f172";
}
.fa-tumblr:before {
  content: "\f173";
}
.fa-tumblr-square:before {
  content: "\f174";
}
.fa-long-arrow-down:before {
  content: "\f175";
}
.fa-long-arrow-up:before {
  content: "\f176";
}
.fa-long-arrow-left:before {
  content: "\f177";
}
.fa-long-arrow-right:before {
  content: "\f178";
}
.fa-apple:before {
  content: "\f179";
}
.fa-windows:before {
  content: "\f17a";
}
.fa-android:before {
  content: "\f17b";
}
.fa-linux:before {
  content: "\f17c";
}
.fa-dribbble:before {
  content: "\f17d";
}
.fa-skype:before {
  content: "\f17e";
}
.fa-foursquare:before {
  content: "\f180";
}
.fa-trello:before {
  content: "\f181";
}
.fa-female:before {
  content: "\f182";
}
.fa-male:before {
  content: "\f183";
}
.fa-gittip:before,
.fa-gratipay:before {
  content: "\f184";
}
.fa-sun-o:before {
  content: "\f185";
}
.fa-moon-o:before {
  content: "\f186";
}
.fa-archive:before {
  content: "\f187";
}
.fa-bug:before {
  content: "\f188";
}
.fa-vk:before {
  content: "\f189";
}
.fa-weibo:before {
  content: "\f18a";
}
.fa-renren:before {
  content: "\f18b";
}
.fa-pagelines:before {
  content: "\f18c";
}
.fa-stack-exchange:before {
  content: "\f18d";
}
.fa-arrow-circle-o-right:before {
  content: "\f18e";
}
.fa-arrow-circle-o-left:before {
  content: "\f190";
}
.fa-toggle-left:before,
.fa-caret-square-o-left:before {
  content: "\f191";
}
.fa-dot-circle-o:before {
  content: "\f192";
}
.fa-wheelchair:before {
  content: "\f193";
}
.fa-vimeo-square:before {
  content: "\f194";
}
.fa-turkish-lira:before,
.fa-try:before {
  content: "\f195";
}
.fa-plus-square-o:before {
  content: "\f196";
}
.fa-space-shuttle:before {
  content: "\f197";
}
.fa-slack:before {
  content: "\f198";
}
.fa-envelope-square:before {
  content: "\f199";
}
.fa-wordpress:before {
  content: "\f19a";
}
.fa-openid:before {
  content: "\f19b";
}
.fa-institution:before,
.fa-bank:before,
.fa-university:before {
  content: "\f19c";
}
.fa-mortar-board:before,
.fa-graduation-cap:before {
  content: "\f19d";
}
.fa-yahoo:before {
  content: "\f19e";
}
.fa-google:before {
  content: "\f1a0";
}
.fa-reddit:before {
  content: "\f1a1";
}
.fa-reddit-square:before {
  content: "\f1a2";
}
.fa-stumbleupon-circle:before {
  content: "\f1a3";
}
.fa-stumbleupon:before {
  content: "\f1a4";
}
.fa-delicious:before {
  content: "\f1a5";
}
.fa-digg:before {
  content: "\f1a6";
}
.fa-pied-piper-pp:before {
  content: "\f1a7";
}
.fa-pied-piper-alt:before {
  content: "\f1a8";
}
.fa-drupal:before {
  content: "\f1a9";
}
.fa-joomla:before {
  content: "\f1aa";
}
.fa-language:before {
  content: "\f1ab";
}
.fa-fax:before {
  content: "\f1ac";
}
.fa-building:before {
  content: "\f1ad";
}
.fa-child:before {
  content: "\f1ae";
}
.fa-paw:before {
  content: "\f1b0";
}
.fa-spoon:before {
  content: "\f1b1";
}
.fa-cube:before {
  content: "\f1b2";
}
.fa-cubes:before {
  content: "\f1b3";
}
.fa-behance:before {
  content: "\f1b4";
}
.fa-behance-square:before {
  content: "\f1b5";
}
.fa-steam:before {
  content: "\f1b6";
}
.fa-steam-square:before {
  content: "\f1b7";
}
.fa-recycle:before {
  content: "\f1b8";
}
.fa-automobile:before,
.fa-car:before {
  content: "\f1b9";
}
.fa-cab:before,
.fa-taxi:before {
  content: "\f1ba";
}
.fa-tree:before {
  content: "\f1bb";
}
.fa-spotify:before {
  content: "\f1bc";
}
.fa-deviantart:before {
  content: "\f1bd";
}
.fa-soundcloud:before {
  content: "\f1be";
}
.fa-database:before {
  content: "\f1c0";
}
.fa-file-pdf-o:before {
  content: "\f1c1";
}
.fa-file-word-o:before {
  content: "\f1c2";
}
.fa-file-excel-o:before {
  content: "\f1c3";
}
.fa-file-powerpoint-o:before {
  content: "\f1c4";
}
.fa-file-photo-o:before,
.fa-file-picture-o:before,
.fa-file-image-o:before {
  content: "\f1c5";
}
.fa-file-zip-o:before,
.fa-file-archive-o:before {
  content: "\f1c6";
}
.fa-file-sound-o:before,
.fa-file-audio-o:before {
  content: "\f1c7";
}
.fa-file-movie-o:before,
.fa-file-video-o:before {
  content: "\f1c8";
}
.fa-file-code-o:before {
  content: "\f1c9";
}
.fa-vine:before {
  content: "\f1ca";
}
.fa-codepen:before {
  content: "\f1cb";
}
.fa-jsfiddle:before {
  content: "\f1cc";
}
.fa-life-bouy:before,
.fa-life-buoy:before,
.fa-life-saver:before,
.fa-support:before,
.fa-life-ring:before {
  content: "\f1cd";
}
.fa-circle-o-notch:before {
  content: "\f1ce";
}
.fa-ra:before,
.fa-resistance:before,
.fa-rebel:before {
  content: "\f1d0";
}
.fa-ge:before,
.fa-empire:before {
  content: "\f1d1";
}
.fa-git-square:before {
  content: "\f1d2";
}
.fa-git:before {
  content: "\f1d3";
}
.fa-y-combinator-square:before,
.fa-yc-square:before,
.fa-hacker-news:before {
  content: "\f1d4";
}
.fa-tencent-weibo:before {
  content: "\f1d5";
}
.fa-qq:before {
  content: "\f1d6";
}
.fa-wechat:before,
.fa-weixin:before {
  content: "\f1d7";
}
.fa-send:before,
.fa-paper-plane:before {
  content: "\f1d8";
}
.fa-send-o:before,
.fa-paper-plane-o:before {
  content: "\f1d9";
}
.fa-history:before {
  content: "\f1da";
}
.fa-circle-thin:before {
  content: "\f1db";
}
.fa-header:before {
  content: "\f1dc";
}
.fa-paragraph:before {
  content: "\f1dd";
}
.fa-sliders:before {
  content: "\f1de";
}
.fa-share-alt:before {
  content: "\f1e0";
}
.fa-share-alt-square:before {
  content: "\f1e1";
}
.fa-bomb:before {
  content: "\f1e2";
}
.fa-soccer-ball-o:before,
.fa-futbol-o:before {
  content: "\f1e3";
}
.fa-tty:before {
  content: "\f1e4";
}
.fa-binoculars:before {
  content: "\f1e5";
}
.fa-plug:before {
  content: "\f1e6";
}
.fa-slideshare:before {
  content: "\f1e7";
}
.fa-twitch:before {
  content: "\f1e8";
}
.fa-yelp:before {
  content: "\f1e9";
}
.fa-newspaper-o:before {
  content: "\f1ea";
}
.fa-wifi:before {
  content: "\f1eb";
}
.fa-calculator:before {
  content: "\f1ec";
}
.fa-paypal:before {
  content: "\f1ed";
}
.fa-google-wallet:before {
  content: "\f1ee";
}
.fa-cc-visa:before {
  content: "\f1f0";
}
.fa-cc-mastercard:before {
  content: "\f1f1";
}
.fa-cc-discover:before {
  content: "\f1f2";
}
.fa-cc-amex:before {
  content: "\f1f3";
}
.fa-cc-paypal:before {
  content: "\f1f4";
}
.fa-cc-stripe:before {
  content: "\f1f5";
}
.fa-bell-slash:before {
  content: "\f1f6";
}
.fa-bell-slash-o:before {
  content: "\f1f7";
}
.fa-trash:before {
  content: "\f1f8";
}
.fa-copyright:before {
  content: "\f1f9";
}
.fa-at:before {
  content: "\f1fa";
}
.fa-eyedropper:before {
  content: "\f1fb";
}
.fa-paint-brush:before {
  content: "\f1fc";
}
.fa-birthday-cake:before {
  content: "\f1fd";
}
.fa-area-chart:before {
  content: "\f1fe";
}
.fa-pie-chart:before {
  content: "\f200";
}
.fa-line-chart:before {
  content: "\f201";
}
.fa-lastfm:before {
  content: "\f202";
}
.fa-lastfm-square:before {
  content: "\f203";
}
.fa-toggle-off:before {
  content: "\f204";
}
.fa-toggle-on:before {
  content: "\f205";
}
.fa-bicycle:before {
  content: "\f206";
}
.fa-bus:before {
  content: "\f207";
}
.fa-ioxhost:before {
  content: "\f208";
}
.fa-angellist:before {
  content: "\f209";
}
.fa-cc:before {
  content: "\f20a";
}
.fa-shekel:before,
.fa-sheqel:before,
.fa-ils:before {
  content: "\f20b";
}
.fa-meanpath:before {
  content: "\f20c";
}
.fa-buysellads:before {
  content: "\f20d";
}
.fa-connectdevelop:before {
  content: "\f20e";
}
.fa-dashcube:before {
  content: "\f210";
}
.fa-forumbee:before {
  content: "\f211";
}
.fa-leanpub:before {
  content: "\f212";
}
.fa-sellsy:before {
  content: "\f213";
}
.fa-shirtsinbulk:before {
  content: "\f214";
}
.fa-simplybuilt:before {
  content: "\f215";
}
.fa-skyatlas:before {
  content: "\f216";
}
.fa-cart-plus:before {
  content: "\f217";
}
.fa-cart-arrow-down:before {
  content: "\f218";
}
.fa-diamond:before {
  content: "\f219";
}
.fa-ship:before {
  content: "\f21a";
}
.fa-user-secret:before {
  content: "\f21b";
}
.fa-motorcycle:before {
  content: "\f21c";
}
.fa-street-view:before {
  content: "\f21d";
}
.fa-heartbeat:before {
  content: "\f21e";
}
.fa-venus:before {
  content: "\f221";
}
.fa-mars:before {
  content: "\f222";
}
.fa-mercury:before {
  content: "\f223";
}
.fa-intersex:before,
.fa-transgender:before {
  content: "\f224";
}
.fa-transgender-alt:before {
  content: "\f225";
}
.fa-venus-double:before {
  content: "\f226";
}
.fa-mars-double:before {
  content: "\f227";
}
.fa-venus-mars:before {
  content: "\f228";
}
.fa-mars-stroke:before {
  content: "\f229";
}
.fa-mars-stroke-v:before {
  content: "\f22a";
}
.fa-mars-stroke-h:before {
  content: "\f22b";
}
.fa-neuter:before {
  content: "\f22c";
}
.fa-genderless:before {
  content: "\f22d";
}
.fa-facebook-official:before {
  content: "\f230";
}
.fa-pinterest-p:before {
  content: "\f231";
}
.fa-whatsapp:before {
  content: "\f232";
}
.fa-server:before {
  content: "\f233";
}
.fa-user-plus:before {
  content: "\f234";
}
.fa-user-times:before {
  content: "\f235";
}
.fa-hotel:before,
.fa-bed:before {
  content: "\f236";
}
.fa-viacoin:before {
  content: "\f237";
}
.fa-train:before {
  content: "\f238";
}
.fa-subway:before {
  content: "\f239";
}
.fa-medium:before {
  content: "\f23a";
}
.fa-yc:before,
.fa-y-combinator:before {
  content: "\f23b";
}
.fa-optin-monster:before {
  content: "\f23c";
}
.fa-opencart:before {
  content: "\f23d";
}
.fa-expeditedssl:before {
  content: "\f23e";
}
.fa-battery-4:before,
.fa-battery:before,
.fa-battery-full:before {
  content: "\f240";
}
.fa-battery-3:before,
.fa-battery-three-quarters:before {
  content: "\f241";
}
.fa-battery-2:before,
.fa-battery-half:before {
  content: "\f242";
}
.fa-battery-1:before,
.fa-battery-quarter:before {
  content: "\f243";
}
.fa-battery-0:before,
.fa-battery-empty:before {
  content: "\f244";
}
.fa-mouse-pointer:before {
  content: "\f245";
}
.fa-i-cursor:before {
  content: "\f246";
}
.fa-object-group:before {
  content: "\f247";
}
.fa-object-ungroup:before {
  content: "\f248";
}
.fa-sticky-note:before {
  content: "\f249";
}
.fa-sticky-note-o:before {
  content: "\f24a";
}
.fa-cc-jcb:before {
  content: "\f24b";
}
.fa-cc-diners-club:before {
  content: "\f24c";
}
.fa-clone:before {
  content: "\f24d";
}
.fa-balance-scale:before {
  content: "\f24e";
}
.fa-hourglass-o:before {
  content: "\f250";
}
.fa-hourglass-1:before,
.fa-hourglass-start:before {
  content: "\f251";
}
.fa-hourglass-2:before,
.fa-hourglass-half:before {
  content: "\f252";
}
.fa-hourglass-3:before,
.fa-hourglass-end:before {
  content: "\f253";
}
.fa-hourglass:before {
  content: "\f254";
}
.fa-hand-grab-o:before,
.fa-hand-rock-o:before {
  content: "\f255";
}
.fa-hand-stop-o:before,
.fa-hand-paper-o:before {
  content: "\f256";
}
.fa-hand-scissors-o:before {
  content: "\f257";
}
.fa-hand-lizard-o:before {
  content: "\f258";
}
.fa-hand-spock-o:before {
  content: "\f259";
}
.fa-hand-pointer-o:before {
  content: "\f25a";
}
.fa-hand-peace-o:before {
  content: "\f25b";
}
.fa-trademark:before {
  content: "\f25c";
}
.fa-registered:before {
  content: "\f25d";
}
.fa-creative-commons:before {
  content: "\f25e";
}
.fa-gg:before {
  content: "\f260";
}
.fa-gg-circle:before {
  content: "\f261";
}
.fa-tripadvisor:before {
  content: "\f262";
}
.fa-odnoklassniki:before {
  content: "\f263";
}
.fa-odnoklassniki-square:before {
  content: "\f264";
}
.fa-get-pocket:before {
  content: "\f265";
}
.fa-wikipedia-w:before {
  content: "\f266";
}
.fa-safari:before {
  content: "\f267";
}
.fa-chrome:before {
  content: "\f268";
}
.fa-firefox:before {
  content: "\f269";
}
.fa-opera:before {
  content: "\f26a";
}
.fa-internet-explorer:before {
  content: "\f26b";
}
.fa-tv:before,
.fa-television:before {
  content: "\f26c";
}
.fa-contao:before {
  content: "\f26d";
}
.fa-500px:before {
  content: "\f26e";
}
.fa-amazon:before {
  content: "\f270";
}
.fa-calendar-plus-o:before {
  content: "\f271";
}
.fa-calendar-minus-o:before {
  content: "\f272";
}
.fa-calendar-times-o:before {
  content: "\f273";
}
.fa-calendar-check-o:before {
  content: "\f274";
}
.fa-industry:before {
  content: "\f275";
}
.fa-map-pin:before {
  content: "\f276";
}
.fa-map-signs:before {
  content: "\f277";
}
.fa-map-o:before {
  content: "\f278";
}
.fa-map:before {
  content: "\f279";
}
.fa-commenting:before {
  content: "\f27a";
}
.fa-commenting-o:before {
  content: "\f27b";
}
.fa-houzz:before {
  content: "\f27c";
}
.fa-vimeo:before {
  content: "\f27d";
}
.fa-black-tie:before {
  content: "\f27e";
}
.fa-fonticons:before {
  content: "\f280";
}
.fa-reddit-alien:before {
  content: "\f281";
}
.fa-edge:before {
  content: "\f282";
}
.fa-credit-card-alt:before {
  content: "\f283";
}
.fa-codiepie:before {
  content: "\f284";
}
.fa-modx:before {
  content: "\f285";
}
.fa-fort-awesome:before {
  content: "\f286";
}
.fa-usb:before {
  content: "\f287";
}
.fa-product-hunt:before {
  content: "\f288";
}
.fa-mixcloud:before {
  content: "\f289";
}
.fa-scribd:before {
  content: "\f28a";
}
.fa-pause-circle:before {
  content: "\f28b";
}
.fa-pause-circle-o:before {
  content: "\f28c";
}
.fa-stop-circle:before {
  content: "\f28d";
}
.fa-stop-circle-o:before {
  content: "\f28e";
}
.fa-shopping-bag:before {
  content: "\f290";
}
.fa-shopping-basket:before {
  content: "\f291";
}
.fa-hashtag:before {
  content: "\f292";
}
.fa-bluetooth:before {
  content: "\f293";
}
.fa-bluetooth-b:before {
  content: "\f294";
}
.fa-percent:before {
  content: "\f295";
}
.fa-gitlab:before {
  content: "\f296";
}
.fa-wpbeginner:before {
  content: "\f297";
}
.fa-wpforms:before {
  content: "\f298";
}
.fa-envira:before {
  content: "\f299";
}
.fa-universal-access:before {
  content: "\f29a";
}
.fa-wheelchair-alt:before {
  content: "\f29b";
}
.fa-question-circle-o:before {
  content: "\f29c";
}
.fa-blind:before {
  content: "\f29d";
}
.fa-audio-description:before {
  content: "\f29e";
}
.fa-volume-control-phone:before {
  content: "\f2a0";
}
.fa-braille:before {
  content: "\f2a1";
}
.fa-assistive-listening-systems:before {
  content: "\f2a2";
}
.fa-asl-interpreting:before,
.fa-american-sign-language-interpreting:before {
  content: "\f2a3";
}
.fa-deafness:before,
.fa-hard-of-hearing:before,
.fa-deaf:before {
  content: "\f2a4";
}
.fa-glide:before {
  content: "\f2a5";
}
.fa-glide-g:before {
  content: "\f2a6";
}
.fa-signing:before,
.fa-sign-language:before {
  content: "\f2a7";
}
.fa-low-vision:before {
  content: "\f2a8";
}
.fa-viadeo:before {
  content: "\f2a9";
}
.fa-viadeo-square:before {
  content: "\f2aa";
}
.fa-snapchat:before {
  content: "\f2ab";
}
.fa-snapchat-ghost:before {
  content: "\f2ac";
}
.fa-snapchat-square:before {
  content: "\f2ad";
}
.fa-pied-piper:before {
  content: "\f2ae";
}
.fa-first-order:before {
  content: "\f2b0";
}
.fa-yoast:before {
  content: "\f2b1";
}
.fa-themeisle:before {
  content: "\f2b2";
}
.fa-google-plus-circle:before,
.fa-google-plus-official:before {
  content: "\f2b3";
}
.fa-fa:before,
.fa-font-awesome:before {
  content: "\f2b4";
}
.fa-handshake-o:before {
  content: "\f2b5";
}
.fa-envelope-open:before {
  content: "\f2b6";
}
.fa-envelope-open-o:before {
  content: "\f2b7";
}
.fa-linode:before {
  content: "\f2b8";
}
.fa-address-book:before {
  content: "\f2b9";
}
.fa-address-book-o:before {
  content: "\f2ba";
}
.fa-vcard:before,
.fa-address-card:before {
  content: "\f2bb";
}
.fa-vcard-o:before,
.fa-address-card-o:before {
  content: "\f2bc";
}
.fa-user-circle:before {
  content: "\f2bd";
}
.fa-user-circle-o:before {
  content: "\f2be";
}
.fa-user-o:before {
  content: "\f2c0";
}
.fa-id-badge:before {
  content: "\f2c1";
}
.fa-drivers-license:before,
.fa-id-card:before {
  content: "\f2c2";
}
.fa-drivers-license-o:before,
.fa-id-card-o:before {
  content: "\f2c3";
}
.fa-quora:before {
  content: "\f2c4";
}
.fa-free-code-camp:before {
  content: "\f2c5";
}
.fa-telegram:before {
  content: "\f2c6";
}
.fa-thermometer-4:before,
.fa-thermometer:before,
.fa-thermometer-full:before {
  content: "\f2c7";
}
.fa-thermometer-3:before,
.fa-thermometer-three-quarters:before {
  content: "\f2c8";
}
.fa-thermometer-2:before,
.fa-thermometer-half:before {
  content: "\f2c9";
}
.fa-thermometer-1:before,
.fa-thermometer-quarter:before {
  content: "\f2ca";
}
.fa-thermometer-0:before,
.fa-thermometer-empty:before {
  content: "\f2cb";
}
.fa-shower:before {
  content: "\f2cc";
}
.fa-bathtub:before,
.fa-s15:before,
.fa-bath:before {
  content: "\f2cd";
}
.fa-podcast:before {
  content: "\f2ce";
}
.fa-window-maximize:before {
  content: "\f2d0";
}
.fa-window-minimize:before {
  content: "\f2d1";
}
.fa-window-restore:before {
  content: "\f2d2";
}
.fa-times-rectangle:before,
.fa-window-close:before {
  content: "\f2d3";
}
.fa-times-rectangle-o:before,
.fa-window-close-o:before {
  content: "\f2d4";
}
.fa-bandcamp:before {
  content: "\f2d5";
}
.fa-grav:before {
  content: "\f2d6";
}
.fa-etsy:before {
  content: "\f2d7";
}
.fa-imdb:before {
  content: "\f2d8";
}
.fa-ravelry:before {
  content: "\f2d9";
}
.fa-eercast:before {
  content: "\f2da";
}
.fa-microchip:before {
  content: "\f2db";
}
.fa-snowflake-o:before {
  content: "\f2dc";
}
.fa-superpowers:before {
  content: "\f2dd";
}
.fa-wpexplorer:before {
  content: "\f2de";
}
.fa-meetup:before {
  content: "\f2e0";
}
.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}
/*!
*
* IPython base
*
*/
.modal.fade .modal-dialog {
  -webkit-transform: translate(0, 0);
  -ms-transform: translate(0, 0);
  -o-transform: translate(0, 0);
  transform: translate(0, 0);
}
code {
  color: #000;
}
pre {
  font-size: inherit;
  line-height: inherit;
}
label {
  font-weight: normal;
}
/* Make the page background atleast 100% the height of the view port */
/* Make the page itself atleast 70% the height of the view port */
.border-box-sizing {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
.corner-all {
  border-radius: 2px;
}
.no-padding {
  padding: 0px;
}
/* Flexible box model classes */
/* Taken from Alex Russell http://infrequently.org/2009/08/css-3-progress/ */
/* This file is a compatability layer.  It allows the usage of flexible box 
model layouts accross multiple browsers, including older browsers.  The newest,
universal implementation of the flexible box model is used when available (see
`Modern browsers` comments below).  Browsers that are known to implement this 
new spec completely include:

    Firefox 28.0+
    Chrome 29.0+
    Internet Explorer 11+ 
    Opera 17.0+

Browsers not listed, including Safari, are supported via the styling under the
`Old browsers` comments below.
*/
.hbox {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
.hbox > * {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
.vbox {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
.vbox > * {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
.hbox.reverse,
.vbox.reverse,
.reverse {
  /* Old browsers */
  -webkit-box-direction: reverse;
  -moz-box-direction: reverse;
  box-direction: reverse;
  /* Modern browsers */
  flex-direction: row-reverse;
}
.hbox.box-flex0,
.vbox.box-flex0,
.box-flex0 {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
  width: auto;
}
.hbox.box-flex1,
.vbox.box-flex1,
.box-flex1 {
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
.hbox.box-flex,
.vbox.box-flex,
.box-flex {
  /* Old browsers */
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
.hbox.box-flex2,
.vbox.box-flex2,
.box-flex2 {
  /* Old browsers */
  -webkit-box-flex: 2;
  -moz-box-flex: 2;
  box-flex: 2;
  /* Modern browsers */
  flex: 2;
}
.box-group1 {
  /*  Deprecated */
  -webkit-box-flex-group: 1;
  -moz-box-flex-group: 1;
  box-flex-group: 1;
}
.box-group2 {
  /* Deprecated */
  -webkit-box-flex-group: 2;
  -moz-box-flex-group: 2;
  box-flex-group: 2;
}
.hbox.start,
.vbox.start,
.start {
  /* Old browsers */
  -webkit-box-pack: start;
  -moz-box-pack: start;
  box-pack: start;
  /* Modern browsers */
  justify-content: flex-start;
}
.hbox.end,
.vbox.end,
.end {
  /* Old browsers */
  -webkit-box-pack: end;
  -moz-box-pack: end;
  box-pack: end;
  /* Modern browsers */
  justify-content: flex-end;
}
.hbox.center,
.vbox.center,
.center {
  /* Old browsers */
  -webkit-box-pack: center;
  -moz-box-pack: center;
  box-pack: center;
  /* Modern browsers */
  justify-content: center;
}
.hbox.baseline,
.vbox.baseline,
.baseline {
  /* Old browsers */
  -webkit-box-pack: baseline;
  -moz-box-pack: baseline;
  box-pack: baseline;
  /* Modern browsers */
  justify-content: baseline;
}
.hbox.stretch,
.vbox.stretch,
.stretch {
  /* Old browsers */
  -webkit-box-pack: stretch;
  -moz-box-pack: stretch;
  box-pack: stretch;
  /* Modern browsers */
  justify-content: stretch;
}
.hbox.align-start,
.vbox.align-start,
.align-start {
  /* Old browsers */
  -webkit-box-align: start;
  -moz-box-align: start;
  box-align: start;
  /* Modern browsers */
  align-items: flex-start;
}
.hbox.align-end,
.vbox.align-end,
.align-end {
  /* Old browsers */
  -webkit-box-align: end;
  -moz-box-align: end;
  box-align: end;
  /* Modern browsers */
  align-items: flex-end;
}
.hbox.align-center,
.vbox.align-center,
.align-center {
  /* Old browsers */
  -webkit-box-align: center;
  -moz-box-align: center;
  box-align: center;
  /* Modern browsers */
  align-items: center;
}
.hbox.align-baseline,
.vbox.align-baseline,
.align-baseline {
  /* Old browsers */
  -webkit-box-align: baseline;
  -moz-box-align: baseline;
  box-align: baseline;
  /* Modern browsers */
  align-items: baseline;
}
.hbox.align-stretch,
.vbox.align-stretch,
.align-stretch {
  /* Old browsers */
  -webkit-box-align: stretch;
  -moz-box-align: stretch;
  box-align: stretch;
  /* Modern browsers */
  align-items: stretch;
}
div.error {
  margin: 2em;
  text-align: center;
}
div.error > h1 {
  font-size: 500%;
  line-height: normal;
}
div.error > p {
  font-size: 200%;
  line-height: normal;
}
div.traceback-wrapper {
  text-align: left;
  max-width: 800px;
  margin: auto;
}
div.traceback-wrapper pre.traceback {
  max-height: 600px;
  overflow: auto;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
body {
  background-color: #fff;
  /* This makes sure that the body covers the entire window and needs to
       be in a different element than the display: box in wrapper below */
  position: absolute;
  left: 0px;
  right: 0px;
  top: 0px;
  bottom: 0px;
  overflow: visible;
}
body > #header {
  /* Initially hidden to prevent FLOUC */
  display: none;
  background-color: #fff;
  /* Display over codemirror */
  position: relative;
  z-index: 100;
}
body > #header #header-container {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  padding: 5px;
  padding-bottom: 5px;
  padding-top: 5px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
body > #header .header-bar {
  width: 100%;
  height: 1px;
  background: #e7e7e7;
  margin-bottom: -1px;
}
@media print {
  body > #header {
    display: none !important;
  }
}
#header-spacer {
  width: 100%;
  visibility: hidden;
}
@media print {
  #header-spacer {
    display: none;
  }
}
#ipython_notebook {
  padding-left: 0px;
  padding-top: 1px;
  padding-bottom: 1px;
}
[dir="rtl"] #ipython_notebook {
  margin-right: 10px;
  margin-left: 0;
}
[dir="rtl"] #ipython_notebook.pull-left {
  float: right !important;
  float: right;
}
.flex-spacer {
  flex: 1;
}
#noscript {
  width: auto;
  padding-top: 16px;
  padding-bottom: 16px;
  text-align: center;
  font-size: 22px;
  color: red;
  font-weight: bold;
}
#ipython_notebook img {
  height: 28px;
}
#site {
  width: 100%;
  display: none;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  overflow: auto;
}
@media print {
  #site {
    height: auto !important;
  }
}
/* Smaller buttons */
.ui-button .ui-button-text {
  padding: 0.2em 0.8em;
  font-size: 77%;
}
input.ui-button {
  padding: 0.3em 0.9em;
}
span#kernel_logo_widget {
  margin: 0 10px;
}
span#login_widget {
  float: right;
}
[dir="rtl"] span#login_widget {
  float: left;
}
span#login_widget > .button,
#logout {
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
span#login_widget > .button:focus,
#logout:focus,
span#login_widget > .button.focus,
#logout.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
span#login_widget > .button:hover,
#logout:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
span#login_widget > .button:active,
#logout:active,
span#login_widget > .button.active,
#logout.active,
.open > .dropdown-togglespan#login_widget > .button,
.open > .dropdown-toggle#logout {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
span#login_widget > .button:active:hover,
#logout:active:hover,
span#login_widget > .button.active:hover,
#logout.active:hover,
.open > .dropdown-togglespan#login_widget > .button:hover,
.open > .dropdown-toggle#logout:hover,
span#login_widget > .button:active:focus,
#logout:active:focus,
span#login_widget > .button.active:focus,
#logout.active:focus,
.open > .dropdown-togglespan#login_widget > .button:focus,
.open > .dropdown-toggle#logout:focus,
span#login_widget > .button:active.focus,
#logout:active.focus,
span#login_widget > .button.active.focus,
#logout.active.focus,
.open > .dropdown-togglespan#login_widget > .button.focus,
.open > .dropdown-toggle#logout.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
span#login_widget > .button:active,
#logout:active,
span#login_widget > .button.active,
#logout.active,
.open > .dropdown-togglespan#login_widget > .button,
.open > .dropdown-toggle#logout {
  background-image: none;
}
span#login_widget > .button.disabled:hover,
#logout.disabled:hover,
span#login_widget > .button[disabled]:hover,
#logout[disabled]:hover,
fieldset[disabled] span#login_widget > .button:hover,
fieldset[disabled] #logout:hover,
span#login_widget > .button.disabled:focus,
#logout.disabled:focus,
span#login_widget > .button[disabled]:focus,
#logout[disabled]:focus,
fieldset[disabled] span#login_widget > .button:focus,
fieldset[disabled] #logout:focus,
span#login_widget > .button.disabled.focus,
#logout.disabled.focus,
span#login_widget > .button[disabled].focus,
#logout[disabled].focus,
fieldset[disabled] span#login_widget > .button.focus,
fieldset[disabled] #logout.focus {
  background-color: #fff;
  border-color: #ccc;
}
span#login_widget > .button .badge,
#logout .badge {
  color: #fff;
  background-color: #333;
}
.nav-header {
  text-transform: none;
}
#header > span {
  margin-top: 10px;
}
.modal_stretch .modal-dialog {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  min-height: 80vh;
}
.modal_stretch .modal-dialog .modal-body {
  max-height: calc(100vh - 200px);
  overflow: auto;
  flex: 1;
}
.modal-header {
  cursor: move;
}
@media (min-width: 768px) {
  .modal .modal-dialog {
    width: 700px;
  }
}
@media (min-width: 768px) {
  select.form-control {
    margin-left: 12px;
    margin-right: 12px;
  }
}
/*!
*
* IPython auth
*
*/
.center-nav {
  display: inline-block;
  margin-bottom: -4px;
}
[dir="rtl"] .center-nav form.pull-left {
  float: right !important;
  float: right;
}
[dir="rtl"] .center-nav .navbar-text {
  float: right;
}
[dir="rtl"] .navbar-inner {
  text-align: right;
}
[dir="rtl"] div.text-left {
  text-align: right;
}
/*!
*
* IPython tree view
*
*/
/* We need an invisible input field on top of the sentense*/
/* "Drag file onto the list ..." */
.alternate_upload {
  background-color: none;
  display: inline;
}
.alternate_upload.form {
  padding: 0;
  margin: 0;
}
.alternate_upload input.fileinput {
  position: absolute;
  display: block;
  width: 100%;
  height: 100%;
  overflow: hidden;
  cursor: pointer;
  opacity: 0;
  z-index: 2;
}
.alternate_upload .btn-xs > input.fileinput {
  margin: -1px -5px;
}
.alternate_upload .btn-upload {
  position: relative;
  height: 22px;
}
::-webkit-file-upload-button {
  cursor: pointer;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
ul#tabs {
  margin-bottom: 4px;
}
ul#tabs a {
  padding-top: 6px;
  padding-bottom: 4px;
}
[dir="rtl"] ul#tabs.nav-tabs > li {
  float: right;
}
[dir="rtl"] ul#tabs.nav.nav-tabs {
  padding-right: 0;
}
ul.breadcrumb a:focus,
ul.breadcrumb a:hover {
  text-decoration: none;
}
ul.breadcrumb i.icon-home {
  font-size: 16px;
  margin-right: 4px;
}
ul.breadcrumb span {
  color: #5e5e5e;
}
.list_toolbar {
  padding: 4px 0 4px 0;
  vertical-align: middle;
}
.list_toolbar .tree-buttons {
  padding-top: 1px;
}
[dir="rtl"] .list_toolbar .tree-buttons .pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .list_toolbar .col-sm-4,
[dir="rtl"] .list_toolbar .col-sm-8 {
  float: right;
}
.dynamic-buttons {
  padding-top: 3px;
  display: inline-block;
}
.list_toolbar [class*="span"] {
  min-height: 24px;
}
.list_header {
  font-weight: bold;
  background-color: #EEE;
}
.list_placeholder {
  font-weight: bold;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
}
.list_container {
  margin-top: 4px;
  margin-bottom: 20px;
  border: 1px solid #ddd;
  border-radius: 2px;
}
.list_container > div {
  border-bottom: 1px solid #ddd;
}
.list_container > div:hover .list-item {
  background-color: red;
}
.list_container > div:last-child {
  border: none;
}
.list_item:hover .list_item {
  background-color: #ddd;
}
.list_item a {
  text-decoration: none;
}
.list_item:hover {
  background-color: #fafafa;
}
.list_header > div,
.list_item > div {
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
  line-height: 22px;
}
.list_header > div input,
.list_item > div input {
  margin-right: 7px;
  margin-left: 14px;
  vertical-align: text-bottom;
  line-height: 22px;
  position: relative;
  top: -1px;
}
.list_header > div .item_link,
.list_item > div .item_link {
  margin-left: -1px;
  vertical-align: baseline;
  line-height: 22px;
}
[dir="rtl"] .list_item > div input {
  margin-right: 0;
}
.new-file input[type=checkbox] {
  visibility: hidden;
}
.item_name {
  line-height: 22px;
  height: 24px;
}
.item_icon {
  font-size: 14px;
  color: #5e5e5e;
  margin-right: 7px;
  margin-left: 7px;
  line-height: 22px;
  vertical-align: baseline;
}
.item_modified {
  margin-right: 7px;
  margin-left: 7px;
}
[dir="rtl"] .item_modified.pull-right {
  float: left !important;
  float: left;
}
.item_buttons {
  line-height: 1em;
  margin-left: -5px;
}
.item_buttons .btn,
.item_buttons .btn-group,
.item_buttons .input-group {
  float: left;
}
.item_buttons > .btn,
.item_buttons > .btn-group,
.item_buttons > .input-group {
  margin-left: 5px;
}
.item_buttons .btn {
  min-width: 13ex;
}
.item_buttons .running-indicator {
  padding-top: 4px;
  color: #5cb85c;
}
.item_buttons .kernel-name {
  padding-top: 4px;
  color: #5bc0de;
  margin-right: 7px;
  float: left;
}
[dir="rtl"] .item_buttons.pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .item_buttons .kernel-name {
  margin-left: 7px;
  float: right;
}
.toolbar_info {
  height: 24px;
  line-height: 24px;
}
.list_item input:not([type=checkbox]) {
  padding-top: 3px;
  padding-bottom: 3px;
  height: 22px;
  line-height: 14px;
  margin: 0px;
}
.highlight_text {
  color: blue;
}
#project_name {
  display: inline-block;
  padding-left: 7px;
  margin-left: -2px;
}
#project_name > .breadcrumb {
  padding: 0px;
  margin-bottom: 0px;
  background-color: transparent;
  font-weight: bold;
}
.sort_button {
  display: inline-block;
  padding-left: 7px;
}
[dir="rtl"] .sort_button.pull-right {
  float: left !important;
  float: left;
}
#tree-selector {
  padding-right: 0px;
}
#button-select-all {
  min-width: 50px;
}
[dir="rtl"] #button-select-all.btn {
  float: right ;
}
#select-all {
  margin-left: 7px;
  margin-right: 2px;
  margin-top: 2px;
  height: 16px;
}
[dir="rtl"] #select-all.pull-left {
  float: right !important;
  float: right;
}
.menu_icon {
  margin-right: 2px;
}
.tab-content .row {
  margin-left: 0px;
  margin-right: 0px;
}
.folder_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f114";
}
.folder_icon:before.fa-pull-left {
  margin-right: .3em;
}
.folder_icon:before.fa-pull-right {
  margin-left: .3em;
}
.folder_icon:before.pull-left {
  margin-right: .3em;
}
.folder_icon:before.pull-right {
  margin-left: .3em;
}
.notebook_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f02d";
  position: relative;
  top: -1px;
}
.notebook_icon:before.fa-pull-left {
  margin-right: .3em;
}
.notebook_icon:before.fa-pull-right {
  margin-left: .3em;
}
.notebook_icon:before.pull-left {
  margin-right: .3em;
}
.notebook_icon:before.pull-right {
  margin-left: .3em;
}
.running_notebook_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f02d";
  position: relative;
  top: -1px;
  color: #5cb85c;
}
.running_notebook_icon:before.fa-pull-left {
  margin-right: .3em;
}
.running_notebook_icon:before.fa-pull-right {
  margin-left: .3em;
}
.running_notebook_icon:before.pull-left {
  margin-right: .3em;
}
.running_notebook_icon:before.pull-right {
  margin-left: .3em;
}
.file_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f016";
  position: relative;
  top: -2px;
}
.file_icon:before.fa-pull-left {
  margin-right: .3em;
}
.file_icon:before.fa-pull-right {
  margin-left: .3em;
}
.file_icon:before.pull-left {
  margin-right: .3em;
}
.file_icon:before.pull-right {
  margin-left: .3em;
}
#notebook_toolbar .pull-right {
  padding-top: 0px;
  margin-right: -1px;
}
ul#new-menu {
  left: auto;
  right: 0;
}
#new-menu .dropdown-header {
  font-size: 10px;
  border-bottom: 1px solid #e5e5e5;
  padding: 0 0 3px;
  margin: -3px 20px 0;
}
.kernel-menu-icon {
  padding-right: 12px;
  width: 24px;
  content: "\f096";
}
.kernel-menu-icon:before {
  content: "\f096";
}
.kernel-menu-icon-current:before {
  content: "\f00c";
}
#tab_content {
  padding-top: 20px;
}
#running .panel-group .panel {
  margin-top: 3px;
  margin-bottom: 1em;
}
#running .panel-group .panel .panel-heading {
  background-color: #EEE;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
  line-height: 22px;
}
#running .panel-group .panel .panel-heading a:focus,
#running .panel-group .panel .panel-heading a:hover {
  text-decoration: none;
}
#running .panel-group .panel .panel-body {
  padding: 0px;
}
#running .panel-group .panel .panel-body .list_container {
  margin-top: 0px;
  margin-bottom: 0px;
  border: 0px;
  border-radius: 0px;
}
#running .panel-group .panel .panel-body .list_container .list_item {
  border-bottom: 1px solid #ddd;
}
#running .panel-group .panel .panel-body .list_container .list_item:last-child {
  border-bottom: 0px;
}
.delete-button {
  display: none;
}
.duplicate-button {
  display: none;
}
.rename-button {
  display: none;
}
.move-button {
  display: none;
}
.download-button {
  display: none;
}
.shutdown-button {
  display: none;
}
.dynamic-instructions {
  display: inline-block;
  padding-top: 4px;
}
/*!
*
* IPython text editor webapp
*
*/
.selected-keymap i.fa {
  padding: 0px 5px;
}
.selected-keymap i.fa:before {
  content: "\f00c";
}
#mode-menu {
  overflow: auto;
  max-height: 20em;
}
.edit_app #header {
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
.edit_app #menubar .navbar {
  /* Use a negative 1 bottom margin, so the border overlaps the border of the
    header */
  margin-bottom: -1px;
}
.dirty-indicator {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator.pull-left {
  margin-right: .3em;
}
.dirty-indicator.pull-right {
  margin-left: .3em;
}
.dirty-indicator-dirty {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator-dirty.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator-dirty.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator-dirty.pull-left {
  margin-right: .3em;
}
.dirty-indicator-dirty.pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator-clean.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean.pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean.pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f00c";
}
.dirty-indicator-clean:before.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean:before.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean:before.pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean:before.pull-right {
  margin-left: .3em;
}
#filename {
  font-size: 16pt;
  display: table;
  padding: 0px 5px;
}
#current-mode {
  padding-left: 5px;
  padding-right: 5px;
}
#texteditor-backdrop {
  padding-top: 20px;
  padding-bottom: 20px;
}
@media not print {
  #texteditor-backdrop {
    background-color: #EEE;
  }
}
@media print {
  #texteditor-backdrop #texteditor-container .CodeMirror-gutter,
  #texteditor-backdrop #texteditor-container .CodeMirror-gutters {
    background-color: #fff;
  }
}
@media not print {
  #texteditor-backdrop #texteditor-container .CodeMirror-gutter,
  #texteditor-backdrop #texteditor-container .CodeMirror-gutters {
    background-color: #fff;
  }
}
@media not print {
  #texteditor-backdrop #texteditor-container {
    padding: 0px;
    background-color: #fff;
    -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
    box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  }
}
.CodeMirror-dialog {
  background-color: #fff;
}
/*!
*
* IPython notebook
*
*/
/* CSS font colors for translated ANSI escape sequences */
/* The color values are a mix of
   http://www.xcolors.net/dl/baskerville-ivorylight and
   http://www.xcolors.net/dl/euphrasia */
.ansi-black-fg {
  color: #3E424D;
}
.ansi-black-bg {
  background-color: #3E424D;
}
.ansi-black-intense-fg {
  color: #282C36;
}
.ansi-black-intense-bg {
  background-color: #282C36;
}
.ansi-red-fg {
  color: #E75C58;
}
.ansi-red-bg {
  background-color: #E75C58;
}
.ansi-red-intense-fg {
  color: #B22B31;
}
.ansi-red-intense-bg {
  background-color: #B22B31;
}
.ansi-green-fg {
  color: #00A250;
}
.ansi-green-bg {
  background-color: #00A250;
}
.ansi-green-intense-fg {
  color: #007427;
}
.ansi-green-intense-bg {
  background-color: #007427;
}
.ansi-yellow-fg {
  color: #DDB62B;
}
.ansi-yellow-bg {
  background-color: #DDB62B;
}
.ansi-yellow-intense-fg {
  color: #B27D12;
}
.ansi-yellow-intense-bg {
  background-color: #B27D12;
}
.ansi-blue-fg {
  color: #208FFB;
}
.ansi-blue-bg {
  background-color: #208FFB;
}
.ansi-blue-intense-fg {
  color: #0065CA;
}
.ansi-blue-intense-bg {
  background-color: #0065CA;
}
.ansi-magenta-fg {
  color: #D160C4;
}
.ansi-magenta-bg {
  background-color: #D160C4;
}
.ansi-magenta-intense-fg {
  color: #A03196;
}
.ansi-magenta-intense-bg {
  background-color: #A03196;
}
.ansi-cyan-fg {
  color: #60C6C8;
}
.ansi-cyan-bg {
  background-color: #60C6C8;
}
.ansi-cyan-intense-fg {
  color: #258F8F;
}
.ansi-cyan-intense-bg {
  background-color: #258F8F;
}
.ansi-white-fg {
  color: #C5C1B4;
}
.ansi-white-bg {
  background-color: #C5C1B4;
}
.ansi-white-intense-fg {
  color: #A1A6B2;
}
.ansi-white-intense-bg {
  background-color: #A1A6B2;
}
.ansi-default-inverse-fg {
  color: #FFFFFF;
}
.ansi-default-inverse-bg {
  background-color: #000000;
}
.ansi-bold {
  font-weight: bold;
}
.ansi-underline {
  text-decoration: underline;
}
/* The following styles are deprecated an will be removed in a future version */
.ansibold {
  font-weight: bold;
}
.ansi-inverse {
  outline: 0.5px dotted;
}
/* use dark versions for foreground, to improve visibility */
.ansiblack {
  color: black;
}
.ansired {
  color: darkred;
}
.ansigreen {
  color: darkgreen;
}
.ansiyellow {
  color: #c4a000;
}
.ansiblue {
  color: darkblue;
}
.ansipurple {
  color: darkviolet;
}
.ansicyan {
  color: steelblue;
}
.ansigray {
  color: gray;
}
/* and light for background, for the same reason */
.ansibgblack {
  background-color: black;
}
.ansibgred {
  background-color: red;
}
.ansibggreen {
  background-color: green;
}
.ansibgyellow {
  background-color: yellow;
}
.ansibgblue {
  background-color: blue;
}
.ansibgpurple {
  background-color: magenta;
}
.ansibgcyan {
  background-color: cyan;
}
.ansibggray {
  background-color: gray;
}
div.cell {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  border-radius: 2px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  border-width: 1px;
  border-style: solid;
  border-color: transparent;
  width: 100%;
  padding: 5px;
  /* This acts as a spacer between cells, that is outside the border */
  margin: 0px;
  outline: none;
  position: relative;
  overflow: visible;
}
div.cell:before {
  position: absolute;
  display: block;
  top: -1px;
  left: -1px;
  width: 5px;
  height: calc(100% +  2px);
  content: '';
  background: transparent;
}
div.cell.jupyter-soft-selected {
  border-left-color: #E3F2FD;
  border-left-width: 1px;
  padding-left: 5px;
  border-right-color: #E3F2FD;
  border-right-width: 1px;
  background: #E3F2FD;
}
@media print {
  div.cell.jupyter-soft-selected {
    border-color: transparent;
  }
}
div.cell.selected,
div.cell.selected.jupyter-soft-selected {
  border-color: #ababab;
}
div.cell.selected:before,
div.cell.selected.jupyter-soft-selected:before {
  position: absolute;
  display: block;
  top: -1px;
  left: -1px;
  width: 5px;
  height: calc(100% +  2px);
  content: '';
  background: #42A5F5;
}
@media print {
  div.cell.selected,
  div.cell.selected.jupyter-soft-selected {
    border-color: transparent;
  }
}
.edit_mode div.cell.selected {
  border-color: #66BB6A;
}
.edit_mode div.cell.selected:before {
  position: absolute;
  display: block;
  top: -1px;
  left: -1px;
  width: 5px;
  height: calc(100% +  2px);
  content: '';
  background: #66BB6A;
}
@media print {
  .edit_mode div.cell.selected {
    border-color: transparent;
  }
}
.prompt {
  /* This needs to be wide enough for 3 digit prompt numbers: In[100]: */
  min-width: 14ex;
  /* This padding is tuned to match the padding on the CodeMirror editor. */
  padding: 0.4em;
  margin: 0px;
  font-family: monospace;
  text-align: right;
  /* This has to match that of the the CodeMirror class line-height below */
  line-height: 1.21429em;
  /* Don't highlight prompt number selection */
  -webkit-touch-callout: none;
  -webkit-user-select: none;
  -khtml-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  /* Use default cursor */
  cursor: default;
}
@media (max-width: 540px) {
  .prompt {
    text-align: left;
  }
}
div.inner_cell {
  min-width: 0;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
/* input_area and input_prompt must match in top border and margin for alignment */
div.input_area {
  border: 1px solid #cfcfcf;
  border-radius: 2px;
  background: #f7f7f7;
  line-height: 1.21429em;
}
/* This is needed so that empty prompt areas can collapse to zero height when there
   is no content in the output_subarea and the prompt. The main purpose of this is
   to make sure that empty JavaScript output_subareas have no height. */
div.prompt:empty {
  padding-top: 0;
  padding-bottom: 0;
}
div.unrecognized_cell {
  padding: 5px 5px 5px 0px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
div.unrecognized_cell .inner_cell {
  border-radius: 2px;
  padding: 5px;
  font-weight: bold;
  color: red;
  border: 1px solid #cfcfcf;
  background: #eaeaea;
}
div.unrecognized_cell .inner_cell a {
  color: inherit;
  text-decoration: none;
}
div.unrecognized_cell .inner_cell a:hover {
  color: inherit;
  text-decoration: none;
}
@media (max-width: 540px) {
  div.unrecognized_cell > div.prompt {
    display: none;
  }
}
div.code_cell {
  /* avoid page breaking on code cells when printing */
}
@media print {
  div.code_cell {
    page-break-inside: avoid;
  }
}
/* any special styling for code cells that are currently running goes here */
div.input {
  page-break-inside: avoid;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.input {
    /* Old browsers */
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-box-align: stretch;
    display: -moz-box;
    -moz-box-orient: vertical;
    -moz-box-align: stretch;
    display: box;
    box-orient: vertical;
    box-align: stretch;
    /* Modern browsers */
    display: flex;
    flex-direction: column;
    align-items: stretch;
  }
}
/* input_area and input_prompt must match in top border and margin for alignment */
div.input_prompt {
  color: #303F9F;
  border-top: 1px solid transparent;
}
div.input_area > div.highlight {
  margin: 0.4em;
  border: none;
  padding: 0px;
  background-color: transparent;
}
div.input_area > div.highlight > pre {
  margin: 0px;
  border: none;
  padding: 0px;
  background-color: transparent;
}
/* The following gets added to the <head> if it is detected that the user has a
 * monospace font with inconsistent normal/bold/italic height.  See
 * notebookmain.js.  Such fonts will have keywords vertically offset with
 * respect to the rest of the text.  The user should select a better font.
 * See: https://github.com/ipython/ipython/issues/1503
 *
 * .CodeMirror span {
 *      vertical-align: bottom;
 * }
 */
.CodeMirror {
  line-height: 1.21429em;
  /* Changed from 1em to our global default */
  font-size: 14px;
  height: auto;
  /* Changed to auto to autogrow */
  background: none;
  /* Changed from white to allow our bg to show through */
}
.CodeMirror-scroll {
  /*  The CodeMirror docs are a bit fuzzy on if overflow-y should be hidden or visible.*/
  /*  We have found that if it is visible, vertical scrollbars appear with font size changes.*/
  overflow-y: hidden;
  overflow-x: auto;
}
.CodeMirror-lines {
  /* In CM2, this used to be 0.4em, but in CM3 it went to 4px. We need the em value because */
  /* we have set a different line-height and want this to scale with that. */
  /* Note that this should set vertical padding only, since CodeMirror assumes
       that horizontal padding will be set on CodeMirror pre */
  padding: 0.4em 0;
}
.CodeMirror-linenumber {
  padding: 0 8px 0 4px;
}
.CodeMirror-gutters {
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}
.CodeMirror pre {
  /* In CM3 this went to 4px from 0 in CM2. This sets horizontal padding only,
    use .CodeMirror-lines for vertical */
  padding: 0 0.4em;
  border: 0;
  border-radius: 0;
}
.CodeMirror-cursor {
  border-left: 1.4px solid black;
}
@media screen and (min-width: 2138px) and (max-width: 4319px) {
  .CodeMirror-cursor {
    border-left: 2px solid black;
  }
}
@media screen and (min-width: 4320px) {
  .CodeMirror-cursor {
    border-left: 4px solid black;
  }
}
/*

Original style from softwaremaniacs.org (c) Ivan Sagalaev <Maniac@SoftwareManiacs.Org>
Adapted from GitHub theme

*/
.highlight-base {
  color: #000;
}
.highlight-variable {
  color: #000;
}
.highlight-variable-2 {
  color: #1a1a1a;
}
.highlight-variable-3 {
  color: #333333;
}
.highlight-string {
  color: #BA2121;
}
.highlight-comment {
  color: #408080;
  font-style: italic;
}
.highlight-number {
  color: #080;
}
.highlight-atom {
  color: #88F;
}
.highlight-keyword {
  color: #008000;
  font-weight: bold;
}
.highlight-builtin {
  color: #008000;
}
.highlight-error {
  color: #f00;
}
.highlight-operator {
  color: #AA22FF;
  font-weight: bold;
}
.highlight-meta {
  color: #AA22FF;
}
/* previously not defined, copying from default codemirror */
.highlight-def {
  color: #00f;
}
.highlight-string-2 {
  color: #f50;
}
.highlight-qualifier {
  color: #555;
}
.highlight-bracket {
  color: #997;
}
.highlight-tag {
  color: #170;
}
.highlight-attribute {
  color: #00c;
}
.highlight-header {
  color: blue;
}
.highlight-quote {
  color: #090;
}
.highlight-link {
  color: #00c;
}
/* apply the same style to codemirror */
.cm-s-ipython span.cm-keyword {
  color: #008000;
  font-weight: bold;
}
.cm-s-ipython span.cm-atom {
  color: #88F;
}
.cm-s-ipython span.cm-number {
  color: #080;
}
.cm-s-ipython span.cm-def {
  color: #00f;
}
.cm-s-ipython span.cm-variable {
  color: #000;
}
.cm-s-ipython span.cm-operator {
  color: #AA22FF;
  font-weight: bold;
}
.cm-s-ipython span.cm-variable-2 {
  color: #1a1a1a;
}
.cm-s-ipython span.cm-variable-3 {
  color: #333333;
}
.cm-s-ipython span.cm-comment {
  color: #408080;
  font-style: italic;
}
.cm-s-ipython span.cm-string {
  color: #BA2121;
}
.cm-s-ipython span.cm-string-2 {
  color: #f50;
}
.cm-s-ipython span.cm-meta {
  color: #AA22FF;
}
.cm-s-ipython span.cm-qualifier {
  color: #555;
}
.cm-s-ipython span.cm-builtin {
  color: #008000;
}
.cm-s-ipython span.cm-bracket {
  color: #997;
}
.cm-s-ipython span.cm-tag {
  color: #170;
}
.cm-s-ipython span.cm-attribute {
  color: #00c;
}
.cm-s-ipython span.cm-header {
  color: blue;
}
.cm-s-ipython span.cm-quote {
  color: #090;
}
.cm-s-ipython span.cm-link {
  color: #00c;
}
.cm-s-ipython span.cm-error {
  color: #f00;
}
.cm-s-ipython span.cm-tab {
  background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAMCAYAAAAkuj5RAAAAAXNSR0IArs4c6QAAAGFJREFUSMft1LsRQFAQheHPowAKoACx3IgEKtaEHujDjORSgWTH/ZOdnZOcM/sgk/kFFWY0qV8foQwS4MKBCS3qR6ixBJvElOobYAtivseIE120FaowJPN75GMu8j/LfMwNjh4HUpwg4LUAAAAASUVORK5CYII=);
  background-position: right;
  background-repeat: no-repeat;
}
div.output_wrapper {
  /* this position must be relative to enable descendents to be absolute within it */
  position: relative;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  z-index: 1;
}
/* class for the output area when it should be height-limited */
div.output_scroll {
  /* ideally, this would be max-height, but FF barfs all over that */
  height: 24em;
  /* FF needs this *and the wrapper* to specify full width, or it will shrinkwrap */
  width: 100%;
  overflow: auto;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.8);
  box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.8);
  display: block;
}
/* output div while it is collapsed */
div.output_collapsed {
  margin: 0px;
  padding: 0px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
div.out_prompt_overlay {
  height: 100%;
  padding: 0px 0.4em;
  position: absolute;
  border-radius: 2px;
}
div.out_prompt_overlay:hover {
  /* use inner shadow to get border that is computed the same on WebKit/FF */
  -webkit-box-shadow: inset 0 0 1px #000;
  box-shadow: inset 0 0 1px #000;
  background: rgba(240, 240, 240, 0.5);
}
div.output_prompt {
  color: #D84315;
}
/* This class is the outer container of all output sections. */
div.output_area {
  padding: 0px;
  page-break-inside: avoid;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
div.output_area .MathJax_Display {
  text-align: left !important;
}
div.output_area .rendered_html table {
  margin-left: 0;
  margin-right: 0;
}
div.output_area .rendered_html img {
  margin-left: 0;
  margin-right: 0;
}
div.output_area img,
div.output_area svg {
  max-width: 100%;
  height: auto;
}
div.output_area img.unconfined,
div.output_area svg.unconfined {
  max-width: none;
}
div.output_area .mglyph > img {
  max-width: none;
}
/* This is needed to protect the pre formating from global settings such
   as that of bootstrap */
.output {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.output_area {
    /* Old browsers */
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-box-align: stretch;
    display: -moz-box;
    -moz-box-orient: vertical;
    -moz-box-align: stretch;
    display: box;
    box-orient: vertical;
    box-align: stretch;
    /* Modern browsers */
    display: flex;
    flex-direction: column;
    align-items: stretch;
  }
}
div.output_area pre {
  margin: 0;
  padding: 1px 0 1px 0;
  border: 0;
  vertical-align: baseline;
  color: black;
  background-color: transparent;
  border-radius: 0;
}
/* This class is for the output subarea inside the output_area and after
   the prompt div. */
div.output_subarea {
  overflow-x: auto;
  padding: 0.4em;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
  max-width: calc(100% - 14ex);
}
div.output_scroll div.output_subarea {
  overflow-x: visible;
}
/* The rest of the output_* classes are for special styling of the different
   output types */
/* all text output has this class: */
div.output_text {
  text-align: left;
  color: #000;
  /* This has to match that of the the CodeMirror class line-height below */
  line-height: 1.21429em;
}
/* stdout/stderr are 'text' as well as 'stream', but execute_result/error are *not* streams */
div.output_stderr {
  background: #fdd;
  /* very light red background for stderr */
}
div.output_latex {
  text-align: left;
}
/* Empty output_javascript divs should have no height */
div.output_javascript:empty {
  padding: 0;
}
.js-error {
  color: darkred;
}
/* raw_input styles */
div.raw_input_container {
  line-height: 1.21429em;
  padding-top: 5px;
}
pre.raw_input_prompt {
  /* nothing needed here. */
}
input.raw_input {
  font-family: monospace;
  font-size: inherit;
  color: inherit;
  width: auto;
  /* make sure input baseline aligns with prompt */
  vertical-align: baseline;
  /* padding + margin = 0.5em between prompt and cursor */
  padding: 0em 0.25em;
  margin: 0em 0.25em;
}
input.raw_input:focus {
  box-shadow: none;
}
p.p-space {
  margin-bottom: 10px;
}
div.output_unrecognized {
  padding: 5px;
  font-weight: bold;
  color: red;
}
div.output_unrecognized a {
  color: inherit;
  text-decoration: none;
}
div.output_unrecognized a:hover {
  color: inherit;
  text-decoration: none;
}
.rendered_html {
  color: #000;
  /* any extras will just be numbers: */
}
.rendered_html em {
  font-style: italic;
}
.rendered_html strong {
  font-weight: bold;
}
.rendered_html u {
  text-decoration: underline;
}
.rendered_html :link {
  text-decoration: underline;
}
.rendered_html :visited {
  text-decoration: underline;
}
.rendered_html h1 {
  font-size: 185.7%;
  margin: 1.08em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h2 {
  font-size: 157.1%;
  margin: 1.27em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h3 {
  font-size: 128.6%;
  margin: 1.55em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h4 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h5 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
  font-style: italic;
}
.rendered_html h6 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
  font-style: italic;
}
.rendered_html h1:first-child {
  margin-top: 0.538em;
}
.rendered_html h2:first-child {
  margin-top: 0.636em;
}
.rendered_html h3:first-child {
  margin-top: 0.777em;
}
.rendered_html h4:first-child {
  margin-top: 1em;
}
.rendered_html h5:first-child {
  margin-top: 1em;
}
.rendered_html h6:first-child {
  margin-top: 1em;
}
.rendered_html ul:not(.list-inline),
.rendered_html ol:not(.list-inline) {
  padding-left: 2em;
}
.rendered_html ul {
  list-style: disc;
}
.rendered_html ul ul {
  list-style: square;
  margin-top: 0;
}
.rendered_html ul ul ul {
  list-style: circle;
}
.rendered_html ol {
  list-style: decimal;
}
.rendered_html ol ol {
  list-style: upper-alpha;
  margin-top: 0;
}
.rendered_html ol ol ol {
  list-style: lower-alpha;
}
.rendered_html ol ol ol ol {
  list-style: lower-roman;
}
.rendered_html ol ol ol ol ol {
  list-style: decimal;
}
.rendered_html * + ul {
  margin-top: 1em;
}
.rendered_html * + ol {
  margin-top: 1em;
}
.rendered_html hr {
  color: black;
  background-color: black;
}
.rendered_html pre {
  margin: 1em 2em;
  padding: 0px;
  background-color: #fff;
}
.rendered_html code {
  background-color: #eff0f1;
}
.rendered_html p code {
  padding: 1px 5px;
}
.rendered_html pre code {
  background-color: #fff;
}
.rendered_html pre,
.rendered_html code {
  border: 0;
  color: #000;
  font-size: 100%;
}
.rendered_html blockquote {
  margin: 1em 2em;
}
.rendered_html table {
  margin-left: auto;
  margin-right: auto;
  border: none;
  border-collapse: collapse;
  border-spacing: 0;
  color: black;
  font-size: 12px;
  table-layout: fixed;
}
.rendered_html thead {
  border-bottom: 1px solid black;
  vertical-align: bottom;
}
.rendered_html tr,
.rendered_html th,
.rendered_html td {
  text-align: right;
  vertical-align: middle;
  padding: 0.5em 0.5em;
  line-height: normal;
  white-space: normal;
  max-width: none;
  border: none;
}
.rendered_html th {
  font-weight: bold;
}
.rendered_html tbody tr:nth-child(odd) {
  background: #f5f5f5;
}
.rendered_html tbody tr:hover {
  background: rgba(66, 165, 245, 0.2);
}
.rendered_html * + table {
  margin-top: 1em;
}
.rendered_html p {
  text-align: left;
}
.rendered_html * + p {
  margin-top: 1em;
}
.rendered_html img {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.rendered_html * + img {
  margin-top: 1em;
}
.rendered_html img,
.rendered_html svg {
  max-width: 100%;
  height: auto;
}
.rendered_html img.unconfined,
.rendered_html svg.unconfined {
  max-width: none;
}
.rendered_html .alert {
  margin-bottom: initial;
}
.rendered_html * + .alert {
  margin-top: 1em;
}
[dir="rtl"] .rendered_html p {
  text-align: right;
}
div.text_cell {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.text_cell > div.prompt {
    display: none;
  }
}
div.text_cell_render {
  /*font-family: "Helvetica Neue", Arial, Helvetica, Geneva, sans-serif;*/
  outline: none;
  resize: none;
  width: inherit;
  border-style: none;
  padding: 0.5em 0.5em 0.5em 0.4em;
  color: #000;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
a.anchor-link:link {
  text-decoration: none;
  padding: 0px 20px;
  visibility: hidden;
}
h1:hover .anchor-link,
h2:hover .anchor-link,
h3:hover .anchor-link,
h4:hover .anchor-link,
h5:hover .anchor-link,
h6:hover .anchor-link {
  visibility: visible;
}
.text_cell.rendered .input_area {
  display: none;
}
.text_cell.rendered .rendered_html {
  overflow-x: auto;
  overflow-y: hidden;
}
.text_cell.rendered .rendered_html tr,
.text_cell.rendered .rendered_html th,
.text_cell.rendered .rendered_html td {
  max-width: none;
}
.text_cell.unrendered .text_cell_render {
  display: none;
}
.text_cell .dropzone .input_area {
  border: 2px dashed #bababa;
  margin: -1px;
}
.cm-header-1,
.cm-header-2,
.cm-header-3,
.cm-header-4,
.cm-header-5,
.cm-header-6 {
  font-weight: bold;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
}
.cm-header-1 {
  font-size: 185.7%;
}
.cm-header-2 {
  font-size: 157.1%;
}
.cm-header-3 {
  font-size: 128.6%;
}
.cm-header-4 {
  font-size: 110%;
}
.cm-header-5 {
  font-size: 100%;
  font-style: italic;
}
.cm-header-6 {
  font-size: 100%;
  font-style: italic;
}
/*!
*
* IPython notebook webapp
*
*/
@media (max-width: 767px) {
  .notebook_app {
    padding-left: 0px;
    padding-right: 0px;
  }
}
#ipython-main-app {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  height: 100%;
}
div#notebook_panel {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  height: 100%;
}
div#notebook {
  font-size: 14px;
  line-height: 20px;
  overflow-y: hidden;
  overflow-x: auto;
  width: 100%;
  /* This spaces the page away from the edge of the notebook area */
  padding-top: 20px;
  margin: 0px;
  outline: none;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  min-height: 100%;
}
@media not print {
  #notebook-container {
    padding: 15px;
    background-color: #fff;
    min-height: 0;
    -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
    box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  }
}
@media print {
  #notebook-container {
    width: 100%;
  }
}
div.ui-widget-content {
  border: 1px solid #ababab;
  outline: none;
}
pre.dialog {
  background-color: #f7f7f7;
  border: 1px solid #ddd;
  border-radius: 2px;
  padding: 0.4em;
  padding-left: 2em;
}
p.dialog {
  padding: 0.2em;
}
/* Word-wrap output correctly.  This is the CSS3 spelling, though Firefox seems
   to not honor it correctly.  Webkit browsers (Chrome, rekonq, Safari) do.
 */
pre,
code,
kbd,
samp {
  white-space: pre-wrap;
}
#fonttest {
  font-family: monospace;
}
p {
  margin-bottom: 0;
}
.end_space {
  min-height: 100px;
  transition: height .2s ease;
}
.notebook_app > #header {
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
@media not print {
  .notebook_app {
    background-color: #EEE;
  }
}
kbd {
  border-style: solid;
  border-width: 1px;
  box-shadow: none;
  margin: 2px;
  padding-left: 2px;
  padding-right: 2px;
  padding-top: 1px;
  padding-bottom: 1px;
}
.jupyter-keybindings {
  padding: 1px;
  line-height: 24px;
  border-bottom: 1px solid gray;
}
.jupyter-keybindings input {
  margin: 0;
  padding: 0;
  border: none;
}
.jupyter-keybindings i {
  padding: 6px;
}
.well code {
  background-color: #ffffff;
  border-color: #ababab;
  border-width: 1px;
  border-style: solid;
  padding: 2px;
  padding-top: 1px;
  padding-bottom: 1px;
}
/* CSS for the cell toolbar */
.celltoolbar {
  border: thin solid #CFCFCF;
  border-bottom: none;
  background: #EEE;
  border-radius: 2px 2px 0px 0px;
  width: 100%;
  height: 29px;
  padding-right: 4px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-pack: end;
  -moz-box-pack: end;
  box-pack: end;
  /* Modern browsers */
  justify-content: flex-end;
  display: -webkit-flex;
}
@media print {
  .celltoolbar {
    display: none;
  }
}
.ctb_hideshow {
  display: none;
  vertical-align: bottom;
}
/* ctb_show is added to the ctb_hideshow div to show the cell toolbar.
   Cell toolbars are only shown when the ctb_global_show class is also set.
*/
.ctb_global_show .ctb_show.ctb_hideshow {
  display: block;
}
.ctb_global_show .ctb_show + .input_area,
.ctb_global_show .ctb_show + div.text_cell_input,
.ctb_global_show .ctb_show ~ div.text_cell_render {
  border-top-right-radius: 0px;
  border-top-left-radius: 0px;
}
.ctb_global_show .ctb_show ~ div.text_cell_render {
  border: 1px solid #cfcfcf;
}
.celltoolbar {
  font-size: 87%;
  padding-top: 3px;
}
.celltoolbar select {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
  width: inherit;
  font-size: inherit;
  height: 22px;
  padding: 0px;
  display: inline-block;
}
.celltoolbar select:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.celltoolbar select::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.celltoolbar select:-ms-input-placeholder {
  color: #999;
}
.celltoolbar select::-webkit-input-placeholder {
  color: #999;
}
.celltoolbar select::-ms-expand {
  border: 0;
  background-color: transparent;
}
.celltoolbar select[disabled],
.celltoolbar select[readonly],
fieldset[disabled] .celltoolbar select {
  background-color: #eeeeee;
  opacity: 1;
}
.celltoolbar select[disabled],
fieldset[disabled] .celltoolbar select {
  cursor: not-allowed;
}
textarea.celltoolbar select {
  height: auto;
}
select.celltoolbar select {
  height: 30px;
  line-height: 30px;
}
textarea.celltoolbar select,
select[multiple].celltoolbar select {
  height: auto;
}
.celltoolbar label {
  margin-left: 5px;
  margin-right: 5px;
}
.tags_button_container {
  width: 100%;
  display: flex;
}
.tag-container {
  display: flex;
  flex-direction: row;
  flex-grow: 1;
  overflow: hidden;
  position: relative;
}
.tag-container > * {
  margin: 0 4px;
}
.remove-tag-btn {
  margin-left: 4px;
}
.tags-input {
  display: flex;
}
.cell-tag:last-child:after {
  content: "";
  position: absolute;
  right: 0;
  width: 40px;
  height: 100%;
  /* Fade to background color of cell toolbar */
  background: linear-gradient(to right, rgba(0, 0, 0, 0), #EEE);
}
.tags-input > * {
  margin-left: 4px;
}
.cell-tag,
.tags-input input,
.tags-input button {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
  box-shadow: none;
  width: inherit;
  font-size: inherit;
  height: 22px;
  line-height: 22px;
  padding: 0px 4px;
  display: inline-block;
}
.cell-tag:focus,
.tags-input input:focus,
.tags-input button:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.cell-tag::-moz-placeholder,
.tags-input input::-moz-placeholder,
.tags-input button::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.cell-tag:-ms-input-placeholder,
.tags-input input:-ms-input-placeholder,
.tags-input button:-ms-input-placeholder {
  color: #999;
}
.cell-tag::-webkit-input-placeholder,
.tags-input input::-webkit-input-placeholder,
.tags-input button::-webkit-input-placeholder {
  color: #999;
}
.cell-tag::-ms-expand,
.tags-input input::-ms-expand,
.tags-input button::-ms-expand {
  border: 0;
  background-color: transparent;
}
.cell-tag[disabled],
.tags-input input[disabled],
.tags-input button[disabled],
.cell-tag[readonly],
.tags-input input[readonly],
.tags-input button[readonly],
fieldset[disabled] .cell-tag,
fieldset[disabled] .tags-input input,
fieldset[disabled] .tags-input button {
  background-color: #eeeeee;
  opacity: 1;
}
.cell-tag[disabled],
.tags-input input[disabled],
.tags-input button[disabled],
fieldset[disabled] .cell-tag,
fieldset[disabled] .tags-input input,
fieldset[disabled] .tags-input button {
  cursor: not-allowed;
}
textarea.cell-tag,
textarea.tags-input input,
textarea.tags-input button {
  height: auto;
}
select.cell-tag,
select.tags-input input,
select.tags-input button {
  height: 30px;
  line-height: 30px;
}
textarea.cell-tag,
textarea.tags-input input,
textarea.tags-input button,
select[multiple].cell-tag,
select[multiple].tags-input input,
select[multiple].tags-input button {
  height: auto;
}
.cell-tag,
.tags-input button {
  padding: 0px 4px;
}
.cell-tag {
  background-color: #fff;
  white-space: nowrap;
}
.tags-input input[type=text]:focus {
  outline: none;
  box-shadow: none;
  border-color: #ccc;
}
.completions {
  position: absolute;
  z-index: 110;
  overflow: hidden;
  border: 1px solid #ababab;
  border-radius: 2px;
  -webkit-box-shadow: 0px 6px 10px -1px #adadad;
  box-shadow: 0px 6px 10px -1px #adadad;
  line-height: 1;
}
.completions select {
  background: white;
  outline: none;
  border: none;
  padding: 0px;
  margin: 0px;
  overflow: auto;
  font-family: monospace;
  font-size: 110%;
  color: #000;
  width: auto;
}
.completions select option.context {
  color: #286090;
}
#kernel_logo_widget .current_kernel_logo {
  display: none;
  margin-top: -1px;
  margin-bottom: -1px;
  width: 32px;
  height: 32px;
}
[dir="rtl"] #kernel_logo_widget {
  float: left !important;
  float: left;
}
.modal .modal-body .move-path {
  display: flex;
  flex-direction: row;
  justify-content: space;
  align-items: center;
}
.modal .modal-body .move-path .server-root {
  padding-right: 20px;
}
.modal .modal-body .move-path .path-input {
  flex: 1;
}
#menubar {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  margin-top: 1px;
}
#menubar .navbar {
  border-top: 1px;
  border-radius: 0px 0px 2px 2px;
  margin-bottom: 0px;
}
#menubar .navbar-toggle {
  float: left;
  padding-top: 7px;
  padding-bottom: 7px;
  border: none;
}
#menubar .navbar-collapse {
  clear: left;
}
[dir="rtl"] #menubar .navbar-toggle {
  float: right;
}
[dir="rtl"] #menubar .navbar-collapse {
  clear: right;
}
[dir="rtl"] #menubar .navbar-nav {
  float: right;
}
[dir="rtl"] #menubar .nav {
  padding-right: 0px;
}
[dir="rtl"] #menubar .navbar-nav > li {
  float: right;
}
[dir="rtl"] #menubar .navbar-right {
  float: left !important;
}
[dir="rtl"] ul.dropdown-menu {
  text-align: right;
  left: auto;
}
[dir="rtl"] ul#new-menu.dropdown-menu {
  right: auto;
  left: 0;
}
.nav-wrapper {
  border-bottom: 1px solid #e7e7e7;
}
i.menu-icon {
  padding-top: 4px;
}
[dir="rtl"] i.menu-icon.pull-right {
  float: left !important;
  float: left;
}
ul#help_menu li a {
  overflow: hidden;
  padding-right: 2.2em;
}
ul#help_menu li a i {
  margin-right: -1.2em;
}
[dir="rtl"] ul#help_menu li a {
  padding-left: 2.2em;
}
[dir="rtl"] ul#help_menu li a i {
  margin-right: 0;
  margin-left: -1.2em;
}
[dir="rtl"] ul#help_menu li a i.pull-right {
  float: left !important;
  float: left;
}
.dropdown-submenu {
  position: relative;
}
.dropdown-submenu > .dropdown-menu {
  top: 0;
  left: 100%;
  margin-top: -6px;
  margin-left: -1px;
}
[dir="rtl"] .dropdown-submenu > .dropdown-menu {
  right: 100%;
  margin-right: -1px;
}
.dropdown-submenu:hover > .dropdown-menu {
  display: block;
}
.dropdown-submenu > a:after {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  display: block;
  content: "\f0da";
  float: right;
  color: #333333;
  margin-top: 2px;
  margin-right: -10px;
}
.dropdown-submenu > a:after.fa-pull-left {
  margin-right: .3em;
}
.dropdown-submenu > a:after.fa-pull-right {
  margin-left: .3em;
}
.dropdown-submenu > a:after.pull-left {
  margin-right: .3em;
}
.dropdown-submenu > a:after.pull-right {
  margin-left: .3em;
}
[dir="rtl"] .dropdown-submenu > a:after {
  float: left;
  content: "\f0d9";
  margin-right: 0;
  margin-left: -10px;
}
.dropdown-submenu:hover > a:after {
  color: #262626;
}
.dropdown-submenu.pull-left {
  float: none;
}
.dropdown-submenu.pull-left > .dropdown-menu {
  left: -100%;
  margin-left: 10px;
}
#notification_area {
  float: right !important;
  float: right;
  z-index: 10;
}
[dir="rtl"] #notification_area {
  float: left !important;
  float: left;
}
.indicator_area {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
}
[dir="rtl"] .indicator_area {
  float: left !important;
  float: left;
}
#kernel_indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
  border-left: 1px solid;
}
#kernel_indicator .kernel_indicator_name {
  padding-left: 5px;
  padding-right: 5px;
}
[dir="rtl"] #kernel_indicator {
  float: left !important;
  float: left;
  border-left: 0;
  border-right: 1px solid;
}
#modal_indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
}
[dir="rtl"] #modal_indicator {
  float: left !important;
  float: left;
}
#readonly-indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
  margin-top: 2px;
  margin-bottom: 0px;
  margin-left: 0px;
  margin-right: 0px;
  display: none;
}
.modal_indicator:before {
  width: 1.28571429em;
  text-align: center;
}
.edit_mode .modal_indicator:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f040";
}
.edit_mode .modal_indicator:before.fa-pull-left {
  margin-right: .3em;
}
.edit_mode .modal_indicator:before.fa-pull-right {
  margin-left: .3em;
}
.edit_mode .modal_indicator:before.pull-left {
  margin-right: .3em;
}
.edit_mode .modal_indicator:before.pull-right {
  margin-left: .3em;
}
.command_mode .modal_indicator:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: ' ';
}
.command_mode .modal_indicator:before.fa-pull-left {
  margin-right: .3em;
}
.command_mode .modal_indicator:before.fa-pull-right {
  margin-left: .3em;
}
.command_mode .modal_indicator:before.pull-left {
  margin-right: .3em;
}
.command_mode .modal_indicator:before.pull-right {
  margin-left: .3em;
}
.kernel_idle_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f10c";
}
.kernel_idle_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_idle_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_idle_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_idle_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_busy_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f111";
}
.kernel_busy_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_busy_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_busy_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_busy_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_dead_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f1e2";
}
.kernel_dead_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_dead_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_dead_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_dead_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_disconnected_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f127";
}
.kernel_disconnected_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_disconnected_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_disconnected_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_disconnected_icon:before.pull-right {
  margin-left: .3em;
}
.notification_widget {
  color: #777;
  z-index: 10;
  background: rgba(240, 240, 240, 0.5);
  margin-right: 4px;
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
.notification_widget:focus,
.notification_widget.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
.notification_widget:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.notification_widget:active,
.notification_widget.active,
.open > .dropdown-toggle.notification_widget {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.notification_widget:active:hover,
.notification_widget.active:hover,
.open > .dropdown-toggle.notification_widget:hover,
.notification_widget:active:focus,
.notification_widget.active:focus,
.open > .dropdown-toggle.notification_widget:focus,
.notification_widget:active.focus,
.notification_widget.active.focus,
.open > .dropdown-toggle.notification_widget.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
.notification_widget:active,
.notification_widget.active,
.open > .dropdown-toggle.notification_widget {
  background-image: none;
}
.notification_widget.disabled:hover,
.notification_widget[disabled]:hover,
fieldset[disabled] .notification_widget:hover,
.notification_widget.disabled:focus,
.notification_widget[disabled]:focus,
fieldset[disabled] .notification_widget:focus,
.notification_widget.disabled.focus,
.notification_widget[disabled].focus,
fieldset[disabled] .notification_widget.focus {
  background-color: #fff;
  border-color: #ccc;
}
.notification_widget .badge {
  color: #fff;
  background-color: #333;
}
.notification_widget.warning {
  color: #fff;
  background-color: #f0ad4e;
  border-color: #eea236;
}
.notification_widget.warning:focus,
.notification_widget.warning.focus {
  color: #fff;
  background-color: #ec971f;
  border-color: #985f0d;
}
.notification_widget.warning:hover {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.notification_widget.warning:active,
.notification_widget.warning.active,
.open > .dropdown-toggle.notification_widget.warning {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.notification_widget.warning:active:hover,
.notification_widget.warning.active:hover,
.open > .dropdown-toggle.notification_widget.warning:hover,
.notification_widget.warning:active:focus,
.notification_widget.warning.active:focus,
.open > .dropdown-toggle.notification_widget.warning:focus,
.notification_widget.warning:active.focus,
.notification_widget.warning.active.focus,
.open > .dropdown-toggle.notification_widget.warning.focus {
  color: #fff;
  background-color: #d58512;
  border-color: #985f0d;
}
.notification_widget.warning:active,
.notification_widget.warning.active,
.open > .dropdown-toggle.notification_widget.warning {
  background-image: none;
}
.notification_widget.warning.disabled:hover,
.notification_widget.warning[disabled]:hover,
fieldset[disabled] .notification_widget.warning:hover,
.notification_widget.warning.disabled:focus,
.notification_widget.warning[disabled]:focus,
fieldset[disabled] .notification_widget.warning:focus,
.notification_widget.warning.disabled.focus,
.notification_widget.warning[disabled].focus,
fieldset[disabled] .notification_widget.warning.focus {
  background-color: #f0ad4e;
  border-color: #eea236;
}
.notification_widget.warning .badge {
  color: #f0ad4e;
  background-color: #fff;
}
.notification_widget.success {
  color: #fff;
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.notification_widget.success:focus,
.notification_widget.success.focus {
  color: #fff;
  background-color: #449d44;
  border-color: #255625;
}
.notification_widget.success:hover {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.notification_widget.success:active,
.notification_widget.success.active,
.open > .dropdown-toggle.notification_widget.success {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.notification_widget.success:active:hover,
.notification_widget.success.active:hover,
.open > .dropdown-toggle.notification_widget.success:hover,
.notification_widget.success:active:focus,
.notification_widget.success.active:focus,
.open > .dropdown-toggle.notification_widget.success:focus,
.notification_widget.success:active.focus,
.notification_widget.success.active.focus,
.open > .dropdown-toggle.notification_widget.success.focus {
  color: #fff;
  background-color: #398439;
  border-color: #255625;
}
.notification_widget.success:active,
.notification_widget.success.active,
.open > .dropdown-toggle.notification_widget.success {
  background-image: none;
}
.notification_widget.success.disabled:hover,
.notification_widget.success[disabled]:hover,
fieldset[disabled] .notification_widget.success:hover,
.notification_widget.success.disabled:focus,
.notification_widget.success[disabled]:focus,
fieldset[disabled] .notification_widget.success:focus,
.notification_widget.success.disabled.focus,
.notification_widget.success[disabled].focus,
fieldset[disabled] .notification_widget.success.focus {
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.notification_widget.success .badge {
  color: #5cb85c;
  background-color: #fff;
}
.notification_widget.info {
  color: #fff;
  background-color: #5bc0de;
  border-color: #46b8da;
}
.notification_widget.info:focus,
.notification_widget.info.focus {
  color: #fff;
  background-color: #31b0d5;
  border-color: #1b6d85;
}
.notification_widget.info:hover {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.notification_widget.info:active,
.notification_widget.info.active,
.open > .dropdown-toggle.notification_widget.info {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.notification_widget.info:active:hover,
.notification_widget.info.active:hover,
.open > .dropdown-toggle.notification_widget.info:hover,
.notification_widget.info:active:focus,
.notification_widget.info.active:focus,
.open > .dropdown-toggle.notification_widget.info:focus,
.notification_widget.info:active.focus,
.notification_widget.info.active.focus,
.open > .dropdown-toggle.notification_widget.info.focus {
  color: #fff;
  background-color: #269abc;
  border-color: #1b6d85;
}
.notification_widget.info:active,
.notification_widget.info.active,
.open > .dropdown-toggle.notification_widget.info {
  background-image: none;
}
.notification_widget.info.disabled:hover,
.notification_widget.info[disabled]:hover,
fieldset[disabled] .notification_widget.info:hover,
.notification_widget.info.disabled:focus,
.notification_widget.info[disabled]:focus,
fieldset[disabled] .notification_widget.info:focus,
.notification_widget.info.disabled.focus,
.notification_widget.info[disabled].focus,
fieldset[disabled] .notification_widget.info.focus {
  background-color: #5bc0de;
  border-color: #46b8da;
}
.notification_widget.info .badge {
  color: #5bc0de;
  background-color: #fff;
}
.notification_widget.danger {
  color: #fff;
  background-color: #d9534f;
  border-color: #d43f3a;
}
.notification_widget.danger:focus,
.notification_widget.danger.focus {
  color: #fff;
  background-color: #c9302c;
  border-color: #761c19;
}
.notification_widget.danger:hover {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.notification_widget.danger:active,
.notification_widget.danger.active,
.open > .dropdown-toggle.notification_widget.danger {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.notification_widget.danger:active:hover,
.notification_widget.danger.active:hover,
.open > .dropdown-toggle.notification_widget.danger:hover,
.notification_widget.danger:active:focus,
.notification_widget.danger.active:focus,
.open > .dropdown-toggle.notification_widget.danger:focus,
.notification_widget.danger:active.focus,
.notification_widget.danger.active.focus,
.open > .dropdown-toggle.notification_widget.danger.focus {
  color: #fff;
  background-color: #ac2925;
  border-color: #761c19;
}
.notification_widget.danger:active,
.notification_widget.danger.active,
.open > .dropdown-toggle.notification_widget.danger {
  background-image: none;
}
.notification_widget.danger.disabled:hover,
.notification_widget.danger[disabled]:hover,
fieldset[disabled] .notification_widget.danger:hover,
.notification_widget.danger.disabled:focus,
.notification_widget.danger[disabled]:focus,
fieldset[disabled] .notification_widget.danger:focus,
.notification_widget.danger.disabled.focus,
.notification_widget.danger[disabled].focus,
fieldset[disabled] .notification_widget.danger.focus {
  background-color: #d9534f;
  border-color: #d43f3a;
}
.notification_widget.danger .badge {
  color: #d9534f;
  background-color: #fff;
}
div#pager {
  background-color: #fff;
  font-size: 14px;
  line-height: 20px;
  overflow: hidden;
  display: none;
  position: fixed;
  bottom: 0px;
  width: 100%;
  max-height: 50%;
  padding-top: 8px;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  /* Display over codemirror */
  z-index: 100;
  /* Hack which prevents jquery ui resizable from changing top. */
  top: auto !important;
}
div#pager pre {
  line-height: 1.21429em;
  color: #000;
  background-color: #f7f7f7;
  padding: 0.4em;
}
div#pager #pager-button-area {
  position: absolute;
  top: 8px;
  right: 20px;
}
div#pager #pager-contents {
  position: relative;
  overflow: auto;
  width: 100%;
  height: 100%;
}
div#pager #pager-contents #pager-container {
  position: relative;
  padding: 15px 0px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
div#pager .ui-resizable-handle {
  top: 0px;
  height: 8px;
  background: #f7f7f7;
  border-top: 1px solid #cfcfcf;
  border-bottom: 1px solid #cfcfcf;
  /* This injects handle bars (a short, wide = symbol) for 
        the resize handle. */
}
div#pager .ui-resizable-handle::after {
  content: '';
  top: 2px;
  left: 50%;
  height: 3px;
  width: 30px;
  margin-left: -15px;
  position: absolute;
  border-top: 1px solid #cfcfcf;
}
.quickhelp {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
  line-height: 1.8em;
}
.shortcut_key {
  display: inline-block;
  width: 21ex;
  text-align: right;
  font-family: monospace;
}
.shortcut_descr {
  display: inline-block;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
span.save_widget {
  height: 30px;
  margin-top: 4px;
  display: flex;
  justify-content: flex-start;
  align-items: baseline;
  width: 50%;
  flex: 1;
}
span.save_widget span.filename {
  height: 100%;
  line-height: 1em;
  margin-left: 16px;
  border: none;
  font-size: 146.5%;
  text-overflow: ellipsis;
  overflow: hidden;
  white-space: nowrap;
  border-radius: 2px;
}
span.save_widget span.filename:hover {
  background-color: #e6e6e6;
}
[dir="rtl"] span.save_widget.pull-left {
  float: right !important;
  float: right;
}
[dir="rtl"] span.save_widget span.filename {
  margin-left: 0;
  margin-right: 16px;
}
span.checkpoint_status,
span.autosave_status {
  font-size: small;
  white-space: nowrap;
  padding: 0 5px;
}
@media (max-width: 767px) {
  span.save_widget {
    font-size: small;
    padding: 0 0 0 5px;
  }
  span.checkpoint_status,
  span.autosave_status {
    display: none;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  span.checkpoint_status {
    display: none;
  }
  span.autosave_status {
    font-size: x-small;
  }
}
.toolbar {
  padding: 0px;
  margin-left: -5px;
  margin-top: 2px;
  margin-bottom: 5px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
.toolbar select,
.toolbar label {
  width: auto;
  vertical-align: middle;
  margin-right: 2px;
  margin-bottom: 0px;
  display: inline;
  font-size: 92%;
  margin-left: 0.3em;
  margin-right: 0.3em;
  padding: 0px;
  padding-top: 3px;
}
.toolbar .btn {
  padding: 2px 8px;
}
.toolbar .btn-group {
  margin-top: 0px;
  margin-left: 5px;
}
.toolbar-btn-label {
  margin-left: 6px;
}
#maintoolbar {
  margin-bottom: -3px;
  margin-top: -8px;
  border: 0px;
  min-height: 27px;
  margin-left: 0px;
  padding-top: 11px;
  padding-bottom: 3px;
}
#maintoolbar .navbar-text {
  float: none;
  vertical-align: middle;
  text-align: right;
  margin-left: 5px;
  margin-right: 0px;
  margin-top: 0px;
}
.select-xs {
  height: 24px;
}
[dir="rtl"] .btn-group > .btn,
.btn-group-vertical > .btn {
  float: right;
}
.pulse,
.dropdown-menu > li > a.pulse,
li.pulse > a.dropdown-toggle,
li.pulse.open > a.dropdown-toggle {
  background-color: #F37626;
  color: white;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
/** WARNING IF YOU ARE EDITTING THIS FILE, if this is a .css file, It has a lot
 * of chance of beeing generated from the ../less/[samename].less file, you can
 * try to get back the less file by reverting somme commit in history
 **/
/*
 * We'll try to get something pretty, so we
 * have some strange css to have the scroll bar on
 * the left with fix button on the top right of the tooltip
 */
@-moz-keyframes fadeOut {
  from {
    opacity: 1;
  }
  to {
    opacity: 0;
  }
}
@-webkit-keyframes fadeOut {
  from {
    opacity: 1;
  }
  to {
    opacity: 0;
  }
}
@-moz-keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
@-webkit-keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
/*properties of tooltip after "expand"*/
.bigtooltip {
  overflow: auto;
  height: 200px;
  -webkit-transition-property: height;
  -webkit-transition-duration: 500ms;
  -moz-transition-property: height;
  -moz-transition-duration: 500ms;
  transition-property: height;
  transition-duration: 500ms;
}
/*properties of tooltip before "expand"*/
.smalltooltip {
  -webkit-transition-property: height;
  -webkit-transition-duration: 500ms;
  -moz-transition-property: height;
  -moz-transition-duration: 500ms;
  transition-property: height;
  transition-duration: 500ms;
  text-overflow: ellipsis;
  overflow: hidden;
  height: 80px;
}
.tooltipbuttons {
  position: absolute;
  padding-right: 15px;
  top: 0px;
  right: 0px;
}
.tooltiptext {
  /*avoid the button to overlap on some docstring*/
  padding-right: 30px;
}
.ipython_tooltip {
  max-width: 700px;
  /*fade-in animation when inserted*/
  -webkit-animation: fadeOut 400ms;
  -moz-animation: fadeOut 400ms;
  animation: fadeOut 400ms;
  -webkit-animation: fadeIn 400ms;
  -moz-animation: fadeIn 400ms;
  animation: fadeIn 400ms;
  vertical-align: middle;
  background-color: #f7f7f7;
  overflow: visible;
  border: #ababab 1px solid;
  outline: none;
  padding: 3px;
  margin: 0px;
  padding-left: 7px;
  font-family: monospace;
  min-height: 50px;
  -moz-box-shadow: 0px 6px 10px -1px #adadad;
  -webkit-box-shadow: 0px 6px 10px -1px #adadad;
  box-shadow: 0px 6px 10px -1px #adadad;
  border-radius: 2px;
  position: absolute;
  z-index: 1000;
}
.ipython_tooltip a {
  float: right;
}
.ipython_tooltip .tooltiptext pre {
  border: 0;
  border-radius: 0;
  font-size: 100%;
  background-color: #f7f7f7;
}
.pretooltiparrow {
  left: 0px;
  margin: 0px;
  top: -16px;
  width: 40px;
  height: 16px;
  overflow: hidden;
  position: absolute;
}
.pretooltiparrow:before {
  background-color: #f7f7f7;
  border: 1px #ababab solid;
  z-index: 11;
  content: "";
  position: absolute;
  left: 15px;
  top: 10px;
  width: 25px;
  height: 25px;
  -webkit-transform: rotate(45deg);
  -moz-transform: rotate(45deg);
  -ms-transform: rotate(45deg);
  -o-transform: rotate(45deg);
}
ul.typeahead-list i {
  margin-left: -10px;
  width: 18px;
}
[dir="rtl"] ul.typeahead-list i {
  margin-left: 0;
  margin-right: -10px;
}
ul.typeahead-list {
  max-height: 80vh;
  overflow: auto;
}
ul.typeahead-list > li > a {
  /** Firefox bug **/
  /* see https://github.com/jupyter/notebook/issues/559 */
  white-space: normal;
}
ul.typeahead-list  > li > a.pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .typeahead-list {
  text-align: right;
}
.cmd-palette .modal-body {
  padding: 7px;
}
.cmd-palette form {
  background: white;
}
.cmd-palette input {
  outline: none;
}
.no-shortcut {
  min-width: 20px;
  color: transparent;
}
[dir="rtl"] .no-shortcut.pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .command-shortcut.pull-right {
  float: left !important;
  float: left;
}
.command-shortcut:before {
  content: "(command mode)";
  padding-right: 3px;
  color: #777777;
}
.edit-shortcut:before {
  content: "(edit)";
  padding-right: 3px;
  color: #777777;
}
[dir="rtl"] .edit-shortcut.pull-right {
  float: left !important;
  float: left;
}
#find-and-replace #replace-preview .match,
#find-and-replace #replace-preview .insert {
  background-color: #BBDEFB;
  border-color: #90CAF9;
  border-style: solid;
  border-width: 1px;
  border-radius: 0px;
}
[dir="ltr"] #find-and-replace .input-group-btn + .form-control {
  border-left: none;
}
[dir="rtl"] #find-and-replace .input-group-btn + .form-control {
  border-right: none;
}
#find-and-replace #replace-preview .replace .match {
  background-color: #FFCDD2;
  border-color: #EF9A9A;
  border-radius: 0px;
}
#find-and-replace #replace-preview .replace .insert {
  background-color: #C8E6C9;
  border-color: #A5D6A7;
  border-radius: 0px;
}
#find-and-replace #replace-preview {
  max-height: 60vh;
  overflow: auto;
}
#find-and-replace #replace-preview pre {
  padding: 5px 10px;
}
.terminal-app {
  background: #EEE;
}
.terminal-app #header {
  background: #fff;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
.terminal-app .terminal {
  width: 100%;
  float: left;
  font-family: monospace;
  color: white;
  background: black;
  padding: 0.4em;
  border-radius: 2px;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.4);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.4);
}
.terminal-app .terminal,
.terminal-app .terminal dummy-screen {
  line-height: 1em;
  font-size: 14px;
}
.terminal-app .terminal .xterm-rows {
  padding: 10px;
}
.terminal-app .terminal-cursor {
  color: black;
  background: white;
}
.terminal-app #terminado-container {
  margin-top: 20px;
}
/*# sourceMappingURL=style.min.css.map */
    </style>
<style type="text/css">
    .highlight .hll { background-color: #ffffcc }
.highlight  { background: #f8f8f8; }
.highlight .c { color: #408080; font-style: italic } /* Comment */
.highlight .err { border: 1px solid #FF0000 } /* Error */
.highlight .k { color: #008000; font-weight: bold } /* Keyword */
.highlight .o { color: #666666 } /* Operator */
.highlight .ch { color: #408080; font-style: italic } /* Comment.Hashbang */
.highlight .cm { color: #408080; font-style: italic } /* Comment.Multiline */
.highlight .cp { color: #BC7A00 } /* Comment.Preproc */
.highlight .cpf { color: #408080; font-style: italic } /* Comment.PreprocFile */
.highlight .c1 { color: #408080; font-style: italic } /* Comment.Single */
.highlight .cs { color: #408080; font-style: italic } /* Comment.Special */
.highlight .gd { color: #A00000 } /* Generic.Deleted */
.highlight .ge { font-style: italic } /* Generic.Emph */
.highlight .gr { color: #FF0000 } /* Generic.Error */
.highlight .gh { color: #000080; font-weight: bold } /* Generic.Heading */
.highlight .gi { color: #00A000 } /* Generic.Inserted */
.highlight .go { color: #888888 } /* Generic.Output */
.highlight .gp { color: #000080; font-weight: bold } /* Generic.Prompt */
.highlight .gs { font-weight: bold } /* Generic.Strong */
.highlight .gu { color: #800080; font-weight: bold } /* Generic.Subheading */
.highlight .gt { color: #0044DD } /* Generic.Traceback */
.highlight .kc { color: #008000; font-weight: bold } /* Keyword.Constant */
.highlight .kd { color: #008000; font-weight: bold } /* Keyword.Declaration */
.highlight .kn { color: #008000; font-weight: bold } /* Keyword.Namespace */
.highlight .kp { color: #008000 } /* Keyword.Pseudo */
.highlight .kr { color: #008000; font-weight: bold } /* Keyword.Reserved */
.highlight .kt { color: #B00040 } /* Keyword.Type */
.highlight .m { color: #666666 } /* Literal.Number */
.highlight .s { color: #BA2121 } /* Literal.String */
.highlight .na { color: #7D9029 } /* Name.Attribute */
.highlight .nb { color: #008000 } /* Name.Builtin */
.highlight .nc { color: #0000FF; font-weight: bold } /* Name.Class */
.highlight .no { color: #880000 } /* Name.Constant */
.highlight .nd { color: #AA22FF } /* Name.Decorator */
.highlight .ni { color: #999999; font-weight: bold } /* Name.Entity */
.highlight .ne { color: #D2413A; font-weight: bold } /* Name.Exception */
.highlight .nf { color: #0000FF } /* Name.Function */
.highlight .nl { color: #A0A000 } /* Name.Label */
.highlight .nn { color: #0000FF; font-weight: bold } /* Name.Namespace */
.highlight .nt { color: #008000; font-weight: bold } /* Name.Tag */
.highlight .nv { color: #19177C } /* Name.Variable */
.highlight .ow { color: #AA22FF; font-weight: bold } /* Operator.Word */
.highlight .w { color: #bbbbbb } /* Text.Whitespace */
.highlight .mb { color: #666666 } /* Literal.Number.Bin */
.highlight .mf { color: #666666 } /* Literal.Number.Float */
.highlight .mh { color: #666666 } /* Literal.Number.Hex */
.highlight .mi { color: #666666 } /* Literal.Number.Integer */
.highlight .mo { color: #666666 } /* Literal.Number.Oct */
.highlight .sa { color: #BA2121 } /* Literal.String.Affix */
.highlight .sb { color: #BA2121 } /* Literal.String.Backtick */
.highlight .sc { color: #BA2121 } /* Literal.String.Char */
.highlight .dl { color: #BA2121 } /* Literal.String.Delimiter */
.highlight .sd { color: #BA2121; font-style: italic } /* Literal.String.Doc */
.highlight .s2 { color: #BA2121 } /* Literal.String.Double */
.highlight .se { color: #BB6622; font-weight: bold } /* Literal.String.Escape */
.highlight .sh { color: #BA2121 } /* Literal.String.Heredoc */
.highlight .si { color: #BB6688; font-weight: bold } /* Literal.String.Interpol */
.highlight .sx { color: #008000 } /* Literal.String.Other */
.highlight .sr { color: #BB6688 } /* Literal.String.Regex */
.highlight .s1 { color: #BA2121 } /* Literal.String.Single */
.highlight .ss { color: #19177C } /* Literal.String.Symbol */
.highlight .bp { color: #008000 } /* Name.Builtin.Pseudo */
.highlight .fm { color: #0000FF } /* Name.Function.Magic */
.highlight .vc { color: #19177C } /* Name.Variable.Class */
.highlight .vg { color: #19177C } /* Name.Variable.Global */
.highlight .vi { color: #19177C } /* Name.Variable.Instance */
.highlight .vm { color: #19177C } /* Name.Variable.Magic */
.highlight .il { color: #666666 } /* Literal.Number.Integer.Long */
    </style>
<style type="text/css">
    
/* Temporary definitions which will become obsolete with Notebook release 5.0 */
.ansi-black-fg { color: #3E424D; }
.ansi-black-bg { background-color: #3E424D; }
.ansi-black-intense-fg { color: #282C36; }
.ansi-black-intense-bg { background-color: #282C36; }
.ansi-red-fg { color: #E75C58; }
.ansi-red-bg { background-color: #E75C58; }
.ansi-red-intense-fg { color: #B22B31; }
.ansi-red-intense-bg { background-color: #B22B31; }
.ansi-green-fg { color: #00A250; }
.ansi-green-bg { background-color: #00A250; }
.ansi-green-intense-fg { color: #007427; }
.ansi-green-intense-bg { background-color: #007427; }
.ansi-yellow-fg { color: #DDB62B; }
.ansi-yellow-bg { background-color: #DDB62B; }
.ansi-yellow-intense-fg { color: #B27D12; }
.ansi-yellow-intense-bg { background-color: #B27D12; }
.ansi-blue-fg { color: #208FFB; }
.ansi-blue-bg { background-color: #208FFB; }
.ansi-blue-intense-fg { color: #0065CA; }
.ansi-blue-intense-bg { background-color: #0065CA; }
.ansi-magenta-fg { color: #D160C4; }
.ansi-magenta-bg { background-color: #D160C4; }
.ansi-magenta-intense-fg { color: #A03196; }
.ansi-magenta-intense-bg { background-color: #A03196; }
.ansi-cyan-fg { color: #60C6C8; }
.ansi-cyan-bg { background-color: #60C6C8; }
.ansi-cyan-intense-fg { color: #258F8F; }
.ansi-cyan-intense-bg { background-color: #258F8F; }
.ansi-white-fg { color: #C5C1B4; }
.ansi-white-bg { background-color: #C5C1B4; }
.ansi-white-intense-fg { color: #A1A6B2; }
.ansi-white-intense-bg { background-color: #A1A6B2; }

.ansi-bold { font-weight: bold; }

    </style>


<style type="text/css">
/* Overrides of notebook CSS for static HTML export */
body {
  overflow: visible;
  padding: 8px;
}

div#notebook {
  overflow: visible;
  border-top: none;
}@media print {
  div.cell {
    display: block;
    page-break-inside: avoid;
  } 
  div.output_wrapper { 
    display: block;
    page-break-inside: avoid; 
  }
  div.output { 
    display: block;
    page-break-inside: avoid; 
  }
}
</style>

<!-- Custom stylesheet, it must be in the same directory as the html file -->
<link rel="stylesheet" href="custom.css">

<!-- Loading mathjax macro -->
<!-- Load mathjax -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.5/latest.js?config=TeX-AMS_HTML"></script>
    <!-- MathJax configuration -->
    <script type="text/x-mathjax-config">
    MathJax.Hub.Config({
        tex2jax: {
            inlineMath: [ ['$','$'], ["\\(","\\)"] ],
            displayMath: [ ['$$','$$'], ["\\[","\\]"] ],
            processEscapes: true,
            processEnvironments: true
        },
        // Center justify equations in code and markdown cells. Elsewhere
        // we use CSS to left justify single line equations in code cells.
        displayAlign: 'center',
        "HTML-CSS": {
            styles: {'.MathJax_Display': {"margin": 0}},
            linebreaks: { automatic: true }
        }
    });
    </script>
    <!-- End of mathjax configuration --></head>
<body>
  <div tabindex="-1" id="notebook" class="border-box-sizing">
    <div class="container" id="notebook-container">

<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><h1>An analysis of todays Arabica Coffee Beans</h1></p>
<h3>Created by Nithin Richard</h3>
<h3>CMSC320 Final Project</h3><p><h4>Table of Contents</h4></p>
<li>Introduction</li>
<li>Initial Data</li>
<li>Chosen Variables</li>
<li>Data given by the Total Cup Points</li>
<li>How Altitude Affects the beans</li>
<li>Linear Regression with the Mean Altitude x Total Cup Points Data</li>
<li>How the Altitude ties in with Global Warming</li>
<li>Conclusion</li><h5>An Introduction into the Background of Crop Disease</h5><p>With many ecological problems in the world such as Climate Change, Deforestation, and Pollution (To name a few), many individuals are not aware of some of the growing issues facing us such as the increased amount of endangered species of plants with a combination of decreased biodiversity. Or in simpler terms, the plants and crops we are using and consuming are in danger of ceasing to exist. This is due to fungi  that is present and causing a disease that renders the plant and/or crop obsolete. While this has been starting to become well known in society regarding bananas, there is a myriad of other plants suceptible to this danger.</p>
<p>As an introductory crop that many people use but are not aware is affected, coffee beans are in danger of going extinct as the fungus spreads throughout the world. This specific fungus being the Hemileia vastatrix, for which there is no cure (McKirdy 2018). A name for this being coffee rust leaf disease, or simply coffee rust.</p>
<p>At the end of the 19th century, Sri Lanka had been heavily affected by this as their whole coffee industry was wiped out due to coffee rust. While they rebuilt towards a new crop, the damage had been done and they would not be able to return to coffee.</p>
<p>While genetically modified organisims, or GMOs are seemingly the answer to this, this fungi can mutate and evolve essentially creating a never ending battle between man and nature.</p>
<p>Looking at data drawn from the Institute of Coffee Quality's trained reviewers, I will be analyzing the data to see how some of the worlds best Arabica beans may be in danger.</p>
<p>The Goal of this project is to see if research individuals have done are similar to what trained coffee reviewers have concluded, along with showing how some coffee beans are getting better or worse.</p>
<p>Picture of Coffee Rust:<a href="https://www.perfectdailygrind.com/wp-content/uploads/2017/06/luchihdez_6_6_2017_16_22_39_687-1.jpg">https://www.perfectdailygrind.com/wp-content/uploads/2017/06/luchihdez_6_6_2017_16_22_39_687-1.jpg</a></p>
<p>Additional Information:
<a href="https://vinepair.com/booze-news/devastating-coffee-rust-hits-central-america/">https://vinepair.com/booze-news/devastating-coffee-rust-hits-central-america/</a></p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[1]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">import</span> <span class="nn">matplotlib.pyplot</span> <span class="k">as</span> <span class="nn">plt</span>
<span class="kn">import</span> <span class="nn">pandas</span> <span class="k">as</span> <span class="nn">pd</span>
<span class="kn">import</span> <span class="nn">numpy</span> <span class="k">as</span> <span class="nn">np</span>
<span class="kn">import</span> <span class="nn">seaborn</span> <span class="k">as</span> <span class="nn">sb</span>
<span class="c1">#Initially Reading the Code from the comma seperated variable file</span>
<span class="n">data</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;arabica_data_cleaned.csv&quot;</span><span class="p">,</span> <span class="n">sep</span><span class="o">=</span><span class="s1">&#39;,&#39;</span><span class="p">)</span>
<span class="c1">#Copying the data for an initial study of it</span>
<span class="n">part1</span> <span class="o">=</span> <span class="n">data</span><span class="o">.</span><span class="n">copy</span><span class="p">()</span>

<span class="n">part1</span><span class="o">.</span><span class="n">columns</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[1]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>Index([&#39;Unnamed: 0&#39;, &#39;Species&#39;, &#39;Owner&#39;, &#39;Country.of.Origin&#39;, &#39;Farm.Name&#39;,
       &#39;Lot.Number&#39;, &#39;Mill&#39;, &#39;ICO.Number&#39;, &#39;Company&#39;, &#39;Altitude&#39;, &#39;Region&#39;,
       &#39;Producer&#39;, &#39;Number.of.Bags&#39;, &#39;Bag.Weight&#39;, &#39;In.Country.Partner&#39;,
       &#39;Harvest.Year&#39;, &#39;Grading.Date&#39;, &#39;Owner.1&#39;, &#39;Variety&#39;,
       &#39;Processing.Method&#39;, &#39;Aroma&#39;, &#39;Flavor&#39;, &#39;Aftertaste&#39;, &#39;Acidity&#39;, &#39;Body&#39;,
       &#39;Balance&#39;, &#39;Uniformity&#39;, &#39;Clean.Cup&#39;, &#39;Sweetness&#39;, &#39;Cupper.Points&#39;,
       &#39;Total.Cup.Points&#39;, &#39;Moisture&#39;, &#39;Category.One.Defects&#39;, &#39;Quakers&#39;,
       &#39;Color&#39;, &#39;Category.Two.Defects&#39;, &#39;Expiration&#39;, &#39;Certification.Body&#39;,
       &#39;Certification.Address&#39;, &#39;Certification.Contact&#39;, &#39;unit_of_measurement&#39;,
       &#39;altitude_low_meters&#39;, &#39;altitude_high_meters&#39;, &#39;altitude_mean_meters&#39;],
      dtype=&#39;object&#39;)</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h5>Initial Data</h5><p>With all of the columns still in place, as shown above, it is not necessary to have these many variables.</p>
<p>Initially the data will look like this as a table. (Shown Below)</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[22]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">part1</span><span class="o">.</span><span class="n">sample</span><span class="p">(</span><span class="mi">10</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[22]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Unnamed: 0</th>
      <th>Species</th>
      <th>Owner</th>
      <th>Country.of.Origin</th>
      <th>Farm.Name</th>
      <th>Lot.Number</th>
      <th>Mill</th>
      <th>ICO.Number</th>
      <th>Company</th>
      <th>Altitude</th>
      <th>...</th>
      <th>Color</th>
      <th>Category.Two.Defects</th>
      <th>Expiration</th>
      <th>Certification.Body</th>
      <th>Certification.Address</th>
      <th>Certification.Contact</th>
      <th>unit_of_measurement</th>
      <th>altitude_low_meters</th>
      <th>altitude_high_meters</th>
      <th>altitude_mean_meters</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>820</th>
      <td>821</td>
      <td>Arabica</td>
      <td>juan luis alvarado romero</td>
      <td>Guatemala</td>
      <td>las cebollas y anexos</td>
      <td>NaN</td>
      <td>la conquista</td>
      <td>11-973-59</td>
      <td>asociación nacional del café - anacafe -</td>
      <td>1300 a 1800 mtrs. a nivel del mar</td>
      <td>...</td>
      <td>Green</td>
      <td>7</td>
      <td>April 19th, 2016</td>
      <td>Asociacion Nacional Del Café</td>
      <td>b1f20fe3a819fd6b2ee0eb8fdc3da256604f1e53</td>
      <td>724f04ad10ed31dbb9d260f0dfd221ba48be8a95</td>
      <td>m</td>
      <td>1300.00</td>
      <td>1800.00</td>
      <td>1550.00</td>
    </tr>
    <tr>
      <th>1176</th>
      <td>1177</td>
      <td>Arabica</td>
      <td>adriana torres rico quevedo</td>
      <td>Mexico</td>
      <td>cre-leg l-4</td>
      <td>NaN</td>
      <td>cre-leg beneficio</td>
      <td>0</td>
      <td>cafessisimo compañia s.a. de c.v.</td>
      <td>800</td>
      <td>...</td>
      <td>Green</td>
      <td>30</td>
      <td>September 11th, 2013</td>
      <td>AMECAFE</td>
      <td>59e396ad6e22a1c22b248f958e1da2bd8af85272</td>
      <td>0eb4ee5b3f47b20b049548a2fd1e7d4a2b70d0a7</td>
      <td>m</td>
      <td>800.00</td>
      <td>800.00</td>
      <td>800.00</td>
    </tr>
    <tr>
      <th>189</th>
      <td>190</td>
      <td>Arabica</td>
      <td>benjamin schmerler</td>
      <td>Ethiopia</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>3600-6200 ft</td>
      <td>...</td>
      <td>NaN</td>
      <td>1</td>
      <td>June 13th, 2012</td>
      <td>Specialty Coffee Association</td>
      <td>36d0d00a3724338ba7937c52a378d085f2172daa</td>
      <td>0878a7d4b9d35ddbf0fe2ce69a2062cceb45a660</td>
      <td>ft</td>
      <td>1097.28</td>
      <td>1889.76</td>
      <td>1493.52</td>
    </tr>
    <tr>
      <th>1224</th>
      <td>1225</td>
      <td>Arabica</td>
      <td>bourbon specialty coffees</td>
      <td>Brazil</td>
      <td>santa maria</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>002/4542/0213</td>
      <td>bourbon specialty coffees</td>
      <td>NaN</td>
      <td>...</td>
      <td>Green</td>
      <td>4</td>
      <td>December 16th, 2015</td>
      <td>Brazil Specialty Coffee Association</td>
      <td>3297cfa4c538e3dd03f72cc4082c54f7999e1f9d</td>
      <td>8900f0bf1d0b2bafe6807a73562c7677d57eb980</td>
      <td>m</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>669</th>
      <td>670</td>
      <td>Arabica</td>
      <td>juan luis alvarado romero</td>
      <td>Guatemala</td>
      <td>various</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>11/08/88-11/08/67</td>
      <td>waelti schoenfeld exportadores de cafe, s.a.</td>
      <td>NaN</td>
      <td>...</td>
      <td>Green</td>
      <td>5</td>
      <td>March 26th, 2013</td>
      <td>Asociacion Nacional Del Café</td>
      <td>b1f20fe3a819fd6b2ee0eb8fdc3da256604f1e53</td>
      <td>724f04ad10ed31dbb9d260f0dfd221ba48be8a95</td>
      <td>m</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>1235</th>
      <td>1236</td>
      <td>Arabica</td>
      <td>lin, che-hao krude 林哲豪</td>
      <td>Taiwan</td>
      <td>大鋤花間 (hoe vs. flower coffee farm)</td>
      <td>2017台南市精品咖啡評鑑批次 Specialty Coffee Evaluation of...</td>
      <td>大鋤花間 (hoe vs. flower coffee farm)</td>
      <td>Taiwan</td>
      <td>taiwan coffee laboratory</td>
      <td>650</td>
      <td>...</td>
      <td>Green</td>
      <td>4</td>
      <td>June 6th, 2018</td>
      <td>Specialty Coffee Association</td>
      <td>36d0d00a3724338ba7937c52a378d085f2172daa</td>
      <td>0878a7d4b9d35ddbf0fe2ce69a2062cceb45a660</td>
      <td>m</td>
      <td>650.00</td>
      <td>650.00</td>
      <td>650.00</td>
    </tr>
    <tr>
      <th>903</th>
      <td>904</td>
      <td>Arabica</td>
      <td>juan luis alvarado romero</td>
      <td>Guatemala</td>
      <td>el morito</td>
      <td>NaN</td>
      <td>beneficio ixchel</td>
      <td>11/23/1014</td>
      <td>unex guatemala, s.a.</td>
      <td>4300</td>
      <td>...</td>
      <td>Green</td>
      <td>1</td>
      <td>July 16th, 2014</td>
      <td>Asociacion Nacional Del Café</td>
      <td>b1f20fe3a819fd6b2ee0eb8fdc3da256604f1e53</td>
      <td>724f04ad10ed31dbb9d260f0dfd221ba48be8a95</td>
      <td>ft</td>
      <td>1310.64</td>
      <td>1310.64</td>
      <td>1310.64</td>
    </tr>
    <tr>
      <th>940</th>
      <td>941</td>
      <td>Arabica</td>
      <td>ipanema coffees</td>
      <td>Brazil</td>
      <td>rio verde</td>
      <td>NaN</td>
      <td>ipanema coffees</td>
      <td>002/1660/0065</td>
      <td>ipanema coffees</td>
      <td>1100</td>
      <td>...</td>
      <td>Green</td>
      <td>0</td>
      <td>October 17th, 2015</td>
      <td>Specialty Coffee Association</td>
      <td>36d0d00a3724338ba7937c52a378d085f2172daa</td>
      <td>0878a7d4b9d35ddbf0fe2ce69a2062cceb45a660</td>
      <td>m</td>
      <td>1100.00</td>
      <td>1100.00</td>
      <td>1100.00</td>
    </tr>
    <tr>
      <th>1293</th>
      <td>1294</td>
      <td>Arabica</td>
      <td>cafes finos de exportacion s de r.l.</td>
      <td>Honduras</td>
      <td>various</td>
      <td>NaN</td>
      <td>cafes finos de exportacion s. de r.l.</td>
      <td>13-117-88</td>
      <td>cafes finos de exportacion s de r.l.</td>
      <td>1350</td>
      <td>...</td>
      <td>Green</td>
      <td>16</td>
      <td>April 26th, 2015</td>
      <td>Instituto Hondureño del Café</td>
      <td>b4660a57e9f8cc613ae5b8f02bfce8634c763ab4</td>
      <td>7f521ca403540f81ec99daec7da19c2788393880</td>
      <td>m</td>
      <td>1350.00</td>
      <td>1350.00</td>
      <td>1350.00</td>
    </tr>
    <tr>
      <th>1300</th>
      <td>1301</td>
      <td>Arabica</td>
      <td>ricardo aaron sampieri marini</td>
      <td>Mexico</td>
      <td>la morena</td>
      <td>NaN</td>
      <td>tlamatoca, hutusco, ver.</td>
      <td>1104351023</td>
      <td>NaN</td>
      <td>1800</td>
      <td>...</td>
      <td>Green</td>
      <td>0</td>
      <td>July 11th, 2013</td>
      <td>AMECAFE</td>
      <td>59e396ad6e22a1c22b248f958e1da2bd8af85272</td>
      <td>0eb4ee5b3f47b20b049548a2fd1e7d4a2b70d0a7</td>
      <td>m</td>
      <td>1800.00</td>
      <td>1800.00</td>
      <td>1800.00</td>
    </tr>
  </tbody>
</table>
<p>10 rows × 44 columns</p>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h5>Chosen Variables</h5><p>However, a lot of this information will not be needed in the overall analysis of it, so we will be tidying the data and only utilising the variables that are relevant. For example, we already know that every single coffee bean in our data is Arabica, thus we can eliminate that from the table so that we do not need to waste space with it. We are also adding the 10 profiles together to get the Total Cup Points since we want to have an overall value for the coffee bean that is being studied.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[23]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#Creating a table with the wanted variables</span>
<span class="n">cleaned_table</span> <span class="o">=</span> <span class="n">part1</span><span class="p">[[</span> <span class="s1">&#39;Country.of.Origin&#39;</span><span class="p">,</span> <span class="s1">&#39;Altitude&#39;</span><span class="p">,</span> <span class="s1">&#39;Region&#39;</span><span class="p">,</span> <span class="s1">&#39;Aroma&#39;</span><span class="p">,</span> <span class="s1">&#39;Flavor&#39;</span><span class="p">,</span>\
               <span class="s1">&#39;Aftertaste&#39;</span><span class="p">,</span> <span class="s1">&#39;Acidity&#39;</span><span class="p">,</span> <span class="s1">&#39;Body&#39;</span><span class="p">,</span> <span class="s1">&#39;Balance&#39;</span><span class="p">,</span> <span class="s1">&#39;Uniformity&#39;</span><span class="p">,</span>\
               <span class="s1">&#39;Clean.Cup&#39;</span><span class="p">,</span> <span class="s1">&#39;Sweetness&#39;</span><span class="p">,</span> <span class="s1">&#39;Cupper.Points&#39;</span><span class="p">,</span><span class="s1">&#39;Total.Cup.Points&#39;</span><span class="p">,</span>\
               <span class="s1">&#39;altitude_low_meters&#39;</span><span class="p">,</span><span class="s1">&#39;altitude_high_meters&#39;</span><span class="p">,</span> <span class="s1">&#39;altitude_mean_meters&#39;</span><span class="p">]]</span><span class="o">.</span><span class="n">copy</span><span class="p">()</span>

<span class="n">cleaned_table</span><span class="p">[</span><span class="s1">&#39;Total.Cup.Points&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">cleaned_table</span><span class="p">[</span><span class="s1">&#39;Aftertaste&#39;</span><span class="p">]</span> <span class="o">+</span> <span class="n">cleaned_table</span><span class="p">[</span><span class="s1">&#39;Acidity&#39;</span><span class="p">]</span> \
    <span class="o">+</span> <span class="n">cleaned_table</span><span class="p">[</span><span class="s1">&#39;Body&#39;</span><span class="p">]</span> <span class="o">+</span> <span class="n">cleaned_table</span><span class="p">[</span><span class="s1">&#39;Balance&#39;</span><span class="p">]</span> <span class="o">+</span> <span class="n">cleaned_table</span><span class="p">[</span><span class="s1">&#39;Uniformity&#39;</span><span class="p">]</span> \
    <span class="o">+</span> <span class="n">cleaned_table</span><span class="p">[</span><span class="s1">&#39;Clean.Cup&#39;</span><span class="p">]</span> <span class="o">+</span> <span class="n">cleaned_table</span><span class="p">[</span><span class="s1">&#39;Sweetness&#39;</span><span class="p">]</span> <span class="o">+</span> <span class="n">cleaned_table</span><span class="p">[</span><span class="s1">&#39;Aroma&#39;</span><span class="p">]</span> \
    <span class="o">+</span> <span class="n">cleaned_table</span><span class="p">[</span><span class="s1">&#39;Flavor&#39;</span><span class="p">]</span> <span class="o">+</span> <span class="n">cleaned_table</span><span class="p">[</span><span class="s1">&#39;Cupper.Points&#39;</span><span class="p">]</span>

<span class="n">cleaned_table</span><span class="o">.</span><span class="n">sample</span><span class="p">(</span><span class="mi">10</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[23]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Country.of.Origin</th>
      <th>Altitude</th>
      <th>Region</th>
      <th>Aroma</th>
      <th>Flavor</th>
      <th>Aftertaste</th>
      <th>Acidity</th>
      <th>Body</th>
      <th>Balance</th>
      <th>Uniformity</th>
      <th>Clean.Cup</th>
      <th>Sweetness</th>
      <th>Cupper.Points</th>
      <th>Total.Cup.Points</th>
      <th>altitude_low_meters</th>
      <th>altitude_high_meters</th>
      <th>altitude_mean_meters</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>1165</th>
      <td>Mexico</td>
      <td>1250</td>
      <td>tepetzingo</td>
      <td>7.08</td>
      <td>7.00</td>
      <td>6.92</td>
      <td>7.33</td>
      <td>7.25</td>
      <td>7.08</td>
      <td>10.0</td>
      <td>10.0</td>
      <td>10.0</td>
      <td>6.92</td>
      <td>79.58</td>
      <td>1250.0</td>
      <td>1250.0</td>
      <td>1250.0</td>
    </tr>
    <tr>
      <th>749</th>
      <td>El Salvador</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>7.75</td>
      <td>7.33</td>
      <td>7.33</td>
      <td>7.50</td>
      <td>7.50</td>
      <td>7.50</td>
      <td>10.0</td>
      <td>10.0</td>
      <td>10.0</td>
      <td>7.33</td>
      <td>82.24</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>435</th>
      <td>Colombia</td>
      <td>175</td>
      <td>huila</td>
      <td>7.67</td>
      <td>7.58</td>
      <td>7.58</td>
      <td>7.42</td>
      <td>7.83</td>
      <td>7.58</td>
      <td>10.0</td>
      <td>10.0</td>
      <td>10.0</td>
      <td>7.58</td>
      <td>83.24</td>
      <td>175.0</td>
      <td>175.0</td>
      <td>175.0</td>
    </tr>
    <tr>
      <th>208</th>
      <td>Mexico</td>
      <td>1400</td>
      <td>la concordia, chiapas</td>
      <td>7.83</td>
      <td>7.92</td>
      <td>7.67</td>
      <td>7.75</td>
      <td>7.50</td>
      <td>7.75</td>
      <td>10.0</td>
      <td>10.0</td>
      <td>10.0</td>
      <td>7.83</td>
      <td>84.25</td>
      <td>1400.0</td>
      <td>1400.0</td>
      <td>1400.0</td>
    </tr>
    <tr>
      <th>532</th>
      <td>Thailand</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>7.50</td>
      <td>7.25</td>
      <td>7.42</td>
      <td>7.75</td>
      <td>8.17</td>
      <td>7.50</td>
      <td>10.0</td>
      <td>10.0</td>
      <td>10.0</td>
      <td>7.42</td>
      <td>83.01</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>740</th>
      <td>Malawi</td>
      <td>1180m</td>
      <td>mzuzu</td>
      <td>7.58</td>
      <td>7.42</td>
      <td>7.33</td>
      <td>7.42</td>
      <td>7.58</td>
      <td>7.50</td>
      <td>10.0</td>
      <td>10.0</td>
      <td>10.0</td>
      <td>7.42</td>
      <td>82.25</td>
      <td>1180.0</td>
      <td>1180.0</td>
      <td>1180.0</td>
    </tr>
    <tr>
      <th>499</th>
      <td>Uganda</td>
      <td>1473</td>
      <td>kasese, mt. rwenzori</td>
      <td>7.67</td>
      <td>7.58</td>
      <td>7.42</td>
      <td>7.42</td>
      <td>7.83</td>
      <td>7.50</td>
      <td>10.0</td>
      <td>10.0</td>
      <td>10.0</td>
      <td>7.58</td>
      <td>83.00</td>
      <td>1473.0</td>
      <td>1473.0</td>
      <td>1473.0</td>
    </tr>
    <tr>
      <th>434</th>
      <td>Brazil</td>
      <td>1200m</td>
      <td>grama valley</td>
      <td>7.75</td>
      <td>7.67</td>
      <td>7.50</td>
      <td>7.58</td>
      <td>7.58</td>
      <td>7.58</td>
      <td>10.0</td>
      <td>10.0</td>
      <td>10.0</td>
      <td>7.58</td>
      <td>83.24</td>
      <td>1200.0</td>
      <td>1200.0</td>
      <td>1200.0</td>
    </tr>
    <tr>
      <th>881</th>
      <td>Indonesia</td>
      <td>NaN</td>
      <td>bener meriah</td>
      <td>7.17</td>
      <td>7.42</td>
      <td>7.33</td>
      <td>7.42</td>
      <td>7.33</td>
      <td>7.42</td>
      <td>10.0</td>
      <td>10.0</td>
      <td>10.0</td>
      <td>7.58</td>
      <td>81.67</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>726</th>
      <td>Guatemala</td>
      <td>5500-6000 psnm</td>
      <td>jalapa</td>
      <td>7.67</td>
      <td>7.50</td>
      <td>7.33</td>
      <td>7.67</td>
      <td>7.50</td>
      <td>7.33</td>
      <td>10.0</td>
      <td>10.0</td>
      <td>10.0</td>
      <td>7.33</td>
      <td>82.33</td>
      <td>1676.4</td>
      <td>1828.8</td>
      <td>1752.6</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h4>After Printing the Cleaned table, the columns that are staying are</h4><ol>
    <li>Country.of.Origin</li>
    <li>'Altitude</li>
    <li>Region</li>
    <li>Aroma</li>
    <li>Flavor</li>
    <li>Aftertaste</li>
    <li>Acidity</li>
    <li>Body</li>
    <li>Balance</li>
    <li>Uniformity</li>
    <li>Clean.Cup</li>
    <li>Sweetness</li>
    <li>Total Cup Points</li>
    <li>Altitude Low Meters</li>
    <li>Altitude High Meters</li>
    <li>Altitude Mean Meters</li>
</ol>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>To further clean the table, we are going to drop all the rows that have missing data present as they will impeded the progress of the analyzing and provide bad results</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[4]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#Dropping the NaN values, and sorting the table by points</span>
<span class="n">cleaned_table</span> <span class="o">=</span> <span class="n">cleaned_table</span><span class="o">.</span><span class="n">dropna</span><span class="p">()</span>
<span class="n">cleaned_table</span> <span class="o">=</span> <span class="n">cleaned_table</span><span class="o">.</span><span class="n">sort_values</span><span class="p">(</span><span class="n">by</span> <span class="o">=</span> <span class="s1">&#39;Total.Cup.Points&#39;</span><span class="p">)</span>
<span class="n">cleaned_table</span><span class="o">.</span><span class="n">head</span><span class="p">(</span><span class="mi">10</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[4]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Country.of.Origin</th>
      <th>Altitude</th>
      <th>Region</th>
      <th>Aroma</th>
      <th>Flavor</th>
      <th>Aftertaste</th>
      <th>Acidity</th>
      <th>Body</th>
      <th>Balance</th>
      <th>Uniformity</th>
      <th>Clean.Cup</th>
      <th>Sweetness</th>
      <th>Cupper.Points</th>
      <th>Total.Cup.Points</th>
      <th>altitude_low_meters</th>
      <th>altitude_high_meters</th>
      <th>altitude_mean_meters</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>1310</th>
      <td>Honduras</td>
      <td>1400</td>
      <td>comayagua</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>1400.00</td>
      <td>1400.00</td>
      <td>1400.00</td>
    </tr>
    <tr>
      <th>1309</th>
      <td>Guatemala</td>
      <td>4650</td>
      <td>nuevo oriente</td>
      <td>7.50</td>
      <td>6.67</td>
      <td>6.67</td>
      <td>7.67</td>
      <td>7.33</td>
      <td>6.67</td>
      <td>8.00</td>
      <td>1.33</td>
      <td>1.33</td>
      <td>6.67</td>
      <td>59.84</td>
      <td>1417.32</td>
      <td>1417.32</td>
      <td>1417.32</td>
    </tr>
    <tr>
      <th>1308</th>
      <td>Nicaragua</td>
      <td>1100</td>
      <td>jalapa</td>
      <td>7.25</td>
      <td>6.58</td>
      <td>6.33</td>
      <td>6.25</td>
      <td>6.42</td>
      <td>6.08</td>
      <td>6.00</td>
      <td>6.00</td>
      <td>6.00</td>
      <td>6.17</td>
      <td>63.08</td>
      <td>1100.00</td>
      <td>1100.00</td>
      <td>1100.00</td>
    </tr>
    <tr>
      <th>1307</th>
      <td>Haiti</td>
      <td>~350m</td>
      <td>department d'artibonite , haiti</td>
      <td>6.75</td>
      <td>6.58</td>
      <td>6.42</td>
      <td>6.67</td>
      <td>7.08</td>
      <td>6.67</td>
      <td>9.33</td>
      <td>6.00</td>
      <td>6.00</td>
      <td>6.42</td>
      <td>67.92</td>
      <td>350.00</td>
      <td>350.00</td>
      <td>350.00</td>
    </tr>
    <tr>
      <th>1306</th>
      <td>Mexico</td>
      <td>900</td>
      <td>juchique de ferrer</td>
      <td>7.08</td>
      <td>6.83</td>
      <td>6.25</td>
      <td>7.42</td>
      <td>7.25</td>
      <td>6.75</td>
      <td>10.00</td>
      <td>0.00</td>
      <td>10.00</td>
      <td>6.75</td>
      <td>68.33</td>
      <td>900.00</td>
      <td>900.00</td>
      <td>900.00</td>
    </tr>
    <tr>
      <th>1305</th>
      <td>Honduras</td>
      <td>1450 msnm</td>
      <td>marcala</td>
      <td>7.00</td>
      <td>6.33</td>
      <td>6.17</td>
      <td>6.50</td>
      <td>6.67</td>
      <td>6.17</td>
      <td>8.00</td>
      <td>8.00</td>
      <td>8.00</td>
      <td>6.33</td>
      <td>69.17</td>
      <td>1450.00</td>
      <td>1450.00</td>
      <td>1450.00</td>
    </tr>
    <tr>
      <th>1304</th>
      <td>Honduras</td>
      <td>1450 msnm</td>
      <td>marcala</td>
      <td>7.00</td>
      <td>6.17</td>
      <td>6.17</td>
      <td>6.67</td>
      <td>6.50</td>
      <td>6.17</td>
      <td>8.00</td>
      <td>8.00</td>
      <td>8.00</td>
      <td>6.50</td>
      <td>69.18</td>
      <td>1450.00</td>
      <td>1450.00</td>
      <td>1450.00</td>
    </tr>
    <tr>
      <th>1303</th>
      <td>Honduras</td>
      <td>1450 msnm</td>
      <td>marcala</td>
      <td>6.67</td>
      <td>6.50</td>
      <td>6.17</td>
      <td>6.67</td>
      <td>6.83</td>
      <td>6.17</td>
      <td>8.00</td>
      <td>8.00</td>
      <td>8.00</td>
      <td>6.33</td>
      <td>69.34</td>
      <td>1450.00</td>
      <td>1450.00</td>
      <td>1450.00</td>
    </tr>
    <tr>
      <th>1301</th>
      <td>Mexico</td>
      <td>1000 meters</td>
      <td>sierra norte yajalon, chiapas</td>
      <td>6.92</td>
      <td>7.00</td>
      <td>6.83</td>
      <td>6.92</td>
      <td>7.42</td>
      <td>6.92</td>
      <td>6.00</td>
      <td>6.00</td>
      <td>10.00</td>
      <td>6.75</td>
      <td>70.76</td>
      <td>1000.00</td>
      <td>1000.00</td>
      <td>1000.00</td>
    </tr>
    <tr>
      <th>1300</th>
      <td>Mexico</td>
      <td>1800</td>
      <td>veracruz</td>
      <td>6.50</td>
      <td>6.67</td>
      <td>6.42</td>
      <td>7.17</td>
      <td>7.33</td>
      <td>6.50</td>
      <td>8.00</td>
      <td>6.00</td>
      <td>10.00</td>
      <td>6.42</td>
      <td>71.01</td>
      <td>1800.00</td>
      <td>1800.00</td>
      <td>1800.00</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h5>Data given by the Total Cup Points</h5><p>By sorting the table by the Total Cup Points in ascending order, we can see that the bottom 10 regions/Country of Origins' beans reside from Central America. With Central America having the lowest gross domestic capital in the western hemispher, it can be concluded that there is not as much research and money being put into these beans as more affluent and stable countries.</p>
<p>Another large point with why these areas suffering, is climate change. One farmer, Abelardo Ayala, has stated that his plantation which resided between 600 and 1000 meters was very ideal for the farming of his beans. With climate change, temperatures are increasing which are resulting in the area getting too hot for coffee to be succesfully grown. This can also be showing how other areas with higher altitudes are starting to raise in popularity due to their beans thriving. With the increase in heat, the fungi responsible for the coffee rust is growing at an alarming rate due to its environment being made more suitable to faciliate it.</p>
<p>Side note, this farmer and many others in the region are moving over to Cocoa beans since that is easier for them to grow due to the increasing heat.</p>
<p>Further information is present at this link.
shorturl.at/hnEI0
<a href="https://www.reuters.com/article/us-centralamerica-climatechange-coffee-c-idUSKCN10Z0VX">https://www.reuters.com/article/us-centralamerica-climatechange-coffee-c-idUSKCN10Z0VX</a></p>
<p>After this show of data, you can see what the table looks like sorted with the data descending from the highest values.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[5]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">cleaned_table</span> <span class="o">=</span> <span class="n">cleaned_table</span><span class="o">.</span><span class="n">sort_values</span><span class="p">(</span><span class="n">by</span> <span class="o">=</span> <span class="s1">&#39;Total.Cup.Points&#39;</span><span class="p">,</span>\
                                          <span class="n">ascending</span> <span class="o">=</span> <span class="kc">False</span>  <span class="p">)</span>
<span class="n">cleaned_table</span><span class="o">.</span><span class="n">head</span><span class="p">(</span><span class="mi">10</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[5]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Country.of.Origin</th>
      <th>Altitude</th>
      <th>Region</th>
      <th>Aroma</th>
      <th>Flavor</th>
      <th>Aftertaste</th>
      <th>Acidity</th>
      <th>Body</th>
      <th>Balance</th>
      <th>Uniformity</th>
      <th>Clean.Cup</th>
      <th>Sweetness</th>
      <th>Cupper.Points</th>
      <th>Total.Cup.Points</th>
      <th>altitude_low_meters</th>
      <th>altitude_high_meters</th>
      <th>altitude_mean_meters</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Ethiopia</td>
      <td>1950-2200</td>
      <td>guji-hambela</td>
      <td>8.67</td>
      <td>8.83</td>
      <td>8.67</td>
      <td>8.75</td>
      <td>8.50</td>
      <td>8.42</td>
      <td>10.00</td>
      <td>10.0</td>
      <td>10.00</td>
      <td>8.75</td>
      <td>90.59</td>
      <td>1950.0</td>
      <td>2200.0</td>
      <td>2075.0</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Ethiopia</td>
      <td>1950-2200</td>
      <td>guji-hambela</td>
      <td>8.75</td>
      <td>8.67</td>
      <td>8.50</td>
      <td>8.58</td>
      <td>8.42</td>
      <td>8.42</td>
      <td>10.00</td>
      <td>10.0</td>
      <td>10.00</td>
      <td>8.58</td>
      <td>89.92</td>
      <td>1950.0</td>
      <td>2200.0</td>
      <td>2075.0</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Ethiopia</td>
      <td>1800-2200</td>
      <td>oromia</td>
      <td>8.17</td>
      <td>8.58</td>
      <td>8.42</td>
      <td>8.42</td>
      <td>8.50</td>
      <td>8.25</td>
      <td>10.00</td>
      <td>10.0</td>
      <td>10.00</td>
      <td>8.67</td>
      <td>89.01</td>
      <td>1800.0</td>
      <td>2200.0</td>
      <td>2000.0</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Ethiopia</td>
      <td>1950-2200</td>
      <td>guji-hambela</td>
      <td>8.25</td>
      <td>8.50</td>
      <td>8.25</td>
      <td>8.50</td>
      <td>8.42</td>
      <td>8.33</td>
      <td>10.00</td>
      <td>10.0</td>
      <td>10.00</td>
      <td>8.58</td>
      <td>88.83</td>
      <td>1950.0</td>
      <td>2200.0</td>
      <td>2075.0</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Ethiopia</td>
      <td>1570-1700</td>
      <td>oromia</td>
      <td>8.25</td>
      <td>8.33</td>
      <td>8.50</td>
      <td>8.42</td>
      <td>8.33</td>
      <td>8.50</td>
      <td>10.00</td>
      <td>10.0</td>
      <td>9.33</td>
      <td>9.00</td>
      <td>88.66</td>
      <td>1570.0</td>
      <td>1700.0</td>
      <td>1635.0</td>
    </tr>
    <tr>
      <th>8</th>
      <td>Ethiopia</td>
      <td>1570-1700</td>
      <td>oromiya</td>
      <td>8.67</td>
      <td>8.67</td>
      <td>8.58</td>
      <td>8.42</td>
      <td>8.33</td>
      <td>8.42</td>
      <td>9.33</td>
      <td>10.0</td>
      <td>9.33</td>
      <td>8.67</td>
      <td>88.42</td>
      <td>1570.0</td>
      <td>1700.0</td>
      <td>1635.0</td>
    </tr>
    <tr>
      <th>9</th>
      <td>Ethiopia</td>
      <td>1795-1850</td>
      <td>snnp/kaffa zone,gimbowereda</td>
      <td>8.08</td>
      <td>8.58</td>
      <td>8.50</td>
      <td>8.50</td>
      <td>7.67</td>
      <td>8.42</td>
      <td>10.00</td>
      <td>10.0</td>
      <td>10.00</td>
      <td>8.50</td>
      <td>88.25</td>
      <td>1795.0</td>
      <td>1850.0</td>
      <td>1822.5</td>
    </tr>
    <tr>
      <th>10</th>
      <td>Ethiopia</td>
      <td>1855-1955</td>
      <td>oromia</td>
      <td>8.17</td>
      <td>8.67</td>
      <td>8.25</td>
      <td>8.50</td>
      <td>7.75</td>
      <td>8.17</td>
      <td>10.00</td>
      <td>10.0</td>
      <td>10.00</td>
      <td>8.58</td>
      <td>88.09</td>
      <td>1855.0</td>
      <td>1955.0</td>
      <td>1905.0</td>
    </tr>
    <tr>
      <th>11</th>
      <td>United States</td>
      <td>meters above sea level: 1.872</td>
      <td>antioquia</td>
      <td>8.25</td>
      <td>8.42</td>
      <td>8.17</td>
      <td>8.33</td>
      <td>8.08</td>
      <td>8.17</td>
      <td>10.00</td>
      <td>10.0</td>
      <td>10.00</td>
      <td>8.50</td>
      <td>87.92</td>
      <td>1872.0</td>
      <td>1872.0</td>
      <td>1872.0</td>
    </tr>
    <tr>
      <th>12</th>
      <td>United States</td>
      <td>meters above sea level: 1.943</td>
      <td>antioquia</td>
      <td>8.08</td>
      <td>8.67</td>
      <td>8.33</td>
      <td>8.42</td>
      <td>8.00</td>
      <td>8.08</td>
      <td>10.00</td>
      <td>10.0</td>
      <td>10.00</td>
      <td>8.33</td>
      <td>87.91</td>
      <td>1943.0</td>
      <td>1943.0</td>
      <td>1943.0</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Because there is such a large amount of data with 326 different regions, it will be easier to understand the plotted data using averages of the regions rather than plotting every single piece of information as shown below.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[6]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#Plotting the information for Country of Origin vs total cup points</span>
<span class="n">plt</span><span class="o">.</span><span class="n">figure</span><span class="p">(</span><span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">15</span><span class="p">,</span><span class="mi">10</span><span class="p">))</span>
<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s2">&quot;Plotting the Total Cup Points versus the Country of Origin&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">xlabel</span><span class="p">(</span><span class="s2">&quot;Country of Origin&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">ylabel</span><span class="p">(</span><span class="s2">&quot;Total Cup Points&quot;</span><span class="p">)</span>

<span class="n">y_data</span> <span class="o">=</span> <span class="n">cleaned_table</span><span class="p">[</span><span class="s1">&#39;Total.Cup.Points&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">values</span>
<span class="n">x_data</span> <span class="o">=</span> <span class="n">cleaned_table</span><span class="p">[</span><span class="s1">&#39;Country.of.Origin&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">values</span>

<span class="k">for</span> <span class="n">x</span><span class="p">,</span><span class="n">y</span> <span class="ow">in</span> <span class="nb">zip</span><span class="p">(</span><span class="n">x_data</span><span class="p">,</span> <span class="n">y_data</span><span class="p">):</span>
    <span class="n">plt</span><span class="o">.</span><span class="n">scatter</span><span class="p">(</span><span class="n">x</span><span class="p">,</span> <span class="n">y</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[14]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">meter_avg_table</span> <span class="o">=</span> <span class="n">cleaned_table</span><span class="p">[[</span> <span class="s1">&#39;Country.of.Origin&#39;</span><span class="p">,</span> <span class="s1">&#39;Region&#39;</span><span class="p">,</span> <span class="s1">&#39;Total.Cup.Points&#39;</span><span class="p">,</span> \
                                 <span class="s1">&#39;altitude_mean_meters&#39;</span><span class="p">,</span> <span class="s1">&#39;Flavor&#39;</span><span class="p">]]</span><span class="o">.</span><span class="n">copy</span><span class="p">()</span>
<span class="n">meter_avg_table</span><span class="p">[</span><span class="s1">&#39;average_points&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="mf">0.0</span>
<span class="c1">#Adding these filters to get rid of the outliers that are present</span>
<span class="n">meter_avg_table</span> <span class="o">=</span> <span class="n">meter_avg_table</span><span class="p">[</span><span class="n">meter_avg_table</span><span class="p">[</span><span class="s1">&#39;altitude_mean_meters&#39;</span><span class="p">]</span> <span class="o">&lt;</span> <span class="mi">5000</span><span class="p">]</span>
<span class="n">meter_avg_table</span> <span class="o">=</span> <span class="n">meter_avg_table</span><span class="p">[</span><span class="n">meter_avg_table</span><span class="p">[</span><span class="s1">&#39;Total.Cup.Points&#39;</span><span class="p">]</span> <span class="o">&gt;</span> <span class="mi">40</span><span class="p">]</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>This next cell will be showing how altitude affects the beans.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[15]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">plt</span><span class="o">.</span><span class="n">figure</span><span class="p">(</span><span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">15</span><span class="p">,</span><span class="mi">10</span><span class="p">))</span>
<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s1">&#39;Average Meters above the Sea X Total Coffee Cup Points&#39;</span><span class="p">)</span>
<span class="n">part2</span> <span class="o">=</span> <span class="n">sb</span><span class="o">.</span><span class="n">scatterplot</span><span class="p">(</span><span class="n">x</span> <span class="o">=</span> <span class="n">meter_avg_table</span><span class="p">[</span><span class="s1">&#39;altitude_mean_meters&#39;</span><span class="p">],</span> <span class="n">y</span> <span class="o">=</span> <span class="n">meter_avg_table</span><span class="p">[</span><span class="s1">&#39;Total.Cup.Points&#39;</span><span class="p">],</span> <span class="n">color</span> <span class="o">=</span> <span class="s1">&#39;g&#39;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h5>How Altitude Affects the beans</h5><p>Based on this scatter plot, it can be seen that the best ranked beans hover around the 2000 average meter mark. This meter marks specifices the altitude at which the beans are growing.</p>
<p>When judging beans, one of the most important characteristics when it comes to growing beans is what altitude it is grown at. This then leading to the fact that the higher altitude a bean is grown at, the better the quality.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[16]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">plt</span><span class="o">.</span><span class="n">figure</span><span class="p">(</span><span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">15</span><span class="p">,</span><span class="mi">10</span><span class="p">))</span>
<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s2">&quot;Average Meters above the Sea X Total Coffee Cup Points with Linear Regression&quot;</span><span class="p">)</span>
<span class="n">sb</span><span class="o">.</span><span class="n">regplot</span><span class="p">(</span><span class="n">meter_avg_table</span><span class="p">[</span><span class="s1">&#39;altitude_mean_meters&#39;</span><span class="p">],</span><span class="n">meter_avg_table</span><span class="p">[</span><span class="s1">&#39;Total.Cup.Points&#39;</span><span class="p">],</span> <span class="n">fit_reg</span> <span class="o">=</span> <span class="kc">True</span><span class="p">,</span> <span class="n">color</span> <span class="o">=</span> <span class="s1">&#39;g&#39;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[16]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>&lt;matplotlib.axes._subplots.AxesSubplot at 0x7fe2e79424a8&gt;</pre>
</div>

</div>

<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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lFLP2vP+ADqAfB66pudL0MlVnPX/wJ6/AbpG05n+MID3QH/mU7CTSpTZnz8DsM8+HpWymALAh+x1PmQfr/uhm6gVMwfdbHIcuvbv9wG8VSn1vH0D/WvQDyFG7fmfhT5fAJ384O04lx6/XCDwF9B9sL7omfZBAIMiUiyorsTJdnoEuvbis9CfD6CbpI4BmBCRY/bN4fsA/JV9vv0J8h+alKWU+hh0gHI79DE4Cp0J9F57kVugv1tPQwdQ34NO4uHXjdDNY5+Fbn78VdhNNO1a3b3QtVTT9vp/uUQ5FXTA9gD0g5tp6Cyel9nTAP3g5XLom+UPQ/ej88pB908bhT6Ou5VSD6J6iz0mjsehv5NH7PO/F/ohy0/sz/LjAH5D5TdX9joA/SDiwRKvS5X96/b2FjqEzeehv1vOz6erebNS6nkAb4XOPHsG+jz/AHQ/wDPQ371/h762vQl2pspF+gR014AXV9i+gv6b8Dro69dHoL9PqaJrrbA/0P2APwx9DToLndnXyd56DXRz8xl7G7+rio99V+56QLTiif7eEtFKJSJ3AlinlNpWcWEiWjbsWtinlFIct4yqIiL3AnhIKVV0yAoiaizW4BGtMKLHGXqZ3VTw56GzBn6j0vuIiGhlspuX99tNin8NuolmYesHIloi+NSOaOXpgG6WuQG6T8df41zTMyIiokIXQCeo6oVusvwupdTTjS0SEZXCJppERERERETLBJtoEhERERERLRNN0URz9erVqr+/v9HFICIiIiIiaohHHnnkjFJqTaXlmiLA6+/vx8MPP9zoYhARERERETWEiBzxsxybaBIRERERES0TDPCIiIiIiIiWCQZ4REREREREywQDPCIiIiIiomWCAR4REREREdEywQCPiIiIiIhomWCAR0REREREtEwwwCMiIiIiIlomGOAREREREREtEwzwiIiIiIiIlgkGeERERERERMsEAzwiIiIiIqJlggEeERERERHRMsEAj4iIiIiIaJlggEdERERERLRMMMAjIiIiIiJaJhjgERERERERLRMM8IiIiIiIiJYJBnhERERERETLBAM8IiIiIiKiZYIBHhERrRjDI8PYum8rBu4awNZ9WzE8MtzoIhEREdUUAzwiIloRhkeGcdPwTTgZP4neSC9Oxk/ipuGbGOQREdGywgCPiIhWhKGDQwgZIbSF2iAiaAu1IWSE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
