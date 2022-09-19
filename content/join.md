+++
title = "Join"
description = "Join Semata Wayang"
date = "2022-09-19"
author = "Semata Wayang"
+++

<form method="post" action="https://api.imajiugm.com/post/form">
  <div class="form-group row post-item">
    <label for="name" class="intro">Nama</label>
    <div class="intro">
      <input id="name" name="name" placeholder="e.g. Luis" type="text" required="required" class="form-control">
    </div>
  </div>
  <div class="form-group row post-item">
    <label for="batch" class="intro">Angkatan</label>
    <div class="intro">
      <input id="batch" name="batch" placeholder="e.g. 99" type="text" required="required" class="form-control">
    </div>
  </div>
  <div class="form-group row post-item">
    <label for="number" class="intro">Nomor WhatsApp</label>
    <div class="intro">
      <input id="number" name="number" type="text" required="required" class="form-control">
    </div>
  </div>
  <div class="form-group row nav">
    <div class="offset-4 col-8">
      <button name="submit" type="submit">Kirim</button>
    </div>
  </div>
</form>
