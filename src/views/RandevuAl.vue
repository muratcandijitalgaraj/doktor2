<template>
  <div>
    <h3>Randevu Al</h3>
    <div class="ortala">
      <h3>Tarih seç</h3>
      <div>
        <label for="example-datepicker">Choose a date</label>
        <b-form-datepicker
          id="example-datepicker"
          v-model="value"
          class="mb-2 datePicker"
        ></b-form-datepicker>
        <p>Buraya saat slot gelecek</p>
        <b-row>
          <b-col md="auto">
            <b-time v-model="value" locale="en" @context="onContext"></b-time>
          </b-col>
          <b-col>
            <p></p>
            <pre class="small">{{ context }}</pre>
          </b-col>
        </b-row>
        <p>Buraya saat slot gelecek</p>
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
      <b-form-file v-model="file2" class="mt-3" plain></b-form-file>
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
</style>
