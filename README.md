<!DOCTYPE html><html><head><meta charset="utf-8"><style>body {
  width: 45em;
  border: 1px solid #ddd;
  outline: 1300px solid #fff;
  margin: 16px auto;
}

body .markdown-body
{
  padding: 30px;
}

@font-face {
  font-family: fontawesome-mini;
  src: url(data:font/woff;charset=utf-8;base64,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) format('woff');
}

@font-face {
  font-family: octicons-anchor;
  src: url(data:font/woff;charset=utf-8;base64,d09GRgABAAAAAAYcAA0AAAAACjQAAQAAAAAAAAAAAAAAAAAAAAAAAAAAAABGRlRNAAABMAAAABwAAAAca8vGTk9TLzIAAAFMAAAARAAAAFZG1VHVY21hcAAAAZAAAAA+AAABQgAP9AdjdnQgAAAB0AAAAAQAAAAEACICiGdhc3AAAAHUAAAACAAAAAj//wADZ2x5ZgAAAdwAAADRAAABEKyikaNoZWFkAAACsAAAAC0AAAA2AtXoA2hoZWEAAALgAAAAHAAAACQHngNFaG10eAAAAvwAAAAQAAAAEAwAACJsb2NhAAADDAAAAAoAAAAKALIAVG1heHAAAAMYAAAAHwAAACABEAB2bmFtZQAAAzgAAALBAAAFu3I9x/Nwb3N0AAAF/AAAAB0AAAAvaoFvbwAAAAEAAAAAzBdyYwAAAADP2IQvAAAAAM/bz7t4nGNgZGFgnMDAysDB1Ml0hoGBoR9CM75mMGLkYGBgYmBlZsAKAtJcUxgcPsR8iGF2+O/AEMPsznAYKMwIkgMA5REMOXicY2BgYGaAYBkGRgYQsAHyGMF8FgYFIM0ChED+h5j//yEk/3KoSgZGNgYYk4GRCUgwMaACRoZhDwCs7QgGAAAAIgKIAAAAAf//AAJ4nHWMMQrCQBBF/0zWrCCIKUQsTDCL2EXMohYGSSmorScInsRGL2DOYJe0Ntp7BK+gJ1BxF1stZvjz/v8DRghQzEc4kIgKwiAppcA9LtzKLSkdNhKFY3HF4lK69ExKslx7Xa+vPRVS43G98vG1DnkDMIBUgFN0MDXflU8tbaZOUkXUH0+U27RoRpOIyCKjbMCVejwypzJJG4jIwb43rfl6wbwanocrJm9XFYfskuVC5K/TPyczNU7b84CXcbxks1Un6H6tLH9vf2LRnn8Ax7A5WQAAAHicY2BkYGAA4teL1+yI57f5ysDNwgAC529f0kOmWRiYVgEpDgYmEA8AUzEKsQAAAHicY2BkYGB2+O/AEMPCAAJAkpEBFbAAADgKAe0EAAAiAAAAAAQAAAAEAAAAAAAAKgAqACoAiAAAeJxjYGRgYGBhsGFgYgABEMkFhAwM/xn0QAIAD6YBhwB4nI1Ty07cMBS9QwKlQapQW3VXySvEqDCZGbGaHULiIQ1FKgjWMxknMfLEke2A+IJu+wntrt/QbVf9gG75jK577Lg8K1qQPCfnnnt8fX1NRC/pmjrk/zprC+8D7tBy9DHgBXoWfQ44Av8t4Bj4Z8CLtBL9CniJluPXASf0Lm4CXqFX8Q84dOLnMB17N4c7tBo1AS/Qi+hTwBH4rwHHwN8DXqQ30XXAS7QaLwSc0Gn8NuAVWou/gFmnjLrEaEh9GmDdDGgL3B4JsrRPDU2hTOiMSuJUIdKQQayiAth69r6akSSFqIJuA19TrzCIaY8sIoxyrNIrL//pw7A2iMygkX5vDj+G+kuoLdX4GlGK/8Lnlz6/h9MpmoO9rafrz7ILXEHHaAx95s9lsI7AHNMBWEZHULnfAXwG9/ZqdzLI08iuwRloXE8kfhXYAvE23+23DU3t626rbs8/8adv+9DWknsHp3E17oCf+Z48rvEQNZ78paYM38qfk3v/u3l3u3GXN2Dmvmvpf1Srwk3pB/VSsp512bA/GG5i2WJ7wu430yQ5K3nFGiOqgtmSB5pJVSizwaacmUZzZhXLlZTq8qGGFY2YcSkqbth6aW1tRmlaCFs2016m5qn36SbJrqosG4uMV4aP2PHBmB3tjtmgN2izkGQyLWprekbIntJFing32a5rKWCN/SdSoga45EJykyQ7asZvHQ8PTm6cslIpwyeyjbVltNikc2HTR7YKh9LBl9DADC0U/jLcBZDKrMhUBfQBvXRzLtFtjU9eNHKin0x5InTqb8lNpfKv1s1xHzTXRqgKzek/mb7nB8RZTCDhGEX3kK/8Q75AmUM/eLkfA+0Hi908Kx4eNsMgudg5GLdRD7a84npi+YxNr5i5KIbW5izXas7cHXIMAau1OueZhfj+cOcP3P8MNIWLyYOBuxL6DRylJ4cAAAB4nGNgYoAALjDJyIAOWMCiTIxMLDmZedkABtIBygAAAA==) format('woff');
}

.markdown-body {
  font-family: sans-serif;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  color: #333333;
  overflow: hidden;
  font-family: "Helvetica Neue", Helvetica, "Segoe UI", Arial, freesans, sans-serif;
  font-size: 16px;
  line-height: 1.6;
  word-wrap: break-word;
}

.markdown-body a {
  background: transparent;
}

.markdown-body a:active,
.markdown-body a:hover {
  outline: 0;
}

.markdown-body b,
.markdown-body strong {
  font-weight: bold;
}

.markdown-body mark {
  background: #ff0;
  color: #000;
  font-style: italic;
  font-weight: bold;
}

.markdown-body sub,
.markdown-body sup {
  font-size: 75%;
  line-height: 0;
  position: relative;
  vertical-align: baseline;
}
.markdown-body sup {
  top: -0.5em;
}
.markdown-body sub {
  bottom: -0.25em;
}

.markdown-body h1 {
  font-size: 2em;
  margin: 0.67em 0;
}

.markdown-body img {
  border: 0;
}

.markdown-body hr {
  -moz-box-sizing: content-box;
  box-sizing: content-box;
  height: 0;
}

.markdown-body pre {
  overflow: auto;
}

.markdown-body code,
.markdown-body kbd,
.markdown-body pre,
.markdown-body samp {
  font-family: monospace, monospace;
  font-size: 1em;
}

.markdown-body input {
  color: inherit;
  font: inherit;
  margin: 0;
}

.markdown-body html input[disabled] {
  cursor: default;
}

.markdown-body input {
  line-height: normal;
}

.markdown-body input[type="checkbox"] {
  box-sizing: border-box;
  padding: 0;
}

.markdown-body table {
  border-collapse: collapse;
  border-spacing: 0;
}

.markdown-body td,
.markdown-body th {
  padding: 0;
}

.markdown-body .codehilitetable {
  border: 0;
  border-spacing: 0;
}

.markdown-body .codehilitetable tr {
  border: 0;
}

.markdown-body .codehilitetable pre,
.markdown-body .codehilitetable div.codehilite {
  margin: 0;
}

.markdown-body .linenos,
.markdown-body .code,
.markdown-body .codehilitetable td {
  border: 0;
  padding: 0;
}

.markdown-body td:not(.linenos) .linenodiv {
  padding: 0 !important;
}

.markdown-body .code {
  width: 100%;
}

.markdown-body .linenos div pre,
.markdown-body .linenodiv pre,
.markdown-body .linenodiv {
  border: 0;
  -webkit-border-radius: 0;
  -moz-border-radius: 0;
  border-radius: 0;
  -webkit-border-top-left-radius: 3px;
  -webkit-border-bottom-left-radius: 3px;
  -moz-border-radius-topleft: 3px;
  -moz-border-radius-bottomleft: 3px;
  border-top-left-radius: 3px;
  border-bottom-left-radius: 3px;
}

.markdown-body .code div pre,
.markdown-body .code div {
  border: 0;
  -webkit-border-radius: 0;
  -moz-border-radius: 0;
  border-radius: 0;
  -webkit-border-top-right-radius: 3px;
  -webkit-border-bottom-right-radius: 3px;
  -moz-border-radius-topright: 3px;
  -moz-border-radius-bottomright: 3px;
  border-top-right-radius: 3px;
  border-bottom-right-radius: 3px;
}

.markdown-body * {
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}

.markdown-body input {
  font: 13px Helvetica, arial, freesans, clean, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol";
  line-height: 1.4;
}

.markdown-body a {
  color: #4183c4;
  text-decoration: none;
}

.markdown-body a:hover,
.markdown-body a:focus,
.markdown-body a:active {
  text-decoration: underline;
}

.markdown-body hr {
  height: 0;
  margin: 15px 0;
  overflow: hidden;
  background: transparent;
  border: 0;
  border-bottom: 1px solid #ddd;
}

.markdown-body hr:before,
.markdown-body hr:after {
  display: table;
  content: " ";
}

.markdown-body hr:after {
  clear: both;
}

.markdown-body h1,
.markdown-body h2,
.markdown-body h3,
.markdown-body h4,
.markdown-body h5,
.markdown-body h6 {
  margin-top: 15px;
  margin-bottom: 15px;
  line-height: 1.1;
}

.markdown-body h1 {
  font-size: 30px;
}

.markdown-body h2 {
  font-size: 21px;
}

.markdown-body h3 {
  font-size: 16px;
}

.markdown-body h4 {
  font-size: 14px;
}

.markdown-body h5 {
  font-size: 12px;
}

.markdown-body h6 {
  font-size: 11px;
}

.markdown-body blockquote {
  margin: 0;
}

.markdown-body ul,
.markdown-body ol {
  padding: 0;
  margin-top: 0;
  margin-bottom: 0;
}

.markdown-body ol ol,
.markdown-body ul ol {
  list-style-type: lower-roman;
}

.markdown-body ul ul ol,
.markdown-body ul ol ol,
.markdown-body ol ul ol,
.markdown-body ol ol ol {
  list-style-type: lower-alpha;
}

.markdown-body dd {
  margin-left: 0;
}

.markdown-body code,
.markdown-body pre,
.markdown-body samp {
  font-family: Consolas, "Liberation Mono", Menlo, Courier, monospace;
  font-size: 12px;
}

.markdown-body pre {
  margin-top: 0;
  margin-bottom: 0;
}

.markdown-body kbd {
  background-color: #e7e7e7;
  background-image: -moz-linear-gradient(#fefefe, #e7e7e7);
  background-image: -webkit-linear-gradient(#fefefe, #e7e7e7);
  background-image: linear-gradient(#fefefe, #e7e7e7);
  background-repeat: repeat-x;
  border-radius: 2px;
  border: 1px solid #cfcfcf;
  color: #000;
  padding: 3px 5px;
  line-height: 10px;
  font: 11px Consolas, "Liberation Mono", Menlo, Courier, monospace;
  display: inline-block;
}

.markdown-body>*:first-child {
  margin-top: 0 !important;
}

.markdown-body>*:last-child {
  margin-bottom: 0 !important;
}

.markdown-body .headeranchor-link {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  display: block;
  padding-right: 6px;
  padding-left: 30px;
  margin-left: -30px;
}

.markdown-body .headeranchor-link:focus {
  outline: none;
}

.markdown-body h1,
.markdown-body h2,
.markdown-body h3,
.markdown-body h4,
.markdown-body h5,
.markdown-body h6 {
  position: relative;
  margin-top: 1em;
  margin-bottom: 16px;
  font-weight: bold;
  line-height: 1.4;
}

.markdown-body h1 .headeranchor,
.markdown-body h2 .headeranchor,
.markdown-body h3 .headeranchor,
.markdown-body h4 .headeranchor,
.markdown-body h5 .headeranchor,
.markdown-body h6 .headeranchor {
  display: none;
  color: #000;
  vertical-align: middle;
}

.markdown-body h1:hover .headeranchor-link,
.markdown-body h2:hover .headeranchor-link,
.markdown-body h3:hover .headeranchor-link,
.markdown-body h4:hover .headeranchor-link,
.markdown-body h5:hover .headeranchor-link,
.markdown-body h6:hover .headeranchor-link {
  height: 1em;
  padding-left: 8px;
  margin-left: -30px;
  line-height: 1;
  text-decoration: none;
}

.markdown-body h1:hover .headeranchor-link .headeranchor,
.markdown-body h2:hover .headeranchor-link .headeranchor,
.markdown-body h3:hover .headeranchor-link .headeranchor,
.markdown-body h4:hover .headeranchor-link .headeranchor,
.markdown-body h5:hover .headeranchor-link .headeranchor,
.markdown-body h6:hover .headeranchor-link .headeranchor {
  display: inline-block;
}

.markdown-body h1 {
  padding-bottom: 0.3em;
  font-size: 2.25em;
  line-height: 1.2;
  border-bottom: 1px solid #eee;
}

.markdown-body h2 {
  padding-bottom: 0.3em;
  font-size: 1.75em;
  line-height: 1.225;
  border-bottom: 1px solid #eee;
}

.markdown-body h3 {
  font-size: 1.5em;
  line-height: 1.43;
}

.markdown-body h4 {
  font-size: 1.25em;
}

.markdown-body h5 {
  font-size: 1em;
}

.markdown-body h6 {
  font-size: 1em;
  color: #777;
}

.markdown-body p,
.markdown-body blockquote,
.markdown-body ul,
.markdown-body ol,
.markdown-body dl,
.markdown-body table,
.markdown-body pre,
.markdown-body .admonition {
  margin-top: 0;
  margin-bottom: 16px;
}

.markdown-body hr {
  height: 4px;
  padding: 0;
  margin: 16px 0;
  background-color: #e7e7e7;
  border: 0 none;
}

.markdown-body ul,
.markdown-body ol {
  padding-left: 2em;
}

.markdown-body ul ul,
.markdown-body ul ol,
.markdown-body ol ol,
.markdown-body ol ul {
  margin-top: 0;
  margin-bottom: 0;
}

.markdown-body li>p {
  margin-top: 16px;
}

.markdown-body dl {
  padding: 0;
}

.markdown-body dl dt {
  padding: 0;
  margin-top: 16px;
  font-size: 1em;
  font-style: italic;
  font-weight: bold;
}

.markdown-body dl dd {
  padding: 0 16px;
  margin-bottom: 16px;
}

.markdown-body blockquote {
  padding: 0 15px;
  color: #777;
  border-left: 4px solid #ddd;
}

.markdown-body blockquote>:first-child {
  margin-top: 0;
}

.markdown-body blockquote>:last-child {
  margin-bottom: 0;
}

.markdown-body table {
  display: block;
  width: 100%;
  overflow: auto;
  word-break: normal;
  word-break: keep-all;
}

.markdown-body table th {
  font-weight: bold;
}

.markdown-body table th,
.markdown-body table td {
  padding: 6px 13px;
  border: 1px solid #ddd;
}

.markdown-body table tr {
  background-color: #fff;
  border-top: 1px solid #ccc;
}

.markdown-body table tr:nth-child(2n) {
  background-color: #f8f8f8;
}

.markdown-body img {
  max-width: 100%;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}

.markdown-body code,
.markdown-body samp {
  padding: 0;
  padding-top: 0.2em;
  padding-bottom: 0.2em;
  margin: 0;
  font-size: 85%;
  background-color: rgba(0,0,0,0.04);
  border-radius: 3px;
}

.markdown-body code:before,
.markdown-body code:after {
  letter-spacing: -0.2em;
  content: "\00a0";
}

.markdown-body pre>code {
  padding: 0;
  margin: 0;
  font-size: 100%;
  word-break: normal;
  white-space: pre;
  background: transparent;
  border: 0;
}

.markdown-body .codehilite {
  margin-bottom: 16px;
}

.markdown-body .codehilite pre,
.markdown-body pre {
  padding: 16px;
  overflow: auto;
  font-size: 85%;
  line-height: 1.45;
  background-color: #f7f7f7;
  border-radius: 3px;
}

.markdown-body .codehilite pre {
  margin-bottom: 0;
  word-break: normal;
}

.markdown-body pre {
  word-wrap: normal;
}

.markdown-body pre code {
  display: inline;
  max-width: initial;
  padding: 0;
  margin: 0;
  overflow: initial;
  line-height: inherit;
  word-wrap: normal;
  background-color: transparent;
  border: 0;
}

.markdown-body pre code:before,
.markdown-body pre code:after {
  content: normal;
}

/* Admonition */
.markdown-body .admonition {
  -webkit-border-radius: 3px;
  -moz-border-radius: 3px;
  position: relative;
  border-radius: 3px;
  border: 1px solid #e0e0e0;
  border-left: 6px solid #333;
  padding: 10px 10px 10px 30px;
}

.markdown-body .admonition table {
  color: #333;
}

.markdown-body .admonition p {
  padding: 0;
}

.markdown-body .admonition-title {
  font-weight: bold;
  margin: 0;
}

.markdown-body .admonition>.admonition-title {
  color: #333;
}

.markdown-body .attention>.admonition-title {
  color: #a6d796;
}

.markdown-body .caution>.admonition-title {
  color: #d7a796;
}

.markdown-body .hint>.admonition-title {
  color: #96c6d7;
}

.markdown-body .danger>.admonition-title {
  color: #c25f77;
}

.markdown-body .question>.admonition-title {
  color: #96a6d7;
}

.markdown-body .note>.admonition-title {
  color: #d7c896;
}

.markdown-body .admonition:before,
.markdown-body .attention:before,
.markdown-body .caution:before,
.markdown-body .hint:before,
.markdown-body .danger:before,
.markdown-body .question:before,
.markdown-body .note:before {
  font: normal normal 16px fontawesome-mini;
  -moz-osx-font-smoothing: grayscale;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  line-height: 1.5;
  color: #333;
  position: absolute;
  left: 0;
  top: 0;
  padding-top: 10px;
  padding-left: 10px;
}

.markdown-body .admonition:before {
  content: "\f056\00a0";
  color: 333;
}

.markdown-body .attention:before {
  content: "\f058\00a0";
  color: #a6d796;
}

.markdown-body .caution:before {
  content: "\f06a\00a0";
  color: #d7a796;
}

.markdown-body .hint:before {
  content: "\f05a\00a0";
  color: #96c6d7;
}

.markdown-body .danger:before {
  content: "\f057\00a0";
  color: #c25f77;
}

.markdown-body .question:before {
  content: "\f059\00a0";
  color: #96a6d7;
}

.markdown-body .note:before {
  content: "\f040\00a0";
  color: #d7c896;
}

.markdown-body .admonition::after {
  content: normal;
}

.markdown-body .attention {
  border-left: 6px solid #a6d796;
}

.markdown-body .caution {
  border-left: 6px solid #d7a796;
}

.markdown-body .hint {
  border-left: 6px solid #96c6d7;
}

.markdown-body .danger {
  border-left: 6px solid #c25f77;
}

.markdown-body .question {
  border-left: 6px solid #96a6d7;
}

.markdown-body .note {
  border-left: 6px solid #d7c896;
}

.markdown-body .admonition>*:first-child {
  margin-top: 0 !important;
}

.markdown-body .admonition>*:last-child {
  margin-bottom: 0 !important;
}

/* progress bar*/
.markdown-body .progress {
  display: block;
  width: 300px;
  margin: 10px 0;
  height: 24px;
  -webkit-border-radius: 3px;
  -moz-border-radius: 3px;
  border-radius: 3px;
  background-color: #ededed;
  position: relative;
  box-shadow: inset -1px 1px 3px rgba(0, 0, 0, .1);
}

.markdown-body .progress-label {
  position: absolute;
  text-align: center;
  font-weight: bold;
  width: 100%; margin: 0;
  line-height: 24px;
  color: #333;
  text-shadow: 1px 1px 0 #fefefe, -1px -1px 0 #fefefe, -1px 1px 0 #fefefe, 1px -1px 0 #fefefe, 0 1px 0 #fefefe, 0 -1px 0 #fefefe, 1px 0 0 #fefefe, -1px 0 0 #fefefe, 1px 1px 2px #000;
  -webkit-font-smoothing: antialiased !important;
  white-space: nowrap;
  overflow: hidden;
}

.markdown-body .progress-bar {
  height: 24px;
  float: left;
  -webkit-border-radius: 3px;
  -moz-border-radius: 3px;
  border-radius: 3px;
  background-color: #96c6d7;
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, .5), inset 0 -1px 0 rgba(0, 0, 0, .1);
  background-size: 30px 30px;
  background-image: -webkit-linear-gradient(
    135deg, rgba(255, 255, 255, .4) 27%,
    transparent 27%,
    transparent 52%, rgba(255, 255, 255, .4) 52%,
    rgba(255, 255, 255, .4) 77%,
    transparent 77%, transparent
  );
  background-image: -moz-linear-gradient(
    135deg,
    rgba(255, 255, 255, .4) 27%, transparent 27%,
    transparent 52%, rgba(255, 255, 255, .4) 52%,
    rgba(255, 255, 255, .4) 77%, transparent 77%,
    transparent
  );
  background-image: -ms-linear-gradient(
    135deg,
    rgba(255, 255, 255, .4) 27%, transparent 27%,
    transparent 52%, rgba(255, 255, 255, .4) 52%,
    rgba(255, 255, 255, .4) 77%, transparent 77%,
    transparent
  );
  background-image: -o-linear-gradient(
    135deg,
    rgba(255, 255, 255, .4) 27%, transparent 27%,
    transparent 52%, rgba(255, 255, 255, .4) 52%,
    rgba(255, 255, 255, .4) 77%, transparent 77%,
    transparent
  );
  background-image: linear-gradient(
    135deg,
    rgba(255, 255, 255, .4) 27%, transparent 27%,
    transparent 52%, rgba(255, 255, 255, .4) 52%,
    rgba(255, 255, 255, .4) 77%, transparent 77%,
    transparent
  );
}

.markdown-body .progress-100plus .progress-bar {
  background-color: #a6d796;
}

.markdown-body .progress-80plus .progress-bar {
  background-color: #c6d796;
}

.markdown-body .progress-60plus .progress-bar {
  background-color: #d7c896;
}

.markdown-body .progress-40plus .progress-bar {
  background-color: #d7a796;
}

.markdown-body .progress-20plus .progress-bar {
  background-color: #d796a6;
}

.markdown-body .progress-0plus .progress-bar {
  background-color: #c25f77;
}

.markdown-body .candystripe-animate .progress-bar{
  -webkit-animation: animate-stripes 3s linear infinite;
  -moz-animation: animate-stripes 3s linear infinite;
  animation: animate-stripes 3s linear infinite;
}

@-webkit-keyframes animate-stripes {
  0% {
    background-position: 0 0;
  }

  100% {
    background-position: 60px 0;
  }
}

@-moz-keyframes animate-stripes {
  0% {
    background-position: 0 0;
  }

  100% {
    background-position: 60px 0;
  }
}

@keyframes animate-stripes {
  0% {
    background-position: 0 0;
  }

  100% {
    background-position: 60px 0;
  }
}

.markdown-body .gloss .progress-bar {
  box-shadow:
    inset 0 4px 12px rgba(255, 255, 255, .7),
    inset 0 -12px 0 rgba(0, 0, 0, .05);
}

/* Multimarkdown Critic Blocks */
.markdown-body .critic_mark {
  background: #ff0;
}

.markdown-body .critic_delete {
  color: #c82829;
  text-decoration: line-through;
}

.markdown-body .critic_insert {
  color: #718c00 ;
  text-decoration: underline;
}

.markdown-body .critic_comment {
  color: #8e908c;
  font-style: italic;
}

.markdown-body .headeranchor {
  font: normal normal 16px octicons-anchor;
  line-height: 1;
  display: inline-block;
  text-decoration: none;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.headeranchor:before {
  content: '\f05c';
}

.markdown-body .task-list-item {
  list-style-type: none;
}

.markdown-body .task-list-item+.task-list-item {
  margin-top: 3px;
}

.markdown-body .task-list-item input {
  margin: 0 4px 0.25em -20px;
  vertical-align: middle;
}

/* Media */
@media only screen and (min-width: 480px) {
  .markdown-body {
    font-size:14px;
  }
}

@media only screen and (min-width: 768px) {
  .markdown-body {
    font-size:16px;
  }
}

@media print {
  .markdown-body * {
    background: transparent !important;
    color: black !important;
    filter:none !important;
    -ms-filter: none !important;
  }

  .markdown-body {
    font-size:12pt;
    max-width:100%;
    outline:none;
    border: 0;
  }

  .markdown-body a,
  .markdown-body a:visited {
    text-decoration: underline;
  }

  .markdown-body .headeranchor-link {
    display: none;
  }

  .markdown-body a[href]:after {
    content: " (" attr(href) ")";
  }

  .markdown-body abbr[title]:after {
    content: " (" attr(title) ")";
  }

  .markdown-body .ir a:after,
  .markdown-body a[href^="javascript:"]:after,
  .markdown-body a[href^="#"]:after {
    content: "";
  }

  .markdown-body pre {
    white-space: pre;
    white-space: pre-wrap;
    word-wrap: break-word;
  }

  .markdown-body pre,
  .markdown-body blockquote {
    border: 1px solid #999;
    padding-right: 1em;
    page-break-inside: avoid;
  }

  .markdown-body .progress,
  .markdown-body .progress-bar {
    -moz-box-shadow: none;
    -webkit-box-shadow: none;
    box-shadow: none;
  }

  .markdown-body .progress {
    border: 1px solid #ddd;
  }

  .markdown-body .progress-bar {
    height: 22px;
    border-right: 1px solid #ddd;
  }

  .markdown-body tr,
  .markdown-body img {
    page-break-inside: avoid;
  }

  .markdown-body img {
    max-width: 100% !important;
  }

  .markdown-body p,
  .markdown-body h2,
  .markdown-body h3 {
    orphans: 3;
    widows: 3;
  }

  .markdown-body h2,
  .markdown-body h3 {
    page-break-after: avoid;
  }
}
</style><style>/*github*/
.codehilite {background-color:#fff;color:#333333;}
.codehilite .hll {background-color:#ffffcc;}
.codehilite .c{color:#999988;font-style:italic}
.codehilite .err{color:#a61717;background-color:#e3d2d2}
.codehilite .k{font-weight:bold}
.codehilite .o{font-weight:bold}
.codehilite .cm{color:#999988;font-style:italic}
.codehilite .cp{color:#999999;font-weight:bold}
.codehilite .c1{color:#999988;font-style:italic}
.codehilite .cs{color:#999999;font-weight:bold;font-style:italic}
.codehilite .gd{color:#000000;background-color:#ffdddd}
.codehilite .ge{font-style:italic}
.codehilite .gr{color:#aa0000}
.codehilite .gh{color:#999999}
.codehilite .gi{color:#000000;background-color:#ddffdd}
.codehilite .go{color:#888888}
.codehilite .gp{color:#555555}
.codehilite .gs{font-weight:bold}
.codehilite .gu{color:#800080;font-weight:bold}
.codehilite .gt{color:#aa0000}
.codehilite .kc{font-weight:bold}
.codehilite .kd{font-weight:bold}
.codehilite .kn{font-weight:bold}
.codehilite .kp{font-weight:bold}
.codehilite .kr{font-weight:bold}
.codehilite .kt{color:#445588;font-weight:bold}
.codehilite .m{color:#009999}
.codehilite .s{color:#dd1144}
.codehilite .n{color:#333333}
.codehilite .na{color:teal}
.codehilite .nb{color:#0086b3}
.codehilite .nc{color:#445588;font-weight:bold}
.codehilite .no{color:teal}
.codehilite .ni{color:purple}
.codehilite .ne{color:#990000;font-weight:bold}
.codehilite .nf{color:#990000;font-weight:bold}
.codehilite .nn{color:#555555}
.codehilite .nt{color:navy}
.codehilite .nv{color:teal}
.codehilite .ow{font-weight:bold}
.codehilite .w{color:#bbbbbb}
.codehilite .mf{color:#009999}
.codehilite .mh{color:#009999}
.codehilite .mi{color:#009999}
.codehilite .mo{color:#009999}
.codehilite .sb{color:#dd1144}
.codehilite .sc{color:#dd1144}
.codehilite .sd{color:#dd1144}
.codehilite .s2{color:#dd1144}
.codehilite .se{color:#dd1144}
.codehilite .sh{color:#dd1144}
.codehilite .si{color:#dd1144}
.codehilite .sx{color:#dd1144}
.codehilite .sr{color:#009926}
.codehilite .s1{color:#dd1144}
.codehilite .ss{color:#990073}
.codehilite .bp{color:#999999}
.codehilite .vc{color:teal}
.codehilite .vg{color:teal}
.codehilite .vi{color:teal}
.codehilite .il{color:#009999}
.codehilite .gc{color:#999;background-color:#EAF2F5}
</style><script type="text/javascript" src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"></script>
<script>
MathJax.Hub.Config({
  config: ["MMLorHTML.js"],
  extensions: ["tex2jax.js"],
  jax: ["input/TeX"],
  tex2jax: {
    inlineMath: [ ['$','$'], ["\\(","\\)"] ],
    displayMath: [ ['$$','$$'], ["\\[","\\]"] ],
    processEscapes: false
  },
  TeX: {
    extensions: ["AMSmath.js", "AMSsymbols.js"],
    TagSide: "right",
    TagIndent: ".8em",
    MultLineWidth: "85%",
    equationNumbers: {
      autoNumber: "AMS",
    },
    unicode: {
      fonts: "STIXGeneral,'Arial Unicode MS'"
    }
  },
  showProcessingMessages: false
});
</script>
<title>untitled</title></head><body><article class="markdown-body"><p>MyToolKit</p>
<p>1.本工具包括6个模块：<br />
  easy_search.py,<br />
  my_bing_domains_v1_alone.py,<br />
  my_GoogleScraper_bing_domain.py,<br />
  mysqlmap.py,<br />
  MyToolKit.py,<br />
  mail.py</p>
<p>2.各模块介绍：</p>
<p>1&gt;easy_search.py： <br />
  google关键字搜索相关网页结果，并对结果通过sqlmap注入，类似啊D里的搜索注入功能，但比啊D里强大，因为这里用sqlmap检测注入并注入,其中google搜索的功能采用完全模仿浏览器方式，可得到所有通过浏览器Google搜索的结果，通过GoogleScraper模块实现，其中GoogleScraper 利用Selenium模块模拟浏览器人工访问功能。</p>
<p>2&gt;my_bing_domains_v1_alone.py：<br />
  通过bing的api接口原理实现，需要注册bing的api_key，每个月免费5000次。</p>
<p>3&gt;my_GoogleScraper_bing_domain.py:<br />
  通过GoogleScraper的浏览器模拟人工访问bing，关键字ip：111.111.111.111,获取所有结果,当只有一页结果 时，GoogleScraper不能得到该查询结果，调用上面的<br />
  my_bing_domains_v1_alone.py模块继续查询。</p>
<p>4&gt;mysqlmap.py：<br />
  sqlmap自动化sqli模块，详情见代码。</p>
<p>5&gt;MyToolKit.py：<br />
  综合入口模块，选择不同需求，实现不同功能。共包括8个功能，分别为：<br />
  &ndash;exp:<br />
   批量使用exp功能 <br />
  &ndash;mygoogle <br />
            &ndash;sqlmap-crawl：<br />
              使用my_GoogleScraper_bing_domain.py模块和sqlmap的crawl<br />
              功能实现批量自动化sqli。<br />
            &ndash;sqlmap-g-nohuman：<br />
              使用my_GoogleScraper_bing_domain.py模块和sqlmap的-g选项功能实现<br />
              批量自动化sqli。<br />
            &ndash;sqlmap-g-human：<br />
              使用my_GoogleScraper_bing_domain.py模块和可绕过验证码的GoogleScraper，人工输入验 证码，获取所有url,用sqlmap的-m选项功能实现批量自动化sqli。<br />
  &ndash;mybing<br />
            &ndash;sqlmap-crawl：<br />
              使用my_bing_domains_v1_alone.py模块和sqlmap的crawl功能实现批量 自动化sqli。<br />
            &ndash;sqlmap-g-nohuman：<br />
              使用my_bing_domains_v1_alone.py模块和sqlmap的-g选项功能实现批量 自动化sqli。<br />
            &ndash;sqlmap-g-human：<br />
              使用my_bing_domains_v1_alone.py模块 和可绕过验证码的 GoogleScraper,人工输入验证码，获取所有url,用sqlmap的-m选项功能实现批量自动化sqli.<br />
  &ndash;easy_search：<br />
    相当于&ndash;mygoogle下的&ndash;sqlmap-g-uman功能的子功能， 但灵活性更强， 可任意关键 字google搜索并利用sqlmap注入。 最常用功能应该是&ndash;mygoogle下的&ndash;sqlmap-g-human 及&ndash;easy_search这两个。<br />
6&gt;mail.py:<br />
  自动发送邮件，内嵌在MytoolKit.py中.</p>
<p>3.环境要求： <br />
  安装GoogleScraper（python3下），并修改部分GoogleScraper中第三方模块selenium中代码(绕过验证码)可参考以前一篇写的关于google search api for python的文章。 90sec链接：<a href="https://forum.90sec.org/forum.php?mod=viewthread&amp;tid=9024">https://forum.90sec.org/forum.php?mod=viewthread&amp;tid=9024</a> 百度网盘链接：<a href="http://pan.baidu.com/s/1kUklzZD">http://pan.baidu.com/s/1kUklzZD</a> 密码: 4cpn</p>
<p>2016.1.26部分代码更新</p>
<p>2016.1.28部分代码更新<br />
1.添加tor匿名功能，可自由选择tor或不用tor</p>
<p>2016.1.28部分代码更新，增加功能：<br />
1.绕过“多次错误访问后屏蔽所有请求”<br />
2.请求延时<br />
3.尝试绕过waf<br />
4.支持post注入</p>
<p>2016.1.29部分代码更新，增加功能：<br />
1.定位旁站的sqli所在主站<br />
2.发送邮件通知功能，将可用sqli的url发送邮件通知（smtp用163）</p>
<p>2016.3.2部分代码更新：<br />
1.easy_search.py line:116 添加自动结束冗余firefox进程功能 <br />
2.修改mysqlmap.py中line:131-161的逻辑错误 <br />
3.修改其它py中fp=open()以后没有fp.close()的错误 <br />
4.修改MyToolKit.py中对easy_search.py调用的逻辑错误 <br />
5.关键字由php|asp变成php|asp|aspx|jsp <br />
6.修改my_bing_domains_v1_alone.py中get_the_one_targe_domains函数使用遇到不工作的<br />
  域名解析异常使全局出错的错误 line:21-22 <br />
7.自动处理output目录移动，使得运行前不必清空output目录<br />
8.修改my_bing_domains_v1_alone.py中get_the_one_targe_domains函数</p></article></body></html>
