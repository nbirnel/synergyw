<html>
<head>
<meta name="generator" content="groff -Thtml, see www.gnu.org">
<meta http-equiv="Content-Type" content="text/html; charset=US-ASCII">
<meta name="Content-Style" content="text/css">
<style type="text/css">
       p       { margin-top: 0; margin-bottom: 0; vertical-align: top }
       pre     { margin-top: 0; margin-bottom: 0; vertical-align: top }
       table   { margin-top: 0; margin-bottom: 0; vertical-align: top }
       h1      { text-align: center }
</style>
<title>synergyw</title>

</head>
<body>

<h1 align="center">synergyw</h1>

<a href="#NAME">NAME</a><br>
<a href="#SYNOPSIS">SYNOPSIS</a><br>
<a href="#DESCRIPTION">DESCRIPTION</a><br>
<a href="#OPTIONS">OPTIONS</a><br>
<a href="#EXIT STATUS">EXIT STATUS</a><br>
<a href="#AUTHOR">AUTHOR</a><br>
<a href="#HISTORY">HISTORY</a><br>
<a href="#FILES">FILES</a><br>
<a href="#BUGS">BUGS</a><br>
<a href="#SEE ALSO">SEE ALSO</a><br>
<a href="#LICENSE">LICENSE</a><br>

<hr>


<h2>NAME
<a name="NAME"></a>
</h2>


<p style="margin-left:11%; margin-top: 1em">synergyw
&minus; a simple wrapper around synergy, useful for multiple
setups</p>

<h2>SYNOPSIS
<a name="SYNOPSIS"></a>
</h2>


<p style="margin-left:11%; margin-top: 1em"><b>synergyw
CONFIG</b></p>

<h2>DESCRIPTION
<a name="DESCRIPTION"></a>
</h2>



<p style="margin-left:11%; margin-top: 1em"><b>synergyw</b>
runs <b>synergys</b> or <b>synergyc</b> with the options in
<b>CONFIG</b>.</p>

<h2>OPTIONS
<a name="OPTIONS"></a>
</h2>


<p style="margin-left:11%; margin-top: 1em"><b>-s
CONFIG</b></p>

<p style="margin-left:22%; margin-top: 1em">show
<b>CONFIG</b>.</p>

<p style="margin-left:11%; margin-top: 1em"><b>-e
CONFIG</b></p>

<p style="margin-left:22%; margin-top: 1em">edit
<b>CONFIG</b>, and any synergy config file it depends
on.</p>

<p style="margin-left:11%; margin-top: 1em"><b>-l</b></p>

<p style="margin-left:22%; margin-top: 1em">list all
<b>CONFIG</b> files.</p>

<h2>EXIT STATUS
<a name="EXIT STATUS"></a>
</h2>


<p style="margin-left:11%; margin-top: 1em">exits non-zero
on error.</p>

<h2>AUTHOR
<a name="AUTHOR"></a>
</h2>


<p style="margin-left:11%; margin-top: 1em">Noah Birnel</p>

<h2>HISTORY
<a name="HISTORY"></a>
</h2>


<p style="margin-left:11%; margin-top: 1em">I use
<b>synergy</b> on a laptop at home as a server in two
different configurations, and at work as a client. Keeping
that all straight was not fun.</p>

<h2>FILES
<a name="FILES"></a>
</h2>



<p style="margin-left:11%; margin-top: 1em"><b>$HOME/.config/synergyw</b></p>

<p style="margin-left:22%;">- config files. These are in
<b>sh(1)</b> and are simply value settings, in the
format:</p>

<p style="margin-left:28%;"><b>KEY=VALUE</b></p>

<p style="margin-left:22%;">You <i>must</i> set <b>role</b>
to either <b>server</b> or <b>client.</b> Servers need
<b>synergy_config</b> set to a valid synergy configuration
file (located in <b>$HOME/.config/synergyw/synergy</b>).
Clients need <b>hostess</b> set, and optionally
<b>password.</b></p>


<p style="margin-left:11%;"><b>$HOME/.config/synergyw/synergy</b></p>

<p style="margin-left:22%;">- synergy config files, used by
server config files. See
<i>http://synergy2.sourceforge.net/configuration.html</i>
for the format.</p>

<h2>BUGS
<a name="BUGS"></a>
</h2>


<p style="margin-left:11%; margin-top: 1em">Sources
<b>CONFIG</b>, which is a security hole. Probably other
bugs. <b>Synergy</b> does not have a man page, which is not
a bug in <b>synergw</b>, but makes it harder to write
configurations.</p>

<h2>SEE ALSO
<a name="SEE ALSO"></a>
</h2>



<p style="margin-left:11%; margin-top: 1em"><i>http://synergy-project.org/
<br>
http://synergy2.sourceforge.net/configuration.html</i></p>

<h2>LICENSE
<a name="LICENSE"></a>
</h2>


<p style="margin-left:11%; margin-top: 1em">Copyright 2014
Noah Birnel</p>

<p style="margin-left:11%; margin-top: 1em">MIT License</p>
<hr>
</body>
</html>
