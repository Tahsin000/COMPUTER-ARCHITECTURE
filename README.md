<html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8"/><title>Computer Architecture</title><style>
/* cspell:disable-file */
/* webkit printing magic: print all background colors */
html {
	-webkit-print-color-adjust: exact;
}
* {
	box-sizing: border-box;
	-webkit-print-color-adjust: exact;
}

html,
body {
	margin: 0;
	padding: 0;
}
@media only screen {
	body {
		margin: 2em auto;
		max-width: 900px;
		color: rgb(55, 53, 47);
	}
}

body {
	line-height: 1.5;
	white-space: pre-wrap;
}

a,
a.visited {
	color: inherit;
	text-decoration: underline;
}

.pdf-relative-link-path {
	font-size: 80%;
	color: #444;
}

h1,
h2,
h3 {
	letter-spacing: -0.01em;
	line-height: 1.2;
	font-weight: 600;
	margin-bottom: 0;
}

.page-title {
	font-size: 2.5rem;
	font-weight: 700;
	margin-top: 0;
	margin-bottom: 0.75em;
}

h1 {
	font-size: 1.875rem;
	margin-top: 1.875rem;
}

h2 {
	font-size: 1.5rem;
	margin-top: 1.5rem;
}

h3 {
	font-size: 1.25rem;
	margin-top: 1.25rem;
}

.source {
	border: 1px solid #ddd;
	border-radius: 3px;
	padding: 1.5em;
	word-break: break-all;
}

.callout {
	border-radius: 3px;
	padding: 1rem;
}

figure {
	margin: 1.25em 0;
	page-break-inside: avoid;
}

figcaption {
	opacity: 0.5;
	font-size: 85%;
	margin-top: 0.5em;
}

mark {
	background-color: transparent;
}

.indented {
	padding-left: 1.5em;
}

hr {
	background: transparent;
	display: block;
	width: 100%;
	height: 1px;
	visibility: visible;
	border: none;
	border-bottom: 1px solid rgba(55, 53, 47, 0.09);
}

img {
	max-width: 100%;
}

@media only print {
	img {
		max-height: 100vh;
		object-fit: contain;
	}
}

@page {
	margin: 1in;
}

.collection-content {
	font-size: 0.875rem;
}

.column-list {
	display: flex;
	justify-content: space-between;
}

.column {
	padding: 0 1em;
}

.column:first-child {
	padding-left: 0;
}

.column:last-child {
	padding-right: 0;
}

.table_of_contents-item {
	display: block;
	font-size: 0.875rem;
	line-height: 1.3;
	padding: 0.125rem;
}

.table_of_contents-indent-1 {
	margin-left: 1.5rem;
}

.table_of_contents-indent-2 {
	margin-left: 3rem;
}

.table_of_contents-indent-3 {
	margin-left: 4.5rem;
}

.table_of_contents-link {
	text-decoration: none;
	opacity: 0.7;
	border-bottom: 1px solid rgba(55, 53, 47, 0.18);
}

table,
th,
td {
	border: 1px solid rgba(55, 53, 47, 0.09);
	border-collapse: collapse;
}

table {
	border-left: none;
	border-right: none;
}

th,
td {
	font-weight: normal;
	padding: 0.25em 0.5em;
	line-height: 1.5;
	min-height: 1.5em;
	text-align: left;
}

th {
	color: rgba(55, 53, 47, 0.6);
}

ol,
ul {
	margin: 0;
	margin-block-start: 0.6em;
	margin-block-end: 0.6em;
}

li > ol:first-child,
li > ul:first-child {
	margin-block-start: 0.6em;
}

ul > li {
	list-style: disc;
}

ul.to-do-list {
	text-indent: -1.7em;
}

ul.to-do-list > li {
	list-style: none;
}

.to-do-children-checked {
	text-decoration: line-through;
	opacity: 0.375;
}

ul.toggle > li {
	list-style: none;
}

ul {
	padding-inline-start: 1.7em;
}

ul > li {
	padding-left: 0.1em;
}

ol {
	padding-inline-start: 1.6em;
}

ol > li {
	padding-left: 0.2em;
}

.mono ol {
	padding-inline-start: 2em;
}

.mono ol > li {
	text-indent: -0.4em;
}

.toggle {
	padding-inline-start: 0em;
	list-style-type: none;
}

/* Indent toggle children */
.toggle > li > details {
	padding-left: 1.7em;
}

.toggle > li > details > summary {
	margin-left: -1.1em;
}

.selected-value {
	display: inline-block;
	padding: 0 0.5em;
	background: rgba(206, 205, 202, 0.5);
	border-radius: 3px;
	margin-right: 0.5em;
	margin-top: 0.3em;
	margin-bottom: 0.3em;
	white-space: nowrap;
}

.collection-title {
	display: inline-block;
	margin-right: 1em;
}

.simple-table {
	margin-top: 1em;
	font-size: 0.875rem;
	empty-cells: show;
}
.simple-table td {
	height: 29px;
	min-width: 120px;
}

.simple-table th {
	height: 29px;
	min-width: 120px;
}

.simple-table-header-color {
	background: rgb(247, 246, 243);
	color: black;
}
.simple-table-header {
	font-weight: 500;
}

time {
	opacity: 0.5;
}

.icon {
	display: inline-block;
	max-width: 1.2em;
	max-height: 1.2em;
	text-decoration: none;
	vertical-align: text-bottom;
	margin-right: 0.5em;
}

img.icon {
	border-radius: 3px;
}

.user-icon {
	width: 1.5em;
	height: 1.5em;
	border-radius: 100%;
	margin-right: 0.5rem;
}

.user-icon-inner {
	font-size: 0.8em;
}

.text-icon {
	border: 1px solid #000;
	text-align: center;
}

.page-cover-image {
	display: block;
	object-fit: cover;
	width: 100%;
	max-height: 30vh;
}

.page-header-icon {
	font-size: 3rem;
	margin-bottom: 1rem;
}

.page-header-icon-with-cover {
	margin-top: -0.72em;
	margin-left: 0.07em;
}

.page-header-icon img {
	border-radius: 3px;
}

.link-to-page {
	margin: 1em 0;
	padding: 0;
	border: none;
	font-weight: 500;
}

p > .user {
	opacity: 0.5;
}

td > .user,
td > time {
	white-space: nowrap;
}

input[type="checkbox"] {
	transform: scale(1.5);
	margin-right: 0.6em;
	vertical-align: middle;
}

p {
	margin-top: 0.5em;
	margin-bottom: 0.5em;
}

.image {
	border: none;
	margin: 1.5em 0;
	padding: 0;
	border-radius: 0;
	text-align: center;
}

.code,
code {
	background: rgba(135, 131, 120, 0.15);
	border-radius: 3px;
	padding: 0.2em 0.4em;
	border-radius: 3px;
	font-size: 85%;
	tab-size: 2;
}

code {
	color: #eb5757;
}

.code {
	padding: 1.5em 1em;
}

.code-wrap {
	white-space: pre-wrap;
	word-break: break-all;
}

.code > code {
	background: none;
	padding: 0;
	font-size: 100%;
	color: inherit;
}

blockquote {
	font-size: 1.25em;
	margin: 1em 0;
	padding-left: 1em;
	border-left: 3px solid rgb(55, 53, 47);
}

.bookmark {
	text-decoration: none;
	max-height: 8em;
	padding: 0;
	display: flex;
	width: 100%;
	align-items: stretch;
}

.bookmark-title {
	font-size: 0.85em;
	overflow: hidden;
	text-overflow: ellipsis;
	height: 1.75em;
	white-space: nowrap;
}

.bookmark-text {
	display: flex;
	flex-direction: column;
}

.bookmark-info {
	flex: 4 1 180px;
	padding: 12px 14px 14px;
	display: flex;
	flex-direction: column;
	justify-content: space-between;
}

.bookmark-image {
	width: 33%;
	flex: 1 1 180px;
	display: block;
	position: relative;
	object-fit: cover;
	border-radius: 1px;
}

.bookmark-description {
	color: rgba(55, 53, 47, 0.6);
	font-size: 0.75em;
	overflow: hidden;
	max-height: 4.5em;
	word-break: break-word;
}

.bookmark-href {
	font-size: 0.75em;
	margin-top: 0.25em;
}

.sans { font-family: ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol"; }
.code { font-family: "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace; }
.serif { font-family: Lyon-Text, Georgia, ui-serif, serif; }
.mono { font-family: iawriter-mono, Nitti, Menlo, Courier, monospace; }
.pdf .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK JP'; }
.pdf:lang(zh-CN) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC'; }
.pdf:lang(zh-TW) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK TC'; }
.pdf:lang(ko-KR) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK KR'; }
.pdf .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.pdf .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK JP'; }
.pdf:lang(zh-CN) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK SC'; }
.pdf:lang(zh-TW) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK TC'; }
.pdf:lang(ko-KR) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK KR'; }
.pdf .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.highlight-default {
	color: rgba(55, 53, 47, 1);
}
.highlight-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.highlight-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.highlight-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.highlight-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.highlight-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.highlight-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.highlight-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.highlight-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.highlight-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.highlight-gray_background {
	background: rgba(241, 241, 239, 1);
}
.highlight-brown_background {
	background: rgba(244, 238, 238, 1);
}
.highlight-orange_background {
	background: rgba(251, 236, 221, 1);
}
.highlight-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.highlight-teal_background {
	background: rgba(237, 243, 236, 1);
}
.highlight-blue_background {
	background: rgba(231, 243, 248, 1);
}
.highlight-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.highlight-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.highlight-red_background {
	background: rgba(253, 235, 236, 1);
}
.block-color-default {
	color: inherit;
	fill: inherit;
}
.block-color-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.block-color-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.block-color-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.block-color-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.block-color-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.block-color-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.block-color-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.block-color-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.block-color-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.block-color-gray_background {
	background: rgba(241, 241, 239, 1);
}
.block-color-brown_background {
	background: rgba(244, 238, 238, 1);
}
.block-color-orange_background {
	background: rgba(251, 236, 221, 1);
}
.block-color-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.block-color-teal_background {
	background: rgba(237, 243, 236, 1);
}
.block-color-blue_background {
	background: rgba(231, 243, 248, 1);
}
.block-color-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.block-color-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.block-color-red_background {
	background: rgba(253, 235, 236, 1);
}
.select-value-color-pink { background-color: rgba(245, 224, 233, 1); }
.select-value-color-purple { background-color: rgba(232, 222, 238, 1); }
.select-value-color-green { background-color: rgba(219, 237, 219, 1); }
.select-value-color-gray { background-color: rgba(227, 226, 224, 1); }
.select-value-color-opaquegray { background-color: rgba(255, 255, 255, 0.0375); }
.select-value-color-orange { background-color: rgba(250, 222, 201, 1); }
.select-value-color-brown { background-color: rgba(238, 224, 218, 1); }
.select-value-color-red { background-color: rgba(255, 226, 221, 1); }
.select-value-color-yellow { background-color: rgba(253, 236, 200, 1); }
.select-value-color-blue { background-color: rgba(211, 229, 239, 1); }

.checkbox {
	display: inline-flex;
	vertical-align: text-bottom;
	width: 16;
	height: 16;
	background-size: 16px;
	margin-left: 2px;
	margin-right: 5px;
}

.checkbox-on {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20width%3D%2216%22%20height%3D%2216%22%20fill%3D%22%2358A9D7%22%2F%3E%0A%3Cpath%20d%3D%22M6.71429%2012.2852L14%204.9995L12.7143%203.71436L6.71429%209.71378L3.28571%206.2831L2%207.57092L6.71429%2012.2852Z%22%20fill%3D%22white%22%2F%3E%0A%3C%2Fsvg%3E");
}

.checkbox-off {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20x%3D%220.75%22%20y%3D%220.75%22%20width%3D%2214.5%22%20height%3D%2214.5%22%20fill%3D%22white%22%20stroke%3D%22%2336352F%22%20stroke-width%3D%221.5%22%2F%3E%0A%3C%2Fsvg%3E");
}
	
</style></head><body><article id="b94f6a8b-07bd-4869-aff9-bb786882478f" class="page sans"><header><img class="page-cover-image" src="https://www.cs.virginia.edu/venkat/img/6354.jpg" style="object-position:center 50%"/><div class="page-header-icon page-header-icon-with-cover"><span class="icon">🖥️</span></div><h1 class="page-title">Computer Architecture</h1></header><div class="page-body"><p id="5c211ae3-0d10-4c5b-882e-0f91ca7bbdc2" class="">
</p><h3 id="b4593848-926b-45ac-8acb-9ec92ee00aa4" class=""><mark class="highlight-orange">What is bits-slice microprocessor and four bits-slice Microprocessor</mark></h3><p id="911c1f62-b6f6-475b-9117-61bbcf647dab" class="">Ans: A bit slice processor in computer architecture is constructed from processor modules of smaller bit width.</p><p id="3690d769-5f42-4b1f-b880-7b4189d1c31a" class="">A 4-bit bit slice processor includes a <mark class="highlight-orange">register file</mark> and an <mark class="highlight-orange">ALU(arithmetic logic unit)</mark> to perform operations on<mark class="highlight-orange"> 4-bit data</mark>, so that four such chips can be combined to build a 16-bit processor unit.</p><p id="eda4b559-c189-4273-9caf-b7aa41a8db31" class="">…………………………………………………………..</p><h3 id="b5194eb4-1703-42ef-99d8-10ed45141c4e" class=""><mark class="highlight-orange">Different types of interrupt, They are:</mark></h3><h3 id="061ba323-257c-4224-9a18-04617362a4f2" class="">H</h3><p id="5f4a06cf-4593-4c4f-b3b9-118bb531307c" class="">Hardware interrupts are classified into two types which are as follows −</p><ul id="652b2b1a-f2e4-4211-88f1-fd3fa3cdd316" class="bulleted-list"><li style="list-style-type:disc"><strong>Maskable Interrupt</strong> − The hardware interrupts that can be delayed when a highest priority interrupt has occurred to the processor.</li></ul><ul id="ecc1195f-0f9d-410d-844e-5835f93865f6" class="bulleted-list"><li style="list-style-type:disc"><strong>Non Maskable Interrupt</strong> − The hardware that cannot be delayed and immediately be serviced by the processor.</li></ul><h3 id="3857635e-4ea3-4d74-8876-381de9db6ccc" class=""><mark class="highlight-orange">2. Software interrupts</mark></h3><p id="c303f4c3-ff0b-4bf6-92b1-f701c2b032f7" class="">The interrupt signal generated from internal devices and software programs need to access any system call then software interrupts are present.</p><p id="2915d50b-fa13-41e4-8a31-398d3054e434" class="">Software interrupt is divided into two types. They are as follows −</p><ul id="82c510cc-09a1-44b9-b3bd-63637eb35eaf" class="bulleted-list"><li style="list-style-type:disc"><strong>Normal Interrupts</strong> − The interrupts that are caused by the software instructions are called Normal interrupt.</li></ul><ul id="8638c1c3-217f-4476-b0b2-cfc4e33ba70a" class="bulleted-list"><li style="list-style-type:disc"><strong>Exception</strong> − Exception is nothing but an unplanned interruption while executing a program. For example − while executing a program if we got a value that is divided by zero is called an exception.</li></ul><p id="5c1d6b44-a4eb-4d15-8a14-a4b73cc2b551" class="">…………………………………………………………..</p><h3 id="6ed31a48-c2d0-4600-8980-7ebc6252921f" class="block-color-yellow"><mark class="highlight-orange">Difference between Synchronous and Asynchronous Transmission:</mark></h3><table id="7dd935ac-301c-4c6a-b484-c77df010369a" class="simple-table"><tbody><tr id="9f38cf30-1206-4978-a3e9-516506e50cef"><td id="wZBO" class="">Synchronous Transmission</td><td id="v_Lv" class="">Asynchronous Transmission</td></tr><tr id="e9a9ac25-6656-42bb-87ba-d1d273c45daf"><td id="wZBO" class="">In Synchronous transmission, Data is sent in form of blocks or frames.</td><td id="v_Lv" class="">In asynchronous transmission, Data is sent in form of byte or character.</td></tr><tr id="2802c752-32ef-4f76-98a1-ea66a7cc04f6"><td id="wZBO" class="">Synchronous transmission is fast.</td><td id="v_Lv" class="">Asynchronous transmission is slow.</td></tr><tr id="2a54cc5b-2d9e-4035-a441-53b38017ba03"><td id="wZBO" class="">In Synchronous transmission, time interval of transmission is constant.</td><td id="v_Lv" class="">In asynchronous transmission, time interval of transmission is not constant, it is random.</td></tr><tr id="3ddebe3b-2c8d-4c1f-8d41-a5f64a3f5bdc"><td id="wZBO" class="">In Synchronous transmission, There is no gap present between data.</td><td id="v_Lv" class="">In asynchronous transmission, There is present gap between data.</td></tr><tr id="96bc264b-1735-4228-beca-16926b24472b"><td id="wZBO" class="">Efficient use of transmission line is done in synchronous transmission.</td><td id="v_Lv" class="">While in asynchronous transmission, transmission line remains empty during gap in character transmission.</td></tr><tr id="b308fc49-6806-4585-86b0-3d6caefc20cb"><td id="wZBO" class="">Synchronous transmission needs precisely synchronized clocks for the information of new bytes.</td><td id="v_Lv" class="">Asynchronous transmission have no need of synchronized clocks as parity bit is used in this transmission for information of new bytes.</td></tr></tbody></table><p id="6c47563d-9b0d-430d-8b26-a475505238c3" class="">…………………………………………………………..</p><h3 id="ea6923bb-ec3a-4fbf-9543-779d07c49c7c" class="block-color-yellow">Direct mapping:</h3><p id="0974269f-e318-4753-a4b5-be88cda923e6" class="">Direct mapping is <strong>a procedure used to assign each memory block in the main memory to a particular line in the cache</strong></p><h3 id="cf133d97-316e-4598-bc3d-964322eda87e" class=""><mark class="highlight-orange">Set associative mapping:</mark></h3><p id="59424e8e-16e4-4fe2-8450-1f306e4307b5" class="">Set associative mapping is <strong>a cache mapping </strong><mark class="highlight-red"><strong>technique </strong></mark><strong>that allows to map a block of main memory to only one particular set of cache.</strong></p><h3 id="d351bbc6-98a5-416f-ad31-d2291872f5f5" class=""><mark class="highlight-orange">Associative memory:  </mark></h3><p id="fab517d9-30ac-4a86-9c5a-1283ecddc624" class="">associative memory is used to store <mark class="highlight-orange">content</mark> and <mark class="highlight-orange">addresses </mark>of the memory word. </p><p id="b2a9c011-a7ed-4072-8411-924c80705446" class="">…………………………………………………………..</p><h3 id="1fff4af8-04d5-4307-97bb-89d9c69f3877" class=""><mark class="highlight-orange">Source initiated strobe method</mark></h3><p id="586c9434-492a-44c5-b77a-bba4e1eff6ca" class="">When source initiates the process of data transfer. Strobe is just a signal.</p><p id="3f9990ee-0da5-4a51-bf9c-45f482f9df7c" class="">In the below block diagram, you can see that strobe is initiated by source.</p><figure id="8e40569c-fccd-4d4d-9df1-46750ebc5906" class="image"><a href="Computer%20Architecture%208e40569cfccd4d4d9df146750ebc5906/Untitled.png"><img style="width:539px" src="Computer%20Architecture%208e40569cfccd4d4d9df146750ebc5906/Untitled.png"/></a></figure><p id="29b5c04f-006c-4519-98e8-1fea48db585e" class="">…………………………………………………………..</p><h3 id="b01f14ed-521d-41c4-b441-d0e282443a05" class=""><mark class="highlight-orange">What is big-endian and little-endian organization of data in memory?</mark></h3><p id="ee5df157-9ea0-4e82-bcb2-45605222541a" class="">Endianness is a term that <mark class="highlight-red">describes</mark> the order in which a sequence of bytes is stored in computer memory. Endianness can be either big or small, with the adjectives referring to which value is stored first.
Big-endian is an order in which the &quot;big end&quot; (most significant value in the sequence) is stored first, at the lowest storage address. Little-endian is an order in which the &quot;little end&quot; (least significant value in the sequence) is stored first.</p><p id="b1b2204d-ce5d-445a-9637-5a0ba9d7b6b3" class="">…………………………………………………………..</p><h3 id="fabf8025-aa9f-4cf9-8268-cb077b7d6fba" class=""><mark class="highlight-orange">Characteristic of CISC –(Complex instruction set computer)</mark></h3><ol type="1" id="2daa840c-8b68-4c11-b3c8-eefa29d354b5" class="numbered-list" start="1"><li>Large number of instruction and Complex instruction.</li></ol><ol type="1" id="4522699c-dcc1-4f4a-9f7e-76cf75b559b5" class="numbered-list" start="2"><li>Complex Addressing Modes.</li></ol><ol type="1" id="c6d37b16-0fe6-444d-b7e4-0dee80ee671d" class="numbered-list" start="3"><li>Variable length instruction format</li></ol><ol type="1" id="1b12699e-bb1c-4cfa-8d51-aab900eaf5aa" class="numbered-list" start="4"><li>More Data types.</li></ol><ol type="1" id="d91d4330-c2e3-42bb-9259-a0051162a35f" class="numbered-list" start="5"><li>Most powerful</li></ol><ol type="1" id="03f9c945-7e9d-48d9-8359-12e745f98dad" class="numbered-list" start="6"><li>Higher cost</li></ol><ol type="1" id="d6d178ec-dc6c-4219-8630-22bbaa2df3ab" class="numbered-list" start="7"><li>Instruction may take more than a single clock cycle to get executed.
</li></ol><h3 id="1d0aa849-361a-4f05-a608-1e224de68a45" class=""><mark class="highlight-orange">Characteristic of RISC –(Reduce instruction set computer)</mark></h3><ol type="1" id="d7196e50-a9cc-4beb-8dac-d0d7b631e7e6" class="numbered-list" start="1"><li>Less number of instruction and Simpler instruction.</li></ol><ol type="1" id="dae56d9b-dfeb-4e87-a220-491d097c639f" class="numbered-list" start="2"><li>Simple Addressing Modes.</li></ol><ol type="1" id="3acf4de4-b8ef-48f4-a205-dc345926f601" class="numbered-list" start="3"><li>Fixed length instruction format</li></ol><ol type="1" id="c2b176fa-a7ae-4972-8196-985e401eae8c" class="numbered-list" start="4"><li>Fewer Data types.</li></ol><ol type="1" id="be388e08-618b-421d-9368-25bc7cc9fd2f" class="numbered-list" start="5"><li>Less powerful</li></ol><ol type="1" id="53632867-34fa-483d-9f08-c34ba8c3c972" class="numbered-list" start="6"><li>Lower cost</li></ol><ol type="1" id="36f4a444-b040-47f1-88f8-b2b0112966f6" class="numbered-list" start="7"><li>Instruction takes a single clock cycle to get executed.</li></ol><ol type="1" id="4a959644-8006-4ba4-9e0c-048d17cc9454" class="numbered-list" start="8"><li>More general-purpose registers.</li></ol><ol type="1" id="573cba94-0ccf-4b85-869e-8f69fa304e45" class="numbered-list" start="9"><li>A pipeline can be achieved.</li></ol><p id="b155787a-6975-485a-afc5-9da5d3789df4" class="">…………………………………………………………..</p><h3 id="94e346cf-743c-47e6-89bd-ecc8207cc345" class=""><mark class="highlight-orange">what is Amdahl’s Law :</mark></h3><p id="62d6289b-4abf-4e27-ba20-f95a042dd7ce" class="">It is used to find the maximum/overall improvement possible by improving a particular part of system.</p><p id="61ade8d6-ef16-4ed7-9b31-2d50e3b2766b" class="">The executions time of a program after making the improvement is given by the following simple equation known as Amdahl’s Law: </p><p id="5e60e5ae-b3f4-45b9-866a-99b58acf9927" class=""><code>Execution time after improvement = (Execution time affected by improvement/Amount of improvement) + (Execution time unaffected)</code></p><figure id="6aa332a4-c236-4218-95d3-35dfcac7ddf0" class="image"><a href="Computer%20Architecture%208e40569cfccd4d4d9df146750ebc5906/Untitled%201.png"><img style="width:932px" src="Computer%20Architecture%208e40569cfccd4d4d9df146750ebc5906/Untitled%201.png"/></a></figure><p id="33b6ac47-a3c9-4c7c-a04b-fffb5ec94632" class="">…………………………………………………………..</p><h3 id="32308876-93d1-449d-abaf-d7aecf53ad8c" class=""><strong><strong>What is Memory Hierarchy ?</strong></strong></h3><p id="d1740ea9-6c3f-4aa6-adcd-0262b02fa20d" class="">The memory in a computer can be divided into <mark class="highlight-orange">five hierarchies</mark> based on the <mark class="highlight-orange">speed </mark>as well as <mark class="highlight-orange">use</mark>. The processor can move from one level to another based on its requirements. The <mark class="highlight-orange">five hierarchies</mark> in the memory are <mark class="highlight-orange">registers, cache, main memory, magnetic discs, and magnetic tapes</mark>. The first <mark class="highlight-orange">three hierarchies are volatile memories</mark> which mean when there is <mark class="highlight-orange">no power</mark>, and then automatically they lose their stored data. Whereas the last two hierarchies are <mark class="highlight-orange">not volatile</mark> which means they store the data permanently.</p><p id="708dc138-75c8-4482-846c-7766e7e24b11" class="">…………………………………………………………..</p><h3 id="de9afadd-be25-4dbf-bdc2-1d83777449be" class=""><mark class="highlight-orange">Clocking methodology</mark></h3><p id="c8b378dc-22d7-4b4f-8e67-ff349f7ff0d2" class="">Clock methodology defines the timing when data(signal) is being read and write. Combinational logic transforms data during the clock cycle Input from state element output to state element. A clocking methodology is designed to make hardware predictable.</p><p id="f8eaa87c-bde4-4795-8763-7668921ac49d" class="">
</p><h3 id="90db0a69-df45-4853-b3b1-af36ae3b761e" class=""><strong><mark class="highlight-orange">MAR:(Memory address register)</mark></strong></h3><p id="e314c0c2-4e18-460d-9985-4adf7f4ddd8a" class="">MAR are used to handle the data transfer between the main memory and the processor. The MAR holds the address of the main memory to or from which data is to be transferred.</p><p id="1dee16f9-d282-428c-9b9e-be59412eef0f" class="">
</p><h3 id="dc52e09f-0ed4-4c50-bc02-7810ebbb62ae" class=""><mark class="highlight-orange"><strong>MDR:(Memory data register)</strong></mark></h3><p id="24c3e119-8c55-433a-b199-4995b76fcb43" class="">MDR are used to handle the data transfer between the main memory and the processor. The MDR contains the data to be written into or read from the addressed word of the main memory.</p><p id="8103ce77-33a0-4df0-afa1-53bef6df37ba" class="">
</p><h3 id="26fb0362-58dd-42cf-baa5-fb3c51c8d8ee" class=""><mark class="highlight-orange"><strong>PC(Program Cointer):</strong></mark></h3><p id="5f40729e-03b3-44a2-8a54-c05f5e524f00" class="">The Program Counter is one of the most important registers in the CPU. A program is a series of instructions stored in the memory. These instructions tell the CPU exactly how to get the desired result. It is important that these instructions must be executed in a proper order to get the correct result. This sequence of instruction execution is monitored by the program counter. It keeps track of which instruction is being executed and what the next instruction will be.</p><h3 id="156b06f6-4413-46d6-82ae-7538fb723f33" class=""><mark class="highlight-orange">Accumulator:</mark></h3><p id="349520a9-8b81-41fa-bf37-b2f1be99cbd3" class="">An accumulator is <strong>a type of register included in a CPU</strong>. It acts as a temporary storage location which holds an intermediate value in mathematical and logical calculations. Intermediate results of an operation are progressively written to the accumulator, overwriting the previous value.</p><p id="29da83a4-e143-49c3-bd1b-725a3e5452df" class="">…………………………………………………………..</p><h3 id="8d435a23-9e40-435f-9bf3-b608ae7f57c3" class=""><mark class="highlight-orange">Microcode: </mark></h3><p id="5c6a3c5c-1549-4fd4-8200-e603b3acd672" class="">Microprogram form the code which in turn consist of series of microinstruction</p><ul id="4d99a294-a1ae-41c0-89ff-67ac5778061e" class="bulleted-list"><li style="list-style-type:disc">it runs on the microcontroller</li></ul><ul id="8904db12-6c21-4e1d-b63c-69e22859d128" class="bulleted-list"><li style="list-style-type:disc">it is not visible to a programmer</li></ul><p id="2051503b-c9c8-4dcf-82af-0a89636436eb" class="">…………………………………………………………..</p><h3 id="56b4114a-2b72-4d2b-b058-bad9a9725868" class=""><mark class="highlight-orange">Microinstruction:</mark></h3><p id="5fa34182-d40b-4dce-8412-1d694862de7b" class="">It is a low-level instructions used to implement complex machine instructions(macroinstruction)</p><p id="d897e1c3-e3a1-42c0-b595-b3051e810ac5" class="">…………………………………………………………..</p><h3 id="20745b43-b12c-4eaa-884e-3d08935ce7d7" class=""><mark class="highlight-orange"><strong>Micro Coded Instructions</strong></mark></h3><p id="93a0cb4a-eacf-4429-9d78-7bd44eb6b08f" class="">Microcode: -Micro programs form the code which in turn consist of series of microinstructions.</p><ul id="aa188a1d-abe7-41d2-b491-cd5503da2b2c" class="bulleted-list"><li style="list-style-type:disc">It runs on the microcontroller.</li></ul><ul id="3ec2ec09-561f-4b83-bd8f-81a17124bc04" class="bulleted-list"><li style="list-style-type:disc">It is not visible to a programmer</li></ul><p id="ee8623b8-cb35-480d-aa02-7304512b8cbb" class="">…………………………………………………………..</p><h3 id="cc16e034-94ce-48cf-a7cc-9ecb881577bf" class=""><mark class="highlight-orange"><strong>Micro-instructions:</strong></mark></h3><p id="f301ae0f-7b68-4d0b-95f2-c37b0abdb5f3" class="">low-level instructions used to implement <mark class="highlight-orange"><strong>complex machine instructions</strong></mark> (macro instructions)</p><p id="c1d024fa-f0d0-440f-9c0f-a2aebf2d5fa3" class="">…………………………………………………………..</p><h3 id="7d3f7634-2114-4f2f-8b69-45a7e6aa57b8" class="">Macro instructions:</h3><p id="9e2033db-433b-4294-875a-9ca31703366b" class="">Implemented as microcode subroutines </p><ul id="03dea247-32df-4b7b-bb67-b20ad0498c1b" class="bulleted-list"><li style="list-style-type:disc">Can be entirely different than micro instructions</li></ul><p id="6180d1ed-f125-42f4-92f4-d40ec8749422" class="">…………………………………………………………..</p><h3 id="d5fee8ad-7a19-4ba8-a444-f27904971b91" class=""><mark class="highlight-orange">Von Neumann architecture</mark></h3><p id="46a9dd5c-974b-42ae-b172-e5c9920465a5" class="">Von Neumann architecture is the design upon which many general purpose computers are based
. The <mark class="highlight-orange">key elements</mark> of von Neumann architecture are: <mark class="highlight-orange">data </mark>and <mark class="highlight-orange">instructions</mark> are both stored as <mark class="highlight-orange">binary digits</mark>. Data and instructions are both stored in <mark class="highlight-orange">primary storage</mark>.</p><p id="f4d18de6-c6fe-4f8f-bd54-804054ce0b53" class="">…………………………………………………………..</p><h3 id="d2142429-8da0-4deb-941e-91683622e216" class=""><mark class="highlight-orange">Data path:</mark></h3><p id="f71a9cd3-4cd2-4f6f-b286-e28bb03d2bcc" class="">A data path (also written as datapath) is a set of functional units that <mark class="highlight-orange"><strong>conduct data</strong></mark> processing operations. Data paths, with a control unit, make up the CPU (central processing unit) of a computer system.</p><p id="54ca8a8c-03e7-4e0e-ae12-108b9429c027" class="">…………………………………………………………..</p><h3 id="d6175375-69f8-434f-acf6-2f01a3ffd20a" class=""><mark class="highlight-orange"><strong>Bus structure in Computer Organization</strong></mark></h3><p id="2aa4891f-4012-4aea-9bcd-bde2c3c96eef" class="">A Bus is a collection of wires that connects several devices. Types of Bus structure:</p><ol type="1" id="4a085bd3-d9e2-4add-aa61-b2d879f5afd9" class="numbered-list" start="1"><li>Address bus</li></ol><ol type="1" id="c0aa56fa-a937-4933-b9f1-f6e909265bd5" class="numbered-list" start="2"><li>Data bus</li></ol><ol type="1" id="17cd874e-82a9-41bc-96a9-c2fe38c5546a" class="numbered-list" start="3"><li>Control bus</li></ol><figure id="4a6501e8-d8c9-46ac-8bc2-e1b2d51df1fe" class="image"><a href="Computer%20Architecture%208e40569cfccd4d4d9df146750ebc5906/Untitled%202.png"><img style="width:432px" src="Computer%20Architecture%208e40569cfccd4d4d9df146750ebc5906/Untitled%202.png"/></a></figure><p id="b8e1db0d-daaa-4961-ae95-d18d16de36e1" class="">
</p><p id="e1684047-2f39-4a6b-8272-5cbb61831232" class="">…………………………………………………………..</p><h3 id="872a58d2-23a5-4c66-8215-f232a92e7d31" class=""><mark class="highlight-orange"><strong>Memory Interleaving:</strong></mark></h3><p id="4b297ed5-dca6-4ae4-af27-00e1b681a78a" class="">Abstraction is one of the most important aspects of computing. It is a widely implemented Practice in the Computational field.</p><p id="87c6b5d7-6624-41e9-bbc2-3b4cfe62426f" class="">…………………………………………………………..</p><h3 id="5ec4f03b-e4f6-413a-9048-aeb745ee1ea4" class=""><mark class="highlight-orange"><strong>Memory Interleaving:</strong></mark></h3><p id="e79b0568-3ec9-4f13-9efb-a66913043375" class="">is less or More an Abstraction technique. Though it’s a bit different from Abstraction. It is a Technique that divides memory into a number of modules such that Successive words in the address space are placed in the Different modules.</p><p id="0cd53df7-574e-4da6-a7f0-e6f8e11a4d2b" class="">…………………………………………………………..</p><h3 id="503f1d18-66fd-4767-911c-ab8e15eb8e6c" class=""><mark class="highlight-orange">Programmed I/O:</mark></h3><p id="05364d89-6001-4b09-9ae9-d095667c47dc" class="">It is due to the result of the I/O instructions that are written in the computer program.
Each data item transfer is initiated by an instruction in the program. Usually the transfer
is from a CPU register and memory. In this case it requires constant monitoring by the
CPU of the peripheral devices.</p><p id="388a95d1-99f1-424a-b8c8-1730ceeb4ac0" class="">…………………………………………………………..</p><h3 id="41d78006-10c8-4a99-a31c-161bee1dea52" class=""><mark class="highlight-orange">Interrupt I/O:</mark></h3><p id="84fb08e3-43f6-467f-b0e2-2f6de217ca7e" class="">An interrupt I/O is a process of data transfer in which an external device or a peripheral informs the CPU that it is ready for communication and requests the attention of the CPU.</p><p id="ba4cb91e-8030-4fd1-abbc-f16de1fbef9b" class="">…………………………………………………………..</p><h3 id="0412f579-b8a0-47cd-915f-0afb4434ea10" class="">Interrupt Initiated I/O :</h3><p id="b81a33a9-a460-4ad0-aed0-0d86805250f9" class="">This mode uses an interrupt facility and special commands to inform the interface to issue the interrupt command when data becomes available and interface is ready for the data transfer. In the meantime CPU keeps on executing other tasks and need not check for the flag.</p><p id="0c08471e-256f-461b-9f07-620da954d005" class="">…………………………………………………………..</p><p id="56ebb282-de54-4806-ac93-63f434d93624" class="">Memory-mapped I/O :
Memory-mapped I/O uses the same address space to address both memory and I/O
devices. The memory and registers of the I/O devices are mapped to (associated with)
address values. So a memory address may refer to either a portion of physical RAM, or
instead to memory and registers of the I/O device.</p><p id="04aa0eae-1cde-402f-a505-437a14b3ba10" class="">…………………………………………………………..</p><h3 id="cc040cf5-e828-44ee-9b63-a69edb31ea11" class=""><mark class="highlight-orange">I/O mapped I/O :</mark></h3><p id="fe8f12cd-2945-42e6-8525-f19cd85a486d" class="">I/O is any general-purpose port used by processor/controller to handle peripherals
connected to it. I/O mapped I/Os have a separate address space from the memory. So,
total addressed capacity is the number of I/Os connected and a memory connected.
Separate I/O-related instructions are used to access I/Os.</p><p id="4f9a4796-504f-456e-a709-c44f07b37687" class="">…………………………………………………………..</p><p id="f7034f53-6ccd-4a2c-8fc2-2684397503c3" class=""><strong>Harvard architecture</strong></p><p id="fe60db84-1296-4c42-a753-07413c2f83ef" class="">The <strong>Harvard architecture </strong>is a computer architecture with separate storage and signal pathways for instructions and data. It contrasts with the von Neumann architecture, where program instructions and data share the same memory and pathways.</p><p id="b3e20ef8-7cc5-469d-9aae-e053ef391ffe" class="">…………………………………………………………..</p><h3 id="da5b6061-61c6-4767-82af-1ae5f122992a" class=""><mark class="highlight-orange"><strong>Million instructions per second (MIPS)</strong></mark></h3><p id="0084cdc3-3f36-462e-a377-080b301badc9" class=""><strong>Million instructions per second (MIPS) </strong>is an approximate measure of a computer’s raw processing power. MIPS figures can be misleading because measurement techniques often differ, and different computers may require different sets of instructions to perform the same activity.</p><p id="2c5361a4-eef6-4113-ae95-b6912b786f6d" class="">…………………………………………………………..</p><h3 id="d6b1554a-4e2b-48ac-89ed-096982b5eb0a" class=""><mark class="highlight-orange">MIPS pipeline has five stages:</mark></h3><ul id="1a450c99-d1c7-4a97-b959-17ae7b6e1b55" class="bulleted-list"><li style="list-style-type:disc">IF: Instruction fetch from memory</li></ul><ul id="c293d460-becf-4cfd-856c-23fb19cfbceb" class="bulleted-list"><li style="list-style-type:disc">ID: Instruction decode &amp; register read</li></ul><ul id="f96283ee-1630-46b8-a1ee-7e9347849363" class="bulleted-list"><li style="list-style-type:disc">EX: Execute operation or calculate address</li></ul><ul id="1b863ff9-0306-4f94-af7b-e7662cc052e5" class="bulleted-list"><li style="list-style-type:disc">MEM: Access memory operand</li></ul><ul id="a786d34b-60d5-4af9-939d-341a29084eab" class="bulleted-list"><li style="list-style-type:disc">WB: Write result back to register</li></ul><p id="bc1b8028-0425-4f57-85f9-e09bd24c4527" class="">…………………………………………………………..</p><h3 id="31890b1f-dba6-4d8f-b21f-ab29fec0e19d" class=""><mark class="highlight-orange"><strong><strong>Cache Memory</strong></strong></mark></h3><p id="36d11620-e55c-4ca0-b7b6-928ec8a23fe2" class="">The data or contents of the main memory that are used again and again by CPU, are stored in the cache memory so that we can easily access that data in shorter time.</p><p id="2dd2cd9f-6935-4c14-90ea-943bb883377b" class="">Whenever the CPU needs to access memory, it first checks the cache memory. If the data is not found in cache memory then the CPU moves onto the main memory. It also transfers block of recent data into the cache and keeps on deleting the old data in cache to accommodate the new one.</p><p id="637f00e9-478b-41fa-ad37-dcef8ca41548" class="">…………………………………………………………..</p><h3 id="507d10b1-eaee-4326-bd40-98e449d9778a" class=""><mark class="highlight-orange">There are two different types of cache memory: </mark></h3><p id="21dd28ed-8d16-4c19-ba95-6466f4ee8a2e" class="">Primary and secondary. Primary cache memory is found on the CPU itself whereas secondary cache memory is found on a separate chip close to the CPU. Although, as time has progressed, the secondary cache has become rather obsolete as most caches are found on the CPU. </p><p id="b62bbbe9-b9d7-486f-9608-4e9856120c06" class="">There are 3 different levels of cache memory that can be on a motherboard:</p><ul id="9493c65e-6436-486f-9f26-1460b9543c94" class="bulleted-list"><li style="list-style-type:disc">L1: Extremely small and is located on the CPU itself. It is extremely fast but houses only around 32KB of data per core.</li></ul><ul id="63609e8a-ee98-41dd-9b30-e045e12cd317" class="bulleted-list"><li style="list-style-type:disc">L2: Can be located on the CPU or rarely on its own chip near the CPU. Larger than L1 but not as fast.</li></ul><ul id="1777c854-4421-43d0-819b-0c0f1db1ec31" class="bulleted-list"><li style="list-style-type:disc">L3: While slower than L1 and L2, it is double the speed of standard DRAM.</li></ul><p id="f0d8c87b-a55d-49c9-adcf-a99f24fe7a2e" class="">…………………………………………………………..</p><p id="8a2017b1-4586-4720-b9fd-793efed77806" class=""><mark class="highlight-orange"><strong>(1) - LOOK THROUGH Policy</strong></mark><mark class="highlight-orange"> </mark>= If processor wants to search content , it will first look into cache , if cache hits - get content , if cache miss <strong>(here it will search into L2 and then go to main memory)</strong> it will go to main memory , read block from main memory and copy block into cache for further access.</p><p id="6206844d-3d5d-48b5-b55d-73ffd7625707" class=""><mark class="highlight-orange"><strong>(2) LOOK ASIDE Policy</strong></mark><mark class="highlight-orange"> </mark>= Processor simultaneously look for content in both cache as well as in main memory.</p><p id="9a37b5fc-1cd4-43e0-8bad-c7555c7e0be3" class="">Look aside requires more signal operation for every access(cache and main memory) and when content found in cache , it require to send a cancel signal to main memory,  which is biggest disadvantage of look aside policy.</p><p id="860d9c76-ecb5-4ce8-9f20-73a1c89b8332" class="">…………………………………………………………..</p><h3 id="9aa09a1e-6e69-4e9d-82fb-fa0fbeecb6ad" class=""><mark class="highlight-orange"><strong>Hit Ratio</strong></mark></h3><p id="c1a54202-3459-4894-b936-b529cb33c912" class="">The performance of cache memory is measured in terms of a quantity called <mark class="highlight-orange"><strong>hit ratio</strong></mark>. When the CPU refers to memory and finds the word in cache it is said to produce a <strong>hit</strong>. If the word is not found in cache, it is in main memory then it counts as a <mark class="highlight-orange"><strong>miss</strong></mark>.</p><p id="75620f8b-9d09-46ec-9422-cb74cd19bc5f" class="">The ratio of the number of hits to the total CPU references to memory is called hit ratio.</p><p id="c887ab81-6271-492f-9091-da92052ac498" class=""><code>Hit Ratio = Hit/(Hit + Miss)</code></p><p id="ee479de0-eb79-4508-b847-4dbf5c2ba9d7" class=""><code>miss ratio = 1 - hit ratio</code></p><p id="1c011abb-7fa0-43fd-a7ba-83ab81c09691" class=""><code>hit ratio = 1 - miss ratio</code></p><p id="3f2f5ed7-351d-4011-bc4e-46b124432cdd" class="">…………………………………………………………..</p><h3 id="3f287c44-da0a-4630-b2a3-785ee2da3b53" class=""><mark class="highlight-orange">Virtual memory:</mark></h3><p id="5a0bc470-7ea2-4ded-a9aa-1c92a5f0fb74" class="">Virtual memory provides virtual address mapping between applications and hardware memory. It provides many functions, including multitasking (multiple tasks executing at once on one CPU), allowing multiple processes to access the same shared library in memory, swapping, and other functions.</p><p id="0119dc94-7091-48ab-9774-458928c15c47" class="">Virtual memory is a common technique used in a computer&#x27;s operating system (OS). Virtual memory uses both hardware and software to <strong>enable a computer to compensate for physical memory shortages, temporarily transferring data from random access memory (RAM) to disk storage</strong>.</p><p id="56469bcf-4ef4-4d9b-86b3-27a2369a63c6" class="">…………………………………………………………..</p><p id="ae7ae4b2-940b-4750-85be-2bee31745cd3" class=""><mark class="highlight-orange"><strong>Difference between Virtual memory and Cache memory:</strong></mark></p><table id="0719da5a-57ad-4dda-a4a7-2105df092a74" class="simple-table"><tbody><tr id="4175dd1e-736b-4446-b254-341fc1cc70a4"><td id="{RKP" class="">Virtual Memory</td><td id="ixWP" class="">Cache Memory</td></tr><tr id="f1420739-bc6b-482b-8866-8d386f6526f8"><td id="{RKP" class="">Virtual memory increases the capacity of main memory.</td><td id="ixWP" class="">While cache memory increase the accessing speed of CPU.</td></tr><tr id="47440924-cfe4-4fe2-adae-26a1b7e34a2c"><td id="{RKP" class="">Virtual memory is not a memory unit, its a technique.</td><td id="ixWP" class="">Cache memory is exactly a memory unit.</td></tr><tr id="81a00630-12e2-45ae-9cc8-c60e81c97499"><td id="{RKP" class="">The size of virtual memory is greater than the cache memory.</td><td id="ixWP" class="">While the size of cache memory is less than       the virtual memory.</td></tr><tr id="48118a8b-5df0-4bdb-9921-6aef85974c15"><td id="{RKP" class="">Operating System manages the Virtual memory.</td><td id="ixWP" class="">On the other hand hardware manages the cache memory.</td></tr><tr id="bb4d040c-d008-4c38-b6f5-810507ce4bf0"><td id="{RKP" class="">In virtual memory, The program with size larger than the main memory are executed.</td><td id="ixWP" class="">While in cache memory, recently used data is copied into.</td></tr><tr id="dda7ed3a-ead2-4044-9846-b31d7529e8b8"><td id="{RKP" class="">In virtual memory, mapping frameworks is needed for mapping virtual address to physical address.</td><td id="ixWP" class="">While in cache memory, no such mapping frameworks is needed.</td></tr></tbody></table><p id="96b41568-4f39-4ea6-8775-2acdfd99f540" class="">…………………………………………………………..</p><p id="e07d0aeb-8859-46b1-ae70-55db0297f428" class="">…………………………………………………………..</p><h3 id="92b43f88-3b5d-422e-95c1-09c695569b20" class=""><mark class="highlight-orange"><strong><strong>What is Pipelining?</strong></strong></mark></h3><p id="51032093-ca2e-445d-9d7f-e64bf15ff6bd" class="">Pipelining is the process of accumulating instruction from the processor through a pipeline. It allows <mark class="highlight-orange">storing </mark>and <mark class="highlight-orange">executing</mark> instructions in an <mark class="highlight-orange">orderly process</mark>. It is also known as <strong>pipeline processing</strong>.</p><h2 id="51f04a15-ff1c-4b28-b819-56594db4f5dc" class=""><mark class="highlight-orange"><strong>Types of Pipeline</strong></mark></h2><p id="f95289af-dc93-4afe-b1f7-5d7a6b7ad000" class="">It is divided into 2 categories:</p><ol type="1" id="133101cf-87cd-4b8c-9f26-bc1b706f269a" class="numbered-list" start="1"><li><mark class="highlight-orange"><strong>Arithmetic Pipeline: </strong></mark>Arithmetic pipelines are usually found in most of the computers. They are used for floating point operations, multiplication of fixed point numbers etc.</li></ol><ol type="1" id="57023835-0e1e-4e6d-b80c-c8b043297393" class="numbered-list" start="2"><li><mark class="highlight-orange"><strong>Instruction Pipeline:</strong></mark> In this a stream of instructions can be executed by overlapping <em>fetch</em>, <em>decode</em> and <em>execute</em> phases of an instruction cycle. This type of technique is used to increase the throughput of the computer system.</li></ol><p id="f4e727ba-e8b4-475a-8e7a-08b830e3a140" class="">
</p><h3 id="667b0f98-1f70-4e0c-95da-b0314b94798f" class=""><mark class="highlight-orange">There are three kinds of hazards:</mark></h3><ul id="9879cc0c-6127-412d-a15b-48825e2bc90f" class="bulleted-list"><li style="list-style-type:disc"><mark class="highlight-orange"><strong>Structural Hazards : </strong></mark><ol type="1" id="30470d01-6e4c-48af-9e0a-381cd13ba450" class="numbered-list" start="1"><li>Arise from resource conflicts</li></ol><ol type="1" id="bba2a9de-f7ba-4880-9f8d-a8df416874d6" class="numbered-list" start="2"><li>HW cannot support all possible combinations of instructions</li></ol></li></ul><ul id="4cf4dc90-ef04-4607-bb09-1485b5dcbc6f" class="bulleted-list"><li style="list-style-type:disc"><mark class="highlight-orange"><strong>Data Hazards :</strong></mark> Occur when given instruction depends on data from an
instruction ahead of it in pipeline</li></ul><ul id="4d3cfa13-9b77-4d41-8152-248ceb1bfd79" class="bulleted-list"><li style="list-style-type:disc"><mark class="highlight-orange"><strong>Control Hazards :</strong></mark> Result from branch, other instructions that change flow of
program (i.e. change PC).</li></ul><p id="8cdf5c41-092a-4158-b979-18d007b47267" class="">…………………………………………………………..</p><h3 id="3142d924-fe2e-405d-9e39-168983d1bd8c" class=""><mark class="highlight-orange"><strong>Input-Output Interface:</strong></mark><mark class="highlight-orange"> </mark></h3><p id="17bd4686-46a6-4b53-9dbd-da5c34a8f47a" class="">is used as an method which helps in transferring of information between the internal storage devices i.e. memory and the external peripheral device . A peripheral device is that which provide input and output for the computer, it is also called Input-Output devices. For Example: A keyboard and mouse provide Input to the computer are called input devices while a monitor and printer that provide output to the computer are called output devices.</p><figure id="159145f4-5591-4f8f-9b35-b1b52e77869c" class="image"><a href="Computer%20Architecture%208e40569cfccd4d4d9df146750ebc5906/Untitled%203.png"><img style="width:646px" src="Computer%20Architecture%208e40569cfccd4d4d9df146750ebc5906/Untitled%203.png"/></a></figure><h3 id="3c3797bd-3bec-4b42-9467-9c44c40faa57" class=""><mark class="highlight-orange">Direct memory access (DMA)</mark></h3><p id="e5db939e-5eb4-4216-8320-0ea36963ca0b" class="">Direct memory access (DMA) is the process of transferring data without the involvement of the processor itself. It is often used for transferring data to/from input/output devices. A separate DMA controller is required to handle the transfer. The controller notifies the DSP processor that it is ready for a transfer.</p><p id="d7540e94-ecc8-4021-90a2-85213a875c9e" class="">…………………………………………………………..</p><h3 id="360310ef-ccfc-4952-ac6c-b295b926ba4f" class=""><mark class="highlight-orange">daisy-chaining</mark></h3><p id="17f9d41e-a611-40db-9546-b420ee73e76e" class="">The daisy-chaining method of <mark class="highlight-orange">creating priority</mark> includes a serial connection of all devices that request an interrupt. The device with the highest priority is located in the first position, followed by lower-priority devices up to the device with the lowest priority, which is situated last in the chain.</p><p id="9e314b58-febc-4227-8339-5c193105e2ad" class="">
</p></div></article></body></html>