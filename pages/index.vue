<template>
<vue-loop :full="true" :horizontal="false">
  <div class="container">
    <div class="me">
    </div>
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
    <div class="skills">
    </div>
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
    <div class="dream">
    </div>
    <section class="part3">
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
    <div class="contact">
    </div>
    <section class="part4">
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
</vue-loop>
</template>
<script>
// import VueLoop from 'vue-loop'
import VueScrollTo from 'vue-scrollto'

export default {
  components: {
    // VueLoop
    VueScrollTo
  },
  head () {
    return {
      title: `Mathieu Anderson`
    }
  }
}
</script>

<style scoped>
.me, .skills, .dream, .contact {
}

.part1, .part2, .part3, .part4
{
  padding: 1em;
  background-color: #EDF2F4;
}

.part1
{
margin-top: -1em;
margin-bottom: 1em;
}

.part2
{
margin-top: 1em;
margin-bottom: 1em;
}

.part3
{
margin-top: 1em;
margin-bottom: 1em;
}

.part4
{
margin-top: 1em;
margin-bottom: -1em;
}

.title
{
  color: #2B2D42;
  font-weight: 600;
  margin-bottom: -0.5em;
}

.info
{
  font-weight: 300;
  color: #D90429;
}

.button
{
  margin-top: 50px;
}
</style>
