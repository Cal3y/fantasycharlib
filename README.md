<h1>Fantasy Characters Random Library</h1>
This is a very simple library full of small, randomly generated images for use as a fantasy character placeholders. Currently there are 190 random character images.

<h3>Random Characters with same url</h3>
All character images share same url link(except their id number at the end) which makes them very easy to use in simple code that returns random url image.
This means that we can just change the number at the end of the url link to get random image.

<h4>First image in the list</h4>
Each image is stored in the same location(in charlib folder), changing the (1) value at the end of the url to other number gives you another image from the library.
https://raw.githubusercontent.com/Cal3y/fantasycharlib/refs/heads/main/charlib/charimg%20(1).png

<h4>Example use in code</h4>
Here is a quick example of a very simple random url code that returns random character image from library

<pre><code>
const randomCharImage = Math.floor(Math.random() * 139) + 1; // random image number between 1-190
const imageUrl = 'https://raw.githubusercontent.com/Cal3y/fantasycharlib/refs/heads/main/charlib/charimg%20(' + randomCharImage + ').png'; //create url string including random number
&lt;img src="${imageUrl}"&gt; //show image from created url string
</code></pre>
