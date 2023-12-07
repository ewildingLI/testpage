Another page...

with a picture of a lama ![lama-image](lama.jpg "LAMA")

And a video too?
<video width="320" height="240" controls>
  <source src="lama.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>

Referencing it via html tags works on the final page, but only if the browser supports it.
Another way of doing this according to this [website](https://bobbyhadz.com/blog/embed-video-into-github-readme-markdown) is to drag and drop the video directly into the markdown editor of github, like I did below:


https://github.com/ewildingLI/testpage/assets/61542252/4d4e84d6-69a9-4f9c-9370-42fc67b2f77e

Because now it is referenced as an asset.

Navigating to the github page, the video isn't loaded, because I just kept the raw url, without transforming it to a markdown link.
If I reference the link now in markdown, it should potentially work?

Test with Bracets
![lama-image](https://github.com/ewildingLI/testpage/assets/61542252/4d4e84d6-69a9-4f9c-9370-42fc67b2f77e "LAMA")

Test with ```<video>``` tag.
<video width="630" height="300" src="https://github.com/ewildingLI/testpage/assets/61542252/4d4e84d6-69a9-4f9c-9370-42fc67b2f77e" controls></video>

Which one works?