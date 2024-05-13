<!DOCTYPE html>
<html lang="en">
<head>
<style>
  h1 {
  background-color: red;
  margin-left: 40px;
}
h2 {
  background-color: purple;
  margin-left: 40px;
}
h3 {
  background-color: pink;
  margin-left: 40px;
}
h4 {
  background-color: orange;
  margin-left: 40px;
}
h5 {
  background-color: yellow;
  margin-left: 40px;
}
h6 {
  background-color: green;
  margin-left: 40px;
}
#a {
  background-color: lightblue;
  color: black;
  padding: 40px;
  text-align: center;
}
#b {
  background-color: blue;
  color: black;
  padding: 40px;
  text-align: center;
}
#c {
  background-color: orange;
  color: black;
  padding: 40px;
  text-align: center;
}
#d {
  background-color: red;
  color: black;
  padding: 40px;
  text-align: center;
}
#e {
  background-color: green;
  color: black;
  padding: 40px;
  text-align: center;
}
#f {
  background-color: purple;
  color: black;
  padding: 40px;
  text-align: center;
}
</style>
</head>

<body>
<header> My name is Matvey Bratishchev, I am a student of SB BSU. This is my 1st work on web-design subject. </header>
<nav>
<ul>
<li> <a href="#a"> a.	When HTML5 has become a standard? What were the main reasons for developing new standard?</a> </li>
<li> <a href="#b"> b.	What is a difference between W3C HTML5 and WHATWG HTML Living Standard?</a> </li>
<li> <a href="#c"> c.	What is the minimal HTML page code?</a> </li>
<li> <a href="#d"> d.	Comment on semantic and presentational markup. Why presentational markup is considered deprecated now?</a> </li>
<li> <a href="#e"> e.	How you can check browser support for particular tag or attribute?</a> </li>
<li> <a href="#f"> f.	What are the audio and video formats, officially supported by HTML standard? What happens if you use other format?</a> </li>
</ul>
</nav>
<section>
 a.<dl>	
<dt><body>
<h1 id="a">When HTML5 has become a standard? What were the main reasons for developing new standard?</h1>

</body></dt>
 <dd>
<h1>HTML5 became a standard on October 28, 2014, when the World Wide Web Consortium (W3C) officially published it as a recommendation. 

The main reasons for developing the new standard were:

 
1. Evolving Web Technologies: The web landscape was rapidly changing with the emergence of new technologies, devices, and multimedia capabilities. HTML needed to evolve to accommodate these changes and provide better support for audio, video, graphics, and interactive content.

2. Compatibility and Interoperability: The previous versions of HTML had various inconsistencies and lacked standardized features, leading to compatibility issues across different web browsers and devices. HTML5 aimed to establish a more consistent and interoperable web platform.

3. Mobile and Responsive Design: With the increasing use of mobile devices for accessing the web, there was a need for a standard that could better support mobile browsing, responsive design techniques, and touch-based interactions. HTML5 introduced features like semantic elements, responsive images, and touch events to address these needs.

4. Rich Multimedia Support: HTML5 aimed to reduce reliance on third-party plugins like Adobe Flash by providing native support for audio and video elements. This made it easier for developers to integrate multimedia content into web pages without requiring additional plugins.

5. Improved Accessibility and Semantics: HTML5 introduced new semantic elements like header, footer, nav, article, etc., which improved the accessibility and structure of web documents. These elements helped search engines better understand and index web content, improving search engine optimization (SEO) and usability. </article>

 Overall, HTML5 was developed to modernize and enhance the capabilities of the web, making it more powerful, efficient, and accessible across different platforms and devices.</h1->
 </dd>
 </dl>
 b.
  <dl>
 <dt><body>

<h1 id="b">What is a difference between W3C HTML5 and WHATWG HTML Living Standard?</h1>

</body></dt>
 <dd><article>
<h2>The main difference between W3C HTML5 and WHATWG HTML Living Standard lies in their development processes and status. 
1. Development Process:
   - W3C HTML5: The W3C (World Wide Web Consortium) initially developed HTML5 as a standard. It went through a traditional standards development process involving drafts, working groups, and formal approval.
   - WHATWG HTML Living Standard: The WHATWG (Web Hypertext Application Technology Working Group) took a more dynamic and iterative approach to develop the HTML Living Standard. It operates as a community-driven effort, where developers from various organizations collaborate continuously to update and improve the specification.

2. Status:
   - W3C HTML5: HTML5 was published by the W3C as a formal recommendation in October 2014. Since then, the W3C has continued to maintain and update the HTML specification.
   - WHATWG HTML Living Standard: The HTML Living Standard is a continuously updated document that reflects the ongoing work and consensus of the WHATWG community. It serves as a living document that evolves over time to incorporate new features, improvements, and clarifications.
   </dd>
   </dl>
   </article>
   </h2>
c.
<article>
<dl>
<dt><body>

<h1 id="c">What is the minimal HTML page code?</h1>

</body></dt>
<dd>
<h3>
!DOCTYPE html
html lang="en"
head
    title Title of the Document /title
/head
body
    !-- Content of the document goes here --
/body
/html
</dd>
</dl>
</article>
</h3>
d.<dl>
<dt><body>

<h1 id="d">Comment on semantic and presentational markup. Why presentational markup is considered deprecated now?</h1>

</body></dt>
<dd>
<h4>
Semantic markup and presentational markup are two approaches to structuring HTML documents, each with its own purpose and characteristics. 

1. Semantic Markup:
   - Semantic markup focuses on using HTML elements to convey the meaning and structure of content. It emphasizes the semantic meaning of elements rather than their appearance.
   - Semantic HTML elements, such as header, nav, article, section, footer, aside, etc., provide context and clarity to the content, making it more accessible, searchable, and understandable for both humans and machines.
   - Semantic markup improves website accessibility, SEO (Search Engine Optimization), and maintainability, as it separates content from presentation and allows developers to style content using CSS while preserving its underlying structure.

2. Presentational Markup:
   - Presentational markup focuses on using HTML elements to define the visual appearance or layout of content. It involves using elements like font, b, i, center, table, etc., to style content directly within the HTML document.
   - Presentational markup mixes content with styling, making it harder to maintain, update, and adapt to different devices and screen sizes. It also reduces accessibility and SEO, as search engines and assistive technologies may have difficulty interpreting the meaning of content.
   - Presentational markup was commonly used in the early days of web development when CSS (Cascading Style Sheets) was less supported or understood. However, with the widespread adoption of CSS and the development of web standards, presentational markup is now considered deprecated and discouraged.

Presentational markup is considered deprecated now because:
   - It conflates content with presentation, making it difficult to maintain and update websites.
   - It hinders accessibility and SEO efforts by obscuring the semantic meaning of content.
   - It does not separate concerns between content and style, leading to less flexible and scalable code.
   - It is less compatible with modern web development practices, such as responsive design and accessibility standards.

 In contrast, semantic markup promotes best practices in web development by emphasizing the separation of concerns, clarity of content, and accessibility of websites, ultimately leading to better user experiences and more maintainable codebases. 
</dd>
 </dl>
 </article>
 </h4>
 e.<article> 
 <dl>
 <dt><body>

<h1 id="e">How you can check browser support for particular tag or attribute?</h1>

</body></dt>
 <dd>
 <h5>
 To check browser support for a particular HTML tag or attribute, you can use online resources or tools that provide compatibility tables and information about browser support. Here are some commonly used resources: 

1. Can I Use (https://caniuse.com/): Can I Use is a popular website that provides up-to-date browser support tables for HTML, CSS, JavaScript, and other web technologies. You can search for a specific HTML tag or attribute to see detailed information about its support across different web browsers and versions.

2. MDN Web Docs (https://developer.mozilla.org/): MDN Web Docs is a comprehensive resource for web developers that provides documentation and reference guides for HTML, CSS, JavaScript, and other web technologies. Each HTML element and attribute page includes information about browser compatibility, including which browsers support it and any known issues or limitations.

3. W3Schools (https://www.w3schools.com/): W3Schools is a popular website for learning web development, and it provides reference guides, tutorials, and examples for HTML, CSS, JavaScript, and more. You can check the browser support section on the documentation pages for HTML elements and attributes to see which browsers support them.

4. Web Platform Tests (https://web-platform-tests.org/): Web Platform Tests is an open-source project that provides a comprehensive test suite for web platform features, including HTML elements and attributes. You can view the test results to see how different browsers perform against the standard and identify any inconsistencies or issues.

By using these resources, you can ensure that the HTML elements and attributes you use in your web development projects are supported across the browsers you need to target, helping you build more compatible and reliable websites.
</h5>
</dd>
 </dl>
 </article>
f. 
<article>
<dl>
 <dt><body>

<h1 id="f">What are the audio and video formats, officially supported by HTML standard? What happens if you use other format?</h1>

</body></dt>
 <dd>
 <h6>
1. Audio Formats:
   - MP3 (MPEG-1 Audio Layer 3)
   - Ogg Vorbis
   - WAV (Waveform Audio File Format)

2. Video Formats:
   - MP4 (MPEG-4 Part 14)
   - WebM (VP8, VP9 video codecs with Vorbis or Opus audio codecs)

These formats are recommended by the HTML standard for cross-browser compatibility and support across different devices and platforms.

If you use other formats that are not officially supported by the HTML standard, the behavior may vary depending on the web browser and device being used:

1. Some web browsers may attempt to play unsupported audio or video formats using built-in codecs or third-party plugins. However, this approach may not be consistent across different browsers and may result in degraded performance or compatibility issues.

2. In some cases, the audio or video element may fail to load or display any content if the browser does not support the specified format. Users may encounter error messages or blank areas where the media should be displayed.

3. Even if the media playback is successful, using unsupported formats may lead to decreased performance, increased loading times, or lack of support for certain features such as subtitles, captions, or streaming protocols.

 Overall, it is recommended to use the audio and video formats officially supported by the HTML standard to ensure maximum compatibility, performance, and user experience across different web browsers and devices.
 </h6>
 </dd>
 </dl>
 </article>
<footer>

<img src="data:image/webp;base64,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" alt="Logo">

<video width="320" height="240" controls>
  <source src="https://www.youtube.com/watch?v=1OeC9CGtWcM" type="video/mp4">
  <source src="https://www.youtube.com/watch?v=1OeC9CGtWcM" type="video/ogg">
</video>
<audio controls>
  <source src="https://open.spotify.com/track/60a0Rd6pjrkxjPbaKzXjfq?si=30d3417bcb544d4a" type="audio/ogg">
  <source src="https://open.spotify.com/track/60a0Rd6pjrkxjPbaKzXjfq?si=30d3417bcb544d4a" type="audio/mpeg">
</audio>
 </footer>
</section>
</body>
</html>