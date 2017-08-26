+++
date = "2017-03-21T19:44:08-03:00"
title = "Contato"

+++
<div class="row">
  <div class="col-md-6 col-sm-6">
    <div id="contact_form">
      <p>Entre em contato conosco</p>
      <div class="contact-phone-header visible-xs-block">
        <div>
          <p class="visible-xs-block"><strong>Por telefone:</strong><br/><a href="tel:+55 21 97236-7871">+55 21 97236-7871</a></p>
          <p class="visible-xs-block"><strong>Whatsapp:</strong><br/><a href="https://api.whatsapp.com/send?phone=5521972367871"><i class="fa fa-whatsapp fa-4" aria-hidden="true"></i></a></p>
          <p class="visible-xs-block"><strong>Ou envie-nos uma mensagem:</strong></p>
        </div>
      </div>
      <div>
        <form role="form" id="contactForm" method="POST">
          <div class="form-group">
            <label for="name">Nome</label>
            <input type="text" class="form-control" id="name" name="name" placeholder="Nome" required>
          </div>
          <div class="form-group">
            <label for="email">Email</label>
            <input type="email" class="form-control" id="email" name="email" placeholder="Email" required>
          </div>
          <div class="form-group">
            <label for="phone-number">Telefone de contato</label>
            <input type="text" class="form-control" id="phone-number" name="phone-number" placeholder="Celular">
          </div>
          <div class="form-group hidden">
            <input type="text" class="form-control" id="subject" name="subject" placeholder="Assunto" value="Contato">
          </div>
          <div class="form-group">
            <label for="message">Mensagem</label>
            <textarea rows="10" cols="100" class="form-control" id="message" name="message" placeholder="Mensagem" required></textarea>
          </div>
          <button type="submit" id="feedbackSubmit" class="btn btn-primary btn-lg" style="display: block; margin-top: 10px;">Enviar Mensagem</button>
        </form>
      </div>
    </div>
  </div>
  <hr class="visible-xs-block"/>
  <div class="col-md-6 col-sm-6">
    <div class="contact-phone-header visible-md-block visible-lg-block">
      <div>
        <p class="hidden-xs"><strong>Telefone:</strong><br>+55 21 97236-7871</p>
        <p class="visible-xs-block"><strong>Telefone:</strong><br><a href="tel:+55 21 97236-7871">+55 21 97236-7871</a></p>
        <p class="visible-xs-block"><br/><a href="https://api.whatsapp.com/send?phone=5521972367871"><i class="fa fa-whatsapp fa-4" aria-hidden="true"></i></a></p>
      </div>
    </div>
    <hr class="visible-md-block visible-lg-block" />
    <div>
      <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3673.494643679893!2d-43.186798784407756!3d-22.968831384980284!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x9bd55a8384b341%3A0x4a033fc41a586c75!2sMarcela+Monnerat+-+Est%C3%A9tica+Avan%C3%A7ada!5e0!3m2!1sen!2sus!4v1501552068644" width="600" height="450" frameborder="0" allowfullscreen></iframe>
    </div>
  </div>
</div>
<script src="/js/send_contact_form.js"></script>
