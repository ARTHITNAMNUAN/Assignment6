<template>
  <navbar />
  <section class="about">

        <h1 class="heading"> about <span>me</span> </h1>

        <div class="row">

            <div class="info-container">

                <h1>personal info</h1>

                <div class="box-container">

                    <div class="box">
                        <h3> <span>name : </span> Arthit Namnuan </h3>
                        <h3> <span>age : </span> 21 </h3>
                        <h3> <span>email : </span> arthit.namn@bumail.net </h3>
                        <h3> <span>address : </span> Phatunthani, Thailand 11110 </h3>
                    </div>

                    <div class="box">
                        <h3> <span>freelance : </span> available </h3>
                        <h3> <span>skill : </span> Full Stack Engineer </h3>
                        <h3> <span>experience : </span> 6 years </h3>
                        <h3> <span>language : </span> thai </h3>
                    </div>

                </div>

                <a href="/profilewithcss/files/resume.pdf" class="btn"> download CV <i class="fas fa-download"></i> </a>

            </div>

            <div class="count-container">

                <div class="box">
                    <h3>5+</h3>
                    <p>years of experience</p>
                </div>

                <div class="box">
                    <h3>10+</h3>
                    <p>happy clients</p>
                </div>

                <div class="box">
                    <h3>20+</h3>
                    <p>project completed</p>
                </div>

                <div class="box">
                    <h3>5+</h3>
                    <p>Certificates</p>
                </div>

            </div>

        </div>

    </section>

</template>

<script>
import Navbar from '../components/Navbar.vue'
export default {
  components: { Navbar },

}
</script>

<style>

</style>