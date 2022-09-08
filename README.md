### Hi there 👋
The pinned repositories are various projects that Kissu uses on it's site.
### Kissu Software and Related Side Projects
Kissu.moe runs on a heavily modified variant of Vichan which interacts with various side services.<br/>
I am currently progressing towards a replacement for Vichan given PHP7.4's security EoL in November 2022. <br/>
There are currently no plans for this replacement to be open source however projects such as ECHibiki/Community-Banners-2.0 , ECHibiki/Kissu-Feedback-and-Forms and the future search.php replacement service are open source and used as ways for me to gain expertise with golang.<br/>
These projects are educational in nature and therefore I have little concern what you do with them, beyond following the licenses. They are ways for me to learn how to write a serious imageboard engine, perhaps you could do the same for your own purpose.

### The Kissu-UI and Vichan-UI
Kissu-Fr(AKA the Kissu-UI or New-UI) is a modern ReactJS user interface blending the old school frames style with modern javascript dynamic page rendering. This UI is also closed source. It is a single page application meaning the client is forever existing within the same document and navigates around through requesting JSON files from the server. It holds the advantage of being easy to develop for(can quickly attatch event listeners to any html element and provide complicated functionality), secure against XSS and HTML injection(ReactJS provides this security) and allows for the client to request less data(JSON APIs are inherently more lightweight than full HTML pages). There are various other advantages, these are just what's on the top of my head.<br/>
However, it's a complicated system which requires constant debugging. Some types of javascript crashes can render pages completely unusable and it forces a reliance on the original vichan pages for a rare set of users which don't fit a certain technological profile. <br/>
<br/>
Because not everyone can run the Kissu-UI( as of writting iOS devices and obviously users not running javascript) Kissu has a dependance on the vichan pages rendered on Twig templates. While they are functional and fullfill a certain purpose, their existence is to make it possible to use the site for specific users who are not able to be satisfied by any improvments to Kissu-Fr and to allow me to focus my time on other tasks instead of writting my own lightweight HTML user interface. 

<!--
**ECHibiki/ECHibiki** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
