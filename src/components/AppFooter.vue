<template>
  <footer class="footer">
    <div class="container">
      <div class="row">
        <div class="col-md-6">
          <div class="footer-logo">
            <img src="../assets/logoGgrifos.jpg" alt="Logo de la empresa">
          </div>
          <div class="footer-company">
            <h4>G Grifos</h4>
            <p>Ituzaingo, Buenos Aires</p>
          </div>
        </div>
        <div class="col-md-6">
          <div class="footer-social">
            <h4>Síguenos en redes sociales</h4>
            <div class="social-icons">
              <a href="#" class="social-icon"><i class="fab fa-facebook-f"></i></a>
              <a href="#" class="social-icon"><i class="fab fa-instagram"></i></a>
              <a href="#" class="social-icon"><i class="fab fa-whatsapp"></i></a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  // Componente del footer
};
</script>

<style scoped>
.footer {
  background-color: #f8f8f8;
  padding: 20px 0;
}

.footer-logo img {
  max-width: 150px;
}

.footer-company h4 {
  margin-top: 10px;
}

.footer-social h4 {
  margin-bottom: 10px;
}

.social-icons .social-icon {
  display: inline-block;
  margin-right: 10px;
  font-size: 24px;
  color: #333;
}

.social-icons .social-icon:hover {
  color: #007bff;
}
</style>
