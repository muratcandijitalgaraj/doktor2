<template>
  <div>
    <h3>Randevu Al</h3>
    <div class="ortala">
      <div>
        <label for="example-datepicker">Tarih seç</label>
        <b-form-datepicker
          id="example-datepicker"
          v-model="value"
          class="mb-2 datePicker"
        ></b-form-datepicker>
        <p class="space">Buraya saat slot gelecek</p>
        <b-row>
          <b-col md="auto">
            <b-time v-model="value" locale="en" @context="onContext"></b-time>
          </b-col>
          <b-col>
            <p></p>
            <pre class="small">{{ context }}</pre>
          </b-col>
        </b-row>
        <p class="space">Buraya saat slot gelecek</p>
      </div>
      <div>
        <b-form-textarea
          id="textarea"
          v-model="text"
          placeholder="Mesajınız (isterseniz)"
          rows="3"
          max-rows="6"
        ></b-form-textarea>

        <pre class="mt-3 mb-0">{{ text }}</pre>
      </div>
      <!-- Plain mode -->
      <b-form-file v-model="file2" class="mt-3 space" plain></b-form-file>
      <b-button class="space" variant="success">Randevuyu onayla</b-button>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
/* .datePicker {
} */
.ortala {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.space {
  margin: 1em;
}
</style>
