
<p><h1>SEO Techniques</h1></p>
<p><b>How to Block Entire website from All  the Search Engine Bots</b></p>


<p>You need to create a robots.txt file and keep it in root folder of server.</p>
<p>You should write following syntax inside robots.txt file.</p>
<p>
<i>User-agent: *<p>
<p>
<i>Disallow: /

<p>These above 2 lines are enough. This will block all search engine bots.</p>

<p>The User-agent: * - means this section applies to all robots. </p>
<p>The Disallow: / tells the robot that it should not visit any pages on the site.</p>

<b>Note</b>: <p>According to offical robots.txt website, Total 302 bots obey this guidelines. </p>
<p>To check list visit http://www.robotstxt.org/db.html</p>

