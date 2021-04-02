<!DOCTYPE html>
<html>
<head><meta charset="utf-8" />

<title>notebook</title>

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
<h2 id="1.-United-Nations-life-expectancy-data">1. United Nations life expectancy data<a class="anchor-link" href="#1.-United-Nations-life-expectancy-data">&#182;</a></h2><p>Life expectancy at birth is a measure of the average a living being is expected to live. It takes into account several demographic factors like gender, country, or year of birth.</p>
<p>Life expectancy at birth can vary along time or between countries because of many causes: the evolution of medicine, the degree of development of countries, or the effect of armed conflicts. Life expectancy varies between gender, as well. The data shows that women live longer that men. Why? Several potential factors, including biological reasons and the theory that women tend to be more health conscious.</p>
<p>Let's create some plots to explore the inequalities about life expectancy at birth around the world. We will use a dataset from the United Nations Statistics Division, which is available <a href="http://data.un.org/Data.aspx?d=GenderStat&f=inID:37&c=1,2,3,4,5,6&s=crEngName:asc,sgvEngName:asc,timeEngName:desc&v=1">here</a>.</p>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[395]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-r"><pre><span></span><span class="c1"># This sets plot images to a nice size</span>
<span class="nf">options</span><span class="p">(</span><span class="n">repr.plot.width</span> <span class="o">=</span> <span class="m">6</span><span class="p">,</span> <span class="n">repr.plot.height</span> <span class="o">=</span> <span class="m">6</span><span class="p">)</span>

<span class="c1"># Loading packages</span>
<span class="nf">library</span><span class="p">(</span><span class="n">dplyr</span><span class="p">)</span>
<span class="nf">library</span><span class="p">(</span><span class="n">tidyr</span><span class="p">)</span>
<span class="nf">library</span><span class="p">(</span><span class="n">ggplot2</span><span class="p">)</span>

<span class="c1"># Loading data</span>
<span class="n">life_expectancy</span> <span class="o">&lt;-</span> <span class="nf">read.csv</span><span class="p">(</span><span class="s">&quot;datasets/UNdata.csv&quot;</span><span class="p">)</span>

<span class="c1"># Taking a look at the first few rows</span>
<span class="nf">head</span><span class="p">(</span><span class="n">life_expectancy</span><span class="p">)</span>
<span class="nf">names</span><span class="p">(</span><span class="n">life_expectancy</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>



<div class="output_html rendered_html output_subarea ">
<table>
<caption>A data.frame: 6 x 7</caption>
<thead>
	<tr><th scope=col>Country.or.Area</th><th scope=col>Subgroup</th><th scope=col>Year</th><th scope=col>Source</th><th scope=col>Unit</th><th scope=col>Value</th><th scope=col>Value.Footnotes</th></tr>
	<tr><th scope=col>&lt;fct&gt;</th><th scope=col>&lt;fct&gt;</th><th scope=col>&lt;fct&gt;</th><th scope=col>&lt;fct&gt;</th><th scope=col>&lt;fct&gt;</th><th scope=col>&lt;int&gt;</th><th scope=col>&lt;int&gt;</th></tr>
</thead>
<tbody>
	<tr><td>Afghanistan</td><td>Female</td><td>2000-2005</td><td>UNPD_World Population Prospects_2006 (International estimate)</td><td>Years</td><td>42</td><td>NA</td></tr>
	<tr><td>Afghanistan</td><td>Female</td><td>1995-2000</td><td>UNPD_World Population Prospects_2006 (International estimate)</td><td>Years</td><td>42</td><td>NA</td></tr>
	<tr><td>Afghanistan</td><td>Female</td><td>1990-1995</td><td>UNPD_World Population Prospects_2006 (International estimate)</td><td>Years</td><td>42</td><td>NA</td></tr>
	<tr><td>Afghanistan</td><td>Female</td><td>1985-1990</td><td>UNPD_World Population Prospects_2006 (International estimate)</td><td>Years</td><td>41</td><td>NA</td></tr>
	<tr><td>Afghanistan</td><td>Male  </td><td>2000-2005</td><td>UNPD_World Population Prospects_2006 (International estimate)</td><td>Years</td><td>42</td><td>NA</td></tr>
	<tr><td>Afghanistan</td><td>Male  </td><td>1995-2000</td><td>UNPD_World Population Prospects_2006 (International estimate)</td><td>Years</td><td>42</td><td>NA</td></tr>
</tbody>
</table>

</div>

</div>

<div class="output_area">

    <div class="prompt"></div>



<div class="output_html rendered_html output_subarea ">
<ol class=list-inline>
	<li>'Country.or.Area'</li>
	<li>'Subgroup'</li>
	<li>'Year'</li>
	<li>'Source'</li>
	<li>'Unit'</li>
	<li>'Value'</li>
	<li>'Value.Footnotes'</li>
</ol>

</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[396]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-r"><pre><span></span><span class="c1"># These packages need to be loaded in the first `@tests` cell. </span>
<span class="nf">library</span><span class="p">(</span><span class="n">testthat</span><span class="p">)</span> 
<span class="nf">library</span><span class="p">(</span><span class="n">IRkernel.testthat</span><span class="p">)</span>

<span class="c1"># Then follows one or more tests of the students code. </span>
<span class="c1"># The @solution should pass the tests.</span>
<span class="c1"># The purpose of the tests is to try to catch common errors and to </span>
<span class="c1"># give the student a hint on how to resolve these errors.</span>

<span class="nf">run_tests</span><span class="p">({</span>
  <span class="nf">test_that</span><span class="p">(</span><span class="s">&quot;Test that life_expectancy exists&quot;</span><span class="p">,</span> <span class="p">{</span>
    <span class="nf">expect_true</span><span class="p">(</span><span class="nf">exists</span><span class="p">(</span><span class="s">&quot;life_expectancy&quot;</span><span class="p">),</span> 
                 <span class="n">info</span> <span class="o">=</span> <span class="s">&quot;It seems that the data frame life_expectancy does not exist.&quot;</span><span class="p">)</span>
  <span class="p">})</span>

  <span class="nf">test_that</span><span class="p">(</span><span class="s">&quot;Test that life_expectancy is loaded correctly&quot;</span><span class="p">,</span> <span class="p">{</span>
    <span class="nf">expect_true</span><span class="p">(</span><span class="nf">nrow</span><span class="p">(</span><span class="n">life_expectancy</span><span class="p">)</span><span class="o">==</span><span class="m">1571</span><span class="p">,</span> 
                 <span class="n">info</span> <span class="o">=</span> <span class="s">&quot;The data frame life_expectancy is not correctly loaded.&quot;</span><span class="p">)</span>
  <span class="p">})</span>

  <span class="nf">test_that</span><span class="p">(</span><span class="s">&quot;Test that life_expectancy is loaded correctly&quot;</span><span class="p">,</span> <span class="p">{</span>
    <span class="nf">expect_true</span><span class="p">(</span><span class="nf">ncol</span><span class="p">(</span><span class="n">life_expectancy</span><span class="p">)</span><span class="o">==</span><span class="m">7</span><span class="p">,</span> 
                 <span class="n">info</span> <span class="o">=</span> <span class="s">&quot;The data frame life_expectancy is not correctly loaded.&quot;</span><span class="p">)</span>
  <span class="p">})</span>
<span class="p">})</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>





</div>

<div class="output_area">

    <div class="prompt"></div>





</div>

<div class="output_area">

    <div class="prompt"></div>




<div class="output_text output_subarea ">
<pre>3/3 tests passed</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="2.-Life-expectancy-of-men-vs.-women-by-country">2. Life expectancy of men vs. women by country<a class="anchor-link" href="#2.-Life-expectancy-of-men-vs.-women-by-country">&#182;</a></h2><p>Let's manipulate the data to make our exploration easier. We will build the dataset for our first plot in which we will represent the average life expectancy of men and women across countries for the last period recorded in our data (2000-2005).</p>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[397]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-r"><pre><span></span><span class="c1"># Subsetting and reshaping the life expectancy data</span>
<span class="n">subdata</span> <span class="o">&lt;-</span> <span class="n">life_expectancy</span>  <span class="o">%&gt;%</span> 
  <span class="nf">filter</span><span class="p">(</span><span class="n">Year</span><span class="o">==</span><span class="s">&quot;2000-2005&quot;</span><span class="p">)</span> <span class="o">%&gt;%</span> 
  <span class="nf">select</span><span class="p">(</span><span class="n">Country.or.Area</span><span class="p">,</span> <span class="n">Subgroup</span><span class="p">,</span> <span class="n">Value</span><span class="p">)</span> <span class="o">%&gt;%</span> 
  <span class="nf">spread</span><span class="p">(</span><span class="n">Subgroup</span><span class="p">,</span> <span class="n">Value</span><span class="p">)</span>

<span class="c1"># Taking a look at the first few rows</span>
<span class="nf">head</span><span class="p">(</span><span class="n">subdata</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>



<div class="output_html rendered_html output_subarea ">
<table>
<caption>A data.frame: 6 x 3</caption>
<thead>
	<tr><th scope=col>Country.or.Area</th><th scope=col>Female</th><th scope=col>Male</th></tr>
	<tr><th scope=col>&lt;fct&gt;</th><th scope=col>&lt;int&gt;</th><th scope=col>&lt;int&gt;</th></tr>
</thead>
<tbody>
	<tr><td>Afghanistan</td><td>42</td><td>42</td></tr>
	<tr><td>Albania    </td><td>79</td><td>73</td></tr>
	<tr><td>Algeria    </td><td>72</td><td>70</td></tr>
	<tr><td>Angola     </td><td>43</td><td>39</td></tr>
	<tr><td>Argentina  </td><td>78</td><td>71</td></tr>
	<tr><td>Armenia    </td><td>75</td><td>68</td></tr>
</tbody>
</table>

</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[398]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-r"><pre><span></span><span class="c1"># one or more tests of the students code. </span>
<span class="c1"># The @solution should pass the tests.</span>
<span class="c1"># The purpose of the tests is to try to catch common errors and to </span>
<span class="c1"># give the student a hint on how to resolve these errors.</span>
<span class="nf">run_tests</span><span class="p">({</span>
  <span class="nf">test_that</span><span class="p">(</span><span class="s">&quot;Test that subdata exists&quot;</span><span class="p">,</span> <span class="p">{</span>
    <span class="nf">expect_true</span><span class="p">(</span><span class="nf">exists</span><span class="p">(</span><span class="s">&quot;subdata&quot;</span><span class="p">),</span> 
                 <span class="n">info</span> <span class="o">=</span> <span class="s">&quot;It seems that dataset subdata does not exist.&quot;</span><span class="p">)</span>
  <span class="p">})</span>

  <span class="nf">test_that</span><span class="p">(</span><span class="s">&quot;Test that subdata is created correctly&quot;</span><span class="p">,</span> <span class="p">{</span>
    <span class="nf">expect_true</span><span class="p">(</span><span class="nf">nrow</span><span class="p">(</span><span class="n">subdata</span><span class="p">)</span><span class="o">==</span><span class="m">195</span><span class="p">,</span> 
                 <span class="n">info</span> <span class="o">=</span> <span class="s">&quot;It seems that subdata is not correctly created.&quot;</span><span class="p">)</span>
  <span class="p">})</span>

  <span class="nf">test_that</span><span class="p">(</span><span class="s">&quot;Test that subdata is created correctly&quot;</span><span class="p">,</span> <span class="p">{</span>
    <span class="nf">expect_true</span><span class="p">(</span><span class="nf">ncol</span><span class="p">(</span><span class="n">subdata</span><span class="p">)</span><span class="o">==</span><span class="m">3</span><span class="p">,</span> 
                 <span class="n">info</span> <span class="o">=</span> <span class="s">&quot;It seems that subdata is not correctly created.&quot;</span><span class="p">)</span>
  <span class="p">})</span>

  <span class="nf">test_that</span><span class="p">(</span><span class="s">&quot;Test that subdata is contains correct columns&quot;</span><span class="p">,</span> <span class="p">{</span>
    <span class="nf">expect_true</span><span class="p">(</span><span class="nf">sum</span><span class="p">(</span><span class="nf">is.element</span><span class="p">(</span><span class="nf">c</span><span class="p">(</span><span class="s">&quot;Country.or.Area&quot;</span><span class="p">,</span> <span class="s">&quot;Female&quot;</span><span class="p">,</span> <span class="s">&quot;Male&quot;</span><span class="p">),</span> <span class="nf">names</span><span class="p">(</span><span class="n">subdata</span><span class="p">)))</span><span class="o">==</span><span class="m">3</span><span class="p">,</span> 
                 <span class="n">info</span> <span class="o">=</span> <span class="s">&quot;It seems that subdata does not contain the correct columns.&quot;</span><span class="p">)</span>
  <span class="p">})</span>
<span class="p">})</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>





</div>

<div class="output_area">

    <div class="prompt"></div>





</div>

<div class="output_area">

    <div class="prompt"></div>




<div class="output_text output_subarea ">
<pre>4/4 tests passed</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="3.-Visualize-I">3. Visualize I<a class="anchor-link" href="#3.-Visualize-I">&#182;</a></h2><p>A scatter plot is a useful way to visualize the relationship between two variables. It is a simple plot in which points are arranged on two axes, each of which represents one of those variables. </p>
<p>Let's create a scatter plot using <code>ggplot2</code> to represent life expectancy of males (on the x-axis) against females (on the y-axis). We will create a straightforward plot in this task, without many details. We will take care of these kinds of things shortly.</p>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[399]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-r"><pre><span></span><span class="c1"># Plotting male and female life expectancy</span>
<span class="nf">ggplot</span><span class="p">(</span><span class="n">subdata</span><span class="p">,</span> <span class="nf">aes</span><span class="p">(</span><span class="n">Male</span><span class="p">,</span> <span class="n">Female</span><span class="p">))</span><span class="o">+</span>
    <span class="nf">geom_point</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAtAAAALQCAMAAACOibeuAAADAFBMVEUAAAABAQECAgIDAwME
BAQFBQUGBgYHBwcICAgJCQkKCgoLCwsMDAwNDQ0ODg4PDw8QEBARERESEhITExMUFBQVFRUW
FhYXFxcYGBgZGRkaGhobGxscHBwdHR0eHh4fHx8gICAhISEiIiIjIyMkJCQlJSUmJiYnJyco
KCgpKSkqKiorKyssLCwtLS0uLi4vLy8wMDAxMTEyMjIzMzM0NDQ1NTU2NjY3Nzc4ODg5OTk6
Ojo7Ozs8PDw9PT0+Pj4/Pz9AQEBBQUFCQkJDQ0NERERFRUVGRkZHR0dISEhJSUlKSkpLS0tM
TExNTU1OTk5PT09QUFBRUVFSUlJTU1NUVFRVVVVWVlZXV1dYWFhZWVlaWlpbW1tcXFxdXV1e
Xl5fX19gYGBhYWFiYmJjY2NkZGRlZWVmZmZnZ2doaGhpaWlqampra2tsbGxtbW1ubm5vb29w
cHBxcXFycnJzc3N0dHR1dXV2dnZ3d3d4eHh5eXl6enp7e3t8fHx9fX1+fn5/f3+AgICBgYGC
goKDg4OEhISFhYWGhoaHh4eIiIiJiYmKioqLi4uMjIyNjY2Ojo6Pj4+QkJCRkZGSkpKTk5OU
lJSVlZWWlpaXl5eYmJiZmZmampqbm5ucnJydnZ2enp6fn5+goKChoaGioqKjo6OkpKSlpaWm
pqanp6eoqKipqamqqqqrq6usrKytra2urq6vr6+wsLCxsbGysrKzs7O0tLS1tbW2tra3t7e4
uLi5ubm6urq7u7u8vLy9vb2+vr6/v7/AwMDBwcHCwsLDw8PExMTFxcXGxsbHx8fIyMjJycnK
ysrLy8vMzMzNzc3Ozs7Pz8/Q0NDR0dHS0tLT09PU1NTV1dXW1tbX19fY2NjZ2dna2trb29vc
3Nzd3d3e3t7f39/g4ODh4eHi4uLj4+Pk5OTl5eXm5ubn5+fo6Ojp6enq6urr6+vs7Ozt7e3u
7u7v7+/w8PDx8fHy8vLz8/P09PT19fX29vb39/f4+Pj5+fn6+vr7+/v8/Pz9/f3+/v7////i
sF19AAAACXBIWXMAABJ0AAASdAHeZh94AAAgAElEQVR4nO2de4BN5d7H1wzGuEUoSRdydCJd
UOl2jqP7xW5cXoUQJR2Oa+EopcjtVJIkuURyKUpSqMgoJAySy4xJMpgxZuYcuc+Y23rXWs+z
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
oy1BPl8AAAAASUVORK5CYII="
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[400]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-r"><pre><span></span><span class="nf">run_tests</span><span class="p">({</span>
  <span class="nf">test_that</span><span class="p">(</span><span class="s">&quot;Check that a geom_point plot was plotted.&quot;</span><span class="p">,</span> <span class="p">{</span>
    <span class="nf">expect_true</span><span class="p">(</span> <span class="s">&quot;GeomPoint&quot;</span> <span class="o">%in%</span> <span class="nf">class</span><span class="p">(</span> <span class="nf">last_plot</span><span class="p">()</span><span class="o">$</span><span class="n">layers[[1]]</span><span class="o">$</span><span class="n">geom</span> <span class="p">)</span> <span class="p">,</span> 
                 <span class="n">info</span> <span class="o">=</span> <span class="s">&quot;Add geom_point() to produce a scatter plot.&quot;</span><span class="p">)</span>
  <span class="p">})</span>
  
  <span class="nf">test_that</span><span class="p">(</span><span class="s">&quot;Check variables are correctly mapped.&quot;</span><span class="p">,</span> <span class="p">{</span>
    <span class="nf">expect_true</span><span class="p">(</span><span class="nf">deparse</span><span class="p">(</span><span class="nf">last_plot</span><span class="p">()</span><span class="o">$</span><span class="n">mapping</span><span class="o">$</span><span class="n">x</span><span class="p">)</span><span class="o">==</span><span class="s">&quot;~Male&quot;</span> <span class="o">&amp;</span> <span class="nf">deparse</span><span class="p">(</span><span class="nf">last_plot</span><span class="p">()</span><span class="o">$</span><span class="n">mapping</span><span class="o">$</span><span class="n">y</span><span class="p">)</span> <span class="o">==</span> <span class="s">&quot;~Female&quot;</span><span class="p">,</span>
                 <span class="n">info</span> <span class="o">=</span> <span class="s">&quot;Check that the variables are mapped to the correct axes.&quot;</span><span class="p">)</span>
  <span class="p">})</span>
  
<span class="p">})</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>





</div>

<div class="output_area">

    <div class="prompt"></div>





</div>

<div class="output_area">

    <div class="prompt"></div>




<div class="output_text output_subarea ">
<pre>2/2 tests passed</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="4.-Reference-lines-I">4. Reference lines I<a class="anchor-link" href="#4.-Reference-lines-I">&#182;</a></h2><p>A good plot must be easy to understand. There are many tools in <code>ggplot2</code> to achieve this goal and we will explore some of them now. Starting from the previous plot, let's set the same limits for both axes as well as place a diagonal line for reference. After doing this, the difference between men and women across countries will be easier to interpret.</p>
<p>After completing this task, we will see how most of the points are arranged above the diagonal and how there is a significant dispersion among them. What does this all mean?</p>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[401]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-r"><pre><span></span><span class="c1"># Adding an abline and changing the scale of axes of the previous plots</span>
<span class="nf">ggplot</span><span class="p">(</span><span class="n">subdata</span><span class="p">,</span> <span class="nf">aes</span><span class="p">(</span><span class="n">Male</span><span class="p">,</span> <span class="n">Female</span><span class="p">))</span><span class="o">+</span>
    <span class="nf">geom_point</span><span class="p">()</span><span class="o">+</span>
    <span class="nf">geom_abline</span><span class="p">(</span><span class="n">intercept</span> <span class="o">=</span> <span class="m">0</span><span class="p">,</span> <span class="n">slope</span> <span class="o">=</span> <span class="m">1</span><span class="p">)</span><span class="o">+</span>
    <span class="nf">xlim</span><span class="p">(</span><span class="nf">c</span><span class="p">(</span><span class="m">35</span><span class="p">,</span> <span class="m">85</span><span class="p">))</span><span class="o">+</span>
    <span class="nf">ylim</span><span class="p">(</span><span class="nf">c</span><span class="p">(</span><span class="m">35</span><span class="p">,</span> <span class="m">85</span><span class="p">))</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAtAAAALQCAMAAACOibeuAAADAFBMVEUAAAABAQECAgIDAwME
BAQFBQUGBgYHBwcICAgJCQkKCgoLCwsMDAwNDQ0ODg4PDw8QEBARERESEhITExMUFBQVFRUW
FhYXFxcYGBgZGRkaGhobGxscHBwdHR0eHh4fHx8gICAhISEiIiIjIyMkJCQlJSUmJiYnJyco
KCgpKSkqKiorKyssLCwtLS0uLi4vLy8wMDAxMTEyMjIzMzM0NDQ1NTU2NjY3Nzc4ODg5OTk6
Ojo7Ozs8PDw9PT0+Pj4/Pz9AQEBBQUFCQkJDQ0NERERFRUVGRkZHR0dISEhJSUlKSkpLS0tM
TExNTU1OTk5PT09QUFBRUVFSUlJTU1NUVFRVVVVWVlZXV1dYWFhZWVlaWlpbW1tcXFxdXV1e
Xl5fX19gYGBhYWFiYmJjY2NkZGRlZWVmZmZnZ2doaGhpaWlqampra2tsbGxtbW1ubm5vb29w
cHBxcXFycnJzc3N0dHR1dXV2dnZ3d3d4eHh5eXl6enp7e3t8fHx9fX1+fn5/f3+AgICBgYGC
goKDg4OEhISFhYWGhoaHh4eIiIiJiYmKioqLi4uMjIyNjY2Ojo6Pj4+QkJCRkZGSkpKTk5OU
lJSVlZWWlpaXl5eYmJiZmZmampqbm5ucnJydnZ2enp6fn5+goKChoaGioqKjo6OkpKSlpaWm
pqanp6eoqKipqamqqqqrq6usrKytra2urq6vr6+wsLCxsbGysrKzs7O0tLS1tbW2tra3t7e4
uLi5ubm6urq7u7u8vLy9vb2+vr6/v7/AwMDBwcHCwsLDw8PExMTFxcXGxsbHx8fIyMjJycnK
ysrLy8vMzMzNzc3Ozs7Pz8/Q0NDR0dHS0tLT09PU1NTV1dXW1tbX19fY2NjZ2dna2trb29vc
3Nzd3d3e3t7f39/g4ODh4eHi4uLj4+Pk5OTl5eXm5ubn5+fo6Ojp6enq6urr6+vs7Ozt7e3u
7u7v7+/w8PDx8fHy8vLz8/P09PT19fX29vb39/f4+Pj5+fn6+vr7+/v8/Pz9/f3+/v7////i
sF19AAAACXBIWXMAABJ0AAASdAHeZh94AAAgAElEQVR4nO3deaBM5f8H8Gfu7tr37FuUJUSI
KEoLua4lWUJI+qaIRKuiUlpUlkooCZUoJUsbZYm4tiwXIS4ud/l9+1YKoTu/8zzPme3MmTPP
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"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[402]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-r"><pre><span></span><span class="nf">for </span><span class="p">(</span><span class="n">i</span> <span class="n">in</span> <span class="m">1</span><span class="o">:</span><span class="nf">length</span><span class="p">(</span><span class="nf">ggplot_build</span><span class="p">(</span><span class="nf">last_plot</span><span class="p">())</span><span class="o">$</span><span class="n">data</span><span class="p">))</span> 
<span class="p">{</span>
  <span class="nf">if </span><span class="p">(</span><span class="s">&quot;slope&quot;</span> <span class="o">%in%</span> <span class="nf">colnames</span><span class="p">(</span><span class="nf">ggplot_build</span><span class="p">(</span><span class="nf">last_plot</span><span class="p">())</span><span class="o">$</span><span class="n">data[[i]]</span><span class="p">))</span> <span class="n">i1</span><span class="o">=</span><span class="n">i</span>
<span class="p">}</span>


<span class="nf">run_tests</span><span class="p">({</span>
    <span class="nf">test_that</span><span class="p">(</span><span class="s">&quot;Intercept of diagonal line is equal to 0.&quot;</span><span class="p">,</span> <span class="p">{</span>
    <span class="nf">expect_equal</span><span class="p">(</span><span class="nf">ggplot_build</span><span class="p">(</span><span class="nf">last_plot</span><span class="p">())</span><span class="o">$</span><span class="n">data[[i1]]</span><span class="o">$</span><span class="n">intercept</span><span class="p">,</span> <span class="m">0</span><span class="p">,</span> 
        <span class="n">info</span> <span class="o">=</span> <span class="s">&quot;Did you add the diagonal line correctly?&quot;</span><span class="p">)</span>
    <span class="p">})</span>
    <span class="nf">test_that</span><span class="p">(</span><span class="s">&quot;Slope of diagonal line is equal to 1.&quot;</span><span class="p">,</span> <span class="p">{</span>
    <span class="nf">expect_equal</span><span class="p">(</span><span class="nf">ggplot_build</span><span class="p">(</span><span class="nf">last_plot</span><span class="p">())</span><span class="o">$</span><span class="n">data[[i1]]</span><span class="o">$</span><span class="n">slope</span><span class="p">,</span> <span class="m">1</span><span class="p">,</span> 
        <span class="n">info</span> <span class="o">=</span> <span class="s">&quot;Did you add the diagonal line correctly?&quot;</span><span class="p">)</span>
    <span class="p">})</span>
    <span class="nf">test_that</span><span class="p">(</span><span class="s">&quot;Limits of x-axis.&quot;</span><span class="p">,</span> <span class="p">{</span>
        <span class="nf">expect_equal</span><span class="p">(</span><span class="nf">length</span><span class="p">(</span><span class="nf">setdiff</span><span class="p">(</span><span class="nf">c</span><span class="p">(</span><span class="m">39</span><span class="p">,</span> <span class="m">79</span><span class="p">),</span> <span class="nf">ggplot_build</span><span class="p">(</span><span class="nf">last_plot</span><span class="p">())</span><span class="o">$</span><span class="n">layout</span><span class="o">$</span><span class="n">panel_scales_x[[1]]</span><span class="o">$</span><span class="n">range</span><span class="o">$</span><span class="n">range</span><span class="p">)),</span> <span class="m">0</span><span class="p">,</span> 
               <span class="n">info</span> <span class="o">=</span> <span class="s">&quot;The limits of x-axis is not equal to [35, 85].&quot;</span><span class="p">)</span>
<span class="p">})</span>
    <span class="nf">test_that</span><span class="p">(</span><span class="s">&quot;Limits of y-axis.&quot;</span><span class="p">,</span> <span class="p">{</span>
        <span class="nf">expect_equal</span><span class="p">(</span><span class="nf">length</span><span class="p">(</span><span class="nf">setdiff</span><span class="p">(</span><span class="nf">c</span><span class="p">(</span><span class="m">39</span><span class="p">,</span> <span class="m">85</span><span class="p">),</span> <span class="nf">ggplot_build</span><span class="p">(</span><span class="nf">last_plot</span><span class="p">())</span><span class="o">$</span><span class="n">layout</span><span class="o">$</span><span class="n">panel_scales_y[[1]]</span><span class="o">$</span><span class="n">range</span><span class="o">$</span><span class="n">range</span><span class="p">)),</span> <span class="m">0</span><span class="p">,</span> 
               <span class="n">info</span> <span class="o">=</span> <span class="s">&quot;The limits of y-axis is not equal to [35, 85].&quot;</span><span class="p">)</span>
    <span class="p">})</span>

<span class="p">})</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>





</div>

<div class="output_area">

    <div class="prompt"></div>





</div>

<div class="output_area">

    <div class="prompt"></div>




<div class="output_text output_subarea ">
<pre>4/4 tests passed</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="5.-Plot-titles-and-axis-labels">5. Plot titles and axis labels<a class="anchor-link" href="#5.-Plot-titles-and-axis-labels">&#182;</a></h2><p>A key point to make a plot understandable is placing clear labels on it. Let's add titles, axis labels, and a caption to refer to the source of data. Let's also change the appearance to make it clearer.</p>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[403]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-r"><pre><span></span><span class="c1"># Adding labels to previous plot</span>
<span class="nf">ggplot</span><span class="p">(</span><span class="n">subdata</span><span class="p">,</span> <span class="nf">aes</span><span class="p">(</span><span class="n">x</span> <span class="o">=</span> <span class="n">Male</span><span class="p">,</span> <span class="n">y</span> <span class="o">=</span> <span class="n">Female</span><span class="p">))</span><span class="o">+</span>
  <span class="nf">geom_point</span><span class="p">(</span><span class="n">colour</span> <span class="o">=</span> <span class="s">&quot;white&quot;</span><span class="p">,</span> <span class="n">fill</span> <span class="o">=</span> <span class="s">&quot;chartreuse3&quot;</span><span class="p">,</span> 
             <span class="n">shape</span> <span class="o">=</span> <span class="m">21</span><span class="p">,</span> <span class="n">alpha</span> <span class="o">=</span> <span class="m">.55</span><span class="p">,</span> <span class="n">size</span> <span class="o">=</span> <span class="m">5</span><span class="p">)</span><span class="o">+</span>
  <span class="nf">geom_abline</span><span class="p">(</span><span class="n">intercept</span> <span class="o">=</span> <span class="m">0</span><span class="p">,</span> <span class="n">slope</span> <span class="o">=</span> <span class="m">1</span><span class="p">,</span> <span class="n">linetype</span> <span class="o">=</span> <span class="m">2</span><span class="p">)</span><span class="o">+</span>
  <span class="nf">scale_x_continuous</span><span class="p">(</span><span class="n">limits</span> <span class="o">=</span> <span class="nf">c</span><span class="p">(</span><span class="m">35</span><span class="p">,</span><span class="m">85</span><span class="p">))</span><span class="o">+</span>
  <span class="nf">scale_y_continuous</span><span class="p">(</span><span class="n">limits</span> <span class="o">=</span> <span class="nf">c</span><span class="p">(</span><span class="m">35</span><span class="p">,</span><span class="m">85</span><span class="p">))</span><span class="o">+</span>
  <span class="nf">labs</span><span class="p">(</span><span class="n">title</span> <span class="o">=</span> <span class="s">&quot;Life Expectancy at Birth by Country&quot;</span><span class="p">,</span>
       <span class="n">subtitle</span> <span class="o">=</span> <span class="s">&quot;Years. Period: 2000-2005. Average.&quot;</span><span class="p">,</span>
       <span class="n">caption</span> <span class="o">=</span> <span class="s">&quot;Source: United Nations Statistics Division&quot;</span><span class="p">,</span>
       <span class="n">x</span> <span class="o">=</span> <span class="s">&quot;Males&quot;</span><span class="p">,</span>
       <span class="n">y</span> <span class="o">=</span> <span class="s">&quot;Females&quot;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAtAAAALQCAIAAAA2NdDLAAAACXBIWXMAABJ0AAASdAHeZh94
AAAgAElEQVR4nOzdd3xUVfow8HP7nZ5egSSQEELvVaVKsaKgdHSXRX6svordxUXYFdS1sIvo
iiigC1IssOy6q6wKCAGk9xLSe50k02duO+8fV8dh0iYhkxB4vn/wYe6cOfeZM3dynzn3nHMJ
jDECAAAAAAgmsr0DAAAAAMDNDxIOAAAAAAQdJBwAAAAACDpIOAAAAAAQdJBwAAAAACDoIOEA
AAAAQNBBwgEAAACAoIOEAwAAAABB18ESjh49ehAE8eWXXzZSJiIigiAIu93uu/Hf//73qFGj
jEYjQRAEQVy4cKG1gmnI119/ff27ADeIup+1wWAYOHDgn//8Z5vN5le43iOwBQiCoGm6vV7e
XF9//fXcuXO7deum1+s1Gk1CQsK0adO2bt0qCEKbxQAAuJG13d+jdnTu3Llp06YhhKZMmRIb
G4sQCgsLa63KU1JS6q0tNDS0tXYRbHq93uFwuFwunufbO5Y20rK33KdPn6ioKISQLMslJSWn
T58+ffr01q1bDx06FB4e3paR3FDKysoeeuih9PR0hFBoaGhaWhrHccXFxTt37ty5c+eyZcsO
HToUExPTvkHeBO0MQEd3EyYcq1atcrlcHMd5t+zevVsUxaVLl65atarVd/faa69Nnz691asF
N6BXXnnF97M+derUpEmTMjIyXnvttXfeece7ve4ReBOrrq4eNWpUTk5Ojx49Vq9ePWnSJJL8
ud80Nzf33Xff/fvf/15VVdXuCQcAoN3dhAnHokWL/LYUFhYihJKSktojHHDTGjhw4DPPPLN0
6dK9e/f6bq97BN7Efv/73+fk5PTs2fPQoUMhISG+TyUlJf31r3+dM2dOB+rtAwAETwcbwxEI
3yvoK1asIAjio48+QggtXLhQvfo+d+5cb2Gbzfbaa68NGjTIaDRqNJpevXqtWLGi7lX567Fo
0SKCICZPnux3n7xHH32UIIh7773Xu1296I4x/vDDDwcMGKDVasPDwx988MHz58/XrTbwyG02
21/+8pdhw4aFhIRoNJquXbvOmDFjz549CKF169YRBOFwOBBCGo3GO0ChrKxMfe3BgweXLFky
cODAyMhIlmXj4+NnzJhx4sQJv114hwt8/vnnI0aM0Ov1RqNx4sSJP/30U7Piyc7OpigqIiLC
7Xb7vUoQhKioKJIkMzIyGmntJgNu8i03S5cuXRBCoij6bqw7hsPbPlu2bBkxYoQ6luhvf/tb
gJEE0qoNafxwus4Gv3r16hdffIEQ+uCDD/yyDa/BgwfHx8d7H+bm5i5atCgpKYnjuNDQ0LFj
x27dutW3fF5eHkEQPXr08KvH7XYTBKHX6303BnLgNfmJ1/vpXLx48ToPRQCAP9yhpKamIoS+
+OKLRsqoV9NtNhvGeN++fcuXLx8wYABC6N57712+fPny5cu/+uortWRubm5KSgpCKDw8fPz4
8XfddZd6hb53795ms7lVgsEYu1yufv36IYRee+0178ZPPvkEIdS5c2ffHSGEKIp6/PHHKYoa
P3783Llze/fujRDSaDT79+/3rTPwyLOyspKTkxFCer3+zjvvnDZt2pAhQ3ieHz9+PMb4+PHj
y5cvZxgGIfTyyy8v/4XaehjjQYMGURTVu3fvKVOm3Hfffd27d0cIMQzzz3/+03cvauSvvPIK
QRBpaWmTJ0/u3LkzQojjuJMnTwYeD8b47rvvRgh98sknfs24ZcsWhNCECRMab+0mA27yLder
oc96yZIlCKHp06f7bvQ9An3b58UXX0QIpaamjh07tlOnTj/++GPjkQTeqvUK8HC6ngZ/++23
EULdunVrMhjVgQMHjEYjQigxMXH69OljxoxRz/Tz5s1TFEUtk5ubq7aS32tdLhdCSKfT1X2P
jTdRk594vZ+Ow+G4zkMRAODnJk84VAsWLEAIffTRR77FZFkeOHAgQmjx4sV2u13daLfbZ8yY
gRCaO3duqwSjysjI0Ov1NE2np6djjC9duqTVar0PvdQUUK/XHz582Lvx1VdfRQjFx8c7nc7m
Ri6KYq9evRBCDz74YHV1tXd7dXX1nj17vA91Oh1CyOVy1Y38888/Lykp8d2ydetWkiSjoqJ8
y6uRh4aGfvfdd+oWQRAefvhhhNB9993XrHi+/fZbhNDQoUP9Ihk5ciRCaNeuXXWDbEHAjbzl
evl91rIsFxYWrl69mqZpjuN++ukn38L1JhzqJ+t9m97zayORBNiqDQnwcLqeBp81axZCaNas
WU0GgzG22+3qSI5nn31WkiR148mTJ9XmWrdunbqluQlHgE3UZDvX/XSu81AEAPi5dROOnTt3
qn9NZFn23W6z2SIjIymKarKTQw2mXhzH+RX+7LPPEEKdOnUqKChQT7pvvPGGXxn1tS+99JLv
RkVR0tLSfH9pBR75tm3bEELJyclut7uRN9Lcs6865cc3ZVEjX7t2rW+x7OxshJDRaPSeXAOJ
R1EUtVvixIkT3o1nz55FCHXu3Nl7omqWugG3LOGo64477jh27Jhf4YYSjuXLl9etuckTYZOt
2pAAD6frafAJEyYghJ566qnGI1GtX79e/fT96lyzZo26XX3YgoQjkCZqsp3rfjrBOBQBuJXd
hGM4AvTf//4XIfTggw96B9Wr9Hr9sGHDZFk+efJkIPWkpKQMq49fsdmzZy9cuLCoqKhPnz4X
L16cPHnyCy+8UG+Fc+bM8X1IEMTs2bMRQvv3729u5OpPtEceeeR6ZkwIgrB379733ntv5cqV
K1asWLFiRUVFBUKo7gXs+++/3/dh165dNRqN1Wr1jmYIJB6CIJ544gmE0Pvvv+/dqP5/0aJF
FEW1YsDN1b9//0m/UEfPHDx4cNmyZWr9TVI/x+ZqslUb1+ThdP0NThBEIJH8+OOPCKF58+b5
1fnb3/4WIZSVlVVcXBxIPXVdZxOp6n46198yAIBrtHfG0zyt2MMxbty4xltm27Zt1x+ML5fL
lZCQgBCKioqqrKysW0Ddr/cqidfmzZuRzzXjwCMfM2ZMIBE2fklFHR1S18qVK30jJ0my7m/u
6OhohJD3zQYYj9VqNRgMGo1G7aqxWCw6nY5l2bKyssZfGHjA13lJRWW32x9//HGEUO/evX1/
7zbUw1Fvv07jv7wDadWGBHg44eto8GZdUlE//c2bN9d9Sn1HR48exc3v4QiwiZrs4aj307me
QxEA4OcmnBYbIFmWEULTp09XL3DU1bNnz9bd44EDBwoKChBC1dXVmZmZERERzXq593dkm0V+
8uTJmTNnchz33nvvTZw4MT4+Xh3kv3Tp0tdffx1fO+lGHfnfKvs1GAyPPvro2rVrN23a9Oyz
z3766acOh2PWrFnqWaS1Ar5+Op1uzZo127dvv3Dhwu7dux988MFGClMU1YJ+plZs1bo1e//f
4gYfNGjQtm3bjh07Fsge1fav9+0E8tEoilLv9lZpooY+nRa3DACgrls34VBHs6uzSdtgd6Wl
pfPmzcMY/+Y3v9m0adPMmTPPnDlT7/oEeXl5fplEfn4+QiguLk59GHjkaodKiy8lbN68WVGU
P/7xj+rveK/MzMyWVRh4PE888cR77723bt26p59+et26dQghvxjaJuAmURSVlJRkNpsvXbrU
eMLRXpo8nFQta/B77rnn+eefz87OPnDgwB133NF44U6dOiGE1AEWvhwOh3pNSp09y7IsQqju
BO+8vLwm4wmGlrUMAKCuW3cMx5QpUxBC27ZtU7tqg0pRlDlz5lRUVDz11FMbN26cP39+QUHB
b37zm3oL+y1LgH8Za6n2SKPmRD5p0iSE0D/+8Q+/hSL8qH/iJUny266eBtQswauysvL7779v
fL/XGQ9CqHv37hMnTszKylq6dOmlS5f69es3atSoJusPPOCG3nJzSZKUk5ODEFJ77FugtSJp
SJOHk6plDZ6amqouvbp48WKLxVJvmRMnTqiDM0aPHo0Q2rJli9pF56VOEU9OTlYTDnUBlbKy
surqat9iu3fvbjKeRrS4nVvWMgCAerTj5ZwWaMUxHKIo9unTByH0wAMPlJaW+j6VmZm5evXq
VglGtXz5coTQ4MGDPR4Pxthut6vrGv3tb3/zLaZ+IgaDwXea5WuvvYYQio2NdTgczY1cFEX1
8srMmTOtVqt3u8Vi+eGHH7wP1dr85nZijF955RWE0Lhx47yXt202m7o4AULo1Vdf9Y2coqi6
b9zvUnqA8ah873734Ycf1q28rsADbugtN6Tez9pms/3f//2f+t6vXLni3d7QOhz11txIJAG2
akMCPJy8WtDgGOOqqqrExESEUFpa2jfffOM7cyonJ2fJkiUsy54/fx77TIt98cUXvcXOnTsX
GRmJfKbF4l9GKT322GPeYv/+97/VJb/qXYejblR1m6gF7ezVspYBAPjpkAlHQxNDCgsLccAJ
B8Y4NzdXnSKo1WpHjBgxY8aMO++8U50IFx0dfZ3BeHe3d+9ekiSNRmNWVpb3tefOneN5nmXZ
48ePezcin5WaJkyYMG/ePPWvJM/zfufjwCPPyMhQzwcmk+nuu++eOXPmyJEjNRqNd6Et/Mt5
OjQ09KGHHlqwYMGCBQssFgvGuKSkRD0ZxMfHP/zww9OmTQsPD4+JiVH7ZlqQcAQYj0pRFHWJ
MJPJVHfkY70CD7iht9wQ9bPu06fP+F/0799fPQUSBPH222/7Fm5WwtFIJNefcAR4OKla0OCq
4uLiESNGqOfj0NDQoUOH3nbbbd47CaSkpHjT4gMHDhgMBoRQcnLyzJkz77zzTnU9Lt+FvzDG
Bw8eVLcnJiZOnjxZzc7/9Kc/XU/C0YJ2vv6WAQD46pAJR0MyMzNxcxIOjLHT6VyzZs3tt98e
GhrKMExsbOzgwYOfe+65Q4cOXWcw6rT+8vJy9f60O3bs8Hu5ej24a9eutbW16hb1D5+iKO+9
917fvn01Gk1oaOj9999/5syZ64m8trb2z3/+c//+/XU6nUajSUpKmjlz5v/+9z9vAY/H84c/
/CElJUXtdkYIec8QhYWFjzzySEJCAsdxXbp0eeyxx0pKStQOm5YlHIHE46X2HwS4zEOzAm7k
Lder7mfNcVxiYuKcOXPqNnizEo5GImmVhCPAw0nVggZXKYqye/fuWbNmJSUlabVatfGnTZu2
fft2QRB8S2ZnZy9cuDAhIYFhGJPJNHr06C1bttSdZvLjjz+OHTtWr9frdLoRI0Z89dVXjaw0
Wjeeuk3Ugnb21eKWAQB4Ebi1h+6DFiMIgqKo4F3O71gEQejSpUtFRcXly5cbz+1Aq4AGbwi0
DACt4tYdNApucO+//355efndd98Nf+LbBjR4Q6BlAGgV0MNxA4EeDoTQ5cuX33nnnZKSkj17
9tA0ffLkSfWWYyBIoMEbAi0DQOu6ddfhADem4uLiDRs2cBzXv3//VatWwZ/4YIMGbwi0DACt
C3o4AAAAABB0MIYDAAAAAEEHCQcAAAAAgg4SDgAAAAAEHSQcAAAAAAg6SDgAAAAAEHSQcAAA
AAAg6CDhAAAAAEDQQcIBAAAAgKCDhKOj+v777wmC+OSTT66nkunTp/M830oRAQAAAA3qMAnH
Aw88QJLk3r17/bYXFRWFhoampqY6nc52CaxJJ06cIHxotdrevXuvWLHihg24cXl5ea+//vrt
t98eHR2t1+t79+790ksvmc3muiW3bds2ZMgQrVYbFhY2bdq0jIyM4JVpxyAlSSLqU1VV1WSc
9RIEITIykiCIV199tWU1AADADajDLG1eWVnZu3dvjuPOnz9vMpnUjRjjiRMn7t+///Dhw0OG
DGnfCBty4sSJIUOGDB069KGHHkIIVVZW7t69OyMjY8yYMXv37iUIomXVKooiCALDMBRFtTi2
6dOnf/311263O/CXLFmyZO3atSNHjhwyZAjHcenp6enp6Z06dTp27FhsbKy32Jo1a5YsWTJg
wID58+ebzeb3338fIXT06NGUlJRWL9O+QUqSxDBMv379pk+f7hvDs88+q9FoAm9Yrx07dsyc
OTM5OVkUxZycHJLsML8KAACgMbjj+Ne//oUQmjt3rnfLmjVrEEIrVqwIxu4cDker1HP8+HGE
0IIFC7xbPB5P3759EUL79u1rx8AwxtOmTeM4rlkv+e6773Jzc323vPDCCwihZ555xrultLRU
o9GkpaW5XC51y7FjxwiCuPfee1u9TLsHKYoiQmjOnDmNhxS48ePHp6am7ty5EyG0Z8+e1qq2
Ia14OAEAQCM6UsKBMV6wYAFC6IsvvsAYX7lyRaPRDB06VBRFjLEoiu+8806/fv14ntfr9aNH
j/b9Y11bW/vyyy8PHTo0PDycZdmkpKRnn33WZrN5C3zxxRcIoR07dqxYsSI5OZlhmBdffFGt
9i9/+Uvv3r31er1er09OTn7kkUesVmvgMddNOPAv57/169c3GXlDgX333XcIoU2bNnlL1tTU
PPPMM4mJiSzLRkVFzZ49OzMz03enZWVl8+fPDw0N1Wq1d9xxx6FDh+omHKdPnz5y5IiiKIG/
wdzcXITQpEmTvFvWrl2LEPrggw98i40dO5aiqKqqqtYt0+5BehOO2tragoICj8fTrMD85OTk
EATxxhtvqBdWHnroIe9T//vf/xBCK1eu9HvJI488QpJkQUGBN54WHE5NfkEwxsXFxXPmzAkJ
CdHpdKNHjz58+HDd46fxvQMAbmUdLOGw2Wxdu3YNDw8vKChQL6tnZGRgjCVJmjJlCkmSM2bM
WLt27VtvvdWvXz+CILZu3aq+8Pz585GRkYsXL/7rX//6/vvvz5gxgyCI22+/3XtmVf8QJyYm
jho16vPPPz9w4MCRI0cwxs899xxCaPbs2evXr//444+XLVs2YMCAoqKiwGOuN+GYOnUqQuir
r75qMvKGAvNLOOx2e58+fdQz3/vvv79kyRKO40JDQ69cueJtutTUVJIkFy1atH79+sWLF+t0
urS0NL8TRrdu3RBC3h/0gTh69ChC6NFHH/VumTt3LkLo3LlzvsWWLVvm+5O9tcq0e5BqwsFx
nNplyHHcfffdd/Xq1WaF57V06VKKooqLizHGS5YsYVm2oqJCfUqW5c6dO6ekpPiWt9vter1+
woQJ6sMWH05NfkEsFku3bt1Ikly8ePH69eufeOIJg8HQs2dP3+Onyb0DAG5lHSzhwBinp6eT
JBkREYEQ+vvf/65uVK+sb9y40VtMEISBAwdGR0er/R9ut1sQBN96Vq1ahRD67rvv1IfqH+Lu
3bur5b2SkpLGjh17PQGrCceMGTNyc3Nzc3OPHz+uJjGRkZEWi6XJyBsKzC/h+NOf/oQQWrVq
lbfAnj17fH/TqwV8f6x/9NFH6gnSt9rmJhyKokyaNAkhdOjQIe/GMWPGIISqq6t9S65btw4h
tGHDhtYt0+5BSpLUu3fvl19+edOmTWvXrr3//vsRQiEhIWoq3CySJMXFxd11113qw7NnzyKE
3n77bW+BpUuX+r2LTZs2IYS2bNmiPmzx4dTkF0RNs9Q+OdU//vEPv+Onyb0DAG5lHS/hwBg/
//zzCKE777zTu2XYsGFRUVGua7311lsIoRMnTvi9XBAEl8t16dIlhNCrr76qblT/EL/++ut+
hQcMGBATE3Ps2LEWR6smHH769OmjBtZk5A0F5pdw9O3bV6/X+yUKI0aMIEnSYrGoBcLDw33/
7suyHB8f39wxHH7Uz+KFF17w3Th06FCEkN/ggE8//RQhtHbt2tYt0+5B1rV69WqE0NSpUwOP
ULV7927vFUPVwIED09LSvA+vXr2KEHrssce8W0aPHm00Gp1Op/qwxYeTr3q/IH369ImIiJAk
yVtMUZROnTr5Hj/N+hoCAG41dN1z4Y1v5MiR3n9Vly9ftlqt9U4KqKioUP/zySefrF+//uzZ
s77zUaurq30LJyUl+b387bfffvjhh4cOHdqlS5fbbrttwoQJM2bM0Gq1zY15woQJjz/+OEEQ
PM937drVO8chkMjrDcxPTk5Ot27d/BbV6NOnz5EjR/Ly8vr27Zudnd2nTx+a/vUTJ0myR48e
6enpzX0vXsuWLXvrrbd+97vfvfHGG77b1fbxeDy+DeVyubxPtVYZWZYLCwu9T2k0mujo6DYO
sq4lS5a8/vrrag9Ts3z00Uc6na5v3755eXnqlilTpqxatSo9Pf22225DCKWkpIwcOXLHjh1r
1qzheT4vL+/AgQMLFizwHj/Xczg1/gXJycnp06eP75QogiBSU1MrKyu9WwLcOwDg1tQhE466
FEVJSUlR+3j99OjRAyG0evXqZ5999t577/3444/j4uI4jjObzffcc4+iKL6FvVfivcaNG5eb
m/vtt9/u27fvxx9/3Lp16/Lly48cORIfH9+sCBMSEtRxG82NvKHA/GCMm5xhW7cAvo5J0S++
+OKbb765aNGiDz74wK/mTp06oV+WSPFuLC4u9j7VWmVKS0t9z52TJk369ttv2zjIugiCSEhI
OHHihNPpDDw3LS4u/uabb2RZTk1N9Xvq448/VhMOhNCjjz762GOP/fOf/5w5c+ann36KMX70
0Ue9JVt8OAXyBWnyAAtw7wCAW9NNknB07979woUL6lySegts2LAhKSlp9+7d3j+aBw8eDLBy
g8Hw0EMPqatobN++fdasWe++++5f/vKXtok8QN26dcvKynK73b6dHBcuXCBJMjExUS2QmZkp
SZK3k0NRlEAW0arXU0899e677z7++ONr166tex4aOnToli1bDh06pI5jVR06dIiiqIEDB7Zi
mYiIiF27dnmf8uveaJsg6xJFMTMz02g0NqsnbNOmTbIsv//++3Fxcb7b161b98UXX6xZs0Zd
fmbGjBlPPfXUp59+OmPGjH/84x8pKSmjRo3yFm7x4dTkF6Rr166ZmZmyLHs7OfAvl3iuf+8A
gFtC+17RaRn1HLN8+XLvlr/97W8IoUWLFvnN51RH+2OMe/funZiY6B3BIEnS5MmTEUJPPfWU
ukW9tr1r1y6/fZnNZt+H6uzK3/3ud+pDWZaPHDly5syZRqKtd5ZK4JE3FJjfGI4VK1aga6/N
qwUmTpzoW+DDDz/0Fti4cSOqM2i0yWmxiqI89thjCKGnn366oTKlpaU8z/fs2dPtdqtbTpw4
QZLkPffc0+pl2j3IjIwM3+GWsiw/9dRTCKH58+f7bmz8OFEUJSkpKSkpqe5T6oIc3vHRGOPZ
s2dTFLVt2zZUZ5Zsiw+nJr8gf/zjHxFCH3/8sfclW7Zs8Tt+mtx7IN8XAMDN6ibp4Xj88ce/
//77Dz/88PTp0/fff39kZGRhYeGRI0fOnj2rXjyePn36ihUrpkyZ8vDDD9tstu3bt+PAribE
xcXdc889gwYNio+Pr6io+PjjjymKmjdvnvqs0+kcMWJEamrqlStXghR5gJ577rkvv/zyD3/4
w8WLF0eOHJmZmfnBBx+Ehoaqa6MhhJ555pnPPvts8eLFZ86cGTBgwNmzZz/99NO0tLScnBzf
eqZPn56dne1yuRq6x8qyZcvWr1/fuXPnsLCwlStXerdHRUWp53iEUExMzKpVq5599tlRo0bN
nTu3urr6vffeMxqNb7/9trd8a5Vp9yBXr169e/fuCRMmdOrUyW6379+//8KFC0lJSb5DRpo8
Tr7//vvc3Fx1cKufyZMn63S6jz/+ePHixeqWRx99dOvWrYsWLSJJcv78+b6FW3w4NfkFee65
5z777LNFixadPn26f//+586d++STT3r27Ol7/DS59+v/vgAAOrD2znhaom4PB8ZYluV169YN
Hz5cr9fzPJ+YmDh16tTNmzerz4qiuHLlym7durEs27lz56efflrtq2iyh2Pp0qUjR46MiIhg
GCY+Pn7q1KmHDx/2Pmuz2RBCqampjUTbeA9Hk5EH2MOBMa6pqXn66acTEhIYhomMjJw1a5bf
wl+lpaVz584NCQnRarW33357vQt/NTktdsaMGfUeSL169fIruWXLloEDB/I8HxISMnXq1MuX
L9etrbXKtGOQ//rXv+67774uXbrwPK92h7z00ks1NTW+ZZo8TtQLdkePHm3k2VOnTqkP1QU5
EELe5Td8texwavILgjEuKiqaNWuWyWTSarW33XZbenr6xIkTQ0NDA997IN8XAMDNqsPcSwUA
cKPp2rWryWQ6ffp0ewcCAOgA4L5QAICA+N3kb8eOHbm5ueqKagAA0CTo4QAABGTcuHFJSUmD
Bw9mGObYsWMbN26MiYk5ffp0ZGRke4cGAOgAIOEAAATkrbfe+uyzz/Ly8hwOR3R09KRJk/70
pz81sh4JAAD4goQDAAAAAEEHYzgAAAAAEHSQcAAAAAAg6CDhAAAAAEDQQcIBAAAAgKCDhAMA
AAAAQQcJBwAAAACCDhIOAAAAAAQdJBwAAAAAuF6XLl0qLy9vpECHuT29xWIRRbHVq9VoNAgh
l8vV6jUHCc/zer3ebrf73djiRsbzPEEQHaiROY4zGAwOh6MDxczzPEmSTqezvQMJFDRyG2BZ
1mg0dqxG5jiOpmmHw9HegQRKbWSn09mBDoxgNPKXX3751FNPde/e/ezZsyRZf18G9HAAAAAA
oOXWr1//+OOPMwyzbNmyhrIN1IF6OAAAAABwQ5Fl+eWXX96wYUN0dPS2bdv69OnTSGFIOAAA
AADQbIIg/P73v9+9e3f37t23b9/euXPnxsvDJRUAAAAANFtpaWl6evqwYcO+/vrrJrMNBD0c
AAAAAGiBhISE3bt3JyYmchwXSHlIOAAAAADQEqmpqYEXhksqAAAAAAg6SDgAAAAA0DRBEK7n
5ZBwAAAAAKAJ69evv/POOy0WS4trgDEcAAAAAGiQLMtLly7duHFjTExMRUWFyWRqWT2QcAAA
AACgfoIgLF68+F//+ldqaur27ds7derU4qog4QAAAABAPWpqaubNm3f06NEhQ4Zs2bIlLCzs
emqDMRwAAAAA8Icxnj179tGjR++9995du3ZdZ7aBoIcDAAAAAHURBLF8+fJvv0KGH/oAACAA
SURBVP32lVdeaeSWbIGDhAMAAAAA9Rg+fPjw4cNbqzZIOAAAANxCaJqmKIokSYIgMMYYY0VR
JElSFKW9Q7vJQcIBAADglkDTNMuyma69ta5Sh1QjKR6SoBhSY2SjjExUAj9CEARIO4IHEg4A
AAA3P47jcsWDxeZLZnceRtj3qQpXFktqqnWFg02zPB6PJEntFWQ7kmX573//+4IFC7RabZB2
AQkHAACAmxzP8xnu/2VZjgiKs94CguLKs520iVUJ+v5x1BBZlts4wvblcrkee+yxb7/9tqys
bNWqVUHaCyQcAAAAbmYsy2Z59mVaDomKu/GSZnc+gYik8Nvcbvetc22lpqZm7ty5x44dGzVq
1AsvvBC8HcE6HAAAAG5aBEEwDJNrO9FktqGqcuedtn7BsmywA7tBFBQU3HXXXceOHbvnnnt2
7NjR4mXLAwEJBwAAgJsWwzBnrDvtYlXgLyl2XswXf2qVlSducGfOnJk8eXJWVtbChQs3bNjA
cVxQdweXVAAAANy0aJqu9hQ06yUe2eEQzRRH3fRXVRwOh9VqXbZs2ZNPPtkGu4OEAwAAwM2J
IIg8zxGrWNncF1rFCkpLiaIYjKhuHKNGjTp27FhcXFzb7K7DJBwURQWvWoZhglF5MKgBUxTV
sWJWL6O2dyCBUhuZJMmOFXNHbOQOdyR3rKOCpml0azcySZJIVhQkNvf6iIQ9NE0HEkYH/XPh
DTghIaHN9tthEg6aptUvT6tX2+p1BpV6cNM0TRBEe8cSKPVc2N5RNAM0chvwNnJ7B9IMaiMH
+zp3K1LPsrdyIxMEgdwt+b1KkNjvLwDGuN6S0Mi+Gr8I1WHayOPxBKN3S6PRIIRcLler1xwk
PM8zDOPxeNzugEZc3wh4nicIogM1MsdxDMMIgtCBYuZ5niRJp7P+NQZuQGojezweaOTgYVmW
ZdmO1cgcx9E07XA4WqU2kiQRQcqSouBmrKtBkiRN8Bjjq459kuIhCZomuSRupCRJoij6ZR5q
IwuCcOMfGE6nk6IojuNat5H9NLJuWIdJOAAAAIBmURQlUTviKn3QFtgwDoIgKIqqkQpCcdyx
6q051mPqdpKgcpijEXxCf+M0QRA64tiO6urquXPnhoWFffrpp+0Vw80/7QcAAMAtS5blUC4+
kJIEQdA0Xeq5WCuUGumoSleu9ykFy7VCSZb1yJ7yv+RJ6R3ospoqNzd38uTJx48f1+l07biI
KiQcAAAAblqSJEXwCSypabyYmm0Uuk7bRXOCdqCGDKt36Q6bWHmldl+WsK8DrQx2+vTpu+66
Kzc3d+HChR988EE7Rg4JBwAAgJuWLMsJzMgEw0ACNTaqmqKoEvcFl2Q1MFGJ+iHFjgt+N3jz
EhRXtvWnAvmnIM2dbF379+9/8MEHzWbz8uXLX3vttfZdzQwSDgAAADczj8fTVz+1i35AQzkH
SZI1UoFDqtbSof1D7xdEj0Uoa6RCl2Qpd2be+J0cZWVlc+fOFUVxw4YNTzzxRHuHA4NGAQAA
3NQwxm63e7BpFkdp8+2nPbL/7AySJJ2CJZrrnmYaj2WywHG6yTrLXZl52sOx5KDghNw6YmJi
3nnnnYSEhOHDh7d3LAhBwgEAAOCmpyiKy+XqqblHz0SY3QW1QolTqhUVD0EQHKllGbYff3cM
16vYcbHSnRNIhTIWbWJVJ+5Gv6oyY8aM9g7hV5BwAAAAuPlhjD0eTxw1uIt+OEVReZ4jGGEC
EV01o6qV3Es131+o3iNhIfAKnVItqSEbWhAM1AUJBwAAgFuFLMvqvNBoor+6kKjb7S6TrpQ6
rzS3KlFxEwQBCUfgIOEAAADQztRZqeoNPtTVMBVFkWXZd6lsbxk1UcAYK4oiSZLvKV+9AYp3
pX+1EkEQfOvxK4MQMngiaZKVFG/3BqGjQ0O4WI7UMSQvY0lUXDax0iKUy/jXJb8o4sY6gebk
5GzevPmVV165Ye9ycGO1FwAAgFsKQRAsy9I0fcnxjU2olJCHIBGhMHomXEeHJfDDBUFACLEs
WyD+5BBq7GKVoLgRQizJ65lIHR3ShRkuCAJJkhqN5opzT42jqEYodss2EpEaKiScTxgWMk8U
RZfLRVGURqO55Pimxl5YIxR7FAeFaB0TFs51GRB5b6Urp8h+SU+Hx+t6unCt2ZNfKlQKspMm
WZ4yRHBdEwyDKlxZZc6ratrBUbob5/71J0+enDNnjtlsHjVq1IQJE9o7nPpBwgEAAKB9qJ0Z
Z207ix0XXbIV/XIjU3XtcIbUmLX5w8LmIoSO12wrcV6qO8GEo/Q12uKh4bMvOv5TZD53ufYH
tR5fJ81f9Qq5c2zk/7tg/U9OxdEM637fegiEIjRdXYolRX/bqJh55e6MS9Y9+Y7Tsv94jh/C
uYQUwx1pIWOzrEfcst3IRCmK0r4rW6j27NmzcOFCQRDeeOONGzbbQJBwAAAAaBc0TRfjY4Xm
8w1NDBEVV6HzTIl4LkE7yC3b6mYbCCGPbNcxoWdsXx6v/tzszq93REWtUFwrlBw0rzMLBfn2
k371YIQ8sl1QnJcs3wmKo7N2ULVQUCfbQAghsye/Wvish3Fsj5AJJc5LKZpxLper3ROObdu2
PfPMMyRJfvjhh/fff3/7BtO49k/NAAAA3GpIkuQ4Lt9+ppFpqOqt1PLtJ4+bd2hYfQgbW7dM
gn6ARLr2Vfw9z3GcIOsfvdBFN8DARn5b9ubZ2t0RfCJH6fwKOKSaKD6ZptiDVR+frN7RP/R+
jvQvo8JYuWz5IcO+t3fopLp3jm17b7755pNPPmkwGHbt2nWDZxsIEg4AAABtj2XZ47Vbze78
Rsqoy417ZEetUJJlO9RJ35cgrjln0STb3XT7uZqvy91XZSw6JLNfAYQQS2qTDaNO1XxlEyvN
noIS98VwPqG+vWGrWK5g6ZL1uzLPlWTTqEYCK3adr/Bk3ghjM6Ojozt37vyf//xn6NCh7R1L
0yDhAAAA0KZIkswTD5c4LzVeplYuckg16sMC5+kaMT+cuyZX6GoYluU4cNn6g/pQVNwebPNL
A7roB5R7Moqc59SH5e6rHsWqoY2+ZXR0aIU7S1TcOiqUJKhzlq/jNL146poyKgIRRjYqiu1e
aD/PMEy75xyPPPLIgQMHUlJS2jeMAEHCAQAAoE3RNG0RykTF3UgZgiA8sg3jn6eBYKyUuq/4
3Wg+WpOc6ziuoJ/vt44RlhQRXZsExPCpuY5j3oeC4nLKtXom/NcdIcRRertUJcgOhCgdHeaW
LeXujCi+m19IHKUN4ztHsz1kWbZ4yq86f7gR7t+m1+vbO4RAwaBRAAAAbYqiKKtQ0XgZgiA8
stN3S5U7t7/pfoQIhDBCiESknokodl3wLSNjkUCE90avLKkjCbLCneFbxiGZw9mkX4MhORE7
3bINIyQoTopgeNJoEUs66fpVC/kKlgmCpAiGJbVhTIK68of6QotQTurgR3szQMIBAACgTREE
ISj1TDnxKyNjyXeLW7YSiKJJVlI8CCGeNha4TtmlKt8yGCm+d4TlaZ2CZJds8y0jKC7K59xH
EbSMRW+OImPRJYsOqTqMSYhhe3kXGcMYq5N1fepxkiTZlktx5OTkJCUltft1nBaD7AwAAEDQ
EQRBkqR3nVAFy/WW8UJq9uBDwqJFLuFIrZY2aWkTT+kRQoLivLYOjBAiCYqhOJpkGZKXsOBN
JlQylgiCZCmtjgnT0iE0ydQNRlBcJKJkWZYkSZIkvzVPvfW0pCFa6ptvvhkzZsybb77Zljtt
XdDDAQAAIFjU9cjVJclz3YcRwkmaUTRNc7TGIf18IxJ1+quai5jFXKSgcDaJIAgTG20TK0XZ
gxCiSTacT0jWjwpjO1cJ2QihKLZ7J23fWE1ameuKetM1ltSY2JgQphNJUC65FiHCwEZpqRA9
E+6UatWsQk+Hx2p6amhjon5QtZiPEBHOJihY1lCmIudZzy/pi4YyNj7EBCHEkHybTYvdunXr
s88+S5JkWlpa2+wxGCDhAAAAEBQMwzAMc9HxH7O1wCpWCIoTY3yO/CYtZJwH2R2o3EDFqtlG
sfucXap0SrUS9iBE5KETJiaGIulwrotLtiGENZSRIpkse/p/Sld6ZBtBEDxpeKjLXw10BKXt
bZeqCERxlNYp1RS6TjukalkRCQJxpD5RO9hAR9MEKytCOJdIk5xTrrls/d7syRcVF0GQHKUz
MjEmJqZXyGSzJz/fcRIhZGRi3bK98XenpUMURQn2BQ6M8VtvvfXWW2+FhoZu3rx52LBhQd1d
UEHCAQAAoPVxHJcrpudbTtV6Sny3i4q71HlFT4df8uRLnEdLhRbazljEMvVZ9fQtYcEmVShI
Ngv53fQjPbI9y3Gol3FShm2/S7YghBBGDrk2y3aQp4xX7T8m60fZpKpC1xlZEQlEqhc7MEYu
2VbkOhvCxNQIBQnaQQ65usB+SkOFCIpLUFwIIYwVl2TzyI4Kd2aVOzdW07OHcVyWLT2GT611
l6CGUQRjYCJkWabpIJ5GJUl6/vnnt2zZ0rlz5x07dnSU6a8NgTEcAAAAWhnLslnCviu1+/yy
DVWNUBzL9QrnE4pd54tcZ/VMBFnnzqsSFjhSH8YmVHlyi13nTUxMvKZPofO0b5ks+6HO2gGd
NP3K3VfL3FcYgqcIxjtLVpXvOJGsv62LdoBZyC9xXaRIjibZOkNWMYEIs5CfbT/skmtHRf4m
nOlqEcobeYMx2u6J7Mhgjxj9+uuvt2zZ0rdv32+//bajZxsIEg4AAACti6KoAulItuVIvXc/
QQhJiqdSyO6qGyoozgp3lke2hbP+q38qWNHSIRRBl7gu2sSqNOOdHsVeK16TvpS5M0xMbHfD
HaWuy3axikQUTXJ+4ypKXJdi+LTOmv6l7ssidmtIo6yICr4mUcAYI0SQBOWSLRWerFi+J0Ww
GDeYTGhoU5QmWb2NbVBNnTr1nXfe2b17d1RUVLD31QYg4QAAANCaWJYtdV6pe9dWL4IgqoQc
GUuDQ2eQBFPhyWIpDUdes4AVRTBaKtQs5FME3S/0Pp7Ul7gusqTWt4yJiXHLFg0VMiDsAZIg
XYqVIXjy2tXNYzQ9asUSPRPZ0zhBT4djpBB17rmCEcJIIRHFk4YBIVNFxdVJ25tC9S/qxZKa
bsbhXajhslzPRJtWN3/+/A60tFfjIOEAAADQaiiKyvEcrHBnN1KGJMkyz+WDlR9pqJDRkf/H
k0abVGlgIn3L6Olwh2wWFOeI8EcSdUMOVn1c6ckyMTG+ZZJ0w7Lsh74v/2s33ahREQsITIrY
zZC8b5kU/W1X7fuPVP9jSNis/iEPOKRqBcvstWUQQhijUDZ+fPQSCQu7ipdmOn5MMA6uG7mR
jUoLHZfMjm2D7o2bDyQcAAAAWg1FURahrN5lNrxIknRI1R7Fcahqo1OuHh/9VDfdiFi+B/lL
pwKBiGg+JZ7vMzH6OYKgD1VtRAh7FKeRuebKQry2T6UnW8KeHys/0FIhd8e93F0/OoLr6i1A
E2ySbphbtumpsCNVn/KkYVLMC0n6oWFsl18DJuhYTY/h4XPHRT1d6ck+Uf2FiN0V7qsJ+v6/
BkzQIVxcsmnkxKgXEqhRHo+ndRrrFgOzVAAAALQaNZlovAxBEB7FhhCSsXi65p8hTFx34+jb
IxYl6Ya5FauMZZ4ydNePPl2780T152XuDIQQTbAUw4SxXSSdKP+y6kYM3yNd/MglWWy46vvy
NZ21/Xoa7xwZ8WiVJ88tW0mC0jORDKmxSZWV7my3bMu2H+miHdDDOH5w6IxqT6FLsdAEy5F6
jHC5+8qPFe/bJDNCiEasWSiM0/QeEH6fqLhJgmZILpEbKUmS0+kM3tobGzZscDgcTz75ZJDq
b3eQcAAAAGg1BEE0uWQWQRCS8usliVqx5Jh5WyTbLdd2TEQugiAFya2nIw6ZN9pFs1pGwoJN
rKwWCgTJJWMRIURRfLWQXy0USPjnFccLnWfLPVcrPDluyc6TeoywngmP0aQWOs6oBTDC+c5T
lUJ2km6EVShhSR1Gsku2WsVK31VNMUJOqQZjHE8MJWhCXdfc6fRb0rQ1YYxXrVq1Zs2a8PDw
efPmhYaGBm9f7QgSDgAAAC1HkiRFUep65BhjkiTJBoZb+iKuHdpJIpKh+HC+i4xEAlEC7dBQ
BhpxvmW0dEiy4bZItpt643hBcRIExdNGb1KCEOJJQySbRLK0hjbJWKQJjiW1JEEoPt0SBCIl
xWUWChsJjyIZhFDbDAuVJOm555777LPPunTpsmPHjps120CQcAAAAGgZmqZZls3xpNs9ZkF2
ylhkSL6Lvp+G1dMyLctyQ1cfMMY0+XMyQRKkiYkJ55I6a/qXuS9bxDKEMU8ZNJQp1Ti6wHGq
SsjT0xF3xb7cVTcix3Gk0HXWJdcihLRUaCdtv7ldPsyypx+t3owQNSxsdqJuSJUn1yzkVbly
CIIMYeJMbEzfkHvL3Vcr3FnqgmA0yXk7RRqio8LbZtlyh8Px29/+du/evT179ty+fXtsbGwb
7LS9QMIBAACgeQiC4Hk+y72vxHy52lOk+NzGzC3bRMJRLmTEcD3qvecZQghjrKFMFlTGktpo
Ptmt2ATFca7233vL31Pnq2KMMMIe2YEIYkzU74eGzblg+e+mvPlFzjMi/nXAZoJ2iI4OSdIN
n5+4QcHKZet3u0v+WO0pEHyu6dwXv8ItW3nKmGK4vcB5yilZdFSop6lly2M03b23oQ8em812
3333XbhwYdy4cRs3btTpdMHeY/uChAMAAEAzEASh0WjO2nbm2o7XvWNqrVAap+8uyK485zET
G2ui4utemFAURUuFamlTJNe1SsitdGffFrmwyHXet0yJ80Ka6U6W0g0Pn/+f0pXHzJ+RBOV3
31ebVI6Qcrx6q4Q9CdrBV2w/mD35yrUhlbguRHBdD1auj9b0SNINK3Se0dJh1Z6CRt5gCBMX
Sndug6koBoNh+PDhvXv3Xr16NcMwwd5du4NpsQAAAJqB5/kztq+yrD/Ve392l2QhFDrZMFKQ
XTWeYqtSQpL+JxpZliOYrp21Ayo8WRXurCg+JYJNyrKn+5YpcJ2N5JLvin35y6Lnj5k/owiG
QKTfbNtasdRAR8Vr+x0xf7qvYu3wsHlGJtavzBXrvli+ZySXXOa6XOG52k0/kkJ04zdmGxT2
UC/93aLYxGWXVrFy5cp33333Vsg2ECQcAAAAAscwzFXX97m2Ewg1OMShyHGhu35snKanpHis
QnndhAP9MjPWJlZoKNPg0BlXbPt+vivbLxQsddOPOFS18ZLlW4yUX2aRXLNTjGUtHVojFNkl
c6b9YKHzzICQ+/3Cskvmq/Yfh4bN5iljjVDklGs5ytDIG+xlmjg5+iWHo/5F2VudOt62bfbV
7iDhAAAAECiGYYqdF5X6+ja83LItz3YizTQhTtPTLdvNUg5FXTNvhaKoKiFb7dsYG/l4jVCc
Yd3rV8ntkb8rcJ46Zv5MT0cwpEbBMkKK3/yXGL6HXaqq8uQY6Eia4M5a/q2nI2M1PfyqOl/z
H6dcPTbq/0Vy3UpdF2UsaClTvZH3NE0YEPKA0+lsgwEctyBIOAAAAASEoqhM176a+m4A66fG
U1zjKh0e/kivkEmyLPn9iKcoyq3YQtkuw8Pmmdj4ItdZdRqqrwEhDxY5z1YLBSJ26+lwntLj
OpNpw9mEWrHEKdXKWDTQkRjJpe6LXbQD/KoiCeqq7Uc9FT4i/NEoPsUj20K5zn5ljEzkuOgn
fpOwuTs7ye1uYh2RlsEY//TTT8GouaOAQaMAAAACQlGU1VPeyMUUXzWeYrdki9f3ieV7iNjt
EV0e2YmxwpB8iDYqWpvilqznLd/UCkWxmp5GJsohVTvkalFxIYRpgo/VpH1X/g5JUC7JIhBO
DW3iSaOMRI/sUG9ATyFaz0QWuE4TBOGQqmmS01AhVrGir+meK7Z9MhYQIhiC11IhWjpEwfK+
8rXx2r4DQ6aTBKlgbGSi3ZKVIlkdFR6rSYtgk/oY7rXZbEEauiEIwpNPPrlr165PPvlkypQp
wdjFjQ8SDgAAAAEhSbKhO87XyyVbsyyHtXTIwIip0fpeGGN1cTCNRrOj6MlTNbvUSzM22wEj
E2ViYkOYOIpkSURKisSRhlqxWMICQkjBsii6GVKjo0I5SkciCiNEEyyJSLdsVRceFRWXqLjN
lEnPREawXWmCwUiRseiWHWZPvlt2IISy7UfyHSeHhD08rdPbd4T/nxokxliWZY/HU1tb2/pN
hhBCyOFw/OY3v9m3b9+AAQOGDBkSpL3c+CDhAAAA0AQ1UUAIqfcxqacAIkiClutbUMsp1dZ4
SkLpFEmSvAlHsfOC70AQq1hhFSsQQjTFUYjSEKEIIZd0zTBSUXG7CbugOAlEIIQ0VIhdqhIV
38mr2CnVSNhT5ckWlfrjlLBQ4DyNMa6pqWleE7RUeXn5rFmzzp8/P2bMmE2bNt0095pvAUg4
AAAA1IOiKJqmfadRkCQZo+lhE81qKkAgIoSLC2Xj9UwEQ3IIEQqSPbK91lNa7SlQp54SiAzj
O0VpuvIU77t2Z3fD7bViiTozhSU1vUwTO2n7hzBxDMkjRMiKQBNML9PEY9U71Nu8kQQTwsSF
svEMwRPEz0NHTWx8BJdoFn5de4OnDLIiNJRtqDR0SNusIooQysjImDlzZlFR0cyZM2+RxTYa
AQkHAACAa5AkyXFcjudgjb3YIpR5FIeCJZpgdWwISZFx+u6KjGqFklhtml2pKHadq7LmumWr
jCWW1BqYiEg+uWfoBLM73yZWxel6WqTiC9b/eASPILswUhiSN2kiGVIzLvr/5dqPMiTf2zSl
0pOVaTtQ5r7slGtkJGnJsFGeq2Fswt2xL2fY9pe5r4SxnUXssYoVDtksKR6ECIbkJMVtZGJM
TIzZk18jFiGETEys89rptXWFMPFtlnBs2rSpqKjo+eeff+GFF9pmjzcySDgAAAD8iqZpjuOO
1W4ucVyWfC6geJDDKdfaUZlTqh0ePm9o5MN7K97Lth3xvcjiki0WsbTIeT7bdrhf6L29wicc
rfqs2HUuluvtnWjqkR0eZC0VL9iEynvil0uKO73qo8vWvRj9umCXFZVn2Q/apCqXZBkWPifV
MGZ/5d8tYglGyNuZISgOs1AgKi5EEFFcMk8by1xX4jS9Kz2Zjb/BOE3PNpv1+uqrr44fP/7O
O+9sm93d4GBaLAAAgJ9RFFWMj+2rfLfAflaqM1wDY2yi4qO4bm7FurPkpRqxEKF6bpWCEJKR
cN769bHqrZFcVx0d4XdHFUmSOvH9Uo1jyl1XDps32iVz3RpKXJd0VLhbsaVXbbBK5b2Nd5GI
xviaelyyhSN1DtFc4DzJkfpkw23RfGqe40Qjb7CTtu/t4YtcLldAzXHdGIaBbMMLEg4AAAAI
IUQQBMdxRY7z5oZvNcIR+l4hk8/U/jPTdtAiFpu4eu5uylIammLLXVePV2+3yKX9Q6b6JRwY
YxMTG811P1D1YYb1RwKhSL6rXyWVnmwdHRrJJVV78g5WfqRnInoYx2Pkl3DUEgSpZ8JFxV3i
utjPdB9FsI0Ez5Dc4LCHRFFsm/vOAz/BvaSCMf7yyy9/+OGHqqoqnU7Xt2/f+fPnR0ZGqs+e
OHFi8+bNRUVFJpNpwoQJs2bNunVWeAUAgBsNy7Ln7f+qcOU0UiZWk5bnOGEW8glEmD35PGXU
UAaXbPMto2ciasUit2KnCCbLdiiKTTEwUTaxwluAQGQsn3a0ZougODGSS91XEnSDLEKpR/n1
FicUwdjECj0dEcWnlLmvnKz+4raIBdn2w075mtkltWJJOJsgYynVMEZHh0uKhyF5Ualn5S4S
UXdELhoZusBiaWKQBwiS4PZw7Ny5c9u2bdOnT1+7du1zzz2Xk5OzatUq9amMjIyVK1f27Nlz
9erVc+fO3blz52effRbUYAAAADSEIAiaposdFxspw1E6RClZ1kMa0sRTekQgq1imZUJ8yzAU
LyPBIpYxJMtTWrdkK3KejdZ08y0TrulU4cm8aPkfS+r0TKSouGxipYmN8y1jYmLtcnWmPT2a
T+2k6VflyTYLeV31I/xCEhWXQ6q5I+KxXsYp35SuqhWL6640ihDSUKZJsc9PinrJarX6dbe0
FrvdPnPmzK+//joYld8cgtvDcenSpZ49e06YMAEhFBsbe/fdd69bt04URYZhdu7cGR8fv2jR
IoRQQkJCaWnp7t27H3roIY7jghoSAACAuiiKynB+75CqGykTwsZZhDJ1LitHGkmCEhU3S2op
gpZ9JqYKsoMltRrShLGCMS5zZfQ23uVbJoSLzXIeFBW3jAUtFWJiYwXsDGO6VKBM7zKmRiba
LVsJRJa4L0ZxKRo6xCqVJ2oHX7D81xuPjg7vqhueZphgYmNzbIcjuK4WsbSLdmC2/civMTMx
yYbbUvR39DdOs1qtQbqYUlxcfP/991++fFmv199zzz3B2MVNILgJR58+fbZv337lypUePXrU
1NSkp6cPHDhQnYh8+fLl0aNHe0sOHDhwx44dOTk5aWlpQQ0JAABAXSRJ2t31DN70paFNxe4z
6v+xghlCS5CkhIVITTdBcShYoQhaR4dVCwU8afR2JFjE8lqpmKcMDunnqyFaOrTSk40QUrBi
l6oZktdQRg1lStaPFBQnRpgm2EguJd95XFCcdqmy2p0fpUkJZeIHhk5nSK2a8Wgok54O5ylD
jv2nQxWbCQKFcfFGOnpI2IwQNs4t20iC1FAhw0LnYYzdbnfwFhK9ePHilClTCgsLZ82atXr1
6iDt5SYQ3IRj6tSpkiT94Q9/QAjJsjxw4MCXXnoJIYQxrq2tDQ0N9ZZU/19d/WtynZ6e/sor
r3gfvvXWWwMHDgxSnFqtNkg1B4lOp9PpdO0dRfN0uEbWarUdLmaNRtPeITQPNHIbCLyRCUFp
/N3pOKPkcdH0NScOTMhhXCffLWYxjyIp3yv2InLptSGK+PPQCpbSuGSrT+YaZgAAIABJREFU
d8yehN02yS1gp1u2K0giEOHGHgm7LGKpoDgRQpjA5e6rNUJRD+N4p1yjrjRaKxRm2w9axHKE
EE2TCCGLVIrcOJpfGcV1v+Z9EUTwjrT9+/c/+OCDFovllVdeWbFiRTB2ESQ8z7d6nY13IAU3
4Th06NDOnTsXLVqUlpZWVVX1ySefvPnmm8uWLQvktTRNGwwG70OKooJx4Y0kSYRQkC7pBQNB
EOrawG22cM31U2OGRg4qaOQ20HEbGSHUUDv7DtXHyP/joAhWT4cxpIYiGEkRWFJHINL/5m34
58q9+/p567Wu/az9nyUQQajxYgKhBmcPKFjKd5xwyQ32Vai7aLPP6NChQ1OmTFEU5eOPP37k
kUc6yrERvCO58a9zcBOODRs2jBs3bvLkyQihhIQEvV7//PPPZ2Rk9OjRIyQkxHcpe/X/YWFh
3i3Dhw/fvXu396HFYgnG0vdqOt9mc7KvH8/zer3e6XQG6QbKwcDzPEEQHaiROY4zGAwul6sD
xczzPEmSTqezvQMJFDRykBAEwbIsTdOZrn2C4kSUjBSSQZru2vGyLAuCoCgKSZIMw9A0fdW5
16M4JMVDk1wkn0RhVhRFRVEwxkYuIl7fy8BEFjpPW6VyQXZwlF4jGQeGTtdQodm2Qy7JRpAE
SZAkwVQK2W7ZqmCZIhkTHUsiCmOkKDLGah5BsYQ233XKKpZhhEmCSjbcpqGMCCH19MSSPE8b
GULDklqP4kAYc6SeJngTE2cVyzyKXS2mo8ONdIxDqFVwgz+jWUYvimKbzUNJTk4eM2bMkiVL
7rjjjja7Ocv14ziOpmmHoxn34QtcREREQ08FN+HweDxqF4JKTaXVLpe0tLRTp04tWLBAferU
qVM8z3ft6j8VGwAAQIAYhmFZ9rT1y3JXpkOsJimSZVlRFCVJyrIeieS7hvNdkrSjCII4Ydle
6cp2SLXezoYKLtvIR1SKWTFcj876vjISLtr2XLX9WO2zrEUo26mLbkAIE3db1IKrtv2Z9oOy
IhiVqGzHEemX25dE8IkcobPLlQY6EmPkVqx6KhJhVOg4610ktNpTGMklZ9sPUwSrpUwIIYSR
S7bk2o+qvRtqhkEgxJA8R+ocsllSpBgu1SpVNJJtIIQi+W5t2c3Asuznn39uNBpv8DT0BhHc
hGPEiBHffvttYmJijx49zGbzxo0bo6Ojk5OTEUIPPvjgiy+++OGHH06ePDknJ2fXrl1Tp06F
KSoAANAyLMvmS4dzK45ZhPK6zzql2nz7qWoxz6FU0libbzuJr72uYRXKkwyDaJKN1aXapIpD
5g2V7ly/SuxSpUOqvmTZk8MfHhI2myToy9YfHHK15HOzNLto1vORDqmaImgZy5Li6aobWeXJ
8703bKnrYpymF0PyGsqkzmuN0fSwSZXY52qKTawwMFFl7gwNZdTTkQ6purN2YLnraiMtQCIy
lu8hivXcsRbcCIKbcCxcuNBoNG7fvr26ulqn0/Xs2XP+/PlqVpGamvryyy9v2bJlz549JpPp
gQcemD17dlCDAQCAmxXDMPnS4YzaH12ytaEyFEWVei5m2g8MCpveWd+3wH7W91kZi1XuvLHR
j+c5jn1X/raCZZqkJeWae46IischVYdziQXO0zbJPD7qSY7Un67Z6VvGLdsk7Inl08xCnku2
mpi4RN3gCzV7fMvk2U/1NN3Z13TvBes3Tqmapwx6OqLAecq3jEUsC+cSjEy0RSxTkNJVNyJB
N/i7ksbmgCQahg4yzbTZbI2UAe0ouAkHx3Hz58+fP39+vc8OGTJkyJAhQQ0AAABueuq4jdyK
441kGwRB2JTSWqFEVDxnanYPi5ijZyLsYpVvGYqkRcV1unaXS7aSBMWSGoWQlWuHAZqFvM6a
/gYmqlrIP2/576SYF87V/vfaXSFRcYUwcVVCLkZ4QOhUu1RZKxb5FlCwlO881VU/Msue7ias
0VwPq1gmyNeM5pGxVOXJi+KSXbKFQGRP08RS1wW33GAyYWSj0ozj3W538C6pFBcX5+XljRo1
Kkj13/TgXioAANCxsSx7xvqVRShrpAxFUS7ZKioehJBdMhc6z8brevmVSTIOvWTdw1MGExOr
YFnGIkUwfmVExVXuyYjmukdy3Urdl6/afrw9csE1OyJoLR1aIxbFa/rcHrGQJvjj1TsI8ppz
DUtp7GJViev8HZGLehjGK0iu9GTXnZpSIxS7ZGuyftS4qP9nl6qu2g9wVP3LARjZqOER83pq
7vZ4PI00wvW4dOnSlClT5s6dW1hYGKRd3PQg4QAAgI6NoqhyV1bjZQiCcEq/zibNd5yUCbfv
+Tuc71zmvnyi5vMy1+VIrls0n4oQQRIUcU0lCGPFIzsQIhO0g3lKn2HfG6fpSaFf8xItHSYp
HlFx9zCMHxg6rcKd6VIs5LX3yTIwkRVCZrb9pyguZXj4/BA2niDIupNhSURo6ZDBoTNTDWOL
XefsYhVPG+qUIbsaht8eubCfdlqQpl0ghNLT0++9996ysrLFixd37tw5SHu56QX3kgoAAICg
oigq233A7+KIH5IkzWKe79BOj2y3iuVGJrpS/vlWbTHa7pWeLKdkQQiJrrMRbLcE7SC3bLP/
f/beO0yu4sz3r3RCn849PXk0QdIo54QQIoPBgMEEY5xtvGC8fta/a/vad73efZbdx/b1Oq7X
Xq/ta2BtWIwzFsEyQQIhoYgkFEejGU3OofPJVfX744jWTE/QSGhAA/X5S9P9dp06p1t9vl31
vt/XHbSYzriDoaxgTcNRH46k3d5u83CRXEegotPUuqJ7jqe3uNxScbDOv65IrlZw6FR214HE
k4vD75mlLU86PWmrz6BpxqmC/LMD6xFEBKr7hn+LIbkk9pF5gSs6jdd7zYasO8w51Ui0RJlb
5VtR5VvWlN3ekt23PvqJNO2mjLZm93k7R34SKVLqytUFq8P3mKY5fWrj6aeffuCBByil3/ve
9z72sY9N01HeDQjBIRAIBDMYCKHpZvkYK60CKC+s3ci5w1Fcnf/TRyIZ43R5i0X1LuOwj4SL
5boStR4ACAHigDrMzLoD/VazZwCquwmNxDhnl8X/pty3GAHicLNUrW9Mv7Rt8Be6mwAA9JoN
Fb5Fa2J3LwnehIEMAXK5VRNY/WL/D/YN/85rD9uY3bYweH1d4JKVkTslpCKALKrn6FCP0fCX
7m9ZNAcAaM8dmBe64o7K/0uLqOewwDlnjNm2Pa2uGz//+c//6Z/+yefz/fKXv7z22mun70Dv
BoTgEAgEghkMhNDlZ0lcgBCOrEr1sJlBpDNOBBJSC7rMG25qCLQCAE2ahRBxziAELrfzThgc
gJw7nKWDSafzme6vI0gYd68p/Xxjdpv+RtsUDliXcURLRwdJu+tSCCHnrNy3oCm7I9+M3mX2
4dQzzbntMvAjSCBELrXBaFxmNqZfPhJ8popd9pY5bdi2/eSTT8bj8V//+tfLli17aw76DkYI
DoFAIHizYIwJIQihkT++Xdedpt6kI+GcEyiPfERCalSpDMmlKgmoRLOpabm6avlPsV35NA4I
gYx9EHFZlj1LcgZsFQfgaNdxCJEnLzg/fY+HY1ItFKTpNAUA8DSNwwwJFTZkwZBwzsEb1uku
txUUGBkA3xiZAQrB+HpCQdqiwHvT6QkrcS44siw/9thjuVxO5G1cEITgEAgEgvMHYyzLcrP1
cjLbk3WHHGZCACTkC0jxiFw+23e5bdvTKjs45wr2AwAB4BiScm1BiW9Ol3n4VG5Hjg0zYENO
NBwNK2Ub4p/oMRqastsdYEAACZJb9F3NuZ2MuwiS6sDKACk+fdt/Y4cGAeKO2YsZCUGShqPt
uYP5RwyaCpL46BgZnRYcp7GZHpJKRsZAiGQUYJTBCfuogIAU95TcuVyeN0ssFhvZc0PwZhCC
QyAQCM4TWZbb3Z09iYZ+s7nAcnvQbMWQ9PuayrR5VdIl02d/SSmt91/dRHa63JoTWj/ktG7t
//Gw3QG8IhOEGWOMMWQgDuii4PXriz+6c+iXw3abhqOvZX+fdU9nmx5JPrsydruMfBbNQYgg
BwgRDCWXj8qQgKNrG2u0tYvD7/1j11fzjwxYzbO0FUdSm/OPhKTSYnnOyPZPw2ZnpW/pyBgM
pbNloYByddFbsGIkmD5EWaxAIBCcD7IstzjbTqS29RqN4zb4oNzt1o83pra30R2yLI8NuFC4
rluuLZgXvrzd2L9n6Nee2iiEA91N7h5+rCH9wsrI7QuC1xk0mVcbAIDGzLYyZcHS8M0MMMYp
gEBBfsqd/GYKAIBzgCBGAOcfWRa+edhqM91s/pFe40RYKo8rpxtjQQCiclXBskRn7lCRUlMk
z8rHEKhM3mhUQmqFtni6bcttuzB3RHABEYJDIBAIzhlCSLu782T61ZHmFuOSdYaaUjs76C6M
8eSR543jOGtid/dYR48k/zI2OdSDcyZhxebmweSmTuP1y+P3nci8PDKAAbpv+HdLQu8NkjgH
HAEsI21cZ8+8OcecwIarSz7/565/GvmsxbIt2d3LwjcjiAEAUWVWlbq8QCgk7R4/LFkdu9vb
wCFIUVFocsGxOHzDssBt0+frBQB45ZVX1q1bd/To0ek7xLscITgEAoHgnJFluSN32HCnVJCZ
c4e79YbpW+RACJ3IbunUX4dwwq90CBEESEF+DMmAeapd3x8gRQUxOwYfjshVN5b9vYI0jUQd
ZjBQKF+8RQ4MpbhSc3Xx55oyrzRlXy2IacxuU1BgReR2P4mWKvNc1x0rJo4mnlseev+a2N0Y
EhmpI9dRxlLjX3VT2T9Oa0fW3//+9/fcc8/AwEBzc/P0HeVdjhAcAoFAcG4QQk7ozw+ZrVN/
Sb/R1GS+RMi0pM1JktSjn/Cj4iJlloTG77kNIcy5QxjKcwKXYkT2Jp6Y49/gLULkYYA+3vq5
BaHr7qz6th9HdTrB4g0HNf7Vt5Z/vcq3/Fctnx77vMusPcOPLwnfcH3pF0vkea47zqKL7iYP
Dm26ofT/XFZ8rwzDk6xuzAtd8ZHqnxmGMe44F4Sf//znn/vc5yRJevTRR2+99dZpOopAJI0K
BALBuUEIGc51nNVraySM06TdNTuAL/hdE0KIEEpYnZTSMK5CCjZoKucmKXNGxlg8p5GiiFQu
QR8AQKdJDllMrhm0TuXDfDhcE1jTmtuzOnq3n8SPp58/knpWd5MjzzOu1K6M3FGtrVwRuX1f
4olFkRtOZF62aHZECChW5iyL3LImcg+l9Gh6czc8nrC6Ru/1QD+JhpVyDcRvLvnnErn+RHpr
l3GEjmhOiwAq9s1ZGL720si9uq5PU3YFpfRrX/vaQw89VFpa+vjjjwuzjWlFCA6BQCA4NxBC
GWfgXF+VtgemI40DY9yQe86z46SU+mFpSK6AChxyWih3AOQAQAwkALlB08NWp0FTKgpG5QoI
4JXFD7TkdnvOGUFSHJJKDTe9f+jJLT3/eW3p52+v/NaS0E1JtyvrDtrM9KFASCq7rOjTnPNc
Ljc0NLRYu21V+O5D6U1JpzPrDrnc9uFQWCq/JPoxSmk6nXZdt066Yl7Rtaes7TlnyGYG466E
ND+JzNOudV03m81yzpf57lwT/tDh7FNJu8tkGc6ZgoMRqXxF6A7btjOZzPSVwn7rW9966KGH
5s2b98QTTwizjelGCA6BQCA4NyCENjPPHjcam+lwEpeJNzWZM43dOefeIkoEVSOEJEny/uyx
D/cYx70Yk2V6zBNlRmOFKiOOAzhuM2PQbGlIbc1nib7Y9x8v9v3HrbP+5fLoA5xzzxyMUppK
pfKLNLqu67o+R75W9skQQgghY8yLydevOo7jOE4FWoMVnHdF45zrup5P7DAMwzCMOdK1JEAk
SUIIWZZFKU0mz5KQ++a5//77Ozs7v/nNb0aj0ek+lkAIDoFAIDgL3raFh5eHwcerg/VuuuCN
e2rBs1PcgvGO5d3gp+hzNe7IjLH8ZAAAIzu3eTjcMlk2RxMSUx1u5tzBsTUpfUbjIu1G13UR
Ql7jkrFbQt6D3rl7Ex577p4XyORn4UkTxhghxDCMyYMvFMXFxf/1X//11hxLIASHQCAQTAjG
WJIkjHGzsY2aNgccA3mhdJ0qB1zb8m6iEEKMMYQw6XZS5gAAMSQRqcpbEsjffSWkTl75Scjp
3/cnja0OtRDEElJnaxsppd6deNxXcc4nShQdNTg6UyNDoByVq2Zpy8rUBRKWbaYrKKAgv4z8
3caxxvTLFs3N0pbfUPHlUrX+UOppi+o2z6kwIGP/stitrut6/uLeCgrGuMXabjOTcZdARUJq
jbzedd3p9swQzDiE4BAIBIJxgBAqitLmvDqQbhm2OnJukhAMAHBdl3LH5MkM7wmTSgBAinbp
VtKkWZedcYlIoE4VB30kHCaV3qpAgMQmEg0IIUVRmsytvdmTSavb68UKAIAANkk7i9TqNeF7
HMcZN3GSMabiIIbS2H6weTjnMvJDADngEbksJtdm3AEG2Obef2vN7fNiZKxVqEvmB6+4rux/
FatzytT5W/t//LvOLW25vfn9owAp2hP49aLQ9Rti93oaaH/qt4NWW8Ye4G80QJGQr0M5WOKr
n69dZ5rmW+xELriYEYJDIBAICoEQqqp6VH+mJb1nZIaEx6DZGiJlpzK7ZU3T3eGk3ctY4Q6L
wyyHWTk36chmXJrjujSiVI7rzI0xVlV1d+JXXfrRAsdSDnjG6c84/f1G0+zQJfXqNSMNwj0Y
Y3XaZW3KgSGzbaLToZQWK3P7yEkNhxUS6ND3Y6hAgDr1w/kYm+qtuT1duQP/sHhfa27f7zu/
eDKznSB55KJM1h06lHz6SPIvzdmdH6v5WWeu4VRmz5gTN/qNUwNma8LqvDT6Kcuypq+c9Vz5
wx/+sGzZsvr6+rd7Iu9ShA+HQCAQFKKq6qHsnxpTr4xVGwCAQbOtxre2JrCy12joNo6CiZMz
GHeTVne/c7JYq17kv3Hsrddb29g29F8duUPj+qN76G6yIbH1hPmcooyze+I4TrlvPpz0+5xS
WuFbqGB/e+5AyulbFHpPu35gbF/7B+Y+eSq768mef2jOvorh+L9IOaR7hv/nhydvHHSalsVu
Gj+Gs67c0a2DP1IUBaGL4kbz7//+75/97Gfvu+++yTe2BNPHRfE5EAgEgosHWZYbjOdaMnsn
sr90mMEArdKWZ9wBm+kGS0I0YfkJB9xyMzG1atxsSkVR9qYe6zfO7m7pcrsptbPF2T7WPcxx
nPna9ZX+RZO8nDEWV2YP2W0mzdT518WVuuPp5wtiNsY/naPDz/d/f9BsYYBBiMZKKQgA54wD
1pjZ9nryz4ui1wTIhM1Uh8y2nYn/HlckvZVQSv/+7//+G9/4RklJyY9+9KPpqBUSTAUhOAQC
geAMEEJJkjqyh+gETUkAAD4Szrg9DjXXxu4hSLWZ7vDcRHcxGflXRN9PuM+rPRn5FCGk2Xq5
KzfV5h0203v04+NapJumuT76yRLf3IleizFu1/dT7tb4V62I3PZa4rdja1LeU/blltzODv0A
BBBwwLgLxp6U9wwHAIB9w7/ZOfTLS0s/Osmcu/VjJ80tkiRN6QynAdu277///oceemj+/Pmb
N29eunTp2zUTgRAcAoFAcAZCyJHsMxmnf5KYImXWgNWyZ+gJHwpfHr8vIlW5zAbjKY4ipeaS
+IeDuKwh+dLhzKaCxQlCSL/RPImyGcuA0dJkvjzWQIwxZprm5bHP1ARWjSxI8fBKbZN2d33g
8hvL/r7DONhnniiImR+8ul3ft2f4fyBAEGAOGBuzwHN6eeONdRoG+OHkMzFl1iTpgJyzPqNp
mjzdz0oikbjjjjs2bdq0du3aTZs2VVVVvS3TEHiIpFGBQCA4A8Y4aXdPHhOWy5uTOxxm7hv+
XX1g41XFf9trHks5fUNmu8WyAEAVB6LyrDJ1fo22tk9vbNZ3csCTdjfxk3yxqFdMm7R7zml6
HLCU3Vur4bH5p5RS0zRXBT8YVSqHzLak3eMAHQBOkKJhDWK2If4pApSdg49x4Nb616bd/qw7
6FCTchtD+Yri+xN2R9rphwB6JSccMMYpgvjMRhAEBQYjzfqrR9Kb64IrWjL7Jppzyu7JO4uc
08m+eSzL6u7uvvnmm3/605+qqvoWH11QgBAcAoFAcAaE0Nl6wEIF+zNuPwCAc9aY2dahv14T
WL06ercEfCnaDQAI4wqTppN2z5Hh55w30k51NzVySwVCeMrcYbrpc52h4aYmSsP01jmq8CW1
wcswxoSQVmsnY2yOtrHJ2Laj/+Eeo8ETEz4SjEnV5coCg53eWClTF5zK7eIAjM6BHSsRRj1i
uBmdJmJq7SSCw6K5JuPlKnTJuEU600pZWdnTTz9dVlZ2kSSuvssRgkMgEAjOACEcaacxFgIl
CNDI6hWDpk6kX0rYHQFQLiOVA3CK7R1bcuIws0BwuMw6pw5wHi6zJk97pJR6t3ZFUeYFr9R1
3XGcluyubuPYmTm7GcPNAOD1mieUuwhgk6YnqbiZCJNl/CQyeYzDLEjenlTNioqKt+W4grEI
wSEQCARn4JyjCcpBPShwAeAEyiNVCQIoTCocxzFH900dCYajEic55xidTyolRpJn3ZG3P/cU
xsgNC1VVPQ9Q79+c8ypt2ZHEZpOdnp4Ph5dF31cXWOPDYRn5bZYLSSVxtRZDmfJz6MuKoaSi
oIz888IbESQOsyyaSdm9WWdopJbCkIhiVIEQHAKBQHAGzrmC/ZM0g+WceW1Rc+5w/kGMpLPe
UBXsH2m7yTn3zMudKfeB85q5MGy1W3vbswcdZmGIFewPyWULtOu9XiSapsmyfCD1+97MibTT
a9GcjNSQXF4sz/lQ3Y8aMy8fSPz5quLP1IeuOJ5+4Wh6c9rptVhOQf4a/xo/Lrq14sFjmedP
ZrZNYgpy+pQhicnVYblCRr4T2Rdbs/sZd2WkBaR4XKutRqu69aMJqwsAgCAhSHlrBEcikRBt
2C5ahOAQCASCM1BKQ3LpoNk6SUzGHogrdYPWmRgF+c86ckguHZnEwDmvkde3yvuGzPapTAxj
nGJdOXO42De7Ob1r9Axfb8vsrw2uWha9ZV/y10d6Nx9PvcgAhRBACDkHCGAF+6Ny1drYB/9u
3qbXk3/+VeunG9IvshGLEO36gZhcnXEHFoduqPIt3zHwC4vlECQFGR0QIACogv0V6iKHWzbL
Bkjxlt4f2/TMHhOCpMa/qta/NiSVtmcPhuSSOmWDrutTOc3zhlL61a9+devWrc8++2xxcfG0
Hktwfog8GoFAIDgDpTQsl0losoqGhN1V6puP4enqUwihioOTNw0hSInKFQVZk5TSuFo3lVkR
QhK0bdjqkJFWrixK2b0FAQZNF/vqXhr88Qt9PziefoGB0QfiLobygNXcnH31xb4fZtzBVn0f
G52u0WuciMiVOXfwr33fdphxTen/p2A/GJNBCiFScaDKtyzj9nfoB6u1VQm7Y6TaAAAw7rZk
9+weetyBudmhS+Jq7XS7mxuG8clPfvKRRx7x+XyiadxFixAcAoFAcAZKaa20odK/eJKYpNUd
QMV1gbXenxqJRsisyQVHhbawVr6sQHA4jrPEf0tUqZx8ShjjhNuesLoYo/OCVwyYLWN3YdYW
39mYfemp7n9N2J0KCsAxjl0Wzc0NbBy0Wp7q/uce49iVxQ+g0d//DNBBq7lYmcuY+8rgz02a
Xl/08bGTQZBU+BannO4B61SxUletrTqa3DzutHU3sW/otxSZqyMfmFYRkEgk7rrrrs2bN69d
u/bJJ58UWaIXLUJwCAQCwShs214duieu1k4UwAFvz76+PHxrsTJbxlqARCcv+CxSqtdFPjq2
1yvn3HGcmsAqFQcneq3n2ZWyexin9aHLy5RFPbnjBTHl2oIE7Xih7wcOM0yacbk1tmF9VK7U
3USbvo8BunPoVwTK9aErCmJOZrdH5Iq6wCWcs1eHHolIlRVqofCKSpUOMwetVhWHLo/fb1G9
1zg50eRdYLfrr01r9kZ7e/tNN920Z8+eW2655Y9//GMsNqHPuuBtRwgOgUAgGAVjzLKs6sDy
Et+ciWKyzmBH9tDK2O1zgxsCsHySe2qxWlcTXGlZ1rhLII7j1EqXzQtf7p+gIwlCqNdqcJmz
IHT1kuB7m9I73TFVJPWRy5qy21NOHwCAA2CyLEFKwSJHXKkbtFtc7iCAXW4eSf9lceg9aHQM
Ze7h1LMVviVzApc5zDyReWlh6PqRARiSkFQ+ZLeG5bIbyr4Slsp39T820YkTpETlSkil15K/
HdeO/c3DOf/EJz7R1NT0wAMPPPTQQ8La6yJHJI0KBAJBIZTSCry2LrbxUPbJrtxR3U0WBCjY
H5DiK4MfWBG467Xkb7r1Y2MLYn0kXKktXh68ffIW7ZZl1cmXk4jUb7T0GicKXEAgRBqOLIpf
XyzXN6ReHmtKpqBAkMRHdmJzmeVyG0HCwOmNDD8pMmhqyG7jnEGIEMdtuddWRe6Mq7P7zeYR
xwImTR9LP7cgeK2M/Cm7Oxi60U9i+XocjUQ5p/MCV8wPXaui0IHEkxJWLZormBKCWCMRjURC
qIJSOmi24WChF/sFAUL4ox/9aOfOnffdd990jC+4sLwNXrPnRyqVmo5dQJ/PBwAwjHE6UF+c
qKoaCASy2axpTrWU7m3HMwyYQRdZUZRgMJjL5WbQnFVVRQhNdyHABWRGXGQIoSzLhJDjuc0Z
Z5BCG3COgBwgMY1EqqX13i6JJEkd7m7dTWXdIYcaAEIZqQGp2OtHb9v2VL5mMcayLLfaO7PO
oO4mHWYiiBXsV2VNg7E+o6lXb6R8nO/A6sAKIuFft//dyAd9JESA4nDDq1IpUxdCCE5mtp0+
LwABhFcWfzbldB9JbfaSQRFAEGIJKhxwBEmNtiYmV1VrqzlgHfpBmxk+HCxR6zUcUVG4M3dk
SO/wynSTbofFdMYdxhmGhCBFRr4QrshbgyCIVxTdWs5XTZ7m4qGkF2a+AAAgAElEQVQoCiEk
lysUMRctsiyHQiFd12fW/77pu8jxeHyip8QKh0AgEIwP59yyLNu2Z5OrsYJlWYYQepsjruvm
Rb9lWaVwJZEJUk/3g/XMuHRdn/ovOkqpYRjlaBVWMPKdHgdC2OHs3T/45LhSw8NHQinaOWbm
DKIzzeUlpBj0zNIIBxxwrruJAI4rKADzpSice31gKXdPZXe1IVLhW3pF/DMsyvKdUHYNPXbi
tEYBjDHGWAhVQgzzJ+4xckWHceoyCyLRFP7djhAcAoHgnQyEo+6F5zGCd/t0XdfL37SscYzP
vfTPqYzmrQqAN+7WBc96D2KMPZNQCGHOHR6rNhAifhxVccBhpow1hxZOqcAxHQPCxxh5udyK
kIr6wEY/jqXdwR7jsE5HNXahzM25Q7ZtZzKn+62oqpq1Bwvsz6eybkG5ixDyrv95vxGCmY4Q
HAKB4B0IhJAQQghBCLWYOxhgCOJa5VJKqeu6b30XMUKIt459PLeZcQoBWhy6Kb9S4t2zVVVV
FAVjfDj9FKUugnhZ6NZ6dSNBcmPqFdPNAoBm+ZdWBZaG5bIO4wDlDobS3MAGK5MqUecMWW35
TvcIoJE3dYebZETdCkHyuuhH1hd9tEZbczzzgjdOfeCKtNvXmH7p2e7/64LTCsaHQwXuqASe
W2KmhNQS35wKbaGClGZjO38Tb4Su61//+te/8pWvRCJnad0iuDgRgkMgELzTkCRJkqSjuWeG
0m1pp9+mOgccQ9JItkXkirhaW6teZlnWW/M7GyGkaVqD8dfuxJFu4+iA1epQAwD4HPlBmVpf
pS27vOgBx3EkSTqU+XNb6rW23L4+86TNdATwJumfa/yrK7WlV5V/plc/EZbLeu3jr6V+057b
P2S1OtzCkNT6166Ivl8j0ahU1W81JezTbuJ8hPeXSbN+EoEAcsAXhq69LP7phN35emrTn7u/
1qrvd5klI1+RUjvHv2Fu4PL/s2jHX3u/u2/4CQRwkJQUuKNqZ+vTNgJY5qsv1xZ0WgcPp54e
1rsdZnLAMZROStsjckVcralRN0zxjRgaGvrwhz+8f/9+WZYffPDBc3kHBBcLQnAIBIJ3FIqi
tDo72lL7E1b3yMV/yt2MM5hxBnuNxpS/d2XoA/mlhekDY+z3+19N/mL/8J+yzuCIZ7jhJluy
e1uye9v011bH7sSO9HTPv6TsvnwEAzTl9J7MbHs9uak1u/eSoo8OOM2buv7ZGLHx4SVbrIre
6TJryGkpUecpKNhvNWIojTQHS9hdlb7FfqloWeh9q6J3bB96qCG9ZZa2vDW3z+UOAMBmRo9x
vMc4vmf48UuLPn5bxdfL1HmHkptWRT4wPHymZYzruiG5GENpkpwSDwhQXXCNi8xtgz8zaLJC
Xeoy9405O2m7P2339+onMsHBZYH3n/WNaG9vv/vuu5ubm2+55ZavfvWrU7jwgosRPFOk4kRV
7G8SSZIAANNtu3sBIYTIsmzb9syaM4RwZk1YURTHcWbWnCGEM8jUeZousizLLc4rJ1LbRt/d
R8G4m7C706yrNrDmnI5+rhcZIRQIBLYM/fuuwcfG1o56SEgJy6WHUk8BgKJSVbdxpCAAQhiU
ikNS2aHkU34S8eFIn9lYEOMn0QrfkiOpZ7PuUFypVXHQYbbDLK+XCgCAcRogRXMCl83SVjzf
/4OG9IvFymyHmymn0CKdcrdNf63DeP19Ff9coswNwcqRfmWc82J1dpK2Zya+vB41gRU2zO4d
+m3GHQjLZTIIjl3GoNxNWJ05PlAdWJl/I7xdsJEX+cCBA7fffntXV9d99933wx/+0PvSvnjA
GHuf5Jn1v6/gIl9ANE2b6Clh/CUQCN4hYIzb6a7m9E6TZs4Wy7tyxw6kf6cohY6cFxBN03am
Ht439NtJOq+WavU9ZsOp7K7tQ78IyWW1b9il56HMqfIt7zUbTuV2vjL4/yp8i8vVhQUxh1JP
l6rzFoauM2m62ziikRiGhb4XGad/eeTW/Ynft+X2+kksQIoHrVMTzepY+rnfdnxxfuiasRmy
tm2XavN8JDzJiUeVSojBwcSfTZoOSkWT+L5zwNuzBw9ln5zojXjxxRff//73Dw8Pf+Mb3/jm
N7/p5dsKZijizRMIBO8QZFnuN5pzbmJq4bw9e7DF3k7ItOwsE0IajL8eGP7TJGojKMd1mugy
DnMAss7Q0dTmhcHrCBz1Cz6uzs64A71mAwQoYXeeyGxZEnlvQRsUi+Z2D/5qeeS2Gm2VQVMZ
py8qzyo41qrYnQ3pLSez23w4VK4uGrSabTahAwqG5FBq00sDP/GcikZCKa3G6+eE1nut3cYC
AarUFrdkd+fcYY1ESuWFk2eGcsDbMvvbnFe9wpwCioqKFEX56U9/ev/9908yiGBGIASHQCB4
J4AQarV39Oonpv4Sl9v9RvM0CQ5FUXrNE2m7f5KYkFySdLryyRansjstni33LRoZE5Urh+12
ym0MCYK4Ib0FQ6lIqS0Yqk0/2JTdfmP5V5eEbx622yFEMjqjFWTkq/AtOZx6OkhKZmmrMm5/
wumaaFYEyhLyMU5fT/x53Itj2/Zc+eoFkavCcul4J1WcYf0dxushubhSXZa3/5oEmxmDZtu4
x1qxYsX+/ftvv/32yUcQzAiE4BAIBO8ECCFpZ+CsyYwFJO1ujLGX6HDB59OtH50kAEEsI3/K
6ck/wgDrNo6Uq2cEh4w0GflTTjfngAEKAWLA7TMbK0aIEggggbKKAz16w96h366OfuCGsv9T
qs4rVevzMYvC7xm22yToK1bnDlttGWdAQX4CpZH9VrxxFOSXkcY5o5y26HteS/5u7CIHAMCy
rBp82fUlX64Pb4wqlXjEqkxcnZ1x+2Jylbe2McVSoITVPe4KBwAgEAhMZQTBxY+oUhEIBO8E
IIS6M8XNlDPobuqU+Uo5XHNhS2QRQhDCIbt9khgZ+dJOrz56A2jYaq8ML83/qZFw2um1qA4A
4BwAwACESadztn+9n4QZ5xBCCKAMAxxwxlivfuJ58/tzgxtWR++yQ7rNDZvmCPIVK7Pb9dcM
lu41Gyh3IQAIEhlpHDDPiut0cilAnDOXWd61cJmddnuJNv5twkv4XaTeTAKk1drpcptxV0LK
vMDVLw/+JIQqzykhV3cTrdbOUrhi6i8RzDhmjOBQFGU60ru8RbyJlPVFiDdVz0Ho7Z7LVPF+
Qc64iyzL8syas+eD+XZPZKrkP8kX6iJjjHnWPY8SBgocv98/xXYnU7zICKFj2b84PIfwhMEy
URl3OeAjl1cMmlFwML/iIiEf5fbo9Rdu0KSC/AoKnXkIcAggxBAAwAE7md2OoHRHxb95c6aU
IoReT/45YbcDALzRGHAZ9/6CEEDOGQMcABcAr9XKaUw3LUnSWdcY5mgb8/+GELrcypulngOI
GTkDAODz+WbQqob3eZBleWb974MQTsdFnryYdMbctKbVHHBcr+KLE1mWJUnyOkK93XOZKvkO
FG/3RKaKZxslLvK0kr/IF2rOsixzDs/1WwJCpOIgYywvODxz8XH1h3dTmcqEvXsPBISzM7/y
CZL8pEhGGoaEA44gdoENAeL8zHe0gn1+Ep0fvApDGQAGIdLdBBzdZRNBQrk7+Te7hiPeuXh3
fc45htJoR3IAIUYQe43cAOcccMZpgQM6goQxdk7vkaIonIFz/7qGbU3dn/vAZ2prazdt2vTW
W8GeN55VwQX8JL8FSJKEMX7rJzxjBAeldDqKhr11ghlUP+19fUzT1ZgmPDU9gyacb3Uxg+aM
MZ6+wvrpwLvIF/CTjBAiQJ26Ww+GpMQ3t0ybn3X7Dxi/t6nOASNI8ZPYQv8Nrus6jlMwGsZ4
6j1TFkXeuxX/JEUNAICMfUVKtYpDw05r0u2i3IYASsin4cii0PVDdlu/2SQhNSyVlauLdJoa
sltdbiOAFBxUUaA+eOWw3T5ktTLOAAAajpk0O9GSTFytmRu8PCKX70s+MWS3utzEQF4evU0j
UYIUyl3GKYaEIIlyyjmlgAF+ulssghghmTInb5Gukah3KaZ4Vb2rROA5vBEe7UdSX/jMlwcG
Bm644YaZ9XVx2ulkRn1deFt+b/2EZ4zgEAgEgkmglIbkEjC1hts+HJoTvnTQbt49/KgfFTnu
qG/eU+nd5dqCVeG7Lcs6b18yxliJWp+ye8NyWUyp6jEbBnIvG+6o7mgRuYxyGpErFoauy7j9
w3Y7RvKx1OaW3B4vAAFUqs6zmB6RK0JSaad+yKK5UnVe0h6nxgRCtCh8XUQub87uoDlqubmM
O4ARZoylncH5oSswkhijCtIodyymU2YX9HiDABIkYyhLUHWZ6SfxECk919/BlNKQVNILzqFc
6Mj2jh99/jkzZz/44INf/OIXZ9DehOCcEO+rQCB4J0ApXeS/cSqdPjQSmR+58mT25V2Dj2Xp
EOOFv8UNmj6V2fNC//c72e7z9rV0HKdKWxpTZxFMTmReatf3F6gNAIDDTJebXfrhIbvVh8MY
krhc1zXCbJQBZjPD5WZLdnfOHar1rylRZ0ekin6zqWAoCNCq2PsVor3Y/8OW3J4ALso5ZyzJ
T6a3zQlsmB+8inLH5TbnzB2jNgAAHHCHWRbLMeBKWF0Uvm5Z6NZz/R1MKQ1I8YlcOsay7Q8N
37vvGddmjzzyyOc+97lzOpZgZiEEh0AgeCfgNZGv9C8BYLIaV4KUOaH1RzObG9JbCJJL5XkT
Lf4n7e6T6Vc72e7zS2u1LGtD7N5ita7TOJx0useNMWlWw1GClB7j2IDVvCF+b8YdGLLbRsZk
3UEZ+TGUuo2jSaf7svins86g7qYKhpofvhJA8FLfTzJOf7E6N+sO57dFPI6nXlgaukWCqkkz
DFAJTZiDzzmzaU5G2qLge85jm58xViOtr9QWTyV4qDv7ywdf9gWVvzz7l1tuueVcjyWYWQjB
IRAI3iHYtr0scFuZNm+SmAptYbd15GT6FQRxWC6bKD/UI+sMduWOnl99nKdjKtQlYMxCQh4O
GATQc+hScXCu/zI45jvZYjnGnZBUAgEK4OIabc1Yr5GQXBJXa3cO/cpk2VJ1QZFUM2wWVuTu
Hvyf+uDl15V+AQHoMBMBjOGEW+oQoKuL/25x+Ibzy5u2bXtl6ANxtfaskUUVgS/86NZHn/3+
mjUXuDJZcBEiBIdAIHiHwDm3LGtj7L5SX/24ATLyxdXaxvQ2BFFUqYyS6rNWQ/Qbp07oz5/H
xoqqqvuSTwxZrRvj94Xl8vFjcMigaZdZ80NXr41+6IW+HxQrs8NSYXDC7sZQXhG5bUXk1ud7
v1fmmy9jdWTAnMCGdn1/yu4uVefVaKv6zeaC5Q0AQFAp/V37ly4t+viNZV9FUHK5haE87qwU
pN1U8Y/rYh/e0f9LVVXHjZkcr7ClOrD8rJpDxYEP3v6Ja5d8ZAZlXArOGyE4BALBOwdKqWma
G2P3zw1dquJgwbNRpbLTOOByI6ZWR3HNVBJCOWCDZut57KpIktShv344sTnnJK4u/tuFoWsK
mqQAAGSkQggXBK9dE72n12zoNA73m4012qqCsAApWhC8Zk3snm7zWI95bNBqLRnhIoqhXKTU
dBmHa/xrq32r+oyTY5NFZOwzaPJE9qWHWj6+vujjH5z1/Wr/GgghhIW3gLmBy++q+t4lsY/8
pu0Lh1PPeNVP53ruAABKaQVYe2XR52YH142bzwEhKvXVL4hcXa+M0yJO8I5EVKkIBIJ3FJRS
wzCWaLeF5LKcO5y2+2yqU+5IyFcbXNOY3VqpLmeMTd3pIWX3nofgwBj3GSc4YA2pLSXqnIWh
99QHr+wzGoadDt1NYihrJFLlW+onsT7z5FPd/8wBj8u1HLC1sXt0mjRoSoKqRqKl6ry4XNdn
Nf6h8yshUlIXWA8BWhm7Q0VBg6YlqJZpCxFE1b41hpvo0o+6bJybt0aiNss5zGzL7fv3E9ff
Oes7D8z+/aHUU136kYTTYbK0ikJRuarSt2xF5LZT2V0PNX/SplkAwL7krxcr7z8/QeCJv+WB
OyNKZdYZSDsDNtUZd2Xs00g0LJfNUa50HEeojXcPQnAIBIJ3Gt7eSjlahWWMfadbpXDOJUlq
Su8810pXi+VazFfL0Mqpv8RzGk27A96f/WbzgNlSpM4qVufOV+o9T3GXWzpNvtj3H8k3+qhl
nH4FB5aG3zfbf6mC/YxTnSaHrJZDyafTTj8AIOMM9JmNoeLiFeHbFvne650XhPC19BNd+mGb
Ttj9lUDZpKfzTDN08L9bP1Us191R9W8LSq9lnElIcZhl0FRH7sDDzZ9K2WdSXHM08WaKVBlj
pmmWo1VYwVjDe/bs+cUvfvGTn/wEY+y6rmFMOGHBOxIhOAQCwcwGQjhuvqHnGToyOQAh5LJz
zoJknHIw1eUQTwQghDjglJ757c4BGzTbBs0zFSgqCRAsJUd0beWAJZ2ehNO5tf8/ZeSn3B6b
H+pyZ9ju5JxnMhnPttzn8+XcxLhqAwKIIGaAI4gLsjoG7JZdw48WyXVHk88RqLjM4mCcah2X
mW++s533RmzatOkzn/mMbdt33333xo0bz/4ywTsOITgEAsHMgxDideuAELaYr9apG7xdEted
zPObcz5JOehESFjBSNIUzdtY8fv9jDHXdV3X9YQOhJAQQggZuRhAbCWsVCTt7rxzOYReq7U3
JgMoghoEMO+HESTFi0M3lCrz3l/5dQgwAMDhxqDV0m0c7TReZ5wCAGYH1l8ZfwBCGIvF8sPW
gXW9xvHmzB4AGABAwqoPB2XkJ0iyeE6RAgryZ6mCIMqbjpQo9fODV0flWeXqIotlFeQ3aXbI
au0xjifszvxZyGhKXWbOyuOPP/6lL30JIfSzn/1MqI13LUJwCASCmQTGWJblZuvlhNGZsnst
qlPuHEMv+nAoIpdHlIpqZb1t2xOteYzNJJ0EhBBCyIYZFYU2936LQosDjpgUkGJRpWqx/2Zv
+USSpKO5ZxOZzqwzZDMDAiBj/8riW/1SlCA55wwbLA0hMGiSMptyyjmDEBKo1ClrFRywaA5D
eWnkpjptncGSrw49ciz1vMmyBMo+HC5V5y8IXbsgdE1LbtfG+Kc54C36nl1Dj/aaJw03qWJ/
TK6p0paXawvnha46nHgmS4c4pLqbHLbbHW5yQCHAcaVOQiqEiECi4ejyyK1hqWzYbj+S2txv
nrSZIWMtQOKlSv3iyPW6m25Iv6i7SQBggBS9ybYmnPPvfOc73/nOd6LR6KOPPnrJJZe8mdEE
MxohOAQCwYyBEKIoys7Ef/fqJ0ZuNzjMNNzUsNWh6oFMYHBZ4DbTNMcudVBKI3J5Z+7IJN4Y
eTDGKdaVNQaqtBU9+vGMM+C1XnLdTM4d7jOaevTjtaHVMXnW64PPDlsdI19rM6Mnd0yCaqux
J6ZWayzUb5102ZkJc85tbpg0FyDFCJDL4vdS7mwZ+HFMnpV1+vNGYVl3cMBqPpZ+bm3s7ruq
vnsis3VL/48otxhn3mg5Ojxsd1o822sen+PfuKH4Uw3pF3cP/Y/LbXC6FSzk3BmwmhcEryFQ
jsmz1sU+0q7v3zf8m2ptZad+2Iu0WDbj9PcYxxoyWxeFrl9X9OFDiacQxCvDd6XThTUv58QX
v/jFxx57rLq6+je/+c3cuXPfzFCCmQ5+8MEH3+45TAnLss61G9BU8Mrrz7tdwluP15nQtu2Z
NWcI4cyasKIojuPMrDnPrJZX53GRMcbdYO9riT8MGM3jJhwAAFxuJ6yODO+rCawaOzLnvEyb
32MfMWnmrMdK0o6E3ckAWxK5MWn1mDST7+rnxVBondJ32MyMyrMSowUHAIABWqLNbsq+krA7
NRxRkF+nycKLgEhErloWuTnl9u4ceoQgKa7UdRtH2eiWrSG5eGP8voPJPzVmXrZ5DgNiU330
OLKM/E3ZbT3msXnBqxDAA1YzeENwAAAod4NScUypXhq66VDqqYb0CxG5HEHs5aKOvoBWj3nc
5eby6G3Fvjnl0tI3WUViGMapU6f++Mc/1tTUTCXe25maQZ9kjLH3SZ5Bc57Wi6xp2kRPCR8O
gUAwA4AQqqrann09aY1vE56HA96RPXQg/buxplVer9cq/1I8xhJjJAihNOtO2l2UOfOCl/tg
NDHmoAihpNvRbzQfGP6TwYfLtQUFAUmrJ4BLloTfa9FMj3lcRlqQxAtihq3OxaEbOGB7hh/n
nJco9Qm7wxld14oAvL7kS+36a9sGftptHilR6gFEBeszSbsnSIo1Em3N7d07/Pia2AeLlMK7
+6B5akPsk03Z7U3Z7RL2haXyhNUJJqA5+2q7vm9j0d/ouj5RzBS5/fbbX3jhhfLy8a3PBO8q
hOAQCAQzAFmWD6b/MGi2Ti2ct2UPNFvbvE2QkTiOU69cMzu0bqznVR6EUNYZdJkzS1uxIHBd
W+a1sVswCKG00884tZl+PPVCqTZPQr6RARDC9tyB+cFrF4avd5g5aLdG5Eo0+is3IlcgiE+k
typIq9SWIkgGrOaCmpD5oWsgRDsGHwYAuMxK2B0hXFIwGcadQau5RKlXcbApu+N45vl1sQ8V
xJRrS7rMw13GYRUHytWFGXfA5hOKCQX5k07XoeTT59dHpoCx74Lg3YkQHAKB4GLHKwPp0o9N
/SWUO33GyXEtyS3LWuq/bX74Cnm0RPBACCXcdpNm5gWvWBv70KnMHoMWJjEghIbcFovmvD8H
rdYOY39crSmI6TAO7B367frYx9fG7tbdhM10jcRGxsz2X9qS3ZNyeub4N8aV2W25fYy7Bb3n
FoWub8y8bDNdRn4EpSGrDSNJRqNXrSFMOb1pt6/KtzwolRxM/KlMXRiSSs9MBuJa/9qDiT8r
ODDHvxEBMmi1TNTlLkCKKrWlUVzblT123s1yBYKxCMEhEAgudjDGx3PPGWNapE5OwupECI21
keCcm6a50PfexbH3VPqXFNStSEiJyrM2xD85P3jtieTLKbt37MgIIdMdlQXSZzZG5IqRj0AI
LTfTZ5zY3v/w/MA1N1f8Y7EyOyZXnhkE4mr/KpNlqrQVYaksREpnBy6NKTUjC3c1Eo4rszuN
12XsRxBTZrvcMWhKI5EzBwKAcptxOmx1DNvt5epCvxTvNo/UB6/Ix8TlWgQxgqhMWaCiYKky
b5a2QsWBkRcHAugnsUptyeLQjTFc67puyu5psbafk/HX3r1732RVi+AdjFjpEggEFzsIoZw7
dK6vsmiuUd9SjTaMvQV6mqMSr60NbcBR3KhvsZnOOSNI9UkByFF79uDR7PN5C40CIIQOM0c+
krC7fCQMAMxvvkAIbW4CAJJ21wu9P5wT3LAycgdGctLuslgGARyUS/0o5sfRYauz1diPESn1
zS0Nzk847Q4zKbchxCXKvKTdlXUHOWf0jcmYNOPHo9JBODhdBJx2+nU3EVWqAODriz4ak2ZZ
PCsjrVxdmHH6NVw0aLa5zJaxL6bMqvQtTdhdLrcYdxEkBCrF8hzGWL6omHJXd1NIQlNM2H/4
4Yf/4R/+4f777//Xf/3XqcQL3m0IwSEQCC52IIST+HZPgs0MiCc0yqSUUkohhNVoA8TQcyxV
ZOUvvd/MucOTj8xGe49aNAsBlJDiCREIYcrtYm+YezJOT6Zf6TUa3lf+4LDbHSKVlLnUYcOw
oz37+unJMLc716Bgrda/jnPuTSYmVRk0NbKeFgDgcBujgp2OMykmLncGzJZ+8+TqyAchx2Gp
zHZNy9YHrdaUdXq1xqZGr94YkktK5QX5Y3l+8GMv4FRWOEaabdx8881njRe8OxGCQyAQTBWv
d2j+/kQpvSA2lFPh/Ay2p/Ia70Tyf8qyfF7HQhJSi9RqBDAH3OEmcB0AmgumY7Fce/agpw8C
UjyuVRWOAhDIe5ICACBEoDBtEwIwBR8RSJkzbHVITHJdV1b8472AF5z7OKOA8W3jR+K67pe/
/GVhtiE4K0JwCASCswAhlCSJENJsbjPstMNMBLCMNR8O1siX2rY93dv2nHMJFda4TgUJ+c5V
Ek3lWJxzBDEFDgAAQVKtrawPXZ5jAxRaBtMBAAr2z/FtqNJWtGb3duive1szKgo4zMxrBYeZ
BKkYSp6DmYIDFdoChQQGzCaL5yhzIEQGT9T618WVWp0m9DdSWAhUKCtwUICj/gWBhqM6Gx5y
TwHKAYcK8ftIECHEOctfDwSls14cCamTx+RyuXvvvXfLli2LFi164oknRPmrYBKE4BAIBJPh
ec0dyT7VYzRk7MGRjlsS8nWrx0t99XXqRsuypm+1gzEWlIpHZkhMBRUH52nXnKuThHeshNU1
eZiMNIeaQal4efRWg6WOpJ9xmT1gtJwJIL6AVDTHv6FKW3YwsUl3EzFlVs5N5ANsmvOjoqhc
NWi1lPjmxJSqTuPQQKYp7fTnO5504AO1/rUIIgmpMSWUsnsod304ZLFcfhwOAAQQnv4HABAw
7paoc9uy+xN2F0bY6522NHqjyVIIYgn5OeNwCmICQ0kjkckTOLZs2bJ169Zrrrnm4Ycf9vv9
k180wbscUaUiEAgmRJKkLr7n5aH/PJHalrb7C/w9HWb06A1HE88fM55VVfXNtxWdCErpfO26
gBQ7e+gIYkrVeWz6UEojcsUkLh3gdE+WQFSuWlt0T6u+56X+/0w5vbozykjUYWaPcWxL/497
zGOXFH0oLJeXqPUpqycfwAFP2b1lvvmV/sUUOEfSmxszLyftnpGZqjY1+8zGuDJn2OqwaS4q
VynYr+KQMdq0FEMZQQwh4IBR7pSqC1aE338o+XQ+IGn3IC7F5BqDpi2WQQjJ2B/BVZNfnKhS
WadcNrngeN/73verX/3qscceE2pDcFaE4BAIBOODMe5ku5vSOye323KY2Zh65XBuk6KccyPW
KeI5hFZoi6b+Egmppb768zBvdl13rnpViTpnkhjGWLm8eHXsrsOpZ46m/upDwQCOF9h1cMZ9
OAIBOJj8c2P25StK7otLs4ftUeaefUZTXWBdsTq70zjYbyr0NB4AACAASURBVJ6EAEIICyTA
ifTWuf7LZOxPOl0GTVX6lrjMskfXyADOESScMwYo5+CS2Ed6zROJUcfibbn984NXAwBNmjFZ
OiAVTa42EMTl2oKpXMAbb7xR2HUIpoIQHAKBYHwURenKHUvbhe02xsI5O5Xe3WRtnb4bj+M4
SwO3lvrqpxIMAawNrqmVLzu/5BLbtiv8i0Z6XYylUlvabR05lXuVQDmm1GSdoYIGKAAAzrmM
NAhgc3bHsN1OuVNQZ+sAa0n4Jh8OZ5yB0xMfowF6zIYhp+3Soo9BiBhwo/IsBQcKDwQAgTKC
hHOwOnrnpUWfeL7n+wUx7foBHwovCr2HA+7D4aBUPLngqA6sqFevmUH9QQQXP0JwCASCcZAk
qUF/rt9ommI85U5X7uj0CQ6vaPPyos8Uq3WTR0KIaoKrlwVuO++uY5TSarx+bmjDRJojIMVd
YJ7K7tZItNQ3D3Ksu4WN2QAAnHEVhQJSUbE6tym9Q2fDPhIeGbCh+KN7h59IO32Xxj8hIz8E
hcsbHruHHguQ+JXFf1uuLuzSD4Wlcgzl0acMHG5iKK2I3rYqeucr/T8fsE4VDMK4ezCxqd5/
+aro7UVyXdLunrjeFVb5l6wO3fMm27YJBAUIwSEQCMaBEDJgNvNzSdIctjpPGlsvSPeNcaGU
mqZ5RdHf1gZXT1RI4iex+eErVwXvNgzjzSSx2rZdJ10+P3Jlqa9+bD5HTKnqMxshh+XKoqhU
5TBj3OwVCKCKQuXqojApSzu9g1ZbTBlVB1uszj6ReXHH4EMSVK8t+XypWtgBzoNxPmA2r43e
szB0vcVySae7SJlVcCgfCl9Z/Nl7a3+l4VhjZvu441Du6Cx5XcmXarRVLnPSdJw2eCoOzgtf
dknkE6ZpFmRvcM6//e1v/8u//Mu4gwsEZ0VUqQgEgkIghG32zuSIDMepwVN2LwmQ6auS9TTH
ysDdUeXVlNWTcnotmqPcJVDRSCgsly8L3uY4jmmab75kxrbtSry2LnpZk7k1YXdn7AGGbM45
QvKswLK+xNEqdQVjDDBQqS5PuO0mzTrM8My+EJRk5FOwP0qqGWOAgypfzOa5Wf5rs86QzQwE
cEyZpWCtRd/lcHPH4EPzgletL/pY2unrNo4knS6DpgmUfSRSpsyr8C3O0eTj7X87S1t5fen/
NlnaYUYT3qG7KRmpIamswreoTF1Q41u3vfe/MZTfU/q/W/Tdg9apHB2iwEZA8qFIXKmNK3WQ
Sa/2PVqizllf9BGTpR3X1Z0U5Q6BkopDYaUsJJVUk/Vj5Zpt25///Of/8Ic/1NbWfuELXwiF
Qm/y8grehQjBIRAICoEQMsBsds7mnibNTF+tigdjzHMlr9YwxtjzyPKMyFzX1XX9AlbnUkoN
w6ghG2cHMMaYEAIhdByHEHKQbbLe2EZhjIVRVZSc9uwCnqPWG1PKx2g4VuNbVymt8mIQQodS
TyWtHg4ABfR4+sWW3O5K3/JydeHc4EYVBSl3DZoctFtfS/y+z2zkgPeZJ0+kt1xT+vmbyv6R
MZY/VtrtPZp4/i+D3/aO1Wc0xpRZi4M3qcSvEM2hpunm0nZ/X/aU56CadYZ8JLwwctWc8BXe
OHknN9d1x+6k5HK5T33qU1u3bl25cuXjjz8u1Ibg/BCCQyAQFAIhdNn57N+73J5uweHhuZK/
BQcCALiu6+kGVVURQoZh9KGDNh1VJ+J5XUw+ju0alNK8L4imaQ412IhKY5Nmm7M7mrM7Jhkk
4w42ZXdcW/yFROK0pYckSQ3WSy2ZvSPH6daPd+vHMcayLDuOk9c9eQw31W+cqiaXnjVRo6+v
70Mf+tDhw4evuuqqRx55JBAoTFkVCKaIEBwCgaAQzjkZnZY4RSSsEEJ8Pl/+x7f3o3mK3b/e
evAb5CfMGPPUzEQrJZzzOnXDMfiCA8xxA8YFQRJXazHG+YuDMS5W55Qp9X1Wk5crAwGAECOI
AIAQQOB1ZeOMATayvKWgve15v1kEyWddDUomkzfeeGNnZ+dHPvKR7373u4SIW4bg/BGfHoFA
UAjnHCEiIZ8z5V0Vr80Kg1Zjbktr5jWX2xhKMtLCcllILq5RN9i2fVHJDu/X/ynrlZTem3b6
HWYwTiWk+kk0olTO913nOM5ERaGcc4UECow3JgbG1doKbWGade9K/DJtDTjMhACrxI8luC7+
0awzeDj19LDdjiBh3PWqZ9+QIAhBhCEGEFPuevogIpWPvJKccwX7z9WGFQCg4uBZBUckErnr
rrskSfrKV75yToMLBGMRgkMgEBTCOa+R17fLBwbMlrNHA0AIGXZbM+ZQme/Drdn9SftMtumA
eUrB/qTWszL0Acuy3rJ9kMkhhCiKsivxy179hMvtkU8lrK7O3NEe9XiltmS2csW4Ow6U0ohc
nrTGqfIoAEFcG1jtInNf8gmdJorI7PwVyDhA5WpjdmtUqt5Y/DdHU39tzLxEC808GOUAQoCh
RKBCgcs4LVMXjlRClNJ6/9XN0q6sM3QOVwApGolO5e342te+NvVhBYJJEGWxAoFgHFzXLfbN
hlPot0oIGXCahq3OqFRZJM3OjDEKs2juVGbPK8M/U1V1+opmpw4hpJPtfr7/u525wwVq4w34
kNl+PLn1hPmcqo5Tf+u6blSunEI/OVgXXKvz4T2Dv+41T8jIV7DGwxgLkOJj6edeGfhFfeDy
Ov/6cUfhHLjMcZiBIFwQunp97OMFMsh13cmtUcdSos6ulS+9qNacBO94hOAQCATj4LruQu3G
+NlctgghQ+6plNWDAKkPbuzRGygvzE/06Deadgz/QlGUtyardCIQQoqitGT2puzeySMdZjSl
X22ytspyYYYEpbRWvqzSv3jyEcq1+TbI7k/80aCpoFQcROVja00rfUuL1bpe8/ju4f9ZGr6p
SK6ZaDTKKQbSysgd+STWM1N1nFXhuwNS0eTzyaNgf6mv3rbHFVsCwXQhBIdAIBgHzrlt27MC
Sye5jUEIU7QrafUCAJdG3hvEZf1m8yRj9ugnjuSefnv7bsiyvCf56MhNn0lwmNmaeU2SpLEi
ybbt1aF7SnwTritISC3zzTuWes6iWb8UK5bmjt2/gBAyxuLynJBU1ms2NGW3L4u8b6JVJQTw
NaX/a2XkjrG7PIwx27ZnBy9R8Nk7qGEozQldWiNtGDsf27afeuqps44gEJwfQnAIBILxcV23
Cl1SH95Y4I+ZB2NsuCkMycrY7bN8q5rTuwp6hYyBd+WOjHv/fmtACLU6r/boJ6b+kowz8Hrm
ybEiiTFmWdYVRZ+t0BaC8SRCsTq73dw/ZLUG5eIKZcm42RIIoR7juAS1Gm11XKltyGwJSsVx
ZZxVJR8J3Vr54JXxB7b1PtTm7BrrSu44zmz5ivnhK/1ksp66Cg4siFw5X71+rGpJp9Mf/OAH
77333qeffnrc1woEbxKRNCoQCCbEcZwqsm5O8eUH03/s0Rty/z97dx4fZXUvDPwszzp7MtlX
EiAQdlkURASBilhtwV6sKMXWpb3a2mtrbW2997W9r+37tti+tffWqr3VWrVKW7WKKAhqRTYB
EWQJa8i+ZzL7s5/z/vHQMSaTYRIYQuR8/+CTzJzneU4eJjO/nOX3M3t6b4XgkJgjji53TheB
50jwH+mk7oga3UfimyrwlZns9YA4jgsrHQYZxHZWAEBAa8DOJEtP7LRgc7JuqxE3tMQOh/R2
2iupRpZYfDhyIFsqz+bKB9pkCyFUrUhIb8uRRk3yXtsU/zhktBTLk3pXQpE5z0TPNZO9S8e6
5m9u+W1E78gWS7GA+y+/0DStQpjH+YRutaFdOa5akd7PCkjOlSvz5DHl3BxV7XsH2traVq5c
efDgwauuumrBggWDuj8MkyYWcDAMk4ppmpZlTXJ8YZrnhmPxd+Jm0CAqgljETp4TiAVa4zX1
2sfp78mMGl2IH56xVYRQ9HRd1kGI6J0IoaSjMoQQRVHGCourHdecVLfEzB57I7GInWWuaXXx
XZDw/ZNu2SCEYavVTufapdZFjM58eWyOUDE7e3W5c5ZqhTAUnJw/iy8e47qiLrLn9fpfAGAB
ACJ6B5Zx0i27uq4Xohnl7jnYh2tib+k0BpAFRMhDh4w95cIcXdf7j20cOXJk5cqVTU1NK1eu
/NWvfsWSbTAZwl5YDMOcgV2pVdf1MnQ5klAiM3etvuVAz/rBnk234sM1pQIhHEK+doOoteq2
Qjg96bP2Yhdd10vwZUj8JC5pVncrepSknGOivTJ6aVasIbpPs2LVriWjHXNF7CZUj5vhlnjN
wa5P1UvTiZLiBtqp3yGEldx8QRAcDoeqqqqq2uMx/dtv27bt1ltvDYfD999/P0u2wWQUCzgY
hkmLnTY0sRaB4zjdGvSHNwCAAmoX7zinvRsQz/P2igdKKUJoCNeliX9Ssuc4EqGAXZ2kb2eQ
5OC8ApYJIAZR40ZXnwYmMbrUuo8Db6Tsz5n3stplXOwf3E72OlDLt956KxaLPfrooytXrjzj
aRnmbLCAg2GYoaCUppGIIgkeSYnCY5nDcZyd9uNgdJ1qRCxqisjpoL5xWVfWR/e2x0+caX1r
r1MhAYJUkQrHcRzHYYyPK+8algoAFLFzvHthTfhtxYhQSiGAOfKoPLnSwfla1EMaiWCInTiv
3DOtSf74VPSDHq3ZPpWInGdcYsIj+RyGaw899NDy5cunTZt2rk7IMANhAQfDMENBCKlyLDwa
ek+zYoM60MX7CSEZzQDmcDgEQdjUsaY+vrdLqU0USMuVKtxCXr44dor/mpOhD9JMzeni/KPE
OYmia71BCEVRPKVv7QidCGhNvddpQgDjNBAD3XniuArXrB6jcU9obXP846gZsBsgAAvk6myx
dILvcxGj81DPJovqPqFIsUJn7M85TNiFEGLRBnN+sICDYZihsOucZQnFbcqx9I+SsHuCc2k8
Hs9cwOF2uz+K/nVX44tBvbnPUyGjXaPRA8HXx3sWzc5eXRveHVAbz3jCLLF4oE2tkiTti7xU
H9nbP2Npp3rKw+XHjMBoz+zD4Y37e14z6KdWaxJAu/X6NrXmSPjd2f5Vl+XctDfwSq5YGVRT
ZUznoOARclNMkTDMBYvl4WAYZogMw8h3jMVwEIm8ipwTTNPM3AIOl8u1J/Ln99of7x9tAAAM
K85D2cX5D4Y2bO78f5WemS4+VdYKAICE3Vlicf8tIRBCSZJ2h54/Gf4gaX70TuXkBPeSy3Nv
/SDw7Afdz5ogSRuDaDySFSv0XsfvAkb9gvy7vFxxyGhP0Z8Cx7hRwtwhj3Cw7KLMMGIBB8Mw
Q2Sa5mhxfqlraprts8Ti6Z4VA5VgPXuiKB6Kr/ug6/mBZnkoAFGj2yMUCshRF929q+fPlZ5L
4cBvgwjiUe6ZZdzs/h/wgiAciL7WGN0/0HpS1Yp6hYJm9cCh0AaLmibV+q9aIdQEAMrYY1Fj
b/AlgyoaiaVYXOLi/Xly5ZCDhra2tiVLlrz44otDO5xhzlJmp1S++93vnjhxovcjEMIXX3xR
lmUAwJ49e5599tmmpiav17t48eKVK1cOb5EFhmEGS1XVGZ4vG0Rtjh1KvZXDI+SNcs/UNC1z
BcNEUTwe2Jp6ZYZmxQQk50mj29Xjh0NvFcuTcx0VHfEkGdkRxBXuWRMcS/unyUIINZg7G6L7
6MA/cpFzQr2y+2Rke55U1a4es6jBQbH/LdKtuITdLp7PFkpqwm/Pyb6Vg0LSIRMH5xvtmV2C
LhtaxFZTU/PlL3+5tbV1//79N9100xDOwDBnKbMBx3333dc7yczPf/7z4uJiO9o4evToww8/
vHTp0u9+97snT5587LHHCCGrVq3KaH8Yhjm3KKWqqs723boPv9wY3Zc0ywWCOF8eW+gYN+QP
y3TwPH8wtu5kdPsZW0aNLreQWyCN79Eba2M7Z3hv7B9wODhfueuSasdSVVX7TwBxHBdS2vqk
8uyjxDn5QHhdQ/yjPGlMsTypUztpUpUDYp9zUUAx5Aul8RDgk9FtpY6pWVJxp3KqdxsIYI5U
UeKaXIZnD214Y+vWrbfeemskEmHJNphhlNmAo7i4OPH1iRMnWltb77zzTvvbl19+ubi4+Bvf
+AYAoLy8vLW19dVXX12xYoUoihntEsMw55adbXOKc5lXyAtoTUGtRbHCBlEx5EXs9AoFfrFs
jHSVruuZizYAADzPd4ZOWeTMqykpAGG9U+Y8BVK1SfRcqdIjHIybIUItAUlOLtsnFl/i+ZJp
mkmjDQAAxjiop1raCQDKEoqblP0WNdqUI1lCSZljetTs0khMs2IW0QFEHORl7HFwfifOjhkB
DomFcnXM7B7rnB/WOw2iYMgLSPYI+dli2XjH5+z0YkO4M6+++uptt91mWdYvf/nLr3zlK0M4
A8OcE+dvl8obb7yRn58/Y8YM+9uampr58+cnnp0+ffratWtra2urq6vtRyKRSFNTU6KB3+/v
XyT67NmJcUZQKl+7wxjjkdVnCOEI6rC9gQIhNIL6jBAa3g6bplmKZ49yY+zDEMJaZVulPBcA
YOcKMwyjz2vAfiWfwz5zHBcx29OfllWtiEZiMvaEjJZri350IvY+AKBSnmvnN9N1nVLaZytN
4iZzHKeSSP8KagkS5+EQ3601QAAAoD16Y8Ts9PD5BeJ4DDmNRAEAAnKZRFWtaLdWTykBFuCQ
YIr6BM+SKseiWmWb3R9CiN0fMPh3Kozxpk2bVq1a5XQ6n3/++UWLFg3q8GGBMR5Zv3oj8e0i
czc59Xrw83SDotHoli1bEqs0KKXBYDArKyvRwP46EAgkHtmzZ8/999+f+Paxxx679NJLM9Q9
e5ZnBJFleST2ebi7MDgj8SZL0lAycWVCtbgwnWbn9iabVB3sbluNRhQS4nm+2pdWh8E/bzLm
gYgHHI718Nl18T0ajUB0OgCygBYymgGgEEAEMQU0anba780IQQAwAIACK2K1Y4wxxmnewDNa
uHDhbbfddvfdd0+fnjw1+4VpxA11S5J04fz2pSkTNznpBvKE8xRwbN68mVK6ePHi9A8pLy+/
9dZbE9/6/f6khQDOkh3ijaBN7RhjQRAMwxhZfYYQjqwOs5ucaalvsj0q1idNeOrVpoIgYMj3
rl2CASdgp4BkBDCEiFDTooZG4gZREos9MeAF5Ejs1LX/JYQMNJNi32Se56kFTeuTnsvY6xMK
ZezlkAQAhYCDkIjIofRa50EhoJQSQCw64JsyBkJiPOPs2Tf5d7/7nWmamXj/zAT7j++Mzr6d
WyP07SJDN5kQ4nQ6B3r2fAQclNI333xz7ty5Xq/XfgRC6PP5enp6Em3sr7OzP9kTX1lZec89
9yS+DYVCsdjgEhqmw/7raqT8KgIAJEkSBEHTtP4r5y9YkiRBCEfQTRZFURAEXddHUJ8lSUII
Jc2GeWEa6CbzPM/z/OHoxrDeploxi+gYCTJ2e4XCsfJVhmGkeJeUsY9YBACAIHbxfhl7IlZX
yGg1iU6AxUGeRw4Ze104J2p0GVRzcX4ei4Ra2zufiZs9BFg8kp1clkfIrxDm6rre58+1xE12
OByICHZPnFx2iWuyCeIBvakxvl+1IhBCB8paWvxAllBCtAadKIRaAAA7P3rqsElGWaZpnqv3
OkEQRtwrWRRFjuMy8W6fIfZNNgxjZP32Ze4mD3PA8dFHH7W2tt577729H6yurt67d+/tt99u
f7t3715JkiorK89DfxiGuQDZqbSOKm81BQ+F9NZ+z+9rEj8uck4cKy3UNK3/CIRpmrniaAAA
jySfUBixOtvjx3TS9zMAAujm87KE4lyuskM9wSE/B6T66N7ebTDk2uVj+Y6qMiH5rhDLsrxC
fkhvy5PHuERfXfyD2ujOPtearFybLYxqVY7I2K0RxSQ6hlyKbbS2PGnMCPpDmWEG5Xwk/nrj
jTdGjRqVWA1qu+GGG5qbm5944on6+vp33333lVde+cIXvjDi5u0YhjknIISyLO+L/K0m+G6y
aAMAQANaU03POwfj6+wxsz5PG4Yxw/vlYuekLLG4S69tV5NEGwAACmjMDHTptQG9HgBQ6pyW
KJyWYFGzJV5zNPherfFe0jcly7KyxJJi50SH4NrX8+qR8Dv9r1Uf3VvpnK3TeMTswpDjkYQR
D1IuqfMK+VlCydkMdB86dOiNN1JVmmWYYZTxgKOzs3PPnj1Lly7t8/i4ceMefPDBw4cPf+c7
3/nTn/60fPnyW265JdOdYRjmwiRJ0v7Iy7WR3WTg9Q0AAIsaJ8LbD8XX948DCCGGYUzxXdel
nwoaSUMWAABAEInYETW6G5X9+XLVVO+y1tjRpC3jZvB4aGudsY3n++ZuN01zrHyVW/R/1PNq
t1af9PD9wVdL5Usme641iBa3QhJ2idCdMt6AE31Lx8tLhjzCsWXLluuvv/7rX/96S0vqLbsM
MzwyPqWSm5v797//PelTs2bNmjVrVqY7wDDMBY7juBPqP05F9qTOVWqjlNSGP3BgbzG+tM8a
C9M0C6UJlc7ZH+p/G+hwHskaiepEcfM5ZY7plFoIDrixRbWiDdGPRudcmbT+S8ToSlHZ1ST6
ru4Xpvq+2KmdbFWPaCTGoVS7GKq9V83PvjsSSZVMLIV169bdddddlmWtWbOmqKhoaCdhmIxi
tVQYhhlmgiC0xo9YNN2pBIOobcqxPol57DwfH3evn+L9wszsGzFM8tcUgggAqlpRv1g+P/eu
Hq3p4+D6fHlsimsFtOZDsfV9MhZwHHcs/nZb/JhPyJc5z0DHHg3/I6y3L8q/d7RzjkFUjUYG
yBICJ/mWLC/6eTweH1re9yeffPKOO+7gOO75559n+ZqZCxYLOBiGGU4IoVPatoB25jLxvXWr
9fbW2cQjGOOa2IZutfFIz7vVrs8tyv92kTwRffotDkOBg+IU7/VX5n4joDUeCm5qUQ75hCIA
UqQLo91qQ/+Ao1trtCzTBQtL5Ut8YhGHkiz14JF4OLwJEHRL2RPzcu504CzQL+LIk8csKPjX
6wv+dzQaHcLqDcuyHnjggQcffDAnJ+e1115buPDcZO9gmEwYMZnRGIb5TMIYx/Se9Ic3bDpR
amIbK7kFiRUPGONwvAMAoJiRQ4HNBY6qa/If6NCPdqq1cStgUl1Ebr9Y7uT8ihk61LMxqLcC
ALq1+jjtlrArRWGUsNHeJ7hBCIX1DgAAIYQQksONzhPGdhunDKJY1IIAIMgJSM7mRxFCjva8
3x47MSnr2jLHJTGrJ6g3q1YUASRhb45YPt17o67rkUhkaGMbhJDa2tqqqqoXX3yxtLR0CGdg
mPOGBRwMwwwnCKFuDSWBgUZivYMACGGidByhVkuspi1+zCPk5QvVPJI5xOmWqtPYwZ43unuN
pljU0InCIzlFwKFbyil1WwH8JFMnhNDotS3FTt/uQ2UQw0QyZUppYsQiqLdub38uV6pcVPBt
0zQROp2Qw7KscDh8NuVzeZ5/6qmnDMPonbiZYS5MLOBgGGaYETqUfRmUEgihPfZwOkPop89D
qBXUWoPaJztWOI6LmoE+5yHUTLFuFABAAaXgk5jADin6Zws9Y9wQNbrsjJ92h22pD0mHy+U6
+5MwzHnAAg6GYYYTpTT19o3+MOTz5NGlzikiLzZauwg1MeTHCPNE3ol0lPqDv99iUiggh0kG
3EYLAOAgDwFOBAf2FwKSDDKI9J0QQpF3chzXBj8i1IQQQohHiXNM0zQM45xEHgxzgWMBB8Mw
w4lS6uR8AMB09sQCAPxiWYlrSpt2eE9wrWGYmhkHgEKAerQmg8bCtMXHlViWlfQjnFLaZ3Wn
i/P7uNJ6a3+KKzp43yhxTu/E1YQQB+eLmT0pjuqN47iw1SwDx+HwWwd7Ntq5RjgknOJ3ZYul
0zxfMgwjzfopwWDQ5/OleV2GuaCwXSoMwwwny7KqHIucXFpLEIqdkzxy7q7Acx/1/F01YpoZ
s8MUCki7csLJ+YNaS5tew3Fc0jr1hBAROXs/kS+NjRpdqZes+oSiPgk/LMvyiWnlurA363YZ
J7vUeifOaVeOJzKbmUQPaE0nwjs2tP+fWuO9dGqN/uUvf5k+ffquXbvSuTTDXGhYwMEwzHCi
lJqmWegYd8aW+fJYnuN2d69tUQ47+aw+Yxgxs0eC3jLn9Ije2aTsSxpzUEp9XKnMna4iySGx
1HlJl1qX4qICknOk8j7ZP03TnOpe7uSyBzoqAWPcrh8Nas0+oaREmpp092/U6K4JvntUfSt1
bYdHH330W9/6FgBA07QzXpdhLkAs4GAYZpjpuj7N86UssThFG5nzukTf/uDrEaPDwXn9XEWf
UQcAaHPsYLlzhovLiZuhVvUQxkmWghJCnLzfXskxzr1AhlkBrWngy8Iy1yXl/OV9rmWnUS9z
TUu92hRj3GWcjOgdGInjPVe1K8cNkrzIs0m0E6Htp4z3+yT8sNnJNh5++OG8vLxXX3113rx5
KS7KMBcsFnAwDDPMKKWapo1yz3TxOQO1KXZObFFqAlqDiJ1uPqdftAEAACG93TSMS7KXydgb
Nbt7zAaE+r7FEUK8qNgnFo12z6lyLaiL7B547QgsdU2Z6l6edETBMIxqxzUV7lkQJn8XhRBG
SGvY6ECQn+q73o0LWuPJi7bYdKI0xw71SZ8KANB1/etf//of/vCHcePGbdiwYfLkySlOwjAX
MhZwMAwz/EzTLEWXVXnn5smVsF/eTwHJAFl10V1OPrvcMdMFCwfa1tEUO8BT52U5N/uFUXGz
p3/AAQAABF3ivWFx/nda40dUK5r0PDySRntmX+pdparqQOtPVVWd6rphnPdKESfZmIoQUqyI
jDyX+r+cL4w7Gd7Ze29tUt1q/THl7T6DHP/5n//52muvzZ49+/XXXy8pKUl9Boa5kOEf//jH
w92HtGiadjbpcQZi14EccnnG84/jOEEQdF0fWX2GEI6sDouiaBjGyOozhPBsKpufZ/1vMiHE
i0oq3bMBRwAAFtUTazkLHeNNoIfMljxh7EA7UBKClQTp5gAAIABJREFUequE3JO814ick0AT
UGiv04QAOjhfrlRZ4ZlVLS/lLGeF61INRACgBlHtaAAC5OKz8+QxFe6Z4+Sr+0Qb/W+yZVn5
4jhRFATkINQyqGKPlyCIfWJBllhY5b4SEaE2sivNVKoidhZLU3qP38yYMYMQ8pvf/GYI+TYw
xiPxlYwQGkGv5MRNHkF9zuhNdjgcA143E9djGIYZAsuy4vH4GH7hePnqen0nBZZJDA4JY53z
dwWf86KS9D44abtyPKA15stjp/mXB/Vmi5gWNTkkVkpzLcuys28BAHRdnyR/gXNzddoOixqE
WjwSK6S5lmUZhqGqyddbfOpKlGqaVohmlLlmYy+u03aYVAMAclCocs/f1f1iS/SwYg5YUba/
/qMyXq/3oYceSv8MDHPBYgEHwzAXFvuPxXw4DUIIEaSU6rquGYOrpGoQtSl2wMX7q4SrCSQA
AkppPB7vPWJhn1nX9Xw4DSFkt4nFYoPtMCHEXudRgC5JbI05FnmvNvzBGadR+nc76YZehvkM
YAEHwzBpsVNKQPhJuRC7hkiGLtc78zelNPV+kIEgiO1+nvFa5+QHSYREEEKAAILIooMLOBAY
yo/JMCMCCzgYhjkDhJAgCA3GzpgeVMygQVQEeQHLbj53jGP+eZi9ppQKaMCJ4YFBATmGJWs4
pbRCuvwQ2mQNXBMuqb8/sTPr2r3jx4/PUMcYZhixgINhmFR4nm8iu7oidW3xo/qnq4dAABvE
j4ocE8fJiwfazXFOWJblFvIggDS99Oc2J5c1Rp7fOyX5+UQI8Qj5qpJuwEEs+qf/3PLOC4f2
vtn81ltvsYkV5rOHBRwMwwxIEIQ6c+vJ8M6o0d3/WQpoj9Yc1FtjZvcMz02qqmZiKxkAwLKs
MY75dcKHIT1VlbU+/FLZGbe0ZI5pmn6xrEM5mU6NGEOzHr9/8+4NJ0ePK3vmmWdYtMF8JrE8
HAzDJMdxXL25/Vjw/aTRRgKlpC7y4Z7QC6IoZu6T0jCMYudEmPZbloRdOdKoNCuiZYJpmhOc
S7PFM2fOiIW0/3vra7s3nJw4c/Q7b71fVJRWlRaGGXFYwMEwTBIQQkEQ6qN7FSucTvuG6L4j
ykY7sU0mmKY5Xr661DUlncYYcpWe2WXc7AyNuKTD3gJT5pomYXeKZl3NkZ+seOn43tZ5103Z
umnPEJJtMMxIwQIOhmGS4Hn+YOz1Hq05zfYUkKbYAZ7nMzTIYWe8mOW9pdQ1tX8q0t54JI3x
zh0vXz3sRc5M0xzFz63yXuHgBiwoLzl5iOAXvjb3t3/8Bei1z4VhPnvYGg6GYZLAGHcppwZ1
SFjvOBJ7q4Kbn6G8loQQVVUv9a5ycusbox/HzEC/JtAvlRU7Jo4W56eTtus80DStQrgS+4T2
+LF25bhF+94Zv9//9IafXlnyVU3TRlA+UIYZAhZwMAzTF4SwXt8ZMtoGe2DYaMciztwHJyFE
UZRx4pJJrusOx94M6W2aFbOowSNJxh6vUDhWvirNJKHnja7rxXhWhW/uKXlryGiPGQE7u5eA
HG4+18XnlPOzFUVhYxvMZx4LOBiG6QshRKhpkkGvuFStWKZ3WNhrIwzDGM0txCK2E4HbWcLs
zOgZvfrQWJalKEoxvrRMxsiJ+mROu6DCI4bJHBZwMAyTRJrFxvofdW4DDgjhQMVaTdM0TdMO
OFIPDyQ+4M9hx4ZwLcuyNE1rbW0tLS09Dz1hmAsNCzgYhumLUsohAQCYTg6J3ngknf3nOsaY
4ziMMYTwlLq9QrrcHgwwTTORgFwURZ7n7TaHo29O8Cy1Q5DeKyE4jrPPAwCwz0MIsc9zbucv
7KTvdgXOxIOEEDskStyQeDx+5513Hjx48I033iguLj6HHWCYEYEFHAzD9EUprZTnHcZvq1Z0
UAfK2HM2n+UIIVEUa7X3A9GGkN6mWlGT6IfQWyJ2+4TCbLFklDSXECJJ0v7IKy2hg23q0ZgZ
MIj6Lv6thy8okMcXSuOr3UtVVeV5/qiyORBrDBsduhUjwDoENzk4n08s8gmFZeJsXdfPyZgH
z/OCIByIruuJNEWMLpNoAAAeSW4+N0ssmei81k79HggEvvKVr+zateuKK65ge1+ZixMLOBiG
6cseUfAKhapyPP2jIEBeoWDIVdA4jhNFcVfw2ZZYjUk/WT5iWYZqRUN6a0v8MMkyJ/mWrmt9
6FBwk/3RbtOsWEhvb4ztd/F+kk8d2NsYPNAeO9G7WKsJdNWKBLRGGXti7p6Jjs9rmnY24RGE
UBTFE9q79cGPwnp776cMosbNYLtyvC1+tMw1DbeVL1u27OTJk9ddd93jjz8uiuKQL8owIxcL
OBiGScI0zTx5dKdaS2i6AUSuPGq0dOXQlm1ijEVRfLfrv7rV+oHaeITcoNX05KkVgA64TiRb
KOvW6z6IvO8XRg1UekWxwseC72tWdIbnJkVRhjzOIYpijbLhRHh779Cnj6DecmBLzS+//nqg
K3TnnXc+/PDDvaddGOaiwl76DMMkYZrmWGlhoSPdsqU8kgsd1UNLJW4PFWztfjJFtCFiZ4Vn
5r6eV49Htnbpp7xCYf/VqR6+YKx73t7A305EtzUoH6ZIe0oBqY/s/Tj66pAHG3ieP6G9ezK8
I0W0AQCghD7+wIaeQPj7P/v6mjVrWLTBXMzYq59hmOQ0TZuT9TW/WHbGlhjyoz2zK/h5Q8vA
wfP8odj6tpTTNyWuSYcib9XHPwQABPVmhQQduG/6zrHuK45H3+/QTgAA2tXjnfoJe8VoUhTQ
usiHdcb2FG0GAiHkeb4hus8gZ9jRChG857+X3PObJfNXVWYuDSvDjAgs4GAYJjlCiKZpV+V+
u8hRnaJqmow9430LquVrhlwpjeO4lnhNih0xHBKzxZKa8Cb7WwpoyGjrky/cxfkdvO94dMvp
zlMrZLSmDiYMonQpp4ZQ/4XjuEOx9SE9rcRoBaN8M6+u7FYbj8TfGkJwwzCfGWwNB8MwA7J3
dc7Juu2ouKlNORbUW3plA4NOLitHGuWXysq42UPOXoUxPqG+F9E7UrTJEovqlT1BvSXxiGIG
dTHOI9H454xGrjQ6oDeoViTRJmp2QggHyuRhC2hNQwgCOI7riaRbZeafaI/WzEkcy1/OXLRY
wMEwTCp2+s5KfkGVvLhO36GTuEFUDDkBOcbI8y3L0nX9bMqkIYRiWiD58s5/cvDeZm1/70cI
IAZRuF4Bh5vL7dRP9m6jE7VDO5aNK1NsnImbPbXq1kI0Y1DbVRBCUaM7/fa2mNnN1nAwFzMW
cDAMc2Z2MolCNB0iCPHpZJqxWOzszwwhNKwzjI7wUOo9dGGziMFBOfGtiF2a2jdriAnOMMtD
ATWJBtEgllbY6zCSrt4IdyvP/GTL6v+Y58119H9WJypbw8FczFjAwTBMujJUYCzpx7A9GHB6
QgSCZItIILSPhQBQQAEF/crWpy5k/0mrc9Hn9vrQmttf72gIlYzNXn7PrGSXYdEGc1FjAQfD
MMOJUiqgTwYqIIR2wvJuo86iBqEWgjjbLHLzuSJ2GkQl1IIAAAg5LKhWSKFBSiiEMG51y5wH
ng4+TuOgkPrqECAOiYNKxWEXiuORpFmfDPDUHuj41dfXh7uVq1dPWfbNmUkPFJB8fuq5MMyF
iQUcDMMMJ0KIk8uGEFFKMMYR0hrXQ3EzaJFPqsc1oY9LXVNNovJIpJSqJAwoRACHjc7E1Ea7
erxAHmdSjYOSvUxURM5cYWzqvTNuIadCvHywycoIIW4+N7GM4+DWxt/cs0GLGzf94PJrb582
4LX43CGnYWWYzwC2golhmOFkWValNM8nFHIcF7Qau7WGiN7ZO9oAAHSqtR6uwMFlx60eAAmP
JAf2UUp6L6RoU4/4+GIJeXUSs4ABIXDzefZoRIqrZ4ulQwgCLMvKFkvsuZjtrx375Z3rLZN8
6zdLUkQbECKfWMQCDuZixgIOhmGGmWEYJa5JQbMhoDX22nb7CZPqTfEDk7xLTaJFjE4M+Vyp
MmR8Kg1G3Ap2aCcmeD5HKDGpDiHy8vmpP+Al7M4WSw3DSNEmKdM0xzuW+KVSAED5hFx/kev7
T10/a8noFIfkSZVV8iK2J5a5mLGAg2GYYUYIKZSr86SqFHVbTkU/yBUrx3sWEmo5cbaHy9dJ
33mQmvDmYnlyuWMGBLBAGp8rjkkRcCDIVXouLeNmD2ElLKVU1/VS51QJu4rHZP18483jZhWl
aO/gfEXOiUNOjMYwnw1sDQfDMMOM5/nDoR3jnAs1K3oisiNpylGDKru6X5zjX+Xk/N1aQ6t6
xMsXdWqfSrwRMwMf9bxySdbyPGk0pbBDPZGFy5PGHBjyoz2XjZeXKIoytD6bpjlKnGt69ROh
7Srou2W3NwfnG+O5vAzPZgEHc5FjIxwMwwwne1tKU+zAsdDWie5rL8le5uSy+7UBOo2oVlgj
savzf1DmmK5ZEZnzoH7vYBAAH198Q/EvvHyBbsWTbrj1CgXVvqsmOq4fcnZUm6ZpY4SrxvsW
5MmVSVO/Q4jy5bHjfPMr+Hks2mAYNsLBMMxwwhgfjr2pk7hO4jXBd0uck+bkfKVbb+hSa+NW
0CCqgGQnn+0TinKF0S3K4ZcbH5jgXbwo/zsaifn4om61XqeKjL1ZQnGJPHmK9wut8SPvtPyu
WJ6a6x+tk5ima6oVpdTikOTgvFlicbXjGsMwhhZtnDhxQpKk7OzTIZGmaaXc7NHZVx5T3g5q
LRGzy7BUCCGPJDef6xOKxkgLdF1n0QbDABZwMAwzvBBCqnl6SsIgyqnIbpnzZgnFkzzVAnJw
SDSJZlClXtmzveuZuBkEAGzr+KNfLJ+Xe/s0zzIKCIaCSVTVinSpdVtan4qZAQBAWG938zlT
sj9f6JlMKbUTiBFCLMtSFGVo+TB27969YsWKioqK1157LVHyzTRN0zRHcfOwGyOE7HxlhJDE
tc7NbWKYkW/EBBwOhyMTZQjsEVdJks75mTPE7rDD4ZBl+YyNLxAj9CbLsjzi+iyK4nB3JF2J
mwwAQPqnXh4UaAFSG1Bre7dvVg/oIMJxpwuthaymemVPyGxtU49+6rwckLjTpzJANGQ1j3LN
PCfpttatW3fLLbdomrZ69eq8vLyzP+F5MEJfyRBCQThDxrYLR+L9bWT99mXoJqdegj1iAo54
PD6E3WtnZL/fjaC/QiRJcrlc8Xj8LKefzydJkiCEI+gmi6LodrsVRRlBfZYkCSE02ARW5x9C
CGOMMeZ5XhRF0zQJIV5c3GweVcyQ3cYe4fAI+QKST49wAAVDvjayK2722G28fGGhONHN5Xtx
yT9HOKJhvT2gNerk9P+am8/14mJN0/qMcNglcAfV7T//+c/33Xcfxvjpp59eunRpT0/PObwn
mSMIgsfjGVmvZFEUOY47J2V6zg/7JquqeuH/9iVk9Cbn5OQM9NSICTgYhhnR7L+oOI77OPJq
UG81aBxyhFpIgDLPCUWuKmrBduVEvjwGYtqtNzSEd396DUfh5TmrW5SaZuVgpesyJ5/VbdTX
hDeH9DaTGgKSXZw/VxozKfvqTuVUUG8pck7UQaRO2XE09A/VilFKOCQ6OK9PKJrgXGqaZprr
Kiila9asWbNmjc/nW7t27RVXXDGCPlcY5oLCAg6GYTIOISSK4qH4+sbofnsdBsZYgIJhGKZp
xmFH3AyN88yfW7D6YOiNj7peTYxk2Lr1upOxGAcdl2Qt+2LJT/b2/O39zpcKxLEd6ilKTw/h
dmmn6mJ7jgvvX+q/aXbWzVu7/tAY+6hAnNA711ZIb22NH2mJHypxTq2SFtmDH6l73tjY+Lvf
/a60tHTt2rWTJ08+1zeGYS4iLOBgGCazIISSJO0OPd8Y3U+T5djw4CKVxBri+3rM5nJ5JoZ9
35coBQJy6zR+KvZBxOjIESu9fJ5G4oloI0FEDoUE32j7qWpGeJy8WFpIb48a7+qe+GTnF844
11BWVvbCCy9UVFTk5+cP5odmGKYvloeDYZjMkiTpo/BfGwaINgAAlmVlCYUBvX5v4KXj0fem
Zn0BQ75PGwhQvjS2Uzu5o/tPHdrxy7JXxYy+CykcnG+i75r9wXWHQ2/FSU+uMHqgTKMWNU6G
dx5RNqaz0G/27Nks2mCYs8cCDoZhMojjuBPqP+qje5PmD7VBCKNmQLGCEMBDobfiVqDcOaNP
GyeXpVjBqNkJIToSeSdmdedJY/u0GeO+okHZ2xjfByGKmB09RmPSxF82Qs3a8K4Gc2cmtr8x
DNMf+01jGCaDeJ5vU45aNFXRMoRQVO8SkVvCbgjhkfA7Zc7pEH7y7gQhkrEnoDXzyOHmcigl
R8LvjnLO7H0SGXt9QuGR8NsYchJ2cUCKm0GMcYrrqlakW21IZNRgGCajWMDBMEymIITq9R09
WnOKNhDCkNWskRghRERuGbt7jEadxrKEkkQbETkUEqaASMgl4ywEcYd2HCPOyfkTbfKk0SGj
1aSahy8QgIsSqlqRFCMctoDW1DsoefPNN2+88UZN04b6EzMMMyAWcDAMkykIIcWKGCRVzhgI
oUFUe3UnJZQHDhn5NCtS6pzqE4s8Qr5PLPJL5QhyTpzNAwexiACcAnSqJFzmmpZoU+yYrFhh
GfmIReyzmUTvMVPNqgAAokbXKW27Pavy9NNPf+1rX9uxY8fHH398Tm8DwzAAsF0qDMNkjh1M
nLFN7wkXSgGlRDEjeUJVFPfYCbsQRCGrLZHE0G6jm1o2HqVjzW7jwUVN5seUfGqlCKEmRDDF
3lcKiEk0AMEvfvGLNWvWZGVlPfvss7NmzTqLH5phmORYwMEwDAAAQAgRQvZ4gJ2U85xkBO+/
czVpq37fE/DPBMwDHQMBlJDbxxcjyJlEE5Dcv78D7YvpzTLNe++/99lnn7WTbYwd23ctKsMw
5wQLOBjmYsfzPMdx9foOnSgGURHEPJLGOq6yLMswjIF2lqaDUirgMxT9oZSiXok3IAQQIZnz
BElDl3WcAAsBzCM5SyxCCEX1AKGWk8uudM2e6Lu6Qz0uUNGkuoN3W1Cd4V8uYkddbI9JTi/C
wIBLHTZBAL9/+y/eXr99ypQpL7zwwkgpksIwIxELOBjm4mUnAD2uvtMeOdajtfSe/jjGbfWL
ZXlyZZk4R9f1oY12EEIk7MaQt+iAhZAopTySIAAUAHuIJWZ18Ug6EHq9VTldmE1Aksx5ReTM
lStzhcoCaXx9fPeWrifaYkcTlVO8Qr5PLPLxxVfk3n4otLFTPYkRn8WXpa7B5OSz777tPqQ7
f//73zudziH8jAzDpIkFHAxzkcIYi6K4K/RcU+xA/4kPxQw1mQc6lJNxT2iC41pVVYcQcxBC
Khxz68WPutX6gdpQSn1cSQi3mUBVSShu9Hj5Eg6KHb2qxRpE44kW0BpHu65w83nvd/8+ZgYK
xepEtAEAiJk9EMHDoU0ljqkTvUtk7OnW6s7Y5yyheObVV1955ZWD/dEYhhksFnAwzMXIHtvY
GniyXTmeoplO4kdDWyxqTnJcP7QCxYZhFDrGB7TGFIs5KKVuPqdVOxQxOi1qTvAsro/t6T0o
QgE1iT49+0s8lN5q/wUP5TxpbOzT9VZMokOKvXxBXWx31Oye7b9F4tyWkWoFCY/kHLkiE2Wo
GYbpL61tsZFIpLn5k530zc3NP/jBD+68884tW7ZkrGMMw2SQKIofhl9MHW3YKCW14Q+Oa+8M
LUGWYRhV0qISx6SUl6Au3s9B0aLmWPc8H198PPp+nzZeoahYmvRB4NmoEZCwy8+XaaRvce2o
0eUXymXs6dJqj0Xem+RZCumAib8ggBXuGaP4y89mkQrDMOlLK+C4++67ly1bZn8dj8fnzJnz
i1/84n/+538WLly4Y8eOTHaPYZhzD2Ncq73fFD2QZnuLGk2xAzzPnzGPVlKapl3q+0qBY9xA
DTiO69Ebs4TSas+iyd7P7+n5a++5Ets491XHo1vjVo9fLHNxuW3aURef3aeNQbSI0Z0jVro5
f6d6qkU5lC/33XLy4aZa0yAQoHL39MmuL7IcXwxz3qQVcGzbtu3666+3v167dm1jY+MLL7xw
6tSpMWPGrFmzJpPdYxjm3OM4rkutM6me/iFBreVofFPqTOEDIYRomjY3645K96U8kvo8a+99
7dGb84QxXyx6OGJ0hY3WPm3cXK6Ly6mN7cgRRhdKEwJ6Q5d2ys6D3qelRmIy8hbKE2XsqY99
6JfKADjdhlLwl0d2PPrNDX/5+e4q37zp7i8PbWEKwzBDk9Yajvb29tLSUvvrTZs2TZgw4aab
bgIA3H777b/5zW8y2DuGYTIAYxzU+36on1FQb8EiNs1UVVEGYlmWoihTXV/yioUBtTGkt+og
jiBFSBA4J+LoFbl3WpbxZsv/LXVMXZj/b83xA+3asZjZpRNFRM7xnkU6iRdI40xiNMUPYIgx
5DQSdXJZihWhlCCIOSiI2CVhlwcXEkI8YlHYajVAPEcaFdbbdF3/nx++/f6rhwvLcr/1rW9W
S0tZtMEw51laAQeEMDHNuW3bts9//vP213l5eR0dHZnqGsMwGQAhrNN2KGZosAcqVvhsCqtS
SlVVLcazyl1zMMYcx9VpOyqkywEAR+Ob3+/4Q6daCwBtVY7kihUF8vhK52weyRqJisjl5fNr
wm93aw2qFQEAQADs+vUljqmEkJDZ4uWKKKV2vjI7JCKEuFC+gJwL8+4Jh8M3rPz81rcPT58+
fe3atdnZ2WwmhWHOv7QCjvLy8n/84x933HHH7t27GxoarrrqKvvx5ubm7Oy+06gMw1zIIIQU
0NTlW5MyiTa0NRy9WZZl//UiimKVe34sFkMI1cX2dKon/9mEdmq1nVotAABBTkAOncQn+67t
1uvsaAMAQAEwqaETxbIs0zQdIDfpThNCiGbG6+rqVqxYceDAgQULFjz99NMulyuRIp1hmPMp
rYBj1apVP/rRj1paWmpqavx+/zXXXGM//uGHH7I0wAwzslBKIYQY4sHGHBjyZ5yD4DgOY5xI
SU4IsYccUlUzoZSHn1rYwSM5V6z0i6Mk7BaQrJO4XyyPWV0IIAI+iRUwPPPbFwf5vXv3Hjp0
6Oabb/7lL3/JcSwRAMMMm7R+/e6///7u7u6XX365sLDwkUcecbvdAIBAIPD6669///vfz3AP
GYY5lyilFdLlh/Hbg51VEbAzRdzA8zzP88eVd0NKq2KFTaIhyInY6RUKJjiXGoZhGEbSwwkh
Ds5nf42hUOGaVe6cETSa29WjMTVgr+HAiM8WS4odU8JGW9hotyukcFA8U9pyJCDHNdcsWL9+
/YwZM85+eIZhmLORVsDBcdwjjzzyyCOP9H6QzYMyzAhlWZZXKBhswOEVCpKmrIAQiqJ4Unuv
OXwooDb0qZfWHDtUH/moxDV5kvM6VVX7T2cYhuHh8yXshgBNy/qiQoLvd/2+UzvZu03Y7JiR
9S/t2rEsocSBfR3aSQ7y+eI4XU+10cbF51RK8+Lx+MyZMwf1kzIMkwmDGGA0TXP//v0dHR1z
5szx+XyZ6xPDMBllWVaOWN4eP05BuqsZZM472XV9PB7v/5QkSYfjb5wM7xyoEn3MDBwLbokZ
gct8q/vHHJZlVXuuqfPu9nJFTer+/cF1pN9cT0BrAIBmC2WN8Y/yxaoCqcqkhr1KNEWfc6VR
LKkXw1w40l1z/sILL5SUlMycOfPaa689cuQIAKClpSUvL++5557LZPcYhjn3DMMY5/hcrlyZ
9hGw1Dk56VIMURSPKG8dD20dKNqwUUCbYgd2h56TJKn/1IaqqjOy/qVDP76v5+/9ow0AAAXk
WGTLBM9iDPk27YhOlVyxIukGXUqBZREAgIv3T/feyNKWM8yFI62AY+PGjbfccktJSUnvNF9F
RUVTpkx56aWXMtY3hmEyRdO0EudEF+9Pp3GRo3qy64v95y8QQg3mztrwzjTXnzZGP66Jb+if
Ip0QEtRb2rWjKZZZNMT36pYyK/smCHDM7NaJ0j/6MQ3y+Pc2/fF/vccjudJ9mWEYbEMKw1w4
0go4fvazn02bNm3nzp3f+ta3ej8+Z86c/fv3Z6ZjDMNkkGVZJeiysZ65PqEwRTMIYIlz8uXZ
tyVNkyUIQpdap1rRNC9KAW2OHewfcAiC0BQ9nMdXFTsmc1BIeiyh1u7A2hxh1FV5d7lwTtQI
9El7Go/oj9y+bse6483HQqX8pZXClalXeDAMc56lFXB8+OGHq1at6r+jrKysrLV10PkKGYa5
EBiGUYIuW5x3X6X7Ugm7+j0PvUJ+ddbCy3yrFUVJOlSAMe5WGwZ10ZDecSz+Tu9YASF0Stsa
UBsMwygUJpY5L8kSShDsm0MdQezis+viH5bJsy7LXpXFl0ZJe+LZYGf8Z6v+fnhn88z51c+v
e2yy7xq2pJ1hLjRpLRq1LEsUxf6Pd3R0DK2AJMMwFwLTNAkhU11fmu698XDszZjRYxAFQiwg
2c3nVjkWGoahKEkmLwAAGOMTynt9asSngYaNDuz4JJ7AGEe1gD0po+t6Fh6V4xzdbZxSSdgg
qkVNDDkBOUTk8vMVlmXVdL+bI42a4Vthwrhh6qoZPXm04adfebG9ObDs5quf/u1aSikb22CY
C1BaAUdVVdXWrVu/+c1v9n6QUvraa69NmpSq6jTDMBc4QoiqqhDC0dxCJCB7FQWl1LKsWKxv
/ffeIISGpQAw6HIkBlF6r9WAEPauDWunIvWi0iwe2QnEEjnLE2FEp3qqS62bmP25yc5rOzs7
b/jS9GAw+MMf/vB73/ve0Eq9MAxzHqQVcNx6663333//1VdfvXLlSvuRaDT6ve99b9euXU88
8UQmu8cwzPlAKR3CRzWhQ9l0SqhlhxG9rt53vsZOUZriJBRQxQybpulyuf7t3/4tKyvr5ptv
ZktEGeZCllbA8e1vf3vz5s233XbbAw88AABYvXp1fX29ruvXX3/9HXfckeEeMgxzIaKU9q81
nw4eSZ+ONiiPkszYpn+ePoOvDMNcmNJaNMqLhDm5AAAgAElEQVRx3Lp16377299WVFR4PJ7W
1tZJkyb9+te/fuWVV86meiTDMCMXIYRH0hBiDgfn6z0UQSl1cFkADC7vOIRIxh5WX55hRpB0
M41ijO++++677747o71hGGakoJSWC3Maxf0dSm36RwlIdnJZpmkKwuntr5ZlVTkW1kY+iBrd
6Z/Hy+fbacsH12mGYYYPG59gGGaITNPMl6sgHMTbSKGjuoyf3WdKxTTNAse4dA6Ph7XNzx8E
ABY4xrP1oQwzsgw4wvHHP/4xzVN89atfPSddYRhmZDEMY6y8sMfR3BQ7kE57N5/nl8r671nV
dX2a+4aA2hjQGlMcHmiLPnLH603HAmWFFV/6yrWKoqRozDDMhWbAgONrX/tamqdgAQfDXLQ0
TZuddesW8rsO5WTqlg7OV+m5tARd2r++CaVU07Ry93SDaBGjI+nhzccDj9z5endL9HM3zvj+
zf+laRpbwMEwI8uAAcemTZvOZz8YhhmJ7DQe87L/dXfo+ebYIYsmLZYG/VJZmXNqGTdnoJRc
pmmW8pdBL2iOHe5QTvYpY1vzQfOj39ygRLTV3136+MMvaZrGysAyzIgzYMCxePHi89kPhmFG
KMuyVFWd6bk5S3yvU6kN6q2KGaaAAABF7PDw+TnSqAnOpbqup04AahhGEZ5VkX3F0fimTvVU
SG/VrBgFdM/GU7/73iZikX//1Td/cOfPVVVl0QbDjETp7lJhGIYZCCFEUZQy7vJK75UY41Pq
dosaCGIIULkw2zTNgfKj92FZVjwer+QXVMmLEUK16jZCzQ+aXhA48Znnn1m0aBFbt8EwI1e6
AQeldPPmzR988EEgEOiTzu/Xv/51BjrGMMwIY5qmvXOkAF2SSEk+hBDBMAzDMCCEhXA6hPA/
v3/pbTf+W1lZGduWwjAjWloBRyQSWbp06bZt25I+ywIOhskEhBDP8xhjhBCE0M72rWnaYBN4
I4QEQbDPYxclsSzLMIzMJQI/J2e24xX767KysrM/IcMwwyutgOOhhx7asWPHz372s2XLlk2Y
MOH11193u90//elPe3p6/vrXv2a6iwxzsUEISZIkCMLe0F+6tHrVChFAJOT0CcVuPm+8c4mi
KOn8uY8xlmWZ47hdwecCeqNqRSCAEvb4xfKZ3pvsSrCs/gjDMOdHWgHHK6+8cuONN/7whz9U
VRUA4Pf7Z8+ePXfu3NmzZ//3f//3mjVrMtxJhrmIcBzndDp3BJ8+3LKpQznR51kX72/xHPpc
3v2qqtq/jwMRRVGW5Xe6Hq0JbQ7pbX2e/bD7bxO8n7si++uKolxQxdzD4bDH4xnuXjAMc+6l
lSKwubl53rx5AAC7coq9jR5jfNNNN7ERDoY5h3ied7lc69r+1z/aHu8fbQAAokb37u6//LH+
q8eMjbIsD3QeSZJOmJufb/jGzs7n+kcbAIBurf79jv95qeV7DocjkWV82NXU1Fx55ZVPPvnk
cHeEYZhzL62Aw+l02kGGIAiSJLW0tNiPezyetrYk72UMwwwBQsjhcPy99YcHgxsASLWnoyV+
aGfnc8f1TUljBZ7nJUnaG3ipPrY39RWPhbe82HSPPe1yVl0/F95///3rrruupaWFbUVhmM+k
tN5lKisrjx49an89derUF1988cYbb7Qsa+3atSUlJamPjcfjzz///I4dO4LBYHZ29tVXX33j
jTfaT+3Zs+fZZ59tamryer2LFy9euXIlhIOrGMkwnyUOh2NL4LHDwbfTadyl1dWE35lY9Pn+
EyKyLL/W+u/N8UPpnKc2snNT5yOL/N+NRCKD7vG5s27durvuusuyrF/96lerVq0axp4wDJMh
aQUcV1999VNPPfXoo4/yPH/HHXfceeedY8aMIYTU1dU9/PDDKQ7Udf1HP/qRZVmrV68uKiqK
RCKJv12OHj368MMPL1269Lvf/e7Jkycfe+wxQgh7o2EuWhzHHVE2nnFso7eT4W17nC9Mkb/U
e0hAFMX9kVeOhN9L/9KHghsK5fGV/ML+ScfPjyeffPI//uM/ZFl+5plnFi1aNCx9YBgm09IK
OB544IFbbrnFXs1+xx13hEKhp556CiH04x//+IEHHkhx4GuvvdbZ2fn444+73e4+T7388svF
xcXf+MY3AADl5eWtra2vvvrqihUrRFEc6s/CMCMYz/PBWHPS9RYDIYA0xvZNd3+5z3laQgdN
kmo9aR+KFe5QT47zLhmWgGPDhg0PPvhgfn7+Cy+8MHny5PPfAYZhzo+0Ag6v1+v1ehPf3nff
fffdd186B27fvn3KlCnPPffczp07JUmaMmXK6tWr7eCjpqZm/vz5iZbTp09fu3ZtbW1tdXX1
IH8Ehvks4Dgu6SrR1NrUYxjj3o9gjNvV44M9T4d6jPMPzzKOJUuW3HvvvatXry4tLR2WDjAM
c35k9i2mtbW1rq5uzpw5//7v/x4Oh3//+9//5Cc/sbfRBoPBrKysREv760AgkHiktrZ2/fr1
iW+vvfbaoqKic95De62cvftmRLA/XURR7PMxcyHDGEMIR9xNFgThfPaZ4ziFhBAe3BXjpOdw
bMM49+cghBBCp9OJMY6T4GDPo1hBezvuoI46G71v8s9+9rPzdt2zYb+Sz+ddOkvD8ko+S3aG
uhF3k3meH1l9ztBNTp3XZxABR2dn58mTJ7u7u/vURLjuuutSXNvpdH7nO9+xP9cFQXjwwQcP
Hz48YcKEM16uvr7+mWeeSXx72WWXjR49Ov3eDgrP8xk6c4bwPD8S+zzcXRic83+TLaAjOLgP
BgIMSkliIpLn+Y9DrxOg9T8PBBBCDACllNB+y0RMqCGEUuyzzRD2Sj4PRuJNvhC2TQ0Ku8m2
1IUV07peT0/PN7/5zbVr1yYNXlLUZMrOzvZ4PImfys5P3NHRMXHiRJ/P19PT0/sSdvvEIzNn
znz22WcT3/r9/mAwmE5vB8V+p9Y07ZyfOUMEQXA4HIqijKw+QwhHVofP/012Op0CkAdVBxVB
7BMKeSRqmnZK3Q4gqBAvn+S+9oPuP6vGCYuaAAAMOZnzisjJIUEjUQCAiFwG0TQrplghQk9f
TgAuQohhGLXKNgBApTzXzoBuWZb9C85xnJ1nHUJ4KPLGRPe1AABCiGmaQ7tL9l+EI+6VjBBK
nW/tgmLf5DPmiLug2Gn4R9DWaHaTe6OU9p676COtgOOuu+5au3bt8uXLFyxY0DsmOKNJkybt
2rXLsix70KmxsREAkJ+fDwCorq7eu3fv7bffbrfcu3evJEmVlZWJY91ud+/1HKFQKBMr2uyY
dAQVhbKjN8uyRlafIYQjqMP2y9X+ND1vF7Usy83np1NS1ebks5xcNo8lGWW93vwTCxkA0ANk
47Sc60Tk9ItlcTMEAHRwnpDZFtRaNBK1iA4g5KAgYbcTZ/nF8pgZiFshCIHMedrVY1vbntaJ
iiA+hDZ7+Dy/VFbtuMY0TUEQjigb2yNHW5WaHr1ZscIb4Bonl5UvVxXLk2d6V6qqmmbc8N57
77W0tKxcuXJYbvJZsn/7RlCH7ZmUkfV2YQe1I6jD9k0eWa/k4brJaQUc69evX7VqVe/xhjQt
W7bs3Xff/a//+q/ly5eHw+HHH3+8qqrKDiNuuOGGH/zgB0888cQ111xTW1v7yiuvLFu2jG1R
YS5ahmHkS1UAwDNui4UQeoVCC+hNysfj3Ata40fjVoiDHADAtJRW5YiM3ccj75U6L1GtcIOy
T7V6JdigQKeKTpSw0eHAbX6x3Im8bcqxAmlcS+yQakUBAISaJtEUM9SunIga3dNzlu/seW5f
z6thvSNxGhNoqhXp1hqOBN85Fd1V7V00zrEkHo+n7vlf//rXe++9FyG0aNEitkSUYS42aQUc
GOOZM2cO4ezFxcUPP/zw008/fd9997lcrunTp3/1q1+1s3uNGzfuwQcffO655zZu3Oj1epcv
X37zzTcP4RIM89lgGMYM70014bcbY/tTt/QIBQaNt6vHeSiVOad3KXW9n+1S6gpdEzq1E916
fVhvQxAPFMIoJNyo7M8Xx451z5vq/eKW1qf6NJA4d5V33tsd/29v4CUeOZJ2hgByIrKtR28k
OeZ4+doUg7SJZBtPPfVUXl5e6p+RYZjPnrQCjgULFuzde4YcyQMZP378z3/+86RPzZo1a9as
WUM7LcN8xhBCdF2v9i7uUE9oVmygZg7OR4HRoZ6wqDEze4UT+Ru0A70bxIweP79wjPvKN1p+
agHDhf08kvR+aTkgBCbVLKJ3aCfm5Hw1pLfHzECfNtNzlu0P/31b59MAAgqJAJ0DTfh0aw27
A3/Bfr6Cv6r/1KdlWQ8++OAf/vAHlmyDYS5maS2Jf+SRRzZu3Pj444+zStYMkzmKolziWnGp
fyVGyZe7Q4icfHZAbzKpPsHzuQnuJbWh3X3a8EimFPi4osm+zwMKFCvMIRGBTxUNgABY1LCo
gSCemf1lD5evmGEMP3XRImd1j1m3vesZAixCLYOoMOUOmg7lRENsX/99Lrqu33777X/4wx+q
qqrefPNNFm0wzEUrrRGOMWPG/Pa3v12xYsX9999fXl7eZy/Nvn37MtM3hrnoxGKxuVl38kja
3b02YnT2eVbCbsXq0a3YzOwVUzzXHw9t7z8WkiuNqovvPBp+d0b2v8jY/WHgbzpRMBJJ70EO
CCixHNg7239roVi9ufXRaVlfzBKLu9S6RJNy14yPQn9LDHuYRNNQJMUgBwCgJvx2mfOSUdz8
3ovROI6z52Sff/75QS05ZxjmMyatgOMvf/nLypUrKaWyLJumOYLW4jLMyEIICYfDM923uLic
pvi++thH3VpDYg1GllgsY8803/IsvrSm513FTFJuzSsUHgh/GDG6dnQ9Ny3r+iWFP6iL7e7W
6rq0ukSbLL640DFptHOOQfT3Op7QrFiHenyUfFki4OCQ4BUK6mKfDJ9QAExiCBiCgSMOzYr2
6I1VbqH3WwRC6LHHHgP/3ILOMMxFK62A46GHHiotLV2/fv3EiRMz3SGGYaLRaAW/oDrnGpyP
P468qloRCogAnTOyVhwJv90Q3X8wvHmAlaBQ5jxBowUAoFnRD7peLJCrRrkunZ/zry3qQc2K
AgAlzlMgjm9Va46G3mtTTleBDuotsvuT8gVuPq9R+bBD/VSqdQJMCGD/pGG9BfTG/jlwWajB
MAxIM+A4derUj3/8YxZtMMx5YxiGvfpyNL8YcQgAQCnVNK2m5x9xc8AMeBziIUD6J/MstE05
2qGeCHs6BODkkQQACBmdtZHtzbFDvQMHjcR4JCU25cqcWydxAj6VhSydHCGKFba3oTEMw/SR
VsBRVlam63qmu8IwnxnonwAAlFJKaSJl52D13vTB8zz89EJvCKCTz3ZyWRLvAgDopiYgB4Jc
nzYm0TQrnggFDKr3Sfjxz6GL048QSmB6K8r7QADX1dWxtRoMw/SX1nvKPffc86c//SkajWa6
Nwwz0mGMZVlug3uPG5sPxF/ZF/vrYXXdKWuLw+EQRfEsa2gRQngs2V8jiAsc46b4/z97dx4Y
VXkujv9dzjb7ZN9IQth3ZRFBRHFXioq2VkTc5Vq8bW9ra7W2va2Wqq3aX6/3a1utXlt3XLCu
iNYVQWRVQQlIQkISsiezn/19f3+MjXGSDJOQbZLn81dy5j1n3nMYkifv8jxLc1xjTRxrNata
zUMaCoTYkVPzbpjgWSRgCSGECRaoZKJom32oyTzQZB5os6uc1C9QsfNQhEI9pv11Cg3NConE
Eb9Ch1TqvLz9jwMzZ8589913j+U2AQAjUkojHMXFxXl5eTNnzvze9743fvz4hF0qy5cvH5i+
AZBOMMayLB8yPmwIHGjRqiz2jVTfFaGtBY7Jc3zfNQyjz0n6GWNeMSegH3EIvvHeBa3moY9a
/9GsVzJudeRXrooWC4QWOGYuyr1mT+C1Bn0fwSRg1LfrdR3XIYiaXDN4TCFezhnnKFMuiXTK
wxEyGucrlxY6ph2Ofb0HjWAhyQIOxviGu+q2rfskPz8/JyenbzcIABjBUgo4LrroovgXt956
a9dX+zZQDMBIgjFWFOWL2OsVoa1mlyxbCCHVClaGt7XoVeM8J5ZKJ/VtjtK2bb9U1C4dmeBZ
+EV44/7Q+xwlpsbR7DDm6MPmhyZ6T52ZsVRtDRJMdTuS0Eah3pDZYHPTRbMIJrnyhKBe39GA
Idau15W5FnQEHBhhioWetqhYBl9/W/XnbwbGTS5+8dlXCwsL+3B3AICRLaWA47nnnhvofgCQ
1mRZ/jz22oHgJs6TJccLGU37A+8jPyoWFvRhe7llWROdp3nE7I9a/1ER+ajbNqodyhbHOsXM
z4MbImbLiVmrKsNba2LfSJces4LZSmmINqh2CKGWGd6lHlpQo+/t3OZg6KMiz4wsubRVr0YI
iUSRsafb1H9q0H7qh5WHd0enzit965+bYU8KAKBbKQUc3/nOdwa6HwCkL0EQKvT3K0Jbk0cb
caodqorsHJ99St+WkXLOD2s7O890dGnAYlabTywIm43VsR0FjqljnDMPR3d3bsO4FbPas+TS
erXcJWSPcR13RN2bMF3SrteO85xwcvZ1G+rvsrnlErJ4D4mG3/1z/eHd0flLx//rmd2maUI+
YgBAt3qxhM2yrJ07d27YsCEQ6HFXHgCjkCRJ9bHyhEUbSQT0I3siL4ti9/nLkyCEVBlbWtUa
v1wQ3+PaFcYoYNXpdqTQMcMn5ZeH3sWYZMljE5pFzDaK5ImexQuyVh2JfV6nf9J1O+vutlfG
Ouafmfdjn5TPWY/R0Vk/Llz5ywV/eewezjlEGwCAnqQacDz99NNjxoyZN2/e0qVLy8vLEUJH
jhzJzc194oknBrJ7AAx3lNJKbVPnPJ6paFIrEhZfp0IQhKDRGDNCXlyYKRe5xMxu6ptgbHPT
ZKpXyMuVJhJMjqh785XJid3GYpY0drb/4lx5UswKGkztuoOGcFId+XRJ9vfPyr1pjHMWQt0k
2HBQ78Ki7/7j15smSmfC5nkAQBIp/cjbuHHj5ZdfPmfOnJ/+9Kc333xz/GBhYeGsWbNeeOGF
VatWDWQPARjWKKUhtTmVyZTOQmbjIf3DAjKvV0MClNKgUY8QYoy5cL5XLgoItbodMW2VYYYQ
x5jKgtOLc0TkDOj1CKEcaQJHaIr3tFajWrPDGGEH9WZIxTnKeBfJrg3vkYlznv/SEKvnjIf0
ZpNpGFGJOrxirk/KHycvDgaD05ULZ3sv2R58slH7MmDUqXZIwLJLyMhVJmTLZdOcSyORCFQ8
AAAkl1LAceeddx5//PFbt261LKsj4EAILVy48MknnxywvgGQBjDGut1NTZPkGLcNpmHSu6Sc
GOOO/Sacc8uyPLjAJxIsYUIIxti2bUJIbeyTkNUcX5Ohsyjjtl8smue/VCQKR8xketRsC6j1
h41P423a9JpC5/STsq82TTM+sRLPVGbbtqqqCCFVVXVdnyl/e65Hwhh3tLEsyzTNcLjXtw8A
GIVSCjh27tx5xx13CIKQ8EdMSUlJfX19T2cBMBpgjC3el7waFjMw7XXAkfBe8cgAIRSfoLEs
K4abVTvcsQKUcx4xWw+ru6uDn3S7XxchZHOrRa/qCC+6xRjTdT0Wi/3yl7+84IILFi5c2Kue
AwBASms4bNvudqtbU1NTHxa+ATCScM4TMnKmSCBSb3eppPJePqGQ4G+UTxOJw0cLLJZsgYWA
5aN2RlXVq6666uGHH77zzjtT7DAAAHRIKeCYNGnShx9+mHCQc/7yyy/PmDFjAHoFQNrgnCvU
09uzKBYk4uhDwHHU9+Kc028GJS4h02Bq1xRhnTkEd/LOtLe3f+c739m4ceOiRYtgqTgAoA9S
CjiuuuqqZ5999tFHH+04EolE1qxZs23btquvvnqgugZAOrAsyyPlJNRLOyqvlFcmL+rtJlLb
tn1yfvI2nHOZOjsfyZHHhYym5Gf5pIL41Ey3Dh8+vHTp0m3bti1btmzdunU+n6+nlgAA0JOU
Ao4f/vCH55xzzrXXXltaWooQuvLKK7Oysh588MHzzz//+uuvH+AeAjCsMcbKpEU5SllvTsK5
jgl9yzTqFXMd1Ju8Pwr1dMyqyNSd75jcph9OcopD8HnEnJ76U15efu655x48eHDNmjWPPPII
JBIFAPRNSgGHIAivvPLKAw88UFZW5vV66+vrZ8yY8ac//enFF188xuqXAIwApmnmOyeLxJFi
+yy5eIZrWR9KuDHGSoQFxe5ZuLuUGHGccx8t8ohflU+b5DmVciVstvTUHiNc7JpVIizoabhl
zJgxhYWF//3f/33HHXfA/3cAQJ+lOg5MKb3xxhtvvPHGAe0NAOnIsqxxymLDGz0Q3GTzo4xb
uITMEs9swzD6VvXQMIyZ7gtjVrA2uqenNrZt50qTTKblyhPHuxaVB5IVix/jmjnTfUGS/Slu
t3vDhg2wPBwAcIyS/b2ydu3armtFAQBd6bo+1XneZP+pMnUlaZYhF03ynVxC+1K5LY5zrmna
if4rx3rmJuxG6dyG2fzErMtPzV1zKLRdt6PdNiOYjvXMm++/QtO05NEPRBsAgGOXLOD41a9+
9d5778W/rqqqys/Pf/XVVwejUwCkG865qqqT5LOmZ5w5xjUjIezACLvF7Am+k87I+fEYcuIx
pgBnjGmaNsdz6YyMs7OVsRR/IxqgWMiSS6b5z5jnuTyXTil2H5cpF9NvrmkVsJSjlM3IOHuO
57uqqkIBFADAIEh1SsWyrMbGRk3rPnEQAAAhpOt6IT2h1HsSzaDl0Tc1FmHMEomiCJ6JjtMs
y4rFYn2bSUnAGFNVday4eGLW6Yf0LTErwLCBOCJIdAq+Mvlk0zSj0ShCaLy4ZEr2WYf0D2NW
0GQaQlgkilPwj5UWmqbZdSYlFotVV1dPnTr12DsJAACd9bp8FAAgiXhGcIxxmXBqPAt4vIZq
/Nd//zJN0zTNAjKHiESWZUJIfLgiFot1aTOPiKQjJXk8Xul6wZaWlssvv7yqquqtt94qKSnp
9w4DAEYzCDgA6DVKaUcw0ZFcvLN4nZHkF8H4qwIoHUFJ36Y24icKgpDkTVO5eHV19aWXXlpR
UXH++efn5eX1oScAAJAEBBwApIoQIooipbRC+8CwYxbTBaLIxDnOuThexizF6RJKafw6B2Lv
GCzGuC0SWabuMuei+IDEQN9IV7t37165cmVLS8vq1avXrl0L218BAP3uKAHHP//5z6qqKoRQ
KBRCCP31r3994403Eto8/PDDA9M3AIYRURQlSdoVfLZZq4yYrR3V0TAmleLHeY6JszzLdV0/
6sCGLMuHrY+aQ4da9GrVCnYcp1isknbmOydPdZ6j63qSvJ/97t1337322muj0eivf/3r73//
+4P2vgCAUeUoAcfOnTt37tzZ8e3bb7/dtQ0EHGDEk2W50vigsn1bpEsGLc5Z0GgMGo3N2qGx
7rkl0sKeNqFgjBVFKVc3VoS2dt2qanOzTa9p12vb9JqTM1enErv0C9u277jjDtM0H3nkkfPP
P38Q3hEAMDolCzi2b98+aP0AYNiSJKnS+KA88J7BYkmatet1uh1FPjRGOLHbWEGW5S9ir38Z
/DBJcjCOeENs/zv2/5ye81/drg7pd5TSJ598sqam5sQTTxzo9wIAjGbJAo558+YNWj8AGJ4I
ITX2xxWhj5JHG3ExK3AosmN8zim2bSes5xAEoUJ/vyK09aipSBFCbXrNlrb/W+C/OkkC0H5U
WFhYWFg4CG8EABjNYGkYAMlIktSiVUWt9hTbB/Qjn4ZflCQp4bgkSUdiX5gs1Uw29Wr5l9o7
kOITADBiQMABQI8wxpTSRvXLXp3VEDtA6TeSjlNKD2rvtWrVqV+Ec9akVggC7CMDAIwQEHAA
0CNK6RfRDT3VIulJxGyp0D7oHHNQSoNGQ8fGlhQFjfp4oo5enZVcdXX10qVLKysr+/GaAACQ
Cgg4AOgRIUS1Qr09iyOu2eHOgULfrqPZ0UptUz8GHDt27Dj77LO3b9/+5ptv9tc1AQAgRRBw
ANAjjLHF+1JozWR650Chr9fhFjP6K+B44403Lr744mAwePfdd3/ve9/rl2sCAEDqYIYYgB5x
zhNqsaYCYywJitPp7NiogjEuck4PGY2pLxqNo1jsl2JvTz311E9+8hNCyIMPPnjhhRce+wUB
AKC3IOAAoEec84RC88lhjAVBIISaKPZe6/82qOUm02Xq8kn5WfLY0wq/Vx3Z/WVgE0Mp1UwR
iUKwwNmxBhx/+9vfbrvttoyMjCeeeGL+/PnHeDUAAOgbCDgA6JFt2y4hUyCSxY4+IRKvtFKn
fabbsTGOmdtbn7WYHn8JY2zwaKFzxnG+ZQvzr9ze9GwqWT18Un6ptODYU3Gcc84569evv//+
+ydOnHiMlwIAgD6DNRwA9IgxNlZamK2UHbVlPNqoiG6uje0pdExv0as7og301UiJ+1Bk6+v1
d1XGPlyYt0ogiYk6usDZSlm/ZBotKSnZsGEDRBsAgKEFAQcAyZimme+YJBIlSRuMsSiKldGP
WvQqr5hf7DyuIrIloQ3nXCIOzQ6+3fCnQ+qW2VlHWUiRpRRPdy0dksqxAAAwECDgACAZy7LK
pJPHexcQTHtqQyk9ou9t1itl4joh89ImtSJsNiW04YwrxCcSp8G1D5ofivLmnJ4HTpyCv8R1
vGEY/bJiFAAAhgMIOAA4Cl3XpzmXTvIt7nacI56NtE0/7BayF+VcZzPrQOiDbq/DOXPRTJk4
g8aR6uiOCb5F3TbzSrmTfItLhIV9qxa7Y8eOurq6PpwIAAADChaNAnAUnHNN06Y6zlOopz5W
3qJV2fzrmQ5CSLt5uMQ5d5zrxDa9Zl/oHd7DJhTOEefMSTMJFg5Ftp2SvUYkSueNsjJ1Fzgn
z/NdZhhGTzXuk9uwYcMNN9wwbty4f/3rX5AWHQAwrMCPJACOLh5zFAsLxmUsrjK2RMwWzY7Y
3BSw7JJ8Njbb9bovgm+36YePeinGmNcK3B0AACAASURBVIw9qh2uUrfPyjy3STvEuC0S2Sn4
p7nOs21bVVXGUto3m+Cxxx77wQ9+QAi56aabINoAAAw3afNTKaEaVv9eNo1qcsY7TClNrz7H
l1UOdUdSFX/I8Y0nCS9ZllUiLCDS1yVORFF8q/menW3PI4RSzwrKOTNZbLz7grHyVxMrjDHT
NDnnlNLefto553fffffvfve7jIyMp59+esGCBb06fUik6Se520/FsBWPO+EhD6gkPy6GraF6
yGkTcAiCMBB/tKXdH4LxD7cgCP1b02tAxQOOoe5FL8Q/FaIoptJtQojKApgktsTo6yPdlm1j
3CKEdCwLJaSPC6osy/rhD3/46KOPjh079qWXXpo0aVLfrjPIOj7JQ92RXoh/kmVZHuqOpCr+
oYKHPKDgIXeWfHQ2bZ6RrusDsUXQ4XAghI49t9KgURRFFEVd1zWtd0myh5CiKBjj4f+QRVEU
BKHa2IowY9giXECclEoLLMuyLKunDSMul0vGLmZ//d8ME4wR1nmYI845JxhLxIPi33S6iITd
qqr2ba1GXPxvlNra2n++vH7qcRMeWHc7zW3ifKJt26Zp9ksOj4Ejy3L8kzz8PxgdFEUhhMRi
R0/aNkxIkiRJUno9ZFmWBUGIRntXonkIxR+yYRhp9MEY0IfsdDp7eiltAg4ABg6lVJbl8tib
TaGKgFHPsCFJkmmamAnV0q5cx/ipznMNw+h22whjzCcVxr/GGGOMVRawmGFzs2NgQ8VhikUR
KzLxcM44Ry4hY7bv26FQr0vIdpBl+bC1tTVyuM1Re/Pfl+aX+Rukj+ta7APiBxnymBxlbKly
kq7rsLEWADBMQMABRjtRFGvZx3VtnzepFfEQoWMJhcm0Fq2qRatuUiuL3bOKxRO7DrPpuu4V
81xCRowFDB7RrVjnPSxxjDPGdQvpFjdcQhZirMg5kzHWt8WhGGNFUfbFNhwKb9fsCEJozOSM
+IguRzxitkbM1sbYgYinbYbrfE3TIOYAAAwHkIcDjGqCINSyjw+GPmpUD3a70gIhhBBv0Q59
Gfywxt7adaaWMTbFcc5U/xkGi2h2uGu08fVVEDKYGraaBCqP9yzs82SKoih7oi/tD34Qjza6
ZTD1y+Dm3eHn4vNZfXsjAADoRxBwgNELYyxJ0uHIpyEjMTFoVxGztSqyU5blrr+/DcMoUKZl
y+MYP/qIhcWMKd7T5/gu6dsqHEmSvghvqAxtY/woSzQ4YlWRnV/EXpeko9ZtAQCAAQcBBxi9
RFHcG3mlRatKsX27Xrc79ELX398YYw/JXZh9ZY48/qgXOc5//smZq7+MbOrDnjSM8SOPPHLp
GT8Ih1Ja7cU5q47sFgShz1tgAACgv8CPITB6CYJQr5b36pSG2P6EPcmEkGpz646W9TL3npn/
X1O9ZxDUfRYNmbpPyVl9bt7PP2l7pSq0o7f76Djna9euvemmm1rqA6314RTPUq3gJ6EX0mvP
HgBgRIIfQ2CUopRWaB+EjZZenRW12g/E3i6lJ3fsWKGURo02k2mftW0Y65m7LP83Ez1vV0a2
1qqfhs1mm1silrPksSWuOWWu+fnS1K1NTwaNRpEo1cZHeXh2iis6DcP4r//6r+effz6/JOvH
fzunoMyfep/bjSPUPSB58wAAIHUQcIBRihCiGqGe6p70jMesABa+McIRswLxr6vCO+uin0/0
nnRGzk0uwV+t7rS5TrFc7JgdNBpqI3veb/0/hBhCyGSayTRCSCrZMqLR6LXXXvvOO+/MmTPn
hw+dTry92+4fswIwpQIAGHIQcIBRCmPcuXBa6kymd55SSbiOybQvAu+gwDsScToFn0gcGgvv
a3ufscQcHgbTME1p/8jll1++efPmM8444+mnn34/8v+pvSwiazH9kLYlDx8P+2MBAEMIAg4w
SnHOCf7GRANG2C1meaV8RXApoku3VM0MB42miNnSeSAk4SzOOcXd/D8yWMwwkg1FdHtWt265
5ZYXXnjh7rvvdrlcNNrr/7ME0zLlpDRK3QgAGJEg4ACjFOdcJh0peHGWUlzonBaxm1qNww1q
K1NNikQH8Wc5S8vovPrYvhatKp6oQ6LOzkMFnHOJ9JjKtycYYYk4UhxyWLhw4cKFCzu9V2uv
3ksiLhjbAAAMOQg4wChl27ZCPTJ1Wcwo85xg4MjuwPo6dQ/jNiaYEhrPBIoxKXRMG+9eOFE+
uTL0MULIJWR2Xnhh27ZXysUI95w3rBtuMWucsri3xRcYY14pt02v6dVZPim3bylNAQCgH0HA
AUYpznmptLBR+dIj5rSYFZ+0v2KwbiYdOGd1sb1N2sFZ/mWT/ae26TVjpYWdS2HZtj3BuaRa
2hUw6lN/9yyltA/F1SzL8kuFAt5j8VSzlBJMM+XibqvAAADAYIK162D0Mgxjou/kduvwzrYX
uo02OphM29W+vsk4MMW/pGs5FdM0C13Tccr/m5yCf57vsm6rH3POH3744Z5qe9q2PU5eXOCc
kuIbIYRyHRMmKKdBwAEAGHIQcIBRLWQ2VsV2MJTC72POqmLbguaRrq9YljXFcXaJ+/hU3lHA
0jjviaZpdp3mMAxjzZo1P//5z3/zm9/0dLqu6ydmXOmXC1N5L4+YXeic0ueiLQAA0I8g4ACj
lyiKDbEDbpLjlwoT9p4kwJj45EIfLToSKe+akpxzruv6PN9lpe7Zycc5ZOqa5F88UT69axAQ
jUZXrVr1wgsvzJ49++abb+7pCowxXdfLPCdkySXJ784n5Y/3LhxDTuzD3A0AAPQ7WMMBRimM
MaW0RauybCtbHC9gKWK1alao68pPhbrdYnaGUGJZVotdVWV8VEDmJIxPMMY0TZvrvcwlZtZG
93StBocxyVXGFzinjBUXdS3b1tjYuGLFir179y5ZsuTRRx91u91Jem5Z1hhh/vicxbuCz9bF
PtftxMkgkTgKnVNP8K80DKPbiRsAABh8EHCAUYpSui/6Zvy3tWVZXlLkV4oDdq1uRxkyEeaI
YIIEmbj8QjFjLL4MwuJGzGqnEu06IRKPOSZKZ05znVceeytkNOp2xOaWSBQH9XqlvHHyYtM0
dV1POHH//v0rVqyora1dsWLFH//4x1SKulmWxRg7zv3tDLkoarWHzWaGTY44YaJbzHKL2aXi
AlVVYXMKAGD4gIADjFIYY4N9vSs1vgnWgwt8IiGECIJg27Zt25zzhBWXhh3rWqE+jnMeH1Qo
o6dQN8UYY4w554wx27Z7WgpaX1/f1NT0s5/9LMlMSlfx+CafzKESJQqRJAljrOt6/L26DqIA
AMDQgoADjC6UUkqpbdsYY5snTjdwzuMvIYTiv7m7XqHrWV0vYllW6htDlixZsmXLltLS0hTb
dxaPkxBCGGNCSNfhEwAAGCYg4ACjgqIosixTShFCe0KvIIxmus932G5RFDtWORBC4r+2Mcbt
Ri3n3CsWxMcnOs9NCETp98SdfYs2AAAgjUDAAUY4QRDcbven4RcPB3cfju5sMw7HrKBEXdtd
6yZ7Tms2v8xXpsRHIwJ2rWaGNBblyEQYIY5b+WGZuhzU6xeK49MrCCGn4INM4QAA0FsQcICR
TJZll8u1ofF3H7c8FbXbOo5rdmh/+P0y14kBs1a1A/nK5HbjSMho5pwhhDDBFFPGbcZMk2lR
q121w4XKdNu2FeKd7DyztynJO4tviJUk6djvDgAA0gjk4QAjliiKLpdrXe0P3mn8f52jjTjG
rVr1s2necwSifBnZ1Gwc7GElKOKcRcyWw7GdEV5f4JxiWVafRziCweAll1xy3XXXQW4MAMBo
AwEHGLHcbvfL9b/c0fZ8Tw0qI1vmZHxbJs4WvTpqtRGCe9p+ghDS7IhE3CdkruhzZosjR46c
f/75W7Zs6brzBQAARjwIOMDI5HK5dgSe3tr6RJI2RY7jqqLbJ7gXZ0mlmh0Jmg2E9Pg/wiPm
THCf/GV0kyD0ZSKyvLz8W9/61r59+y677LK///3vsiz34SIAAJC+IOAAI5MkSeXhd0zW4zZR
jHCpa+7W1scPhN8/Jec/ylzzVTuAMep2jCPfMeWErBWmZR4I9CXg2Lx587Jly+rq6m6++eb7
77+/byELAACkNfjBB0YgSume8CuVkY+StMmQxmBEGrT9Nt8bsVqP9y8vcy1o0g+EUYvJvsqa
JWApSx5b4pozRjmuJvpZq1aNET6ovVdMF6a+CKO5uXnlypWmad5///0rVqw41nsDAID0BAEH
GIFEUdT0UMRKXCjamUfMDZr18SxedeqeJv3gRPfJM33fkohDt2MW1wQsi9jpJJnteu3e9o0W
MxBCHPGo1U5kknrAkZOTc9ddd+Xn559++unHfmsAAJCmIOAAIxClVGOR5G0U4tFZuONbk6lf
hN5qN2tmeL5FueyQXRGjPWZUa3YEoW/sSTFtLcna0m6tXLmyV+0BAGDkgYADjATx0q/xPKGc
c4yxgBITXcjEnatMcNIMmbospmdJY22UuFUEI6yziGUFNCyZpmnZ3ewlwRhWPgEAQK9BwAHS
GyFEFEVBEMpjb6lW0GQawdRvF8jUXeScETTqo1abV8yf4j09V54QMOtCZqPBYgKWCaH58pQz
8360L/SvI+rnHHGUWtpyiTgg0ygAAPQWBBwgjYmiKEnSruCz9ep+1Qp+fTwqz8m90GSaR8yd
4TsvQyquju3c1f58xGr9ug1RylzzEULH+y8scc7d0b7OYpqT+JKXdCdYcIuZSRZw1NXVPfbY
Y7feemtvp10AAGBkg4ADpCtJkqqtLYeatgeNhoSXTKaHzKZcZTxG1CcV7Ao8Vxv7jHH2zTaa
ZofazbpD0W0Ls648Jec/dre/mKdM0TQtXuOtWxlyYZl8ck+pzb/44osVK1bU19cfd9xxS5cu
PfZ7BACAEQNmo0FaEgThsPXRgeCmrtFGXH10/1z/JfnKlLca7mvWKpzU33XAod08kikVmyz2
fvODJlNPyf0PxpLNlWBMCpxTe8o0+uGHH55//vkNDQ0333wzRBsAAJAAAg6QfjDGkiQdjnwS
swI9tVHNUI484XBsV8xui9rtHHGJOhPaRMwmm5t5yiTOrc+CryrE4yF5Sd631D17knJGtwHH
K6+8smLFilgsdt999/3sZz/r230BAMAIBgEHSD+iKH4efa1Vr0nSJt8xeUfbczYzihyzCCKa
HZKIK2GQgyPUoO13UH+xc7aTZlSEtxY4pyLUzdoLjHCJ+7i53hWapnV99YEHHrjuuutEUXzq
qaeuuOKKY7o3AAAYoSDgAOmHUtqsViakx+gMI5IhF1VHd7bptX6xcKxrvkw9nNsCSaxgImKZ
EnGiZ7FPKGzQDsRYq0vISGjjEjIm+U85wbdK07Ru96e4XK6cnJyXXnrptNNOO/a7AwCAEQkW
jYI0gzGuNrb2tHQjziVmBK26dqOWc9aq1bjFrAnuk2J2u25Ho1abyXWKBJm6XEKWQjzZ0nhd
1zNoaZZYpvPoWM/cRm0/FjjHWJAcPil/pvt80zRVVe1pN+zVV1+9fPlyv98/MHcMAAAjAQQc
IM0QQmxuWtxI0kYiDo2FOWcIIc552GiJWu0ZUlGR67iONpxzxpht27r+VYE327YFJk/znjvd
c54sy4ZhGIZh23YsFjtq4g2INgAAIDkIOED6SR5tIIQolhLqxDJmx6ygZVmW1U3y0A6mrVuW
xTmXZdk0zW5XbAAAAOgDWMMB0o+AE9OWJ7C4LhKl8xGMESUCIUQQBFEU48lJ49nQv3FlIh11
MKOmJtliVQAAAN2CgAOkGcYYxWJCPJHAsGMO6iX4qwE8TDAmhCGrxThUpW6rjG45FP24Rt3V
ZB6IoAZBEDrCDoV6k2ca3bRp05IlS+65557+uh0AABglIOAAaYZzXiot8EsFSdpErYCb5GbJ
pRgjQojGgkGzQcBS2Gw2bc1ipsk0zY6EjMYWrarRKBcEgRBCsegWs5KkLX/llVcuu+yyWCxW
WFg4AHcGAAAjGQQcIP1YlpXrGI+7S5jxb7xdry11zcWYRO023Y64qF/GbtNWE9oxboeMphp1
N6U0zzlxrHRSTyMcDz300PXXXy8IwpNPPnn55Zf3390AAMCoAAEHSD+maU5xnpPrGJ+kTYN6
oNQ5zycVGCxGsOCXCiNWK+8hdYdqhVqNQ/nOSd1mEbVt+9Zbb/3FL36Rk5Pz8ssvn3766f1z
GwAAMJoM7C6V11577cEHH+x85Le//e1xx321NXHHjh2PP/54bW2tz+c788wzL7vsMiiwCVKk
63qRa7pqh0NGY7cNbGTsD7893Xt20DgiUzdBkma19HQ1gciTvafJxEUx7bqNZcOGDY888sik
SZOeeeaZ4uLi/rwNAAAYNQZ8W6zH4/ntb3/b8W3H5Pf+/fvXrl173nnn3XTTTRUVFX/+858Z
Y6tWrRro/oCRwbbtMeKJyItqIp81a1Vds44SQg5Ft5fwOWfl33Qouv3L0Ic9bT5xC1nHZVzg
Jrl72jYW5c02jMQ9t8uWLbvrrru+/e1vZ2QkJiEFAACQogEPOCil48aN63p8/fr1RUVFN9xw
A0KotLS0vr7+pZdeuuSSS2Q5Mfk0AN0yTbOQnlCWdfLn0dfqY+Uhs4l3KkCvCO4xdFahY5qC
MmZ6znfTnKro9na9lqOv27iF7GLncUXOGaZlfhnczBErj71VRk/p+l7XX3/9YNwSAACMXAMe
cITD4SuvvNKyrDFjxlx44YWLFi2KH9+3b9+pp57a0WzOnDnr1q2rrKycOnXqQHcJjBi2bauq
Olk+Z7rrW5XaJtUOmUynWJCps8g5/VBk55Hovkpzh0gchc6pp2avCVg1EavNYDGRyA7qz5Um
hczG+kh51GqLXzBithARFjYBAED/G9iAo7i4eM2aNaWlpYZhvP/++7///e+vv/76Cy64gHMe
CAQ6D1DHv25ra+s4snXr1rvuuqvj29tvv33mzJn93kNCCEJIUZIldRhW4stcnE6nw+EY6r6k
CmOMMR7ohzxVPrPzGqC94dertY8RRQpVEOKN1hdNVrlLyJSp2yX6bW6aLLo/+rbNDSQgRfiq
b5gyt9sd/9rhcKTXBwNjnEYDhPF/LHjIAyp9H7IkHSW53/ARf8iKoqTXB2OAHnLyPEYDG3DM
mjVr1qxZ8a9nzpwZjUZfeOGFCy64IJVzLcsKh8Md39q2HQ8OBsLAXXmAxD8uQ92L3hnkh8y4
1eUR8ajdGrVbOx9KbIPR448/3tzc/NOf/hQe8iCAhzwI4CEPAnjIcckzNQ9qLZWpU6du3rzZ
sixBEPx+f3t7e8dL8a8zMzM7jpx88snvvPNOx7fBYLC19Ru/KvpFfJxAVRPTMwxbiqK43e5o
NJpGZT4URcEYd33I8fziVcZHuh02mYYQlohDpq5SaaFpmsmLniRHKcVM6MM/62MPbHj49y96
vd6rrrrK6XSm1weDEBKLxYa6I6mSZdnj8cRiMXjIA0eSJK/Xm14PWZZlQRCi0ehQdyRV8Yes
qmoafTAG9CFnZ2f39NKgBhz79u3z+/2CICCEpk6dumvXruuuuy7+0q5duxRF6XZ5KRh5CCGy
LB/Q3m4I7Q/oRzoXY5OIo07+PM85abzjFE3TjlrZpFuMsUnOM/YHP9DtVP9HMZs/vnbT20/u
zcvLe/7553NyctLoRx4AAAx/AxtwPPDAA1OnTi0oKDAM44MPPti8efM111wTf+niiy++5ZZb
HnzwwXPPPbeysvLFF19cvnx5Gs2BgT6jlMqyvD34RE10T+d9JXEGUxvUA83aoYin9XjPxZqm
JZ8U7Fa89HyGPKYhtj+V9pZh//Xmf23bUDF16tSnn34aAl8AAOh3AxtwSJK0bt261tZWSZKK
iopuvvnmxYsXx1+aPHnyL37xiyeeeGLjxo0+n++iiy5auXLlgHYGDAfxNXdb2h+pj5UnaWZz
syK01ebGHM+lfRvnME0z3zGpRT101Fr2umr+/upXDu5umL1wykvrNqbRalwAAEgjAxtwrF69
evXq1T29esIJJ5xwwgkD2gEw3MiyvDv0XPJo4994dXi3Qj2T5XO6JuM6KsuyxjkWhzxNlaFt
XdOCfaNLDnHstOzcvOyXn3gPHW3REwAAgL4Z1DUcYJSjlFaZW2qin6XYniNWE/lshnuZaZp9
iAM0TZvt+Y7F9JrIpz1VUYn74R0rx/rmEEKSlIoFAABwLNJs6xFIa4IgtGk1JuvF/pqo1bYn
8kp8oXFvcc41TTvBd/lE38kK9XTfJSyVuI87s+BHxfREiDYAAGDgwAgHGDyU0qBR39uzAvoR
6qDd1nE9KsaYqqrTHN9yi1lBozFgHNGsf2cjFdw+MT9DLhonL1ZVtQ9LUwEAAKQOAg4weDDG
qh0+ertv0uzwsSSo4Zzrul5A5hY7BOqmhJAdO3bMmzePc27btmVZaZSiAAAA0hdMqYBBgjE+
pG2xmN7bEy2mH3sKP8aYYRiRSGTNmjVLlix5/vnnY7GYruswjQIAAIMDRjjA4ClTTtpLNtr2
V5MjGGGvlOeXChyCTyQKR9xkWtRsCxj1EbM1vrUEY5IhFxFCHA4HxphzHs+xYVlWbydBVFVd
vXr1xo0bp0yZMhB1eQAAACQBAQcYJPFYQSKuePZPv1RY5JoRYU3N+sFA7IhhRxHGCvFkyGNy
XGVj0Iza6B6Zugqd06KsZXvwqbDeYjINYyIRp1fM9Uo5pcpJhmGkGHa0t7evWrVq27ZtixYt
+sc//uHz+Qb4dgEAAHwDBBxg8Ni27ZfyI2ZzkWuGKEqfh1+vju5i/Bs1U2pin4hEGedeuCjn
6hr1k92BFyJ2a5ZQ1nnuo0k9KBKl1Vlzgn+lrutHrbpy+PDhSy+99ODBg8uWLfvrX/8KCW0B
AGDwQcABBo9t25lKMSWihbXtrc+EzeZum5lMV6j78/CGQ9EdqhlwCv6uwxgm06oju8Jm81jP
nCJhfvKY4y9/+cvBgwfXrFnzm9/8Ju2qUAIAwMgAAQcYPJZlTXSd9hl/cVvTU1Grx9q/49zz
FcH9QfPfMEIT3CfLyNtTPNGm1yCExuUsZowlmVu5/fbbFy5ceMEFFxz7LQAAAOgb+GsPDJ74
ZpOg0WDzHveqyMRV5j7xk/aXNDtkcSNg1iW/ZptesyP4tCRJSdpIkgTRBgAADC0IOMDgEQTh
i+gbzbEqn5TnFLpftlnimtOg72vWD0rE4RayI0Zb0K5Lvi32SPSLavMjmCsBAIDhDH5Gg8FD
KW3TaxizXSi/SDkuQy4SqZLQJleZcET9XKEeF83ijDFua3YkeTBhMDVstvQt/TkAAIDBAQEH
GDyU0rDRjBDinFuWlSWMK3OemKOU+eQCj5TjlXKylbJsZaxuR2XiZYzF67WZduyoib9CRmM8
KInFYldeeeXrr78+8HcDAACgF+CPQjBI4kGDwWIdR2zbtm3bS4o64gmFeGJWQDXDnYu72ugo
u14RQiZTMcYtLS2XX375rl27bNteunRpf98BAACAvoOAA/QdISQeK/B/67ZNvBkhpErbynni
XhLMiYN645lGBSJzzhJKyXPOjzrCwTg7dOjQ8uXLKyoq4sk2ju3OAAAA9DMIOECvEUJEUaSU
HtI3W0xniIlEGe9YbNu2aZrxDF2U0nibSm2TrVsIcYrEyZ7TY1ZbTXRv2GxCCPnlgjznBI+Y
02JUaCxCEHUJGU6ake0YGzTqTfurKvYEC92GMp0d2tN83bWnNzc3r169eu3atbCAFAAAhhsI
OEDvyLJ82NraFq1p1WoiZnPHaES58F6GVJTrGF+mnIwQqja3NIer2vXaiNkmCBQhZFn2wcgW
ho1c18RCNJUSGmHN+yJv1sQ+DRh18etQJCwfsxZj7hS9WMgIGo2cM5EkLixNUPlZ091XvmJo
5p133rl69eoBfgAAAAD6AgIOkCqMsaIo5eqblaGPtS5V5lUrqFrBdr3Wk5vTqh+qCG6L10zp
hEfNtharojLy8bys72YJpW/U3tVm1nRuYSOrMrpVJp4vI5sKlKlZSnGbVqdQV/KCKaXTck5Y
NOvqFd+DZBsAADBswcgzSJUsy5/HXtsfeK9rtBFHsDDWM+/TwMsftjxi425SezHGcqWJbjFr
U/NDO9vXHZdxgUASy5pURXeUOGeL2FET+yRkNeQ6yjKE0uQBR5Fn8oYX34VoAwAAhjMIOEBK
RFE8qL9bEfrI5j3uGSl0TmuzqvcGNgSNhmbzYNfEGPHln1G7pUk7sLN9vcbC07xnJ7RpN2qb
9co5Gd9GCDdo+zUWTr5i1EG9Bc4ppmn2+dYAAAAMAgg4wNFhjEVRrI3usZjRUxuJOHMdZeWh
d2xuIoTCRlOoS4ZQQkireShkNiqCl3P7k/aXSpzHu4WshEt9FnjFLeTMzfiOk/pDZkPHXpiu
ZOoa71tYIiw8asFYAAAAQwsCDnB0lNL9sbfa9SNJ2mQqxYfVXQHjq9InNrdUO5ywW4QQErMD
EbNVwg6XkBm2Guu1fcXO2QmXMpj6SeCf490nLci6wmJGvf4FpbTj1WBL7MDOeoRQhlw0xX/a
BOk0w+gxDAIAADBMQMABjo5SGjCOIJRsb6pfKmjSvux8RLejCSMTlNKo1coR1+wwRtQn5rcZ
1cWOWRSLGGGMsIAlt5CVp0zKEkt3ta1nNjs1d02pc16GXCgSBSHcWB1au+Kf961+3ROcenr2
j0rpSbreYx04AAAAwwfsUgFHRwiJWcHkbWTqDplNnY+YTO86FaLZEYQQR8hgMYtrEbM1V5k0
3rVI5yGEsIzdFjd0O9qiVTNuBfTXfGL+zIxvLcm5sTz47me79t218ldtzYE1a9acOv5yVVWP
mp8DAADAMAEBBzg6jLHJkg0kYEQELBpM7XyQcyto1blwXsdFWs1DFv96+oNxFrFaNTvSbtQy
biPEg7wxIRVp0GzYF/zXKVnf2/16w+rVPzMM4/e///21114bTy8GAAAgXUDAARJhjCmllNKO
tOWEEJeQETabO2ZVRKJkKIVurfz3OAAAIABJREFUMUskCsHUsFWnmKFQd9Rq7XQhghDuPAiR
JZZV452s0z4XAUsIcZNpXVOef92GSI8++uiNN95ICHnwwQcvvPDCfr9lAAAAAw0CDvC1+G4U
URTLo2+G1EbDVhmyBSx75CyfIzdDLqyNfq7b4TGeGVlySVVsW2Vss2oHGbIV4slQCvxKAcIs
ZDbHs5JTLPqEwo4Nq/HIQ8SKib4eLHEKfsOOJYk2EEIK8v/54Yc9Hs8TTzwxf/78gXwAAAAA
BgoEHOArhBBFUfZGX61r2xsxWzu/RHUasGsyxDGTvUuy5LJdgeffafmfgPGNTSsEixyxNrPa
I+ZJxBE122XqTFhjwTl3Cpkx++vlILnyxDbjG8lGuypwT37uuV/W1dVNnDjxmO8SAADA0IBd
KgAhhAghDodja+Dv+wMfJEQbCCHGGMVCyGrkmG1t+0d58O2EaAMhVK/ty1MmtRtHjqifE0I8
Uo5CvQkZQm3b9ghZ5N8rSQUsFTqmN2kHk3TMQb058jifzwfRBgAApDUIOMBXRVK2tP1fXfTz
bve+cs5zpElzMi/e1PzQ1tYnJOr0irkJbZq1g5odnuI5PWYFjqh7BSJkS2VdA44caZJfHBP/
doLnZMxJ8oBjuv/sac6lkEgUAADSHQQcAEmStCfy8pHYviRtipzTa9RPDsd2m0xr0g/6xUKK
vzEfxxHfG3x9gufkIscMg6lhq7nb9KC2bWdIY5yCL1eZOM1zdnnoXY4SF3Aw+6ugp8x9wtm5
t6iq2uUyAAAA0gwEHKMdxlgQhLro3iR5vZyi30SxvYHX3EKmTJ1Rqy1mB7xiXkKzdqPus8Cr
87Mum+Q5NWw2N+j7upZTsW07g5bO8C09KevKA6EP2o3ahAZ1e2P/e0F5w351guekmf6lqqpC
2nIAABgBYNHoaCcIwhfRDVGrPUmbTGVMs14RNJsoFpw0Q8By1GrNlErbUV3nZhSLMautQTsw
L2NFhlTSpJYnpDZHCMnUVeiYNj9zJaU0bDa3GFWqFeh4tfzd4PO3VNsmd9fPvaToT6qqQiJR
AAAYGSDgGO0IIUGjMXkbj5hzIPo2ildIsUIicQhElqkzWx5rMBUhTrEoE5dM3ZjTw+Fd9dF9
Ezwnz8281C3kBNR6G5sIIcpFt5jtEjJKxAWRSIQQckbWT4scMwPWkXa9VrVD7z+779nbPiOE
PPnE48uXLw+Hw8mr0gMAAEgjEHCMdhhjw44mbyMSJWK1xb/miBssZjI1SxrrEXLjFedtZllc
jxht8XKyJtM/a3/VK+WdX/SrieKZoihijHVdZ4xZlqVpGkKIMRYOh0vo4glOibjJnXfe+eDa
f2VkZKxbt27u3LmRSGSgbxwAAMBggoBjlIonEmWMYYwZ7yZNuESdPilPxErYaqVYsPk3KrJy
xG1ualbUsGM9vUXEaI5YrVnIQgjFA46ubWzbVlX1vvvuu/vuu0tKStatWzdhwgQY2AAAgJEH
Ao7RxeFwiKJICPkisoEjjgmeriwt9cy2kBHUGxBCTpoxK+u8HKVMpu79kXc44ie5r6REpETY
1PzI/vA78etghAkWOicp70oWvNPdS0Oh0FF7dcUVV+zZs+cPf/hDbm7iblsAAAAjAwQco4Us
y4qibA8+WdPyaYO2P2K12MxUqOcTxyteKTvDUVLomuIWcopdx21vf2pT218Ox3YFzHrGTKeQ
VeyaVajMmJO5fEH25S/X/rrdrBWJQ8auIE+2+CNTKuKcpzJckZub+/e//73fbhUAAMDwAwHH
qOB0OvfrG/fV/asyvJV1ynuh2eEj6udtpmtn24vfLblX56EnD9+wN/A667RFNmK1VIS3HI7u
+rj18VNy1lxZ9rcXa38espoMdpQaKAWOqbCjFQAAQBwEHCOfw+HYp72+teXxVv1w11dNW/WK
uQuzVzVq+3cGnhOwIhDZYNo32nBdwd6I1fLqkdsjdstFY+5+s/HeNrWbq3VwCZmFjumGYSRp
AwAAYPSAxF8jnCAIXxr/2tH2fLfRBkKII+6XCtxC1vvNfzkU2RY2G/OUyQkpQjnnOos6qI8j
/l7jA3uCry3JvlGzk2wkwcdnXjDVeV63Kck3bNhQUVFxDPcEAAAg/UDAMcI5HI46dU+jur/n
JmSi55Ty8HttxmGEULNeQTD1dCmVEt866xazEEabWh5qt2ome5f0cEF8fMYFp2TeGI12s9v2
kUceueaaa6655hrYigIAAKMKBBwjGaW0XN34RfDtJG0KHJNjdvvnwdcRwhQLjNvtRk3XtOUc
oZgdFLDiFfOiVmtFZMsM/3ldryZT98KcVefl/SIajSaEFJzzP/zhD7feeqvX67333nu7JiEF
AAAwgsEajpFMkqRgrKFz7vCuilwzG7UDBtMwQhhjisWo3Z6rTBSwaPGvJkQwxgQRggWTaRJx
eITcOvWzs3JvkqjDsL+qrOaXisY4Z451z5vuXNY1SahhGP/5n//53HPPdSTbGKBbBgAAMDxB
wDGSEUIC+pHkbTxCTnVsG0KII8Q5x9jmTLO56RD8mh3iiGOEKZYQQohzzrluxwimAbO+Vvvs
ojG/C5oNjFsydc/0nG/btq7r4XA44S2i0egVV1zx1ltvHX/88U899VROTs7A3C4AAIDhK20C
DlmWZVnu98vGy5lSSvv9ygMk3lVZlrsWYu1KFEWdRwhNNnmhULfKQp0ryXPETaZLxGn9e6/K
V3tk/11vniOmWkHDjs3wfcu2v8pSGt8BK0mSJEkJb9HQ0LBv376zzz77ySefdLvdqdzm0Io/
ZEmS0uuDgTFOo4mqjk8yPOSBE+9qOj7ktPhBERd/yJIkpdEHY+AecvLFeWkTcNi2PRDLDOO/
Q7vdTDFsiaJo23YqfaaUEkw577HuPEKIcYuixB9GGBHOGe+5YD1CiGBqGEYqmTby8/Pffvvt
nJwcQRDS5VGLosgYS5fexmGM06jDnPPUP8nDByEkjToc/7MEHvKASseHzDmnlA5Eh5P/ukmb
gMOyrIF4OvGYNI1qoMcjJMuyUumzIAgK8XKW7BOgs4iTZnb+kGCEBCJZzEjyyZGpW8CSpmkd
IxzJ+1xUVKSqaiqNhwlFUVJ8yMNE/C/vNOpwHDzkAcU5dzgc6fWQEUKCIKRRh+MPOT6hPNR9
6Z3B73DaDAGBPrAsK1sem7xNm16Tp0zqfEQRvCJWDNZjVTaEUInz+BmeZWkUQAAAABhaEHCM
ZKZpzvVdmqOMS9KmOro7Qyr2S1/vg/UKeaodTD6fUuZekCTagOLyAAAAEkDAMZIxxgzDmOY/
CyHcU5ugUW8zc7b/4vi3MnV4xbygUZ/kskWO6Wfl/KTbvF7xZBunnXZaS0vLMXYeAADASAIB
xwinadpJ/uum+89K0ubT9lenec+Z6judYpqvTNPtqN7zfIqTZizKvsY0za4jHIZhrFmz5p57
7kEIdRuOAAAAGLXSZtEo6BvGWDQavbDgd4xb+4Lvou4mSoJG/a629bP9384USxu0/Q1aeU9X
84p5p+d9f67vskAgMZlYNBq95ppr3n333dmzZz/11FPZ2dn9fCcAAADSGYxwjHyWZUWj0eUF
dy/Kvcon5XfXBHPOs6TSy0v+Os17VtdCKgghguh03zlLC36+wHdN12ijsbFx2bJl77777pIl
S9avXw/RBgAAgAQwwjEqmKYZDocX+W7Ilsrazdom9WDMbre4LhO3TyzMc0yc4/2uYRjBYPDs
nFsKlGmtRlW9ui9it9jMUARvtjSuQJkyz3+ZruvBYDDh4pzzK664Yu/evatWrbrnnntSyUgG
AABgtIHfDaMFYywSiZTQxRNckuATMMYYY855PL1VR/WTQCAwXjpjml+mWfTfmUW/Wnza3t7e
7ZUxxvfee+8777zzox/9aPDuBwAAQFqBgGN4IYQMaN1227ZVVU3exjAMwzB6ddlZs2bNmjXr
GPoFAABghIOAY+gJgiBJkiAIHan4OefxzKq9/cUPAAAADE8QcAwlQojT6SxXNzaHKhu08pDR
oLOogBWPmJ2nTMx3TJnuWaaqair1SgAAAIDhDAKOISMIgsvl+rDtwc8CrwaNxs4vBYy6muin
MnUf8X9+bu5tqqoOnyz9hmH84Q9/+MEPfuDz+Ya6LwAAANIGBBxDgxDicrk2NP3us7ZXGOp+
0YZuR3a1vtiu115W/GfO+XCYXgkGg1ddddXmzZtjsdidd9451N0BAACQNiAPx9Bwu93vtPzp
k7aXe4o2OhyKbH++7icOh6NjhcdQaWhoWL58+ebNm0877bTbbrttaDsDAAAgvUDAMQRkWf4s
8s9dbeu7zfvZ1YHQBx+2PeRwOAa6Y0mUl5efd955e/fuveyyy5566im32z2EnQEAAJB2IOAY
ArIsV4S3mExL/ZR9obdFURyqQY6PPvpo2bJldXV1t9566/333w+pvQAAAPQWBByDjRCyL/ZG
beyzXp3VolXtCj4riuIA9So5RVE45/fee+9PfvKTIekAAACAdAd/qg42QRA0Mxy1us/a2TPe
btRSBx3QtGA9mT179vbt2zMzMwf/rQEAAIwMMMIx2AghOov04UTNDg/hulGINgAAABwLGOEY
dTDGlH5VJ4Vzzjm3bXuoOwUAAGCEg4BjsDHGZNKXLR4K9RzjfAqlVBRFSml57C3DjtncFImi
UM945ynxTOqcc4RQMBiklMI+FAAAAP0IAo7BZlnWXN+lm5sfjZitvTkPZ0jFtm13VHDtLVmW
D1sfNYUqW7QqzQ5/fV1EKqWP8x2TZ7ovMAyjtrZ2xYoVmZmZzzzzjCRJfXsvAAAAIAEEHION
McYYG+OYVW6+m/pZOY5xc3yXhEKhPgQBGGNFUcrVjRWhrbodTXiVIxYymkJGU6tWbdRlfv+S
2+vq6lauXDnkecYAAACMJPBLZQjouj7es1AkSuqnTPedZRhG36ZUZFneF9uwP/B+12ijsw/f
/+jyc35w5MiRW2655X/+538g2QYAAIB+BAHHENB1fab7wnlZlyCU0vzIFO9pC/3XalovEoV1
EASh0th0MLTV5slKzm7fWHHv6lf1mPmDu7793//9332euAEAAAC6BQHH0IhEIkuyfjAn6yJy
tH+C8Z6FFxf9IRaL9W14Q5Kk+li5ydQkbdqbog/e/DYVyE0PLZ13cd4X0deHKsMYAACAkQqG
zYcGYywajZ6dfYtHyP60/bWAUde1jYN6p/vPPSvnp7FYzDTNPrwLpbRS29SiHUreLCPXtea+
M7MKPWOn5yDEm9SKaS5hOBSnBQAAMGJAwDFkLMuKRCLzPVf7xMJWo6pB3R80G3Q7IhGnS8jM
c0zKVyZNc34rGo1aVrLZkCQopSG1mfGjp9mYe9a4jq8DRv0hfUsBmTMkWU0BAACMSBBwDKX4
OMdY4dRJnrOEDAFjHF88wRizbdswjHA4fNSLJIEx1uxQb8+yuWkxDRNYxgEAAKDfQMAx9CzL
6vMYRnIYY4v1ZWbE4gasGwUAANCPYNHoSMY5F0hi3o6a/a3/98v3mM2TnEixGM86CgAAAPQL
GOEYyTjnMnF1PvL5R7X/+/031Igx7+xxs04p6fYsigWRKBBwAAAA6EcwwjGS2bbtlfLwv/+V
t79R8cf/eE2PWdesXdJTtIEQ8kp5ZfIiWDEKAACgH0HAMZLZtj1eOSVLKUEIbfzHZ//vR29S
Sn784NIll0xLclaOMm6A1pQAAAAYtWBKZYQzDKPQOfV/f/30hkd3+3OcP/nbstJp2UnaZ8hF
M90XqGqyRGEAAABAb8EIxwhnWdZ4ecnCExflj/X/4qmLkkcbDuotdc8xDAMWcAAAAOhfMMIx
8um6ftOqu09bdmKNtjPJLlmPmDvOO79UOAlyjAIAAOh3EHCMfJxzTdOO9y33OrIaYvtbtCqb
fyNRuoN6852T5/ouNQwDog0AAAADAQKOUSEec5QIC8dnnFJlfBS12nQ7yrgpEMVJfVNcZ9u2
raoq7EwBAAAwQCDgGIH27Nkzffp0QhIX6MRTmhaQOVSi8TTqnHPGWCwWg0UbAAAABhQsGk0n
hJB4GNHxRVfPPvvsueeee/vtt/d0EcaYaZqGYei6bhiGZVkQbQAAABhoMMKRBjDGoigKgnBI
38J0k5sWZgLBYpnzJMuyTNPsiBgeeuihX/3qVw6H49RTTx3aPgMAAACdQcAx3AmCIEnS59HX
mgIVQaMBUy6Komma3MZV0vZcx4Tprm/Fhyt+8YtfPPLII3l5eU8//fTMmTOHuuMAAADA1yDg
GNZEUaxhHx9u3d2q1SDEEULCv//JbG626bVtem2TWlEgzlj7n//34osvTpo06ZlnnikuLh7S
XgMAAACJIOAYvgRBqLG3Hgh+GLXakjRr02vef33Hiy++uHDhwscee8zv9w9aDwEAAIAUwaLR
YQpjLMtyVWRn8mgjbuYZeT/7f5e+9tprGRkZg9A3AAAAoLcGaYSjvLz85z//Oef8n//8Z8fB
HTt2PP7447W1tT6f78wzz7zsssswxoPTn+FPkqRPQuvb9boU2884O2uf8epM53Jd1we0YwAA
AEAfDMYIRygUuueee2bPnt354P79+9euXTtt2rQ//vGPq1atWr9+/ZNPPjkInUkXgiA0qPt7
dUpD7IAgCBC0AQAAGIYGPODgnN93331nnnlmwr6J9evXFxUV3XDDDaWlpaeffvpFF1308ssv
w1/ncZTSL9V3I+bRJ1M6i1rtB2JvU0oHqFcAAABAnw34lMozzzxjWdaKFSs6T6YghPbt29c5
V8ScOXPWrVtXWVk5derU+JFwOFxbW9vRICsrS5Kkfu9ePH2WIAyvxbOCIGhqiBCMUDfDFa8/
squtKXLJTSd2fUllIUEeXveCECKEYIyH20NOIh60EULSqM/xXHDp1WEED3mAxT/JlNL06nM6
PuS06/MAdTh5GsmBfUCffvrpG2+88ac//SlhnJ9zHggEOq9wjH/d1vb13/Q7duy4+eabO779
85//PH/+/AHqp8PhGKAr953BZFlOOMZs/siv3n7z8U8z893L18x3+5WEBpgyt9s9WF3sneH4
kJNyOBxp12dFSfxIDHPwkAeBoihp1+euP/2GOXjIcbZtJ3l1AAOO9vb2++6770c/+lHftk4U
FRVdfPHFHd9mZGRomtZ/vftKPMSzLKvfr9wrGOPOqcoxxpjThF6Zuv3Ajzd+vOHLMROzfv7Y
RYpb6NptzrBhGMOtBhulFGM85A85dZTSeHa15P95hpU0fcjx+j5D3ZdUpd1DJoRIkgQPeUDB
Q+6MMeZ0Ont6dQADjkOHDgUCgTvuuCP+Leecc758+fLvfve7K1eu9Pv97e3tHY3jX2dmZnYc
mTRp0m233dbxbTAYjEQi/d7J+F9Xqqr+/+3deVwTZ/4H8GdycyOnEi2CYgVFkYhHtdpWi1gp
qIsH6CIWXXV72BUVtVq1XhUs9VirVBALKLpVW+0qVms9wGPV4oWCB0p/iCAi9xFyze+P6WZT
JCFiwhD8vP9KnplMPs8z8wpf5jT4kvXE3Eg0T3q2UlZcr6xSqGRciucg6ionUubJakz1UFvZ
8PXso3d/K/Lw7bR41ziRJU8ulzexNFpUV1fX1rZ7kUhEURSLg/yihEIhn8+XyWQmlFkkEnE4
nLq6OraD6IsZ5IaGBgyy8QgEAoFAYFqDLBQKeTxebW0t20H0xQyyTCYzoQ3DqIPMTsHh5eW1
ZcsW9duTJ08ePnx406ZNzJ2pPD09s7KyIiMjmalZWVkikcjd3d14edoa5k4beQ1nip7llEp/
p8n/dkuUNTxytelTIrvH4/DteF2rK+pWTjhQnF8x8L3uf48bZW4harLa4HNE5jybtrZ7AwAA
gBi14BCJRK6uruq3zIEVdcv48eOjo6Pj4+MDAgIePHjwww8/jB071uSO270MkUh0u+5oXtVF
uarxoSK5qp5HmzkI3R7UXJCrGpxtX/cd0VUhV01ZMoQv0HoRioOoq6tgsAn9KwMAAK8O1s6q
ff311z/77LPU1NSff/7ZxsZm3LhxYWFhbIVpfUKhMLf++L3Kc0q6iX0VhJCiuhxXc99HdTeq
ZE8oQk1ZMkyp1HWghM8ROZt5yGQy4+QFAAB4Ka1XcIwbN27cuHGaLX5+fn5+fq0WoO3gcDj/
p7j4oOqitmqDEFIpe+IgcvPpEHT52b+q5E/4HJENp7O2wyUUxelmPchNMNQY59UCAAC8PDxL
hQUCgaBU+lCqbOYc2PzqKw78bhK7ED5lXiN/pnkZiyYeR9DDeqiX+Xu4bRoAALRZKDhaG0VR
XC63VPq7thmUStW1078TQpS04k7FWVte58GOf3UUdatWFTe6nQlFOA4iNy/bkV7mY6RSqe47
rgAAALDIZO6M1m5wOJx79afqFJVNTpXVK/756fHrp/M/3DhqwOhuSlp+v/KCveg1X5u/yKha
hULeoKohXBXhUXzKwprv1E00TCaT4UgKAAC0cSg4WhtFUQ2KOkKa2BtRW9kQN+vovawiz4Hi
3kM6/7eZfib9vUz6fx62Q32s/kJRlEgkkkqlMplMqVSa0JXfAADwKkPB0dooilLRTVxv8vRR
1YbIfxc9rPAb5T57w7t84Z8uf6UJXSsvUygUzFEVhUKBC1IAAMCEoOBobTRN8zmNHx7x4GbJ
17OOVpbW+Yf3mbJkCMVp4pltfI6Ipmk8fR4AAEwRCo7WplKphFxzLsXXvCb2P0fuV5XVT1ky
ZFREX20fNOfZqlQqbdeqAAAAtGUoOFqbSqVyMx+SL/itrKFA3Th54WDJu249JJ20fUrItfCy
GF1XV2dCT0AGAABQw7/LLJDL5R3NX6fI/w6OUBxKR7VBCOlk3lOpVOLCVwAAMFEoOFigUCg8
zUc5m3noOb8V39FO2AVniQIAgOlCwcEChULR0NAw1P5vHYTiZmc249m4Ww/szBmAx8ACAIDp
QsHR2srKyoKCgvbs2dPQ0DDC8R8u5p4UpW0tUHbCLj1thnflDWnyefQAAACmAmcgtqqHDx9O
nDgxPz/f3d190qRJNE0Psp1+V3SypD6vUlbUoKxlZuNRAhthR0eRey+LMTKZDAdTAADA1KHg
aD1Xr14NCwsrLS2dOXPm6tWrCSFKpbK+vt6dP7xHhxEcDidPmiFXSXmUgEvxXQWDmKk4URQA
ANoBFByt5NSpUx988EFtbe2KFSs+/PBDzUlyuVwul1MU5UL1Z275pVKp6uvrWUoKAABgeCg4
WsP58+fDwsK4XO7OnTsDAwObnIemaezMAACA9goFR2sYMGDA2LFjIyIiBg4cyHYWAAAAFqDg
aA08Hm/btm1spwAAAGANLosFAAAAo0PBAQAAAEaHgsPw8vLyjh8/znYKAACANgTncBjYlStX
pkyZUltbe+HChS5durAdBwAAoE3AHg5DOnbs2Pjx4ysrK1euXIlqAwAAQA17OAxmz549UVFR
HA4nPj4+ODiY7TgAAABtCAoOA6BpOjY2NjY21tbWNiUlZdCgQWwnAgAAaFtQcBiAQqG4dOlS
ly5d9u3b5+HhwXYcAACANgcFhwHw+fykpKT6+nonJye2swAAALRFKDgMw8rKysrKiu0UAAAA
bRSuUgEAAACjQ8HRErW1tWxHAAAAMCUoOF5Yenq6r6/v5cuX2Q4CAABgMlBwvJidO3dOnz69
vr6+vLyc7SwAAAAmAyeN6kt9s40OHTqkpKQMHDiQ7UQAAAAmAwWHXhQKxYIFC1JTU1977bV9
+/Z1796d7UQAAACmBIdU9LJu3brU1NS+ffump6ej2gAAAHhR2MOhl48//ri2tnbZsmUWFhZs
ZwEAADA9KDj0Ymtr++WXX7KdAgAAwFThkAoAAAAYHQoOAAAAMDoUHE1ISkrKzs5mOwUAAED7
gXM4/oSm6VWrVm3ZssXLy+vUqVMcDgoyAAAAA0DB8T8ymWzu3Ln79+9/7bXXEhMTUW0AAAAY
CgqOP9TW1n7wwQe//vqrj4/Pnj17HB0d2U4EAADQfqDgIISQ4uLiyZMn37p1a+TIkYmJiebm
5mwnAgAAaFdw1IAQQgQCQUNDw+TJk5OTk1FtAAAAGBz2cBBCiJ2d3ZEjR+zs7NgOAgAA0D5R
NE2znUEvCoWCy+WynaJNoCiTWWumC4PcCkxxkE0us8kFJiaY2eQCE6NlViqVPJ7WHRkms4ej
trZWLpcbfLFmZmaEkPr6eoMv2UhEIpGlpWVtba1UKmU7i75EIhFFUSY0yEKh0MrKqq6uzoQy
i0QiDodTV1fHdhB9YZBbgUAgsLa2Nq1BFgqFPB6vtraW7SD6Yga5vr7ehDYMow6yg4ODtkmv
4jkcNE0XFxeznQIAAOAV8soVHDKZbM6cOf7+/oWFhWxnAQAAeFW8WgVHTU3N1KlTDxw40LFj
R6FQyHYcAACAV4XJnMPx8p48eTJ58uTs7Oy33357586dlpaWbCcCAAB4Vbwqezju3LkTEBCQ
nZ0dGhq6e/duVBsAAACt6ZUoOGianjNnTmFhYXR09ObNm/l8PtuJAAAAXi2vxCEViqLi4+N/
++23yZMns50FAADgVfRKFByEEA8PDw8PD7ZTAAAAvKJeiUMqAAAAwC4UHAAAAGB07bDgqKys
/Oijj54+fcp2EAAAAPhDeys4CgsL33///X379m3bto3tLAAAAPCHdnXSaG5u7uTJkwsLC8PC
wpYsWcJ2HAAAAPhD+9nDkZmZGRgY+Pjx4wULFmzatEnHE3IBAACglbWTv8r//ve/Z82aRdP0
5s2bcbMNAACAtqad7OHo3r27g4NDcnIyqg0AAIA2qJ3s4ejZs+fly5cFAgHbQQAAAKAJ7WQP
ByEE1QYAAECb1X4KDgAAAGizTLLgKCwsLCsrYzsFAAAA6Mv0Co7bt2+PHj166tSpMpmM7SwA
AACgFxMrODIzM99///3i4uK33noLJ20AAACYClO6SuWnn36aM2eOUqmMi4ubOnUq23EAAABA
XyazhyM+Pj4yMpLP56dmkJD0AAAVm0lEQVSlpaHaAAAAMC0ms4fjp59+cnJySktL8/b2NuBi
aZo24NJagUwmq6ysVCqVbAdpz+RyuckNMk3TprUxm+KWbFojTAhRKBSVlZUqlYrtIC/GtMaZ
+bkwrUFm7eeCNhG//vrrw4cP2U7BvsOHD0skkv3797MdpD1LT0+XSCRpaWlsB2nPTpw4IZFI
UlJS2A7Snp0+fVoikezcuZPtIO1ZZmamRCL59ttv2Q5iAkxmD8fbb7/NdgQAAABoIZM5hwMA
AABMFwoOAAAAMDruihUr2M4AL0ClUllbW/fv39/JyYntLO2WSqWytLT08/NzdnZmO0u7pVKp
LCws+vfv36lTJ7aztFsqlcrc3Lx///4uLi5sZ2m3aJo2MzOTSCRisZjtLG0dRZvU+cAAAABg
inBIBQAAAIwOBQcAAAAYnclcFvuKy83NXbx4MU3TP/74o7rxypUrKSkpjx49srGxGTlyZGho
KEVRLIY0UUeOHImPj9dsWbVqVd++fZnXGGRDqaur271794ULFyoqKuzs7Pz9/SdOnMhMwiAb
xLx58+7fv6/ZQlHU3r17zczMCAbZQGia3r9//8mTJ0tLSy0sLPr06RMeHu7o6MhMxSDrhoLD
BFRVVcXGxvbr1y8rK0vdeOfOndWrV48ePXrevHl5eXnffPONSqXCTd9bxsrKatWqVeq36jPs
MMiGIpPJlixZolQqw8PDXVxcqqur6+vrmUkYZEOJiopqaGhQv12/fr1YLGaqDQyyoRw8eDAt
Le3vf/97r169SktLt2/fvmbNmo0bNxIMsh5QcLR1NE1/9dVXI0eOFIlEmgXHwYMHxWLxrFmz
CCGurq5FRUWHDh2aMGGCUChkL6yp4nK57u7uz7djkA3l8OHDT58+3b59u5WVVaNJGGRD0bxK
4v79+0VFRTNnzmTeYpAN5fbt215eXiNHjiSEdOrUacyYMdu3b5fL5Xw+H4PcLJzD0dbt3btX
oVBMnjy5UXtOTo6vr6/6ra+vr1QqffDgQeumayeqq6vDw8PDwsIWLlx47tw5dTsG2VDOnz/f
p0+f1NTUadOmzZo1a+vWrdXV1cwkDLIxHD161NnZWSKRMG8xyIbi7e19//793NxcQkh5eXlm
Zqavry+fzycYZD1gD0ebdv369WPHjm3cuLHRgUCapisqKjp06KBuYV6XlZW1dkTT16VLlzlz
5ri6uspksjNnzqxfv37GjBlBQUEYZAMqKirKz88fPHjw0qVLq6qqduzYsXLlytjYWEIIBtng
ampqzp49qz6BAFuyAY0dO1ahUCxevJgQolQqfX19Fy1aRDDI+kHB0XaVl5d/9dVXn376qeZG
DAbXp0+fPn36MK+9vb1ra2sPHDgQFBTEbqp2hrnN1z/+8Q8ej0cIEQgEn332GbN3mu1o7dAv
v/xC0zSz2x8M69y5cwcPHpw1a5anp2dpaemuXbtiYmKWLVvGdi7TgIKj7Xr48GFFRcUXX3zB
vGWetjd27NiJEyeGhYXZ2tqWl5erZ2Ze29nZsZO1HfH09Dx37pxCoeDxeBhkQ7Gzs7O2tmaq
DULIa6+9RggpKSnp1asXBtmwaJpOT08fMmSIjY0N00JRFAbZUBITE995552AgABCiKurq6Wl
5YIFC+7cudOzZ08McrNwDkfb5eXltWXLlk3/FRwczOFwNm3aNGbMGEKIp6en5jmkWVlZIpGo
yTMf4YXk5OTY2toyfxoxyIbSu3fv4uJipVLJvC0oKCCEMHeOxyAb1tWrV4uKikaPHq3ZiEE2
lIaGBg7nf383mYNWzIaNQW4WnqXSdjH/Yavl5+dfv3599uzZIpGIEOLk5HTw4MHKykpHR8er
V68mJycHBwdrnrIEetq6dWtNTY1UKn38+PH3339/+vTp0NBQT09PgkE2HLFYfPjw4eLi4k6d
OhUUFGzfvr1jx45hYWEURWGQDSsxMZHP54eHh2s2YpANpaio6OTJk/b29kKhMD8/f8eOHQKB
YOrUqTweD4PcLDxLxWT88MMP3333neaNvy5fvpyamlpQUMDcZIb5+WYxoYnasWPHlStXnj17
JhAIxGJxUFDQm2++qZ6KQTaU3NzcpKSkvLw8S0tLX1/fiIgIa2trZhIG2VCePn06c+bMWbNm
NdrDQTDIBtLQ0LBv377MzMyysjILCwsvL6/w8HD1AwgxyLqh4AAAAACjwzkcAAAAYHQoOAAA
AMDoUHAAAACA0aHgAAAAAKNDwQEAAABGh4IDAAAAjA4FBwCw6ZdffqEoateuXWwHAQDjQsEB
AC/gypUrFEVRFDV27NhGk2ia7t69OzNVKpWyEg8A2iwUHADwwkQi0ZEjR4qLizUbT58+nZeX
x9x6HwCgERQcAPDCgoODVSpVcnKyZmNiYqKLi8ugQYPYSgUAbRkKDgB4YZ07dx41atTOnTvV
LRUVFQcPHoyIiOByuZpzVlZWLl26dODAgQ4ODkKh0N3dff78+TU1NToWrlAo4uLifHx8zMzM
rKys3nrrrePHj2tOjYmJ8fb2trKysrKy8vDwiIiIqK6uNngfAcCwUHAAQEtERkbeuXPn3Llz
zNs9e/ZIpdIPPvig0WwFBQXffvutRCJZunTp119/PWDAgLi4uPfee0/bU5yUSmVQUNCCBQt6
9uwZGxu7fPnyioqKgICAtLQ0ZobFixdHR0f36dMnLi5u48aNoaGhN27cqKqqMl5PAcAwaAAA
vV2+fJkQEhUVJZPJHB0dp0+fzrT7+vq+/fbbNE2PGDGCEFJfX8+0S6VSmUymuYQ1a9YQQk6c
OMG8PXHiBCEkKSmJebt161ZCyM6dO9Xzy2QyX19fZ2dnuVxO07SbmxvzRQBgWrCHAwBags/n
h4eHf//99zU1NdeuXcvKyoqMjHx+NqFQyOfzmddyuVwqlY4bN44QcvHixSYXm5yc7OTkFBoa
Kv0vpVIZGhr65MmT69evE0JsbW1zcnKYugcATAgKDgBoocjIyJqamn379iUmJtra2o4fP77J
2Xbt2vXGG29YWFgIBAIzMzMvLy9CSFlZWZMz5+TklJSUmP3ZggULCCElJSWEkA0bNsjl8gED
Bri6uk6ZMiUpKamurs5oXQQAg+GxHQAATJWnp+fgwYO3b9+el5cXFhZmZmb2/DxxcXFRUVHv
v/9+QkKCi4uLUCh89uxZYGCgSqVqcpkqlcrDw6PR9S+Mnj17EkLeeeedhw8fHjt27NSpU2fO
nNmzZ8/y5csvXLggFosN2zsAMCwUHADQcpGRkTNmzGBeNDlDYmKim5vboUOHKIpiWjIyMnQs
sEePHtnZ2b1797a0tNQ2j5WV1YQJEyZMmEAI2bt3b2ho6ObNm9evX9/ybgCA8eGQCgC03KRJ
k5YvXx4bG+vr69vkDBwOh6ZppVLJvFUqlWvXrtWxwPDwcJlMNn/+fPrPl7E8fvyYedHoWAxz
2w9tB2gAoO3AHg4AaDlLS8sVK1bomCEkJGTFihWjR4+eOHFidXX13r17aS0XxDI+/PDDX375
JT4+/urVq8HBwY6OjgUFBRcuXLh+/TpzDoeLi0tgYKBEIhGLxSUlJQkJCVwu969//ath+wUA
BoeCAwCM6LPPPuPxeElJSR999JGzs3NISMgnn3zi5uambX4ej3fo0KEdO3bs2rVr3bp1CoWi
Y8eOPj4+cXFxzAxRUVGnT5+Oi4urrKx0cnLy8/NLSkoaPHhwa3UIAFqI0v3fBgAAAMDLwzkc
AAAAYHQoOAAAAMDoUHAAAACA0aHgAAAAAKNDwQEAAABGh4IDAAAAjA4FBwAAABgdCg4AAAAw
OhQcAAAAYHQoOAAAAMDoUHAAAACA0aHgAAAwJREREYGBgS+/nL179/J4rfH8TkMFZlHLutCa
Hdfzu/SZzXixUXAAgGmrq6v7/PPPe/ToYWZmZm9v7+fnt2rVKrZDNSMgIGDkyJGNGnk83pdf
ftnsZ4cOHar+7NSpU8eOHWvweJ9++ilFURMmTNBs7Nq166JFi5r97PORNAMblY4t4YUGqmVd
MGrHmTVCURSXy7W1tZVIJAsWLPj9999f9Lv0mc146wuPpwcA0zZz5sxjx45t2LBBIpHU19dn
Z2dfuXLFUAuXy+V8Pt9QSzOIGTNmtMK3iESi/fv3Z2RkvPnmmy+5qNYJTIy5JbSsC4btuLOz
8+nTp2marq6uvn79+tatW7dt23b48OF33nlH/+/SZzYjri8aAMBkqVQqMzOzL774osmpSqVy
9erVXbt25fP5bm5u69evV6lUzKThw4fPnTtXPWdKSopQKGRe/+UvfwkJCVm4cKGLiwuXy62v
r6dpOjk52cfHRygU2tnZ+fv7l5SUMDPv2rXL29tbKBS6urp+8sknVVVV+sQeNWrUiBEjGjVy
udx169apM0ycOHH58uVdunSxsbEZM2ZMYWEhM2natGljxoyhaToyMlLzx3zbtm26IykUioUL
Fzo4OFhYWISEhGzZsoXL5TYZb+7cua+//npISIhEIlGPmKura3R0NPP62LFjw4cPt7e3t7S0
9PPzO3r0KNPeZCR1YN1rREeXMzIyhgwZYmVlZWFh0atXrwMHDjyfWceW0GSqFnehyTDNforW
sgnp0zVmjYjFYs2WhoaGN954QywWS6VSze9KSkoyNzfX3A7T0tL4fP7Tp0/16YhB1pc2OKQC
ACaMoigXF5ezZ8+WlZU9PzUmJmbt2rXLli27devWokWLli9fvmnTJn0We+jQIQ6Hc+fOnYqK
CqFQuHnz5sjIyIkTJ169evX06dOBgYEKhYIQ8s9//nP+/PnR0dG3b9/evXv3+fPnp0+fzizh
2LFjFEVlZma2uGs//vgjj8e7e/dufn5+eXn5xx9/3GiGhISEKVOmBAcHM7/ms2fP1h1p7dq1
27Zt27x5840bNwYMGLBs2TLdAWJiYrKzs1NSUp6fVFlZOXv27IyMjCtXrowZMyYoKOjWrVva
IjVapo410mSX5XJ5YGDg4MGDr127lp2dHRMTY2Nj83wkHVtCk6la1gVtYZrteJObkJ5da5JA
IFi0aFFhYWGjbWzChAkcDudf//qXuuW7774LDAx0cHDQpyONtGB96aK7HgEAaOMyMzO7devG
4/H69es3e/bsgwcPKpVKmqZVKpWNjc2yZcvUc0ZHR9vb2zOvde/hcHd3ZxZC07RCoejQoUNU
VFSj71UoFPb29gkJCeqWrKwsQkhxcTFN0xcuXBg4cOD169ebzKzPHo7evXurJ+3evdvKyop5
rfkPqOYfOd2RlEqltbX16tWr1ZMmTJigew8HTdPR0dFisbi2tpb+8x6ORoYNG6Ye50aRNAPr
XiPaulxSUkIIOXnyZJNfrUnbltBkqpZ1QUcYHZ/Stgnp37Xn93DQNP3w4UNCSHx8PP3nrSIi
ImLo0KHM68ePH3O53EOHDunfkZdcXzpgDwcAmLYhQ4bcu3fv0qVLM2fOrKmpCQsLGz58eEND
w6NHjyorK4cNG6aec/jw4c+ePSsqKmp2mb179+Zw/vh5fPDgQXl5ub+/f6N5Hj58+OzZsxkz
ZlD/5evrSwi5f/8+IWTQoEEXL17s06dPi/vVs2dP9WsnJ6fq6uq6ujrdH9ER6dGjR1VVVZon
ZAwfPrzZDEuWLFEoFDExMY3ai4qK5s6d6+vr27lz544dO166dCk/P7/ZpTW7RprssqOjY0RE
REBAgL+//5o1a27evKlt+dq2hCZnblkX9A+jSdsm1LKlqdE0TQihKKpRe0RERGZmZl5eHiEk
JSXF3t7+vffea8FXt2x96QiMggMATB5FUf369ZszZ05KSsrx48czMzP37dun7eeYaVHXEwyl
Uqn51szMTP1a23KYj6Snpzf6N27IkCHNBhYKhRUVFZot1dXVSqVSJBKpW7hcbqNPqVQq3YvV
EYnphVAo1MzQbE5ra+tVq1bFxsY+evRIsz0wMPDGjRtxcXEZGRnXrl0bPny4TCZrdmm61wjR
3uWkpKTffvvN398/MzOzX79+zxdAmot6fktocs6WdeGFwqhp63jLlqZ248YNQki3bt0atQ8b
Nszd3X3Xrl2EkOTk5KlTpzZ5/XOzX93i9aUNCg4AaFeY398nT54w57KdOXNGPenMmTP29vYd
O3YkhDg5OZWWlqon5eTk6Fhghw4dfv755ybbf/zxxxaE9PT0zM3N1aw5zp8/z7S/0HIEAgFz
Nkmzkbp06WJtbX3t2jV1y9WrV/X5isjISA8PjyVLlqhbysrKsrKyPv/887feesvNzc3Jyenu
3bvaIjXKoGON6Obt7T1//vz09PSFCxfGx8frk1y9JTyfqsVd0BFGx6e0bUIt7hohRCaTrV+/
vnPnzkOHDm00iaKoadOmJScnX7p06datWxERES/UEbWXWV9NQsEBAKbNx8dnw4YNv/76661b
t9LT0ydNmiQQCAIDAymKWrx48VdffZWUlHTv3r1vv/1206ZNS5cuZT7l7+9/5MgR5s9MRkZG
QkKCtuVzudzPP/988+bN69aty8nJuX379jfffFNUVMTj8VauXLljx46lS5fevHnz7t27hw4d
Cg8PZz71n//8Z+jQodp2kv/tb3+jKGr8+PEnTpy4efPm3r17Z82a5ePj86L3P+jWrduNGzdy
cnJKS0ulUqmOSBwOZ968eV9++SVzxOfs2bOpqan6fAWHw4mLi0tNTS0uLmZabG1tHR0dmf0o
CoVi0aJFBQUF2iJpLkr3GtHmzp07ixcvvnDhQmFhIXPGZe/evZucU9uW8HyqFndBRxgdn9K2
CenfNUKIQqHIzc3Nzc29fPlyQkLCgAEDbty48d133wkEgudnnjZtWkFBwezZsyUSibe3d8tG
tWXrSxfdp3gAALRxa9asefPNNx0dHQUCgVgsHj9+/MWLF5lJzEV9rq6uPB6v0UV9crk8Kiqq
Y8eOzs7O48aNi4mJ0TxpdNKkSY2+JSEhoXfv3nw+387OLiAgQH1ZbFpamp+fn0gksrKy6tu3
7/Lly5n29PR0QkhGRoa22Lm5uSEhIV26dBGJRD169Jg3b155ebl6aqMMJ06cIIRUV1fTfz49
8OnTpwEBAdbW1kTjslhtkeRy+fz58+3t7cVi8bvvvrt27dpmTxpVCwoKIoSoTxo9e/Zsv379
nJ2d3d3do6OjQ0JC1Gmfj/T8ZZZNrhFtXS4oKAgODhaLxQKBoFOnTtOmTWOu8Hyeji3h+VQt
64KOMLo7Tje1Cenftblz5zJ/sjkcjrW1tY+PT1RUVH5+vnqGRt9F0/SIESMIIVu2bNFs1Kcj
L7m+mszPoGiabnm1AgAAAKAHHFIBAAAAo0PBAQAAAEaHggMAAACMDgUHAAAAGB0KDgAAADA6
FBwAAABgdCg4AAAAwOhQcAAAAIDRoeAAAAAAo0PBAQAAAEaHggMAAACM7v8B3CXDjvpdpZYA
AAAASUVORK5CYII="
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[404]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-r"><pre><span></span><span class="nf">run_tests</span><span class="p">({</span>
    <span class="nf">test_that</span><span class="p">(</span><span class="s">&quot;Title is correct.&quot;</span><span class="p">,</span> <span class="p">{</span>
    <span class="nf">expect_equal</span><span class="p">(</span><span class="nf">toupper</span><span class="p">(</span><span class="nf">gsub</span><span class="p">(</span><span class="s">&quot;[[:space:]]&quot;</span><span class="p">,</span> <span class="s">&quot;&quot;</span><span class="p">,</span> <span class="nf">last_plot</span><span class="p">()</span><span class="o">$</span><span class="n">labels</span><span class="o">$</span><span class="n">title</span><span class="p">)),</span> <span class="s">&quot;LIFEEXPECTANCYATBIRTHBYCOUNTRY&quot;</span><span class="p">,</span> 
        <span class="n">info</span> <span class="o">=</span> <span class="s">&quot;Did you add the title correctly?&quot;</span><span class="p">)</span>
    <span class="p">})</span>

        <span class="nf">test_that</span><span class="p">(</span><span class="s">&quot;x-axis label is correct.&quot;</span><span class="p">,</span> <span class="p">{</span>
    <span class="nf">expect_equal</span><span class="p">(</span><span class="nf">toupper</span><span class="p">(</span><span class="nf">gsub</span><span class="p">(</span><span class="s">&quot;[[:space:]]&quot;</span><span class="p">,</span> <span class="s">&quot;&quot;</span><span class="p">,</span> <span class="nf">last_plot</span><span class="p">()</span><span class="o">$</span><span class="n">labels</span><span class="o">$</span><span class="n">x</span><span class="p">)),</span> <span class="s">&quot;MALES&quot;</span><span class="p">,</span> 
        <span class="n">info</span> <span class="o">=</span> <span class="s">&quot;Did you set the x-axis label correctly?&quot;</span><span class="p">)</span>
    <span class="p">})</span>

    
        <span class="nf">test_that</span><span class="p">(</span><span class="s">&quot;y-axis label is correct.&quot;</span><span class="p">,</span> <span class="p">{</span>
    <span class="nf">expect_equal</span><span class="p">(</span><span class="nf">toupper</span><span class="p">(</span><span class="nf">gsub</span><span class="p">(</span><span class="s">&quot;[[:space:]]&quot;</span><span class="p">,</span> <span class="s">&quot;&quot;</span><span class="p">,</span> <span class="nf">last_plot</span><span class="p">()</span><span class="o">$</span><span class="n">labels</span><span class="o">$</span><span class="n">y</span><span class="p">)),</span> <span class="s">&quot;FEMALES&quot;</span><span class="p">,</span> 
        <span class="n">info</span> <span class="o">=</span> <span class="s">&quot;Did you set the y-axis label correctly?&quot;</span><span class="p">)</span>
    <span class="p">})</span>

          <span class="nf">test_that</span><span class="p">(</span><span class="s">&quot;caption is correct.&quot;</span><span class="p">,</span> <span class="p">{</span>
    <span class="nf">expect_equal</span><span class="p">(</span><span class="nf">toupper</span><span class="p">(</span><span class="nf">gsub</span><span class="p">(</span><span class="s">&quot;[[:space:]]&quot;</span><span class="p">,</span> <span class="s">&quot;&quot;</span><span class="p">,</span> <span class="nf">last_plot</span><span class="p">()</span><span class="o">$</span><span class="n">labels</span><span class="o">$</span><span class="n">caption</span><span class="p">)),</span> <span class="s">&quot;SOURCE:UNITEDNATIONSSTATISTICSDIVISION&quot;</span><span class="p">,</span> 
        <span class="n">info</span> <span class="o">=</span> <span class="s">&quot;Did you set the caption correctly?&quot;</span><span class="p">)</span>
    <span class="p">})</span>

    
    
<span class="p">})</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>





</div>

<div class="output_area">

    <div class="prompt"></div>





</div>

<div class="output_area">

    <div class="prompt"></div>




<div class="output_text output_subarea ">
<pre>4/4 tests passed</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="6.-Highlighting-remarkable-countries-I">6. Highlighting remarkable countries I<a class="anchor-link" href="#6.-Highlighting-remarkable-countries-I">&#182;</a></h2><p>Now, we will label some points of our plot with the name of its corresponding country. We want to draw attention to some special countries where the gap in life expectancy between men and women is significantly high. These will be the final touches on this first plot.</p>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[405]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-r"><pre><span></span><span class="c1"># Subseting data to obtain countries of interest</span>
<span class="n">top_male</span> <span class="o">&lt;-</span> <span class="n">subdata</span> <span class="o">%&gt;%</span> 
    <span class="nf">arrange</span><span class="p">(</span><span class="n">Male</span> <span class="o">-</span> <span class="n">Female</span><span class="p">)</span> <span class="o">%&gt;%</span> 
    <span class="nf">head</span><span class="p">(</span><span class="m">3</span><span class="p">)</span>
<span class="n">top_female</span> <span class="o">&lt;-</span> <span class="n">subdata</span> <span class="o">%&gt;%</span> 
    <span class="nf">arrange</span><span class="p">(</span><span class="n">Female</span> <span class="o">-</span> <span class="n">Male</span><span class="p">)</span> <span class="o">%&gt;%</span> 
    <span class="nf">head</span><span class="p">(</span><span class="m">3</span><span class="p">)</span>

<span class="c1"># Adding text to the previous plot to label countries of interest </span>
<span class="nf">ggplot</span><span class="p">(</span><span class="n">subdata</span><span class="p">,</span> <span class="nf">aes</span><span class="p">(</span><span class="n">x</span><span class="o">=</span><span class="n">Male</span><span class="p">,</span> <span class="n">y</span><span class="o">=</span><span class="n">Female</span><span class="p">,</span> <span class="n">label</span> <span class="o">=</span> <span class="n">Country.or.Area</span><span class="p">))</span><span class="o">+</span>
    <span class="nf">geom_point</span><span class="p">(</span><span class="n">colour</span> <span class="o">=</span> <span class="s">&quot;white&quot;</span><span class="p">,</span> <span class="n">fill</span> <span class="o">=</span> <span class="s">&quot;chartreuse3&quot;</span><span class="p">,</span> 
               <span class="n">shape</span> <span class="o">=</span> <span class="m">21</span><span class="p">,</span> <span class="n">alpha</span> <span class="o">=</span> <span class="m">.55</span><span class="p">,</span> <span class="n">size</span> <span class="o">=</span> <span class="m">5</span><span class="p">)</span><span class="o">+</span>
    <span class="nf">geom_abline</span><span class="p">(</span><span class="n">intercept</span> <span class="o">=</span> <span class="m">0</span><span class="p">,</span> <span class="n">slope</span> <span class="o">=</span> <span class="m">1</span><span class="p">,</span> <span class="n">linetype</span><span class="o">=</span><span class="m">2</span><span class="p">)</span><span class="o">+</span>
    <span class="nf">scale_x_continuous</span><span class="p">(</span><span class="n">limits</span><span class="o">=</span><span class="nf">c</span><span class="p">(</span><span class="m">35</span><span class="p">,</span><span class="m">85</span><span class="p">))</span><span class="o">+</span>
    <span class="nf">scale_y_continuous</span><span class="p">(</span><span class="n">limits</span><span class="o">=</span><span class="nf">c</span><span class="p">(</span><span class="m">35</span><span class="p">,</span><span class="m">85</span><span class="p">))</span><span class="o">+</span>
    <span class="nf">labs</span><span class="p">(</span><span class="n">title</span><span class="o">=</span><span class="s">&quot;Life Expectancy at Birth by Country&quot;</span><span class="p">,</span>
        <span class="n">subtitle</span><span class="o">=</span><span class="s">&quot;Years. Period: 2000-2005. Average.&quot;</span><span class="p">,</span>
        <span class="n">caption</span><span class="o">=</span><span class="s">&quot;Source: United Nations Statistics Division&quot;</span><span class="p">,</span>
        <span class="n">x</span><span class="o">=</span><span class="s">&quot;Males&quot;</span><span class="p">,</span>
        <span class="n">y</span><span class="o">=</span><span class="s">&quot;Females&quot;</span><span class="p">)</span><span class="o">+</span>
    <span class="nf">geom_text</span><span class="p">(</span><span class="n">data</span> <span class="o">=</span> <span class="n">top_male</span><span class="p">,</span> <span class="n">size</span> <span class="o">=</span> <span class="m">3</span><span class="p">)</span><span class="o">+</span>
    <span class="nf">geom_text</span><span class="p">(</span><span class="n">data</span> <span class="o">=</span> <span class="n">top_female</span><span class="p">,</span> <span class="n">size</span> <span class="o">=</span> <span class="m">3</span><span class="p">)</span><span class="o">+</span>
    <span class="nf">theme_bw</span><span class="p">()</span>
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
8PHHHycnJ2/ZssXzS3Pv3r1+Vm40GidPniyvorF+/fpp06b961//ev31169P5H7q1KnTxYsX
WZb17uQ4ffo0TdNJSUlygdzcXEEQPJ0ckiT5s4hWvR5//PF//etf8+fPX7ZsWd3rUL9+/das
WbNv3z55HKts3759DMNkZmYGsExkZORXX33lecune+P6BFkXz/O5ubkmk6lZPWGrV68WRfH9
999v166d9/bly5dv2rRp6dKl8vIzU6ZMefzxxz/77LMpU6b8+9//TklJGTBggKdwi0+nJn9A
OnbsmJubK4qip5OD/HaL59r3jhC6JbTuHZ2Wka8xixYt8mx59913AWDu3Lk+8znl0f6EkK5d
uyYlJXlGMAiCMHr0aAB4/PHH5S3yve2vvvrKZ1/V1dXeL+XZlX/84x/ll6IoHjhw4Pjx441E
W+8sFf8jbygwnzEcixcvhqvvzcsFRo4c6V1gxYoVngKffPIJ1Bk02uS0WEmS5syZAwBPPPFE
Q2XKyso0Gk1GRgbLsvKWI0eO0DR9zz33BLxMqweZk5PjPdxSFMXHH38cAGbOnOm9sfHzRJKk
5OTk5OTkum/JC3J4xkcTQh588EGGYdatWwd1Zsm2+HRq8gfkb3/7GwCsWrXK85E1a9b4nD9N
7t2fnxeE0M3qJunhmD9//k8//bRixYpjx47dd999UVFRRUVFBw4cOHHihHzzeNKkSYsXLx4z
ZswDDzxgs9nWr19P/Lub0K5du3vuuad3797x8fEVFRWrVq1iGOahhx6S33U6nVlZWampqefP
nw9S5H56+umn//Of//z1r389c+ZM//79c3NzP/zww7CwMHltNAB48sknv/jii3nz5h0/frxX
r14nTpz47LPP0tPT8/LyvOuZNGnSpUuXXC5XQ89YeeGFF1auXNm+ffvw8PCXX37Zsz06Olq+
xgNAbGzskiVLnnrqqQEDBsyYMcNsNr/33nsmk+mtt97ylA9UmVYP8p133tmyZcuIESMSEhLs
dvuuXbtOnz6dnJzsPWSkyfPkp59+ys/Plwe3+hg9erRer1+1atW8efPkLbNmzVq7du3cuXNp
mp45c6Z34RafTk3+gDz99NNffPHF3Llzjx071rNnz5MnT3766acZGRne50+Te7/2nxeEUBvW
2hlPS9Tt4SCEiKK4fPnyO+64w2AwaDSapKSk8ePHf/755/K7PM+//PLLnTp1UqlU7du3f+KJ
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
9aYVc+fOfQvvYmJicurUqZycnAkTJrxhV28nMNHlnqDZELQ7cDs7u+zsbIqiRCJRQUHB7t27
9+7de/bs2UmTJqn/XuqspsPtRQEAGCy5XG5qavrNN9+0uVQmk61fv75///5sNtvJySk2NlYu
l9OLPD09Fy1apFgzNTWVw+HQjz/99NOAgIBly5Y5ODgwmczGxkaKolJSUjw8PDgcTq9evby8
vMrLy+mVk5OT3dzcOByOo6Pjl19+WVtbq07sjz76aPLkyS0amUzmpk2bFBlmzpwZExPTr18/
S0vLadOmPX/+nF4UFhY2bdo0iqIiIiKUP8z37t2rOpJUKl22bFnv3r3NzMwCAgJ27drFZDLb
jLdo0aIhQ4YEBAQIBALFjDk6OkZFRdGPs7KyPD09ra2tzc3NR44c+cMPP9DtbUZSBFa9RVQM
OScnZ9y4cVwu18zMbNiwYadPn26dWcWe0GYqjYfQZpgOX0W1swupMzR6i/B4POWWpqam999/
n8fjicVi5fdKSkrq0aOH8n54/PhxNpv96tUrdQaile3VHpxSAQADxmAwHBwcrly5UlVV1Xpp
XFzcxo0bV61adf/+/eXLl8fExOzYsUOdbjMyMoyMjB4+fFhTU8PhcHbu3BkRETFz5sw7d+5k
Z2f7+vpKpVJCyLfffrtkyZKoqKgHDx4cPXr02rVrs2fPpnvIyspiMBi5ubkaD+3MmTMsFuvR
o0clJSXV1dV///vfW6yQkJDw2Wef+fv705/mCxYsUB1p48aNe/fu3blzZ2Fh4ahRo1atWqU6
QFxc3L1791JTU1svev369YIFC3Jycm7dujVt2jQ/P7/79++3F6lFnyq2SJtDbm5u9vX1HTt2
bH5+/r179+Li4iwtLVtHUrEntJlKsyG0F6bDgbe5C6k5tDYZGxsvX778+fPnLfaxwMBAIyOj
kydPKloOHz7s6+vbu3dvdQbSggbbSxXV9QgAQBeXm5s7cOBAFos1fPjwBQsWpKeny2QyiqLk
crmlpeWqVasUa0ZFRVlbW9OPVR/hGDBgAN0JRVFSqbRnz56RkZEt3lcqlVpbWyckJChabt++
TQh58eIFRVF5eXmjR48uKChoM7M6RzhcXV0Vi44ePcrlcunHyv+AKv+RUx1JJpNZWFisX79e
sSgwMFD1EQ6KoqKiong8Xn19PfX7IxwtTJw4UTHPLSIpB1a9Rdobcnl5OSHk4sWLbb61svb2
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"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[406]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-r"><pre><span></span><span class="n">texts</span><span class="o">=</span><span class="nf">c</span><span class="p">()</span>
<span class="nf">for </span><span class="p">(</span><span class="n">i</span> <span class="n">in</span> <span class="m">1</span><span class="o">:</span><span class="nf">length</span><span class="p">(</span><span class="nf">last_plot</span><span class="p">()</span><span class="o">$</span><span class="n">layers</span><span class="p">))</span> <span class="n">texts</span><span class="o">=</span><span class="nf">c</span><span class="p">(</span><span class="nf">last_plot</span><span class="p">()</span><span class="o">$</span><span class="n">layers[[i]]</span><span class="o">$</span><span class="n">data</span><span class="o">$</span><span class="n">Country.or.Area</span> <span class="o">%&gt;%</span> <span class="n">as.character</span><span class="p">,</span> <span class="n">texts</span><span class="p">)</span>


<span class="nf">run_tests</span><span class="p">({</span>
   
      <span class="nf">test_that</span><span class="p">(</span><span class="s">&quot;Test that countries defined by top_female and top_male are correctly labeled.&quot;</span><span class="p">,</span> <span class="p">{</span>
    <span class="nf">expect_true</span><span class="p">(</span><span class="nf">length</span><span class="p">(</span><span class="nf">setdiff</span><span class="p">(</span><span class="n">texts</span><span class="p">,</span> <span class="nf">c</span><span class="p">(</span><span class="s">&quot;Russian Federation&quot;</span><span class="p">,</span> <span class="s">&quot;Belarus&quot;</span><span class="p">,</span> <span class="s">&quot;Estonia&quot;</span><span class="p">,</span> <span class="s">&quot;Niger&quot;</span><span class="p">,</span> <span class="s">&quot;Afghanistan&quot;</span><span class="p">,</span> <span class="s">&quot;Maldives&quot;</span><span class="p">)))</span><span class="o">==</span><span class="m">0</span><span class="p">,</span> 
                 <span class="n">info</span> <span class="o">=</span> <span class="s">&quot;It seems that countries defined by top_female and top_male are not labeled correctly.&quot;</span><span class="p">)</span>
  <span class="p">})</span>
    
        <span class="nf">test_that</span><span class="p">(</span><span class="s">&quot;Theme is theme_bw().&quot;</span><span class="p">,</span> <span class="p">{</span>
    <span class="nf">expect_equal</span><span class="p">(</span><span class="nf">last_plot</span><span class="p">()</span><span class="o">$</span><span class="n">theme</span><span class="o">$</span><span class="n">panel.background</span><span class="o">$</span><span class="n">fill</span><span class="p">,</span> <span class="s">&quot;white&quot;</span><span class="p">,</span> 
        <span class="n">info</span> <span class="o">=</span> <span class="s">&quot;It seems that your plot does not have theme_bw().&quot;</span><span class="p">)</span>
    <span class="p">})</span>


<span class="p">})</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>





</div>

<div class="output_area">

    <div class="prompt"></div>





</div>

<div class="output_area">

    <div class="prompt"></div>




<div class="output_text output_subarea ">
<pre>2/2 tests passed</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="7.-How-has-life-expectancy-by-gender-evolved?">7. How has life expectancy by gender evolved?<a class="anchor-link" href="#7.-How-has-life-expectancy-by-gender-evolved?">&#182;</a></h2><p>Since our data contains historical information, let's see now how life expectancy has evolved in recent years. Our second plot will represent the difference between men and women across countries between two periods: 2000-2005 and 1985-1990.</p>
<p>Let's start building a dataset called <code>subdata2</code> for our second plot. </p>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[407]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-r"><pre><span></span><span class="c1"># Subsetting, mutating and reshaping the life expectancy data</span>
<span class="n">subdata2</span> <span class="o">&lt;-</span> <span class="n">life_expectancy</span> <span class="o">%&gt;%</span> 
    <span class="nf">filter</span><span class="p">(</span><span class="n">Year</span> <span class="o">%in%</span> <span class="nf">c</span><span class="p">(</span><span class="s">&quot;1985-1990&quot;</span><span class="p">,</span> <span class="s">&quot;2000-2005&quot;</span><span class="p">))</span> <span class="o">%&gt;%</span> 
    <span class="c1"># example result: &quot;Female_1985-1990&quot;</span>
    <span class="nf">mutate</span><span class="p">(</span><span class="n">Sub_Year</span> <span class="o">=</span> <span class="nf">paste</span><span class="p">(</span><span class="n">Subgroup</span><span class="p">,</span> <span class="n">Year</span><span class="p">,</span> <span class="n">sep</span> <span class="o">=</span> <span class="s">&quot;_&quot;</span><span class="p">))</span> <span class="o">%&gt;%</span> 
    <span class="c1"># replaceing &quot;-&quot; with &quot;_&quot; because &quot;-&quot; shouldn&#39;t be used to name a column</span>
    <span class="c1"># example result: &quot;Female_1985_1990&quot;</span>
    <span class="nf">mutate</span><span class="p">(</span><span class="n">Sub_Year</span> <span class="o">=</span> <span class="nf">gsub</span><span class="p">(</span><span class="s">&quot;-&quot;</span><span class="p">,</span> <span class="s">&quot;_&quot;</span><span class="p">,</span> <span class="n">Sub_Year</span><span class="p">))</span> <span class="o">%&gt;%</span> 
    <span class="c1"># we don&#39;t need these 2 columns anymore</span>
    <span class="nf">select</span><span class="p">(</span><span class="o">-</span><span class="n">Subgroup</span><span class="p">,</span> <span class="o">-</span><span class="n">Year</span><span class="p">)</span> <span class="o">%&gt;%</span>
    <span class="nf">spread</span><span class="p">(</span><span class="n">Sub_Year</span><span class="p">,</span> <span class="n">Value</span><span class="p">)</span> <span class="o">%&gt;%</span>
    <span class="nf">mutate</span><span class="p">(</span><span class="n">diff_Female</span> <span class="o">=</span> <span class="n">Female_2000_2005</span> <span class="o">-</span> <span class="n">Female_1985_1990</span><span class="p">,</span>
           <span class="n">diff_Male</span> <span class="o">=</span> <span class="n">Male_2000_2005</span> <span class="o">-</span> <span class="n">Male_1985_1990</span><span class="p">)</span>

<span class="c1"># Taking a look at the first few rows</span>
<span class="nf">head</span><span class="p">(</span><span class="n">subdata2</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>



<div class="output_html rendered_html output_subarea ">
<table>
<caption>A data.frame: 6 x 10</caption>
<thead>
	<tr><th scope=col>Country.or.Area</th><th scope=col>Source</th><th scope=col>Unit</th><th scope=col>Value.Footnotes</th><th scope=col>Female_1985_1990</th><th scope=col>Female_2000_2005</th><th scope=col>Male_1985_1990</th><th scope=col>Male_2000_2005</th><th scope=col>diff_Female</th><th scope=col>diff_Male</th></tr>
	<tr><th scope=col>&lt;fct&gt;</th><th scope=col>&lt;fct&gt;</th><th scope=col>&lt;fct&gt;</th><th scope=col>&lt;int&gt;</th><th scope=col>&lt;int&gt;</th><th scope=col>&lt;int&gt;</th><th scope=col>&lt;int&gt;</th><th scope=col>&lt;int&gt;</th><th scope=col>&lt;int&gt;</th><th scope=col>&lt;int&gt;</th></tr>
</thead>
<tbody>
	<tr><td>Afghanistan</td><td>UNPD_World Population Prospects_2006 (International estimate)</td><td>Years</td><td>NA</td><td>41</td><td>42</td><td>41</td><td>42</td><td>1</td><td>1</td></tr>
	<tr><td>Albania    </td><td>UNPD_World Population Prospects_2006 (International estimate)</td><td>Years</td><td>NA</td><td>75</td><td>79</td><td>69</td><td>73</td><td>4</td><td>4</td></tr>
	<tr><td>Algeria    </td><td>UNPD_World Population Prospects_2006 (International estimate)</td><td>Years</td><td>NA</td><td>67</td><td>72</td><td>65</td><td>70</td><td>5</td><td>5</td></tr>
	<tr><td>Angola     </td><td>UNPD_World Population Prospects_2006 (International estimate)</td><td>Years</td><td>NA</td><td>42</td><td>43</td><td>38</td><td>39</td><td>1</td><td>1</td></tr>
	<tr><td>Argentina  </td><td>UNPD_World Population Prospects_2006 (International estimate)</td><td>Years</td><td>NA</td><td>75</td><td>78</td><td>68</td><td>71</td><td>3</td><td>3</td></tr>
	<tr><td>Armenia    </td><td>UNPD_World Population Prospects_2006 (International estimate)</td><td>Years</td><td>NA</td><td>71</td><td>75</td><td>66</td><td>68</td><td>4</td><td>2</td></tr>
</tbody>
</table>

</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[408]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-r"><pre><span></span><span class="nf">run_tests</span><span class="p">({</span>
  <span class="nf">test_that</span><span class="p">(</span><span class="s">&quot;Test that subdata2 is created correctly.&quot;</span><span class="p">,</span> <span class="p">{</span>
    <span class="nf">expect_true</span><span class="p">(</span><span class="nf">nrow</span><span class="p">(</span><span class="n">subdata2</span><span class="p">)</span><span class="o">==</span><span class="m">195</span><span class="p">,</span> 
                 <span class="n">info</span> <span class="o">=</span> <span class="s">&quot;It seems that dataset subdata2 is not correctly created.&quot;</span><span class="p">)</span>
  <span class="p">})</span>

  <span class="nf">test_that</span><span class="p">(</span><span class="s">&quot;Test that subdata2 is created correctly.&quot;</span><span class="p">,</span> <span class="p">{</span>
    <span class="nf">expect_true</span><span class="p">(</span><span class="nf">ncol</span><span class="p">(</span><span class="n">subdata2</span><span class="p">)</span><span class="o">==</span><span class="m">10</span><span class="p">,</span> 
                 <span class="n">info</span> <span class="o">=</span> <span class="s">&quot;It seems that dataset subdata2 is not correctly created.&quot;</span><span class="p">)</span>
  <span class="p">})</span>

  <span class="nf">test_that</span><span class="p">(</span><span class="s">&quot;Test that subdata2 is created correctly.&quot;</span><span class="p">,</span> <span class="p">{</span>
    <span class="nf">expect_true</span><span class="p">(</span><span class="nf">length</span><span class="p">(</span><span class="nf">setdiff</span><span class="p">(</span><span class="nf">c</span><span class="p">(</span><span class="s">&#39;diff_Female&#39;</span><span class="p">,</span> <span class="s">&#39;diff_Male&#39;</span><span class="p">),</span> <span class="nf">names</span><span class="p">(</span><span class="n">subdata2</span><span class="p">)))</span><span class="o">==</span><span class="m">0</span><span class="p">,</span> 
                 <span class="n">info</span> <span class="o">=</span> <span class="s">&quot;It seems that subdata2 does not contain columns diff_Female or diff_Male.&quot;</span><span class="p">)</span>
  <span class="p">})</span>

    <span class="nf">test_that</span><span class="p">(</span><span class="s">&quot;Test that subdata2 is created correctly.&quot;</span><span class="p">,</span> <span class="p">{</span>
    <span class="nf">expect_true</span><span class="p">(</span><span class="nf">sum</span><span class="p">(</span><span class="n">subdata2</span><span class="o">$</span><span class="n">diff_Female</span><span class="p">)</span><span class="o">==</span><span class="m">492</span><span class="p">,</span> 
                 <span class="n">info</span> <span class="o">=</span> <span class="s">&quot;It seems that the diff_Female column is not correctly created.&quot;</span><span class="p">)</span>
  <span class="p">})</span>  
    
  <span class="nf">test_that</span><span class="p">(</span><span class="s">&quot;Test that subdata2 is created correctly.&quot;</span><span class="p">,</span> <span class="p">{</span>
    <span class="nf">expect_true</span><span class="p">(</span><span class="nf">sum</span><span class="p">(</span><span class="n">subdata2</span><span class="o">$</span><span class="n">diff_Male</span><span class="p">)</span><span class="o">==</span><span class="m">503</span><span class="p">,</span> 
                 <span class="n">info</span> <span class="o">=</span> <span class="s">&quot;It seems that the diff_Male column is not correctly created.&quot;</span><span class="p">)</span>
  <span class="p">})</span>
<span class="p">})</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>





</div>

<div class="output_area">

    <div class="prompt"></div>





</div>

<div class="output_area">

    <div class="prompt"></div>




<div class="output_text output_subarea ">
<pre>5/5 tests passed</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="8.-Visualize-II">8. Visualize II<a class="anchor-link" href="#8.-Visualize-II">&#182;</a></h2><p>Now let's create our second plot in which we will represent average life expectancy differences between "1985-1990" and "2000-2005" for men and women.</p>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[409]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-r"><pre><span></span><span class="c1"># Doing a nice first version of the plot with abline, scaling axis and adding labels</span>
<span class="nf">ggplot</span><span class="p">(</span><span class="n">subdata2</span><span class="p">,</span> <span class="nf">aes</span><span class="p">(</span><span class="n">x</span> <span class="o">=</span> <span class="n">diff_Male</span><span class="p">,</span> <span class="n">y</span> <span class="o">=</span> <span class="n">diff_Female</span><span class="p">,</span> <span class="n">label</span> <span class="o">=</span> <span class="n">Country.or.Area</span><span class="p">))</span><span class="o">+</span>
    <span class="nf">geom_point</span><span class="p">(</span><span class="n">colour</span> <span class="o">=</span> <span class="s">&quot;white&quot;</span><span class="p">,</span> <span class="n">fill</span> <span class="o">=</span> <span class="s">&quot;chartreuse3&quot;</span><span class="p">,</span> 
                <span class="n">shape</span> <span class="o">=</span> <span class="m">21</span><span class="p">,</span> <span class="n">alpha</span> <span class="o">=</span> <span class="m">.55</span><span class="p">,</span> <span class="n">size</span> <span class="o">=</span> <span class="m">5</span><span class="p">)</span><span class="o">+</span>
    <span class="nf">geom_abline</span><span class="p">(</span><span class="n">intercept</span> <span class="o">=</span> <span class="m">0</span><span class="p">,</span> <span class="n">slope</span> <span class="o">=</span> <span class="m">1</span><span class="p">,</span> <span class="n">linetype</span> <span class="o">=</span> <span class="m">2</span><span class="p">)</span><span class="o">+</span>
    <span class="nf">scale_x_continuous</span><span class="p">(</span><span class="n">limits</span> <span class="o">=</span> <span class="nf">c</span><span class="p">(</span><span class="m">-25</span><span class="p">,</span> <span class="m">25</span><span class="p">))</span><span class="o">+</span>
    <span class="nf">scale_y_continuous</span><span class="p">(</span><span class="n">limits</span> <span class="o">=</span> <span class="nf">c</span><span class="p">(</span><span class="m">-25</span><span class="p">,</span> <span class="m">25</span><span class="p">))</span><span class="o">+</span>
    <span class="nf">labs</span><span class="p">(</span><span class="n">title</span> <span class="o">=</span> <span class="s">&quot;Life Expectancy at Birth by Country in Years&quot;</span><span class="p">,</span>
        <span class="n">subtitle</span> <span class="o">=</span> <span class="s">&quot;Difference between 1985-1990 and 2000-2005. Average.&quot;</span><span class="p">,</span>
        <span class="n">caption</span> <span class="o">=</span> <span class="s">&quot;Source: United Nations Statistics Division&quot;</span><span class="p">,</span>
        <span class="n">x</span> <span class="o">=</span> <span class="s">&quot;Males&quot;</span><span class="p">,</span>
        <span class="n">y</span> <span class="o">=</span> <span class="s">&quot;Females&quot;</span><span class="p">)</span><span class="o">+</span>
    <span class="nf">theme_bw</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[410]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-r"><pre><span></span><span class="nf">run_tests</span><span class="p">({</span>
    
<span class="c1">#    test_that(&quot;Check that a geom_point plot was plotted.&quot;, {</span>
<span class="c1">#     expect_true( &quot;GeomPoint&quot; %in% class( last_plot()$layers[[1]]$geom ) , </span>
<span class="c1">#                  info = &quot;Add geom_point() to produce a scatter plot.&quot;)</span>
<span class="c1">#   })</span>
  
  <span class="nf">test_that</span><span class="p">(</span><span class="s">&quot;Check variables are correctly mapped.&quot;</span><span class="p">,</span> <span class="p">{</span>
    <span class="nf">expect_true</span><span class="p">(</span> <span class="nf">deparse</span><span class="p">(</span><span class="nf">last_plot</span><span class="p">()</span><span class="o">$</span><span class="n">mapping</span><span class="o">$</span><span class="n">x</span><span class="p">)</span><span class="o">==</span><span class="s">&quot;~diff_Male&quot;</span> <span class="o">&amp;</span> <span class="nf">deparse</span><span class="p">(</span><span class="nf">last_plot</span><span class="p">()</span><span class="o">$</span><span class="n">mapping</span><span class="o">$</span><span class="n">y</span><span class="p">)</span><span class="o">==</span><span class="s">&quot;~diff_Female&quot;</span><span class="p">,</span> 
                 <span class="n">info</span> <span class="o">=</span> <span class="s">&quot;Check that the variables are mapped to the correct axes.&quot;</span><span class="p">)</span>
  <span class="p">})</span>
  
    
<span class="c1">#     test_that(&quot;Intercept of diagonal line is equal to 0.&quot;, {</span>
<span class="c1">#     expect_equal(ggplot_build(last_plot())$data[[2]]$intercept, 0, </span>
<span class="c1">#         info = &quot;Did you add the diagonal line correctly?&quot;)</span>
<span class="c1">#     })</span>
<span class="c1">#     test_that(&quot;Slope of diagonal line is equal to 1.&quot;, {</span>
<span class="c1">#     expect_equal(ggplot_build(last_plot())$data[[2]]$slope, 1, </span>
<span class="c1">#         info = &quot;Did you add the diagonal line correctly?&quot;)</span>
<span class="c1">#     })</span>
    <span class="nf">test_that</span><span class="p">(</span><span class="s">&quot;Limits of x-axis&quot;</span><span class="p">,</span> <span class="p">{</span>
        <span class="nf">expect_equal</span><span class="p">(</span><span class="nf">length</span><span class="p">(</span><span class="nf">setdiff</span><span class="p">(</span><span class="nf">c</span><span class="p">(</span><span class="m">-20</span><span class="p">,</span> <span class="m">15</span><span class="p">),</span> <span class="nf">ggplot_build</span><span class="p">(</span><span class="nf">last_plot</span><span class="p">())</span><span class="o">$</span><span class="n">layout</span><span class="o">$</span><span class="n">panel_scales_x[[1]]</span><span class="o">$</span><span class="n">range</span><span class="o">$</span><span class="n">range</span><span class="p">)),</span> <span class="m">0</span><span class="p">,</span> 
               <span class="n">info</span> <span class="o">=</span> <span class="s">&quot;Limits of x-axis is not equal to [-25, 25].&quot;</span><span class="p">)</span>
    <span class="p">})</span>
    <span class="nf">test_that</span><span class="p">(</span><span class="s">&quot;Limits of y-axis&quot;</span><span class="p">,</span> <span class="p">{</span>
        <span class="nf">expect_equal</span><span class="p">(</span><span class="nf">length</span><span class="p">(</span><span class="nf">setdiff</span><span class="p">(</span><span class="nf">c</span><span class="p">(</span><span class="m">-24</span><span class="p">,</span> <span class="m">15</span><span class="p">),</span> <span class="nf">ggplot_build</span><span class="p">(</span><span class="nf">last_plot</span><span class="p">())</span><span class="o">$</span><span class="n">layout</span><span class="o">$</span><span class="n">panel_scales_y[[1]]</span><span class="o">$</span><span class="n">range</span><span class="o">$</span><span class="n">range</span><span class="p">)),</span> <span class="m">0</span><span class="p">,</span> 
               <span class="n">info</span> <span class="o">=</span> <span class="s">&quot;Limits of y-axis is not equal to [-25, 25]&quot;</span><span class="p">)</span>
    <span class="p">})</span>
    
<span class="c1">#     test_that(&quot;Intercept of diagonal line is equal to 0.&quot;, {</span>
<span class="c1">#     expect_equal(toupper(gsub(&quot;[[:space:]]&quot;, &quot;&quot;, last_plot()$labels$title)), &quot;LIFEEXPECTANCYATBIRTHBYCOUNTRYINYEARS&quot;, </span>
<span class="c1">#         info = &quot;Did you add the title correctly?&quot;)</span>
<span class="c1">#     })</span>
<span class="c1">#     test_that(&quot;Slope of diagonal line is equal to 1.&quot;, {</span>
<span class="c1">#     expect_equal(last_plot()$theme$panel.background$fill, &quot;white&quot;, </span>
<span class="c1">#         info = &quot;It seems that your plot does not have theme_bw().&quot;)</span>
<span class="c1">#     })</span>
<span class="p">})</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>





</div>

<div class="output_area">

    <div class="prompt"></div>





</div>

<div class="output_area">

    <div class="prompt"></div>




<div class="output_text output_subarea ">
<pre>3/3 tests passed</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="9.-Reference-lines-II">9. Reference lines II<a class="anchor-link" href="#9.-Reference-lines-II">&#182;</a></h2><p>Adding reference lines can make plots easier to understand. We already added a diagonal line to visualize differences between men and women more clearly. Now we will add two more lines to help to identify in which countries people increased or decreased their life expectancy in the period analyzed.</p>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[411]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-r"><pre><span></span><span class="c1"># Adding an hline and vline to previous plots</span>
<span class="nf">ggplot</span><span class="p">(</span><span class="n">subdata2</span><span class="p">,</span> <span class="nf">aes</span><span class="p">(</span><span class="n">x</span> <span class="o">=</span> <span class="n">diff_Male</span><span class="p">,</span> <span class="n">y</span> <span class="o">=</span> <span class="n">diff_Female</span><span class="p">,</span> <span class="n">label</span> <span class="o">=</span> <span class="n">Country.or.Area</span><span class="p">))</span><span class="o">+</span>
    <span class="nf">geom_point</span><span class="p">(</span><span class="n">colour</span> <span class="o">=</span> <span class="s">&quot;white&quot;</span><span class="p">,</span> <span class="n">fill</span> <span class="o">=</span> <span class="s">&quot;chartreuse3&quot;</span><span class="p">,</span> 
               <span class="n">shape</span> <span class="o">=</span> <span class="m">21</span><span class="p">,</span> <span class="n">alpha</span> <span class="o">=</span> <span class="m">.55</span><span class="p">,</span> <span class="n">size</span> <span class="o">=</span> <span class="m">5</span><span class="p">)</span><span class="o">+</span>
    <span class="nf">geom_abline</span><span class="p">(</span><span class="n">intercept</span> <span class="o">=</span> <span class="m">0</span><span class="p">,</span> <span class="n">slope</span> <span class="o">=</span> <span class="m">1</span><span class="p">,</span> <span class="n">linetype</span> <span class="o">=</span> <span class="m">2</span><span class="p">)</span><span class="o">+</span>
    <span class="nf">scale_x_continuous</span><span class="p">(</span><span class="n">limits</span> <span class="o">=</span> <span class="nf">c</span><span class="p">(</span><span class="m">-25</span><span class="p">,</span><span class="m">25</span><span class="p">))</span><span class="o">+</span>
    <span class="nf">scale_y_continuous</span><span class="p">(</span><span class="n">limits</span> <span class="o">=</span> <span class="nf">c</span><span class="p">(</span><span class="m">-25</span><span class="p">,</span><span class="m">25</span><span class="p">))</span><span class="o">+</span>
    <span class="nf">geom_vline</span><span class="p">(</span><span class="n">linetype</span> <span class="o">=</span> <span class="m">2</span><span class="p">,</span> <span class="n">xintercept</span> <span class="o">=</span> <span class="m">0</span><span class="p">)</span><span class="o">+</span>
    <span class="nf">geom_hline</span><span class="p">(</span><span class="n">linetype</span> <span class="o">=</span> <span class="m">2</span><span class="p">,</span> <span class="n">yintercept</span> <span class="o">=</span> <span class="m">0</span><span class="p">)</span><span class="o">+</span>
    <span class="nf">labs</span><span class="p">(</span><span class="n">title</span> <span class="o">=</span> <span class="s">&quot;Life Expectancy at Birth by Country&quot;</span><span class="p">,</span>
        <span class="n">subtitle</span> <span class="o">=</span> <span class="s">&quot;Years. Difference between 1985-1990 and 2000-2005. Average.&quot;</span><span class="p">,</span>
        <span class="n">caption</span> <span class="o">=</span> <span class="s">&quot;Source: United Nations Statistics Division&quot;</span><span class="p">,</span>
        <span class="n">x</span> <span class="o">=</span> <span class="s">&quot;Males&quot;</span><span class="p">,</span>
        <span class="n">y</span> <span class="o">=</span> <span class="s">&quot;Females&quot;</span><span class="p">)</span><span class="o">+</span>
    <span class="nf">theme_bw</span><span class="p">()</span>
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
SURBVHtOIFzia3tWXqvVRkdHE0KszZiRkWE7Do5l2enTpxNCnn/+eWfCq36QztTJzc0VPiBr
zbS0NJqmn3rqqQqiqtr33e7TmT9/PiFk7dq11gpffvklcTRolOO4KVOmEEJmzpxZXh1nVspV
dUQP0pnNzOGOlOO4yMjIyMjI0m8JY7OsFxDwPP/cc89JJBLhRsx2V8lWeW/pcIuaO3cuIeTz
zz+3TrJp0ya7rcXh0p05oHiWutnDMW3atNTU1LVr1549e3bo0KHBwcF37tw5ceLE+fPnhXNj
I0eOnD9/fkJCwujRozUazbZt23jnukZDQ0Ofeuqp9u3bh4WFPXjw4PPPP5dIJOPHjxfe1ev1
Xbp0iY2NvXLlSsXzuXjx4ocffkgIMRgMt27dSk1NvXXrVkxMzK5du2x7I92x7i6f0G4me/fu
/fjjj8+dO5eQkODr63vt2rX9+/dfunSpOoto3Lhxx44dX375ZZVKtW3btuPHj7/11lvWX70O
Zytc5r5q1Sq5XO7v7x8SEtKnTx9CSLdu3RQKxeXLlwcMGCD0mnp5eXXt2vXgwYPe3t7C9bdO
LsIlrVemzZs3C3mt0DW9aNEimqalUqlwmyxBWFhYv379mjZtqtPpfvjhh8zMzFdeeUW46EYw
Y8aMjRs3Ll269MqVK7169dJoNN98882NGzemTJlibcbly5enpKT069evUaNGWq328OHDly5d
ioyMtDuX774gnanToEGDhQsXvvHGG926dRs3blxBQcEnn3zi6+srfJvKU+Xvu63XX3998+bN
U6dOPXfuXLt27c6fP//111/HxcUJlziV59133123bl14eHi9evUWLFhgLQ8JCRGO8U6ulKvq
iB6kM5uZwx1pampqVlaWMLjVzqBBg3x8fD7//POpU6cKJRMnTtyyZUtSUhJN03bbW5W/tg63
qDfffHPz5s1JSUlnz5597LHHLly48NVXX7Vo0cJ2a3G4dOcPKB5D5ITHFUr3cPA8z7LsmjVr
Hn/8cZVKJdwg+ZlnnrGOdbdYLAsWLBBuJBUeHj5z5kxhd+mwh2POnDldu3YNCgqSyWRhYWHP
PPPM77//bn1Xo9EQQmJjYyuIVujhEFAUpVKpmjZtOmLEiK+//trwzzsQVK2Hw+G6V3DvzipM
WPo3utlsXrp0aevWrb28vNRqdZs2bWzv/VrxIkqzvfFXVFSUXC5v2rTpRx99ZPebwOFsd+/e
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"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[412]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-r"><pre><span></span><span class="nf">for </span><span class="p">(</span><span class="n">i</span> <span class="n">in</span> <span class="m">1</span><span class="o">:</span><span class="nf">length</span><span class="p">(</span><span class="nf">ggplot_build</span><span class="p">(</span><span class="nf">last_plot</span><span class="p">())</span><span class="o">$</span><span class="n">data</span><span class="p">))</span> 
<span class="p">{</span>
  <span class="nf">if </span><span class="p">(</span><span class="s">&quot;slope&quot;</span>      <span class="o">%in%</span> <span class="nf">colnames</span><span class="p">(</span><span class="nf">ggplot_build</span><span class="p">(</span><span class="nf">last_plot</span><span class="p">())</span><span class="o">$</span><span class="n">data[[i]]</span><span class="p">))</span> <span class="n">i1</span><span class="o">=</span><span class="n">i</span>
  <span class="nf">if </span><span class="p">(</span><span class="s">&quot;yintercept&quot;</span> <span class="o">%in%</span> <span class="nf">colnames</span><span class="p">(</span><span class="nf">ggplot_build</span><span class="p">(</span><span class="nf">last_plot</span><span class="p">())</span><span class="o">$</span><span class="n">data[[i]]</span><span class="p">))</span> <span class="n">i2</span><span class="o">=</span><span class="n">i</span>
  <span class="nf">if </span><span class="p">(</span><span class="s">&quot;xintercept&quot;</span> <span class="o">%in%</span> <span class="nf">colnames</span><span class="p">(</span><span class="nf">ggplot_build</span><span class="p">(</span><span class="nf">last_plot</span><span class="p">())</span><span class="o">$</span><span class="n">data[[i]]</span><span class="p">))</span> <span class="n">i3</span><span class="o">=</span><span class="n">i</span>
<span class="p">}</span>
      

<span class="nf">run_tests</span><span class="p">({</span>
<span class="c1">#     test_that(&quot;Intercept of diagonal line is equal to 0.&quot;, {</span>
<span class="c1">#     expect_equal(ggplot_build(last_plot())$data[[i1]]$intercept, 0, </span>
<span class="c1">#         info = &quot;Did you add the diagonal line correctly?&quot;)</span>
<span class="c1">#     })</span>
<span class="c1">#     test_that(&quot;Slope of diagonal line is equal to 1.&quot;, {</span>
<span class="c1">#     expect_equal(ggplot_build(last_plot())$data[[i1]]$slope, 1, </span>
<span class="c1">#         info = &quot;Did you add the diagonal line correctly?&quot;)</span>
<span class="c1">#     })</span>

        <span class="nf">test_that</span><span class="p">(</span><span class="s">&quot;Horizontal line is well defined.&quot;</span><span class="p">,</span> <span class="p">{</span>
    <span class="nf">expect_equal</span><span class="p">(</span><span class="nf">ggplot_build</span><span class="p">(</span><span class="nf">last_plot</span><span class="p">())</span><span class="o">$</span><span class="n">data[[i2]]</span><span class="o">$</span><span class="n">yintercept</span><span class="p">,</span> <span class="m">0</span><span class="p">,</span> 
        <span class="n">info</span> <span class="o">=</span> <span class="s">&quot;Did you add the horizontal line correctly?&quot;</span><span class="p">)</span>
    <span class="p">})</span>
    <span class="nf">test_that</span><span class="p">(</span><span class="s">&quot;Vertical line is well defined.&quot;</span><span class="p">,</span> <span class="p">{</span>
    <span class="nf">expect_equal</span><span class="p">(</span><span class="nf">ggplot_build</span><span class="p">(</span><span class="nf">last_plot</span><span class="p">())</span><span class="o">$</span><span class="n">data[[i3]]</span><span class="o">$</span><span class="n">xintercept</span><span class="p">,</span> <span class="m">0</span><span class="p">,</span> 
        <span class="n">info</span> <span class="o">=</span> <span class="s">&quot;Did you add the vertical line correctly?&quot;</span><span class="p">)</span>
    <span class="p">})</span>
<span class="p">})</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>





</div>

<div class="output_area">

    <div class="prompt"></div>





</div>

<div class="output_area">

    <div class="prompt"></div>




<div class="output_text output_subarea ">
<pre>2/2 tests passed</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="10.-Highlighting-remarkable-countries-II">10. Highlighting remarkable countries II<a class="anchor-link" href="#10.-Highlighting-remarkable-countries-II">&#182;</a></h2><p>As we did in the first plot, let's label some points. Concretely, we will point those three where the aggregated average life expectancy for men and women increased most and those three where decreased most in the period.</p>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[413]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-r"><pre><span></span><span class="c1"># Subseting data to obtain countries of interest</span>
<span class="n">top</span> <span class="o">&lt;-</span> <span class="n">subdata2</span> <span class="o">%&gt;%</span> 
    <span class="nf">arrange</span><span class="p">(</span><span class="n">diff_Male</span> <span class="o">+</span> <span class="n">diff_Female</span><span class="p">)</span> <span class="o">%&gt;%</span> 
    <span class="nf">head</span><span class="p">(</span><span class="m">3</span><span class="p">)</span>
<span class="n">bottom</span> <span class="o">&lt;-</span> <span class="n">subdata2</span> <span class="o">%&gt;%</span> 
    <span class="nf">arrange</span><span class="p">(</span><span class="o">-</span><span class="p">(</span><span class="n">diff_Male</span> <span class="o">+</span> <span class="n">diff_Female</span><span class="p">))</span> <span class="o">%&gt;%</span> 
    <span class="nf">head</span><span class="p">(</span><span class="m">3</span><span class="p">)</span>

<span class="c1"># Adding text to the previous plot to label countries of interest</span>
<span class="nf">ggplot</span><span class="p">(</span><span class="n">subdata2</span><span class="p">,</span> <span class="nf">aes</span><span class="p">(</span><span class="n">x</span> <span class="o">=</span> <span class="n">diff_Male</span><span class="p">,</span> <span class="n">y</span> <span class="o">=</span> <span class="n">diff_Female</span><span class="p">,</span> 
                     <span class="n">label</span> <span class="o">=</span> <span class="n">Country.or.Area</span><span class="p">),</span> <span class="n">guide</span> <span class="o">=</span> <span class="kc">FALSE</span><span class="p">)</span><span class="o">+</span>
    <span class="nf">geom_point</span><span class="p">(</span><span class="n">colour</span> <span class="o">=</span> <span class="s">&quot;white&quot;</span><span class="p">,</span> <span class="n">fill</span> <span class="o">=</span> <span class="s">&quot;chartreuse3&quot;</span><span class="p">,</span> 
               <span class="n">shape</span> <span class="o">=</span> <span class="m">21</span><span class="p">,</span> <span class="n">alpha</span> <span class="o">=</span> <span class="m">.55</span><span class="p">,</span> <span class="n">size</span> <span class="o">=</span> <span class="m">5</span><span class="p">)</span><span class="o">+</span>
    <span class="nf">geom_abline</span><span class="p">(</span><span class="n">intercept</span> <span class="o">=</span> <span class="m">0</span><span class="p">,</span> <span class="n">slope</span> <span class="o">=</span> <span class="m">1</span><span class="p">,</span> <span class="n">linetype</span><span class="o">=</span><span class="m">2</span><span class="p">)</span><span class="o">+</span>
    <span class="nf">scale_x_continuous</span><span class="p">(</span><span class="n">limits</span> <span class="o">=</span> <span class="nf">c</span><span class="p">(</span><span class="m">-25</span><span class="p">,</span> <span class="m">25</span><span class="p">))</span><span class="o">+</span>
    <span class="nf">scale_y_continuous</span><span class="p">(</span><span class="n">limits</span> <span class="o">=</span> <span class="nf">c</span><span class="p">(</span><span class="m">-25</span><span class="p">,</span> <span class="m">25</span><span class="p">))</span><span class="o">+</span>
    <span class="nf">geom_hline</span><span class="p">(</span><span class="n">yintercept</span> <span class="o">=</span> <span class="m">0</span><span class="p">,</span> <span class="n">linetype</span> <span class="o">=</span> <span class="m">2</span><span class="p">)</span><span class="o">+</span>
    <span class="nf">geom_vline</span><span class="p">(</span><span class="n">xintercept</span> <span class="o">=</span> <span class="m">0</span><span class="p">,</span> <span class="n">linetype</span> <span class="o">=</span> <span class="m">2</span><span class="p">)</span><span class="o">+</span>
    <span class="nf">labs</span><span class="p">(</span><span class="n">title</span> <span class="o">=</span> <span class="s">&quot;Life Expectancy at Birth by Country&quot;</span><span class="p">,</span>
        <span class="n">subtitle</span> <span class="o">=</span> <span class="s">&quot;Years. Difference between 1985-1990 and 2000-2005. Average.&quot;</span><span class="p">,</span>
        <span class="n">caption</span> <span class="o">=</span> <span class="s">&quot;Source: United Nations Statistics Division&quot;</span><span class="p">,</span>
        <span class="n">x</span> <span class="o">=</span> <span class="s">&quot;Males&quot;</span><span class="p">,</span>
        <span class="n">y</span> <span class="o">=</span> <span class="s">&quot;Females&quot;</span><span class="p">)</span><span class="o">+</span>
    <span class="nf">geom_text</span><span class="p">(</span><span class="n">data</span> <span class="o">=</span> <span class="n">top</span><span class="p">,</span> <span class="n">size</span> <span class="o">=</span> <span class="m">3</span><span class="p">)</span><span class="o">+</span>
    <span class="nf">geom_text</span><span class="p">(</span><span class="n">data</span> <span class="o">=</span> <span class="n">bottom</span><span class="p">,</span> <span class="n">size</span> <span class="o">=</span> <span class="m">3</span><span class="p">)</span><span class="o">+</span>
    <span class="nf">theme_bw</span><span class="p">()</span>
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
SURBVLA6hiyUseqwHqQhq1mxG1KSJF1cXFxcXPK/RZ+bxVxAQFHUkCFDuFwufSNmvatkS721
LHaNmj17NgBs3bqVmWTPnj16a0uxczdkh2JeKucIx8SJE2NjYzdt2nT79u1evXo5ODi8fPny
ypUr//zzD31srH///vPmzQsODh44cKBMJtu3bx9l2NBorVq1evTo0bRpUycnp3fv3m3dupXL
5Q4fPpx+Ny8vr2XLlp6eno8ePSq6nXv37v3yyy8AIJfLnz9/Hhsb+/z5cw8Pj0OHDumORppi
2Y0+oV4jx44dW7Vq1Z07d4KDg62srJ48eXLq1Kn79++XZRZ16tQJCAj46quvJBLJvn37Ll26
9P333zO/eottlr7Mfc2aNQKBwMbGxtHRsX379gDQqlUroVD48OHDzp0706OmIpEoMDAwLi7O
wsKCvv7WwFkYpfcKtHfvXjqvpYemFy1axOFweDwefZssmpOTU8eOHd3c3HJzc48ePZqcnDxh
wgT6ohva5MmTd+/evWzZskePHrVt21Ymk+3atSspKWn8+PFMN65YsSImJqZjx461a9fOyck5
e/bs/fv3XVxc9I7lmy5IQ+rUqFFj4cKF06ZNa9Wq1bBhwzIyMtauXWtlZUV/mwpT6u+7rqlT
p+7duzcsLOzOnTtNmjT5559/du7c6eXlRV/iVJg5c+Zs3rzZ2dm5WrVqCxYsYModHR3pfbyB
C2WsOqwHachqVuyGNDY2NiUlhT65VU/Xrl0tLS23bt0aFhZGl4wcOTIyMjI0NJTD4eitb6X+
2ha7Rn333Xd79+4NDQ29fft248aN7969u2PHDm9vb921pdi5G75DMRssJzzGkH+Eg6IorVa7
cePGzz77TCKR0DdI7t27N3Ouu1qtXrBgAX0jKWdn5ylTptCby2JHOGbOnBkYGGhvb8/n852c
nHr37n358mXmXZlMBgCenp5FREuPcNAIgpBIJG5ubv369du5c6f8/+9AULoRjmKXvYh7d5Zi
wvy/0VUq1bJly3x9fUUikVQq9fPz0733a9GzyE/3xl+urq4CgcDNze3XX3/V+01QbLOHDx9u
1KgRnVW0adOGKW/Xrh38/+0o6MvbOnfuXKLOMVbv5Ucf69Gj96s6NDS0fv36YrHYysqqTZs2
Bw4cyN9OSkoKfRN9Ho9nYWHRrFmz9evX614g88cff/Ts2bNOnToikYj+nTpjxgwDR1+MFaQh
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
Q8IBAAAAjPsvilJyp6mmqhMAAAAASUVORK5CYII="
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[414]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-r"><pre><span></span><span class="n">texts</span><span class="o">=</span><span class="nf">c</span><span class="p">()</span>
<span class="nf">for </span><span class="p">(</span><span class="n">i</span> <span class="n">in</span> <span class="m">1</span><span class="o">:</span><span class="nf">length</span><span class="p">(</span><span class="nf">last_plot</span><span class="p">()</span><span class="o">$</span><span class="n">layers</span><span class="p">))</span> <span class="n">texts</span><span class="o">=</span><span class="nf">c</span><span class="p">(</span><span class="nf">last_plot</span><span class="p">()</span><span class="o">$</span><span class="n">layers[[i]]</span><span class="o">$</span><span class="n">data</span><span class="o">$</span><span class="n">Country.or.Area</span> <span class="o">%&gt;%</span> <span class="n">as.character</span><span class="p">,</span> <span class="n">texts</span><span class="p">)</span>

<span class="nf">run_tests</span><span class="p">({</span>
  <span class="nf">test_that</span><span class="p">(</span><span class="s">&quot;Test that dataset bottom exists.&quot;</span><span class="p">,</span> <span class="p">{</span>
    <span class="nf">expect_true</span><span class="p">(</span><span class="nf">exists</span><span class="p">(</span><span class="s">&quot;bottom&quot;</span><span class="p">),</span> 
                 <span class="n">info</span> <span class="o">=</span> <span class="s">&quot;It seems that bottom does not exist.&quot;</span><span class="p">)</span>
  <span class="p">})</span>

  <span class="nf">test_that</span><span class="p">(</span><span class="s">&quot;Test that dataset bottom is correctly created.&quot;</span><span class="p">,</span> <span class="p">{</span>
    <span class="nf">expect_true</span><span class="p">(</span><span class="nf">nrow</span><span class="p">(</span><span class="n">bottom</span><span class="p">)</span><span class="o">==</span><span class="m">3</span><span class="p">,</span> 
                 <span class="n">info</span> <span class="o">=</span> <span class="s">&quot;It seems that bottom is not correctly created.&quot;</span><span class="p">)</span>
  <span class="p">})</span>

  <span class="nf">test_that</span><span class="p">(</span><span class="s">&quot;Test that countries defined by top and bottom are correctly labeled.&quot;</span><span class="p">,</span> <span class="p">{</span>
    <span class="nf">expect_true</span><span class="p">(</span><span class="nf">length</span><span class="p">(</span><span class="nf">setdiff</span><span class="p">(</span><span class="n">texts</span><span class="p">,</span> <span class="nf">c</span><span class="p">(</span><span class="s">&quot;Timor Leste&quot;</span><span class="p">,</span> <span class="s">&quot;Bhutan&quot;</span><span class="p">,</span> <span class="s">&quot;Egypt&quot;</span><span class="p">,</span> <span class="s">&quot;Zimbabwe&quot;</span><span class="p">,</span> <span class="s">&quot;Botswana&quot;</span><span class="p">,</span> <span class="s">&quot;Swaziland&quot;</span><span class="p">)))</span><span class="o">==</span><span class="m">0</span><span class="p">,</span> 
                 <span class="n">info</span> <span class="o">=</span> <span class="s">&quot;It seems that countries defined by top and bottom are not labeled correctly.&quot;</span><span class="p">)</span>
  <span class="p">})</span>


<span class="p">})</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>





</div>

<div class="output_area">

    <div class="prompt"></div>





</div>

<div class="output_area">

    <div class="prompt"></div>




<div class="output_text output_subarea ">
<pre>3/3 tests passed</pre>
</div>

</div>

</div>
</div>

</div>
    </div>
  </div>
</body>

 


</html>
