<template>
  <div class="contact">
    <main>
      <h1>Contact Us!</h1>
        <div class="fcf-body">
          <!-- placeholder for a form component -->
                <div id="fcf-form">
              

                <form id="fcf-form-id" class="fcf-form-class" method="post" action="contact-form-process.php">
                    
                    <div class="fcf-form-group">
                        <label for="Name" class="fcf-label">Your name</label>
                        <div class="fcf-input-group">
                            <input type="text" id="Name" name="Name" class="fcf-form-control" required>
                        </div>
                    </div>

                    <div class="fcf-form-group">
                        <label for="Email" class="fcf-label">Your email address</label>
                        <div class="fcf-input-group">
                            <input type="email" id="Email" name="Email" class="fcf-form-control" required>
                        </div>
                    </div>

                    <div class="fcf-form-group">
                        <label for="Message" class="fcf-label">Your message</label>
                        <div class="fcf-input-group">
                            <textarea id="Message" name="Message" class="fcf-form-control" rows="6" maxlength="3000" required></textarea>
                        </div>
                    </div>

                    <div class="fcf-form-group">
                        <button type="submit" id="fcf-button" class="fcf-btn fcf-btn-primary fcf-btn-lg fcf-btn-block">Send Message</button>
                    </div>

                    <div class="fcf-credit" id="fcf-credit">
                    Simple HTML email form provided by: <a href="https://www.freecontactform.com" target="_blank">FreeContactForm.com</a>
                    </div>

                </form>
                </div>

            </div>
            
        
    </main>
    <footer class="footer">© [name of rightsholder or rightsholders] [publication year]: e.g.  © XYZ Press and contributors 2014</footer>
  </div>
</template>

<script>

</script>

<style>
.footer {
  position: relative;
  margin-right: 10%;
}
</style>