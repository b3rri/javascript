# JavaScript
- HTML structure

```sh
<html>
<body>
<h2>My First JavaScript</h2>

Write you stuff here.

</body>
</html> 

```
- Button

```sh
<button type="button"
onclick="document.getElementById('demo').innerHTML = Date()">
Click me to display Date and Time.</button>
```

- Image
```sh
<img src="pic_trulli.jpg" alt="Trulli" width="500" height="333">
```
- Table
```sh
<table>
  <tr>
    <th>Company</th>
    <th>Contact</th>
    <th>Country</th>
  </tr>
  <tr>
    <td>Alfreds Futterkiste</td>
    <td>Maria Anders</td>
    <td>Germany</td>
  </tr>
  <tr>
    <td>Centro comercial Moctezuma</td>
    <td>Francisco Chang</td>
    <td>Mexico</td>
  </tr>
</table>
```
- List
```sh
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>

```


- JavaScript Text
```sh
<script>
document.getElementById("demo").innerHTML = "Hello JavaScript!";
</script>

```


- Color
```sh
<h1 style="color:Tomato;">Hello World</h1>
<p style="color:DodgerBlue;">Lorem ipsum...</p>
<p style="color:MediumSeaGreen;">Ut wisi enim...</p>

```
- Attributes
```sh
<a href="https://www.w3schools.com">Visit W3Schools</a>

```



- Videos
```sh
<video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4">
  <source src="movie.ogg" type="video/ogg">
</video>

```


- Audio
```sh
<audio controls autoplay>
  <source src="horse.ogg" type="audio/ogg">
  <source src="horse.mp3" type="audio/mpeg">
</audio>

```

- Canvas
```sh
<canvas id="myCanvas" width="200" height="100" style="border:1px solid #000000;">
</canvas>

```

- Formatting
```sh
<p><b>This text is bold</b></p>
<p><i>This text is italic</i></p>
<p>This is<sub> subscript</sub> and <sup>superscript</sup></p>

<b> - Bold text
<strong> - Important text
<i> - Italic text
<em> - Emphasized text
<mark> - Marked text
<small> - Smaller text
<del> - Deleted text
<ins> - Inserted text
<sub> - Subscript text
<sup> - Superscript text

```

- Elements
```sh
<h1>My First Heading</h1>
<p>My first paragraph.</p>

```

- Classes
```sh
<div class="city">
<h2>London</h2>
<p>London is the capital of England.</p>
</div> 

<div class="city">
<h2>Paris</h2>
<p>Paris is the capital of France.</p>
</div>

<div class="city">
<h2>Tokyo</h2>
<p>Tokyo is the capital of Japan.</p>
</div>


```

- Symbols
```sh
<p>I will display &euro;</p>
<p>I will display &#8704;</p>
<p>I will display &#8721;</p>

```

- Responsive Images that change depending on the browser width
```sh
<picture>
  <source srcset="img_smallflower.jpg" media="(max-width: 600px)">
  <source srcset="img_flowers.jpg" media="(max-width: 1500px)">
  <source srcset="flowers.jpg">
  <img src="img_flowers.jpg" alt="Flowers" style="width:auto;">
</picture>
