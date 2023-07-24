# Video and audio content:   

- The start of online video and audio was made possible by propritetary plug-based technologies like Flash and Silverlight.
- Both of these had security and accessibility issues and are no longer.
  -The &lt;video> element allows you to embed a video very easily.
- In the same way as for the &lt;img> element, the src (source) attribute contains a path to the video you want to embed. It works in exactly the same way.  
- The paragraph inside the &lt;video> tags is called fallback content — this will be displayed if the browser accessing the page doesn't support the &lt;video> element, allowing us to provide a fallback for older browsers. This can be anything you like; in this case, we've provided a direct link to the video file, so the user can at least access it some way regardless of what browser they are using.
## Questions:  
1. Explain how the ability to use video and audio on the web has evolved since the early 2000s.
- Since the early 2000s, the web's ability to use video and audio has undergone a transformative evolution. Initially reliant on Flash for multimedia playback, the introduction of HTML5's &lt;audio> and &lt;video> elements eliminated the need for third-party plugins, making media embedding easier and more standardized. WebRTC technology enabled real-time audio and video communication directly within browsers, revolutionizing interactive applications. Advanced web APIs, adaptive streaming, and open video codecs further improved media delivery, interactivity, and overall user experience, making video and audio seamlessly integrated components of modern web applications.
2. Describe the use of the src and controls attributes in the &lt;video> element.
-The src attribute in the &lt;video> element is used to specify the source URL of the video file that should be played. It tells the browser where to fetch the video content from. The value of the src attribute can be a local file path or a URL to a video hosted on a server.  
-The controls attribute in the &lt;video> element is a boolean attribute. When present, it adds default playback controls to the video player, such as play, pause, volume control, and timeline scrubbing. This allows users to interact with the video and control its playback without any additional coding effort. It provides a standard set of controls that are common across different browsers.
3. Why is it important to have fallback content inside the &lt;video> element?
- It is important to have fallback content inside the &lt;video> element to ensure that users have a good experience even if the video cannot be played for some reason. Not all browsers or devices support the same video formats or codecs, and some users may have disabled video autoplay or have slow internet connections. By providing fallback content, such as alternative text or a link to download the video, users who cannot view the video will still understand its context or have an option to access the content in a different way. This ensures inclusivity and accessibility, making the web content more user-friendly for a wider audience.
4.Write a very short story where &lt;audio> and &lt;video> are characters.
-In a digital world where websites came alive, &lt;audio> and &lt;video> were two extraordinary characters, each with their unique charm. &lt;audio> had a melodious voice that resonated through the virtual realm, captivating every user who stumbled upon its enchanting tunes. Meanwhile, &lt;video> was a captivating performer, weaving stunning visual tales that mesmerized onlookers. Together, they formed an inseparable duo, harmonizing sound and image to create immersive experiences. With every click, they transported users to distant lands, sparking joy and wonder in the hearts of all who encountered them, proving that technology could be an art that touched the soul.

# A Complete Guide to CSS Grid:  
-CSS Grid Layout (aka “Grid” or “CSS Grid”), is a two-dimensional grid-based layout system.  
-Grid is the very first CSS module created specifically to solve the layout problems we’ve all been hacking our way around for as long as we’ve been making websites.  
## Questions:  
1. How does Grid layout differ from Flex?
-They most importantly differ from orientation. Flexbox is a one-dimensional layout system, meaning it deals with either rows or columns at a time. It is best suited for creating flexible and dynamic layouts along a single axis. Grid layout is a two-dimensional layout system, allowing you to create both rows and columns simultaneously. It offers more control over the positioning and alignment of elements in both the row and column directions.
2. Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.
-Grid Container: The grid container is the parent element that holds all the items (child elements) arranged in a grid layout. By applying the CSS property display: grid; to an element, you create a grid container. It establishes the context for the grid layout and defines the grid lines, rows, and columns.
-Grid Item: Grid items are the child elements inside the grid container that participate in the grid layout. Each grid item is placed within the grid cells defined by the rows and columns of the grid. You can use the CSS property grid-column and grid-row to control the position and spanning of grid items.
-Grid Line: Grid lines are the horizontal and vertical lines that form the grid's structure. They separate the grid cells, defining the rows and columns of the grid. Grid lines are numbered starting from 1, and you can use these line numbers or names to position and align grid items within the grid container.
# Responsive Images:  
-Images that work well on devices with widely differing screen sizes, resolutions, and other such features.  
## Questions:  
1.Besides making a site visually appealing across different screen sizes, why should developers make images responsive?  
-making images responsive is not only about aesthetics; it has significant implications for user experience, page performance, mobile-friendliness, and SEO. By optimizing images for different devices and screen sizes, developers can create a more inclusive and efficient web experience for all users.  
2. Define the following &lt;img> attributes srcset and sizes. Write an example of how they are used.  
-The srcset attribute in the &lt;img> element allows specifying multiple image sources with different resolutions, and the sizes attribute defines the display size of the image based on the viewport, enabling responsive image selection and rendering; for example, &lt;img src="example.jpg" srcset="example-320w.jpg 320w, example-480w.jpg 480w, example-800w.jpg 800w" sizes="(max-width: 600px) 100vw, (max-width: 1000px) 50vw, 33.3vw" alt="Example Image"> provides different image options based on the viewport size, ensuring optimal image display on various devices.  
3.How is srcset more helpful for responsive images than CSS or JavaScript?  
-srcset is more helpful for responsive images than CSS or JavaScript because it allows the browser to automatically choose and download the appropriate image based on the user's device and viewport, resulting in optimized image delivery and improved performance without the need for additional code or scripting.  
## Things I want to know more about:  
Responsive images  














  
