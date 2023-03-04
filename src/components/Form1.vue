<template>
    <div>
        <b-form>
          <b-form-group id="input-group-1"
          label="Name:"
          label-for="input-1">
            <b-form-input id="input-1" v-model="form.name" required></b-form-input>
          </b-form-group>
          <b-button type="submit" variant="primary">Submit</b-button>
          <b-button type="reset" variant="danger">Reset</b-button>
        </b-form>
    </div>
</template>

<script>
export default {
  name: 'form-1',
  props: {
    msg: String
  },
  data() {
    return {
      form: {
        name: ''
      }
    }
  }
}
</script>
