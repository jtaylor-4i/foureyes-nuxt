<template lang="pug">
  v-form(v-model="valid")
    v-container
      v-row
        v-col(
          cols="12"
          md="4"
        )
          v-text-field(
            v-model="firstname"
            :rules="nameRules"
            :counter="10"
            label="First Name"
            required
          )
</template>
