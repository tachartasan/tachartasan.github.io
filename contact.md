---
layout: page
title: Cuir Fios
permalink: /cuir-fios/
---

<form action="https://getsimpleform.com/messages?form_api_token=a7f1c2224c700f1d8c64896757363f9a" method="post">
  <!-- the redirect_to is optional, the form will redirect to the referrer on submission -->
  <input type='hidden' name='redirect_to' value='{{ site.baseurl}}' />
  <!-- all your input fields here.... -->
  <div class="form-group">

    <label for="name">D' ainm</label>
    <input class="form-control" type='text' id='name' required />

    <label for="email">Do sheòladh puist-d</label>
    <input class="form-control" type='text' id='email' required />

    <label for="eventname">Ainm an Tachartais</label>
    <input class="form-control" type='text' id='eventname' required />

    <div class="row">
      <div class="col">
        <label for="date">Ceann-latha</label>
        <input class="form-control" type='text' id='date' required />
      </div>
      <div class="col">
        <label for="time">Àm tòisichidh</label>
        <input class="form-control" type='text' id='time' required />
      </div>
    </div>

    <label for="address">Seòladh</label>
    <input class="form-control" type='text' id='address' required />

    <label for="website">Làrach-lìn an tachartais / nan eagraichean</label>
    <input class="form-control" type='text' id='website' />

    <label for="twitter">Duilleag Twitter an tachartais / nan eagraichean</label>
    <input class="form-control" type='text' id='twitter' />

    <label for="facebook">Duilleag Facebook an tachairtais / nan eagraichean</label>
    <input class="form-control" type='text' id='facebook' />

    <label for="description">Tuairisgeul</label>
    <input class="form-control" type='textarea' id='description' required />

  </div>
  <input class="btn btn-primary" type='submit' value='Cuir a-steach' />
</form>
