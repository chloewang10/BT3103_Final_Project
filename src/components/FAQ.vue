<template>
  <div class="float-container">
    <div id="faqright">
      <p id="other">Other burning questions unanswered?</p>
      <router-link id="contactlinkfaq" to="/ContactUs" exact
        >Click here to contact us now!</router-link
      >
    </div>
    <Header></Header>
    <h1>Frequently Asked Questions</h1>
    <div id="questions">
      <h3 id="q">How does this platform work?</h3>
      <p id="a">
        Tuition Connect serves as a platform for Tutors and Students to connect
        easily, allowing for easy communication between both parties. Students
        can scroll through the profiles of Tutors and find the best suited tutor
        for them. Our site also allows students to review the tutors, allowing
        future students to find tutors better suited for them.
      </p>
      <br />
      <h3 id="q">Do we make payment for lessons through this site?</h3>
      <p id="a">
        At the moment, Tuition Connect are not accepting any payment through this
        site. In the future, we are looking into offering more functions for our
        users.
      </p>
    </div>
  </div>
</template>

<script>
import Header from "./Header.vue";

export default {
  components: {
    Header,
  },
};
</script>

<style scoped>

h1 {
  font-weight: 900;
  font-size: 50px;
  color: #388087;
  position: relative;
  left: 70px;
  text-align: left;
}
.float-container {
  border: 3px solid #fff;
  padding: 10px;
  background-color: #FFFFFF;
  overflow: hidden;
  height: 100vh;
}
#faqright {
  width: 20%;
  float: right;
  padding: 10px;
  text-align: center;
  vertical-align: middle;
  height: 100%;
  background-color: #BADFE7;
}

#q{
  color: white;
  font-size: 20px;
}

#a{
  color: white;
  font-size: 16px;
}

#questions {
  width: 70%;
  float: left;
  padding: 10px;
  margin-right: 20px;
  text-align: center;
  vertical-align: middle;
  height: 80%;
  background-color: #6FB3B8;
  border-radius: 25px;
  position: relative;
  top: 20px;
}

#other {
  color: white;
  top: 240px;
  position: relative;
font-style: normal;
font-weight: bold;
font-size: 24px;
line-height: 28px;
}

#contactlinkfaq:hover {
  color: #388087;
}

#contactlinkfaq {
  text-decoration: none;
  color: white;
  text-align: center;
  top: 250px;
  position: relative;
font-style: normal;
font-weight: bold;
font-size: 24px;
line-height: 28px;
}
</style>