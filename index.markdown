---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
<!-- modify this form HTML and place wherever you want your form -->
To order, please fill in your details below.

<form
  action="https://formspree.io/f/mnqwnowg"
  method="POST"
>
  <label for="email">Your email:&nbsp;&nbsp;&nbsp;</label>
  <input type="email" name="_replyto" required>
  <br>
  <label for="name">Your name:&nbsp;&nbsp;&nbsp;</label>
  <input type="text" id="name" name="name" required><br>
  <label for="address">Your address:</label>
  <textarea id="address" name="address" rows="5" cols="50" required>
  </textarea><br>
  Please tick the boxes to indicate the type of seed you desire. <br>
  Fill in the boxes on the right to indicate the amount of each type of seed in kilograms.<br>
  <input type="checkbox" id="mixed" name="mixed" value="Mixed Seed">
  <label for="mixed">Mixed Seed</label>
   <input type="number" id="quantitym" name="quantitym" min="1" max="10" step="0.5">
  <label for="quantitym">Amount of Mixed Seed (kg)</label>
 
  <br>
  <input type="checkbox" id="peanuts" name="peanuts" value="Peanuts">
  <label for="peanuts">Peanuts &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</label>

  <input type="number" id="quantityp" name="quantityp" min="1" max="10" step="0.5">
  <label for="quantityp">Amount of Peanuts (kg)</label>
  <br>
  <button type="submit">Send</button>
  
  I will email back with details of payment and delivery(check your spam folder!)
</form>