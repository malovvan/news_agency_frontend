<template>
  <footer class="footer">
    <div class="footer__row">
      <div class="footer__content">
        Task to get into RTU IT LAB by Malov Ivan.
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "v-footer"
}
</script>

<style>

.footer {
  background-color: #f7f7f7;
  border-top: 1px solid #dfdfe6;


}

.footer__row {
  height: 95px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.footer__content {
  color: #00077b;
  font-size: 20px;
}

</style>