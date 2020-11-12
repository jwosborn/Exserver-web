<template>
  <div class="section columns wrapper">
    <div class="column select is-rounded is-large">
      <select class="column select" name="exercise">
        <option
          value="exercise"
          v-for="(exercise, index) in exercises"
          :key="index"
        >
          {{ exercise }}
        </option>
      </select>
    </div>
    <div class="column select">
      <select name="colors">
        <option value="color" v-for="(color, index) in colors" :key="index">{{
          color
        }}</option>
      </select>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      exercises: [
        "Resistor",
        "Resistor-duo",
        "Gigasecond",
        "RNA-Transcription",
        "Space-Age"
      ],
      colors: [
        "black",
        "brown",
        "red",
        "orange",
        "yelow",
        "green",
        "blue",
        "violet",
        "grey",
        "white"
      ],
      firstParam: ""
    };
  }
};
</script>
<style></style>
