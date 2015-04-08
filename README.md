
<b>SEO Techniques</b>
<b>How to Block Entire website for All Search Engine Bots</b>
Solution to block all the website from all the search engines bots.

You need to create a robots.txt file and keep it in root folder of server.
You should write following syntax inside robots.txt file.
<p>
<i>User-agent: *<p>
<p>
<i>Disallow: /

These above 2 lines are enough. This will block all search engine bots. 


The User-agent: * - means this section applies to all robots. 
The Disallow: / tells the robot that it should not visit any pages on the site.

