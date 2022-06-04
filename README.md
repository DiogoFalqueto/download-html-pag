<h1>Download HTML Pag</h1>

<p>pacote npm para baixar HTML de paginas.</p>

<h2>Instalação</h2>
<p>Execute:</p>
<code>npm i download-html-pag</code>
<p>ou</p>
<code>npm i https://github.com/DiogoFalqueto/download-html-pag</code>
<h2>Utilização</h2>

<pre>
<code>
const downloadHtmlPag = require("download-html-pag")
const nameFile = "google.html"
const url = "https://www.google.com"

const download = downloadHtmlPag.download(nameFile, url)

download.then(function(){
	console.log("Download file!")
})
</code>
</pre>
