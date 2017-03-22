<template>
  <div class="container">
    <a name="start"></a>
    <section class="part1">
      <h1 class="title">
        Mathieu Anderson
      </h1>
      <h2 class="info">
        is a web developer.
      </h2>
      <p>
        He really should not speak of himself in the third person, though.
      </p>
    </section>
    <section class="part2">
      <h1 class="title">
        My journey
      </h1>
      <h2 class="info">
        through code.
      </h2>
      <p>
        Here is a fancy table of my skills with a timeline of when and how I learned them, as well as related projects.
      </p>
      <p>
        Here is a fancy table of my skills with a timeline of when and how I learned them, as well as related projects.
      </p>
      <p>
        Here is a fancy table of my skills with a timeline of when and how I learned them, as well as related projects.
      </p>
      <p>
        Here is a fancy table of my skills with a timeline of when and how I learned them, as well as related projects.
      </p>
      <p>
        Here is a fancy table of my skills with a timeline of when and how I learned them, as well as related projects.
      </p>
      <p>
        Here is a fancy table of my skills with a timeline of when and how I learned them, as well as related projects.
      </p>
      <p>
        Here is a fancy table of my skills with a timeline of when and how I learned them, as well as related projects.
      </p>
      <p>
        Here is a fancy table of my skills with a timeline of when and how I learned them, as well as related projects.
      </p>
    </section>
    <section class="part2">
      <h1 class="title">
        I am looking for
      </h1>
      <h2 class="info">
        truth... and a job.
      </h2>
      <p>
        I will detail my idal job here. Damn this is hard
      </p>
    </section>
    <section class="part3">
      <h1 class="title">
        Find me
      </h1>
      <h2 class="info">
        everywhere!
      </h2>
      <p>
        <a name="contact"></a>
        All my social links and my CV!
      </p>
    </section>
  </div>
</template>
<script>
export default {
  data ({ req }) {
    return {
      name: req ? 'server' : 'client'
    }
  },
  head () {
    return {
      title: `About Page (${this.name}-side)`
    }
  }
}
</script>

<style scoped>
.title
{
  margin-top: 50px;
}
.info
{
  font-weight: 300;
  color: #9aabb1;
  margin: 0;
  margin-top: 10px;
}
.button
{
  margin-top: 50px;
}
</style>
