reading-note-rd11
Audio, Video, Images
Video and Audio Content
Explain how the ability to use video and audio on the web has evolved since the early 2000s.

The first influx of online videos and audio were made possible by proprietary plugin-based technologies like Flash and Silverlight. Both of these had security and accessibility issues, and are now obsolete, in favor of native HTML solutions video and audio elements and the availability of JavaScript APIs for controlling them.
Describe the use of the src and controls attributes in the video element.

The source HTML element specifies multiple media resources for the picture, the audio element, or the video element. It is an empty element, meaning that it has no content and does not have a closing tag. It is commonly used to offer the same media content in multiple file formats in order to provide compatibility with a broad range of browsers given their differing support for image file formats and media file formats.
Why is it important to have fallback content inside the video element?

This is called fallback content for this will be displayed if the browser accessing the page doesn't support the video element, allowing us to provide a fallback for older browsers. This can be anything you like; in this case, we've provided a direct link to the video file, so the user can at least access it some way regardless of what browser they are using.
Write a very short story where audio and video are characters.

The audio and video tracks within the container hold data in the appropriate format for the codec used to encode that media. Different formats are used for audio tracks versus video tracks. Each audio track is encoded using an audio codec, while video tracks are encoded using (as you probably have guessed) a video codec. As we talked about before, different browsers support different video and audio formats, and different container formats (like MP3, MP4, and WebM, which in turn can contain different types of video and audio).
A Complete Guide To Grid
How does Grid layout differ from Flex?

Grid and flexbox. The basic difference between CSS Grid Layout and CSS Flexbox Layout is that flexbox was designed for layout in one dimension - either a row or a column. Grid was designed for two-dimensional layout - rows, and columns at the same time
Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.

The terms/meaning of grid container, grid items and grid line and are as follows. Grid containers consist of grid items, placed inside columns and rows. The items within the CSS Grid container are known as grid items or child elements. Alternatively referred to as a column separator or row separator, grid lines or gridlines divide each of the cells, rows, and columns.
Responsive Images
Besides making a site visually appealing across different screen sizes, why should developers make images responsive?

Having responsive images is important because it helps us deliver optimal file size, the right image for the right screen size, improves user experience and improves loading time. Having various versions of your image is important for creating a responsive image.
Define the following img attributes srcset and sizes. Write an example of how they are used.

The srcset defines the set of images we will allow the browser to choose between, and what size each image is. Each set of image information is separated from the previous one by a comma. For each one, we write:
An image filename (elva-fairy-480w.jpg) A space The image's intrinsic width in pixels (480w) — note that this uses the w unit, not px as you might expect. An image's intrinsic size is its real size, which can be found by inspecting the image file on your computer (for example, on a Mac you can select the image in Finder and press Cmd + I to bring up the info screen).

The sizes defines a set of media conditions (e.g. screen widths) and indicates what image size would be best to choose, when certain media conditions are true — these are the hints we talked about earlier. In this case, before each comma we write:
A media condition ((max-width:600px)) — you'll learn more about these in the CSS topic, but for now let's just say that a media condition describes a possible state that the screen can be in. In this case, we are saying "when the viewport width is 600 pixels or less". A space The width of the slot the image will fill when the media condition is true (480px).

How is srcset more helpful for responsive images than CSS or JavaScript?

The srcset attribute on an img tag specifies multiple image resources (URLs) for the img element. Together with the sizes attribute they create responsive images that adjust according to browser conditions.