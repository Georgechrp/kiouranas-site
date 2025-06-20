---
layout: default
title: Elements Reference
permalink: /elements/
---

<section class="post">
  <header class="major">
    <h1>Elements<br />Reference</h1>
  </header>

  <!-- Text stuff -->
  <h2>Text</h2>
  <p>This is <b>bold</b> and this is <strong>strong</strong>. This is <i>italic</i> and this is <em>emphasized</em>.
  This is <sup>superscript</sup> text and this is <sub>subscript</sub> text.
  This is <u>underlined</u> and this is code: <code>for (;;) { ... }</code>.
  Finally, this is a <a href="#">link</a>.</p>
  <hr />
  <h2>Heading Level 2</h2>
  <h3>Heading Level 3</h3>
  <h4>Heading Level 4</h4>
  <h5>Heading Level 5</h5>
  <h6>Heading Level 6</h6>
  <hr />
  <header>
    <h2>Heading with a Subtitle</h2>
    <p>Lorem ipsum dolor sit amet nullam id egestas urna aliquam</p>
  </header>
  <p>Nunc lacinia ante nunc ac lobortis...</p>
  <hr />

  <!-- Lists -->
  <h2>Lists</h2>
  <div class="row">
    <div class="col-6 col-12-small">
      <h3>Unordered</h3>
      <ul>
        <li>Dolor pulvinar etiam.</li>
        <li>Sagittis lorem eleifend.</li>
        <li>Felis feugiat dolore viverra.</li>
        <li>Dolor pulvinar etiam.</li>
      </ul>
      <h3>Alternate</h3>
      <ul class="alt">
        <li>Dolor pulvinar etiam etiam.</li>
        <li>Sagittis adipiscing eleifend.</li>
        <li>Felis enim dolore viverra.</li>
        <li>Dolor pulvinar etiam etiam.</li>
      </ul>
    </div>
    <div class="col-6 col-12-small">
      <h3>Ordered</h3>
      <ol>
        <li>Dolor pulvinar etiam.</li>
        <li>Etiam vel felis at viverra.</li>
        <li>Felis enim feugiat magna.</li>
        <li>Etiam vel felis nullam.</li>
        <li>Felis enim et tempus.</li>
      </ol>

      <h3>Icons</h3>
      <ul class="icons">
        <li><a href="#" class="icon brands fa-twitter"><span class="label">Twitter</span></a></li>
        <li><a href="#" class="icon brands fa-facebook-f"><span class="label">Facebook</span></a></li>
        <li><a href="#" class="icon brands fa-instagram"><span class="label">Instagram</span></a></li>
        <li><a href="#" class="icon brands fa-github"><span class="label">GitHub</span></a></li>
      </ul>
    </div>
  </div>

  <h3>Definition</h3>
  <dl>
    <dt>Item 1</dt>
    <dd><p>Λίγο lorem ipsum</p></dd>
    <dt>Item 2</dt>
    <dd><p>Λίγο ακόμα lorem ipsum</p></dd>
  </dl>

  <!-- Buttons -->
  <h2>Buttons</h2>
  <ul class="actions">
    <li><a href="#" class="button primary">Primary</a></li>
    <li><a href="#" class="button">Default</a></li>
  </ul>

  <!-- Blockquote -->
  <h2>Blockquote</h2>
  <blockquote>Fringilla nisl. Donec accumsan interdum nisi...</blockquote>

  <!-- Tables -->
  <h2>Table</h2>
  <div class="table-wrapper">
    <table>
      <thead>
        <tr><th>Name</th><th>Description</th><th>Price</th></tr>
      </thead>
      <tbody>
        <tr><td>Item 1</td><td>Sample description</td><td>29.99</td></tr>
        <tr><td>Item 2</td><td>Another item</td><td>19.99</td></tr>
      </tbody>
      <tfoot>
        <tr><td colspan="2"></td><td>49.98</td></tr>
      </tfoot>
    </table>
  </div>

  <!-- Form -->
  <h2>Form</h2>
  <form method="post" action="#">
    <div class="row gtr-uniform">
      <div class="col-6 col-12-xsmall">
        <input type="text" name="name" placeholder="Name" />
      </div>
      <div class="col-6 col-12-xsmall">
        <input type="email" name="email" placeholder="Email" />
      </div>
      <div class="col-12">
        <textarea name="message" placeholder="Message" rows="6"></textarea>
      </div>
      <div class="col-12">
        <ul class="actions">
          <li><input type="submit" value="Send Message" class="primary" /></li>
          <li><input type="reset" value="Reset" /></li>
        </ul>
      </div>
    </div>
  </form>

  <!-- Images -->
  <h2>Images</h2>
  <span class="image fit"><img src="/images/pic01.jpg" alt="" /></span>

  <!-- Box -->
  <h2>Box</h2>
  <div class="box">
    <p>Ένα παράδειγμα κουτιού (box).</p>
  </div>

  <!-- Preformatted -->
  <h2>Preformatted</h2>
  <pre><code>i = 0;
while (!deck.isInOrder()) {
    print 'Iteration ' + i;
    deck.shuffle();
    i++;
}
print 'It took ' + i + ' iterations to sort the deck.';</code></pre>
</section>
