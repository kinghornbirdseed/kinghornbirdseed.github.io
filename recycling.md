---
title: Recycling
---

<style>/* reset */
#fs-frm input,
#fs-frm select,
#fs-frm textarea,
#fs-frm fieldset,
#fs-frm optgroup,
#fs-frm label,
#fs-frm #card-element:disabled {
  font-family: inherit;
  font-size: 100%;
  color: inherit;
  border: none;
  border-radius: 0;
  display: block;
  width: 100%;
  padding: 0;
  margin: 0;
  -webkit-appearance: none;
  -moz-appearance: none;
}
#fs-frm label,
#fs-frm legend,
#fs-frm ::placeholder {
  font-size: .825rem;
  margin-bottom: .5rem;
  padding-top: .2rem;
  display: flex;
  align-items: baseline;
}

/* border, padding, margin, width */
#fs-frm input,
#fs-frm select,
#fs-frm textarea,
#fs-frm #card-element {
  border: 1px solid rgba(0,0,0,0.2);
  background-color: rgba(255,255,255,0.9);
  padding: .75em 1rem;
  margin-bottom: 1.5rem;
}
#fs-frm input:focus,
#fs-frm select:focus,
#fs-frm textarea:focus {
  background-color: white;
  outline-style: solid;
  outline-width: thin;
  outline-color: gray;
  outline-offset: -1px;
}
#fs-frm [type="text"],
#fs-frm [type="email"] {
  width: 100%;
}
#fs-frm [type="button"],
#fs-frm [type="submit"],
#fs-frm [type="reset"] {
  width: auto;
  cursor: pointer;
  -webkit-appearance: button;
  -moz-appearance: button;
  appearance: button;
}
#fs-frm [type="button"]:focus,
#fs-frm [type="submit"]:focus,
#fs-frm [type="reset"]:focus {
  outline: none;
}
#fs-frm [type="submit"],
#fs-frm [type="reset"] {
  margin-bottom: 0;
}
#fs-frm select {
  text-transform: none;
}

#fs-frm [type="checkbox"] {
  -webkit-appearance: checkbox;
  -moz-appearance: checkbox;
  appearance: checkbox;
  display: inline-block;
  width: auto;
  margin: 0 .5em 0 0 !important;
}

#fs-frm [type="radio"] {
  -webkit-appearance: radio;
  -moz-appearance: radio;
  appearance: radio;
}

/* address, locale */
#fs-frm fieldset.locale input[name="city"],
#fs-frm fieldset.locale select[name="state"],
#fs-frm fieldset.locale input[name="postal-code"] {
  display: inline;
}
#fs-frm fieldset.locale input[name="city"] {
  width: 52%;
}
#fs-frm fieldset.locale select[name="state"],
#fs-frm fieldset.locale input[name="postal-code"] {
  width: 20%;
}
#fs-frm fieldset.locale input[name="city"],
#fs-frm fieldset.locale select[name="state"] {
  margin-right: 3%;
}
</style>
# Glass Recycling Collection Request Form

Please clean all bottles and jars before leaving for collection. Please put your recycling in 'bag for life' size carrier bags and leave on your doorstep at the collection time. You can leave your donation underneath the bag on collection day or if you prefer you can pay through an online payment link (Stripe). The suggested donation per bag is £2.50. Please enter how many bags you will leave out in the box provided below.

<form id="fs-frm" name="recycling" action="https://formspree.io/f/mzbordvz" method="post">

    <label for="Name">Name</label>

  <input type="text" name="Name" id="Name" placeholder="Enter your name" required="">
    <label for="Email">Email Address</label>
    <input type="Email" name="_replyto" id="Email" placeholder="email@domain.tld" required>
    <label for="Address">Collection Address</label>
    <textarea rows="5" name="Address" id="Address" placeholder="" required=""></textarea>
    <input type="hidden" name="_subject" id="email-subject" value="Recycling Collection Form Submission">
<label for="quantity">Number of Bags</label>
<input type="number" id="quantity" name="quantity" min="1" max="200" value="1">
  <input type="submit" value="Submit Collection Request">
</form>

I will email back with details of collection (check your spam folder!).
Thank you for you support.
