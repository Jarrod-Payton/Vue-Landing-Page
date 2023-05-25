<template>
  <div class="page">
    <div class="row p-3">
      <div class="col-12 text-center header">
        <div class="picture">
          <img class="profile-pic" src="../assets/img/Head-Only.jpg" alt="Proffessional Photo" />
        </div>
        <h1 class="name font">Jarrod P</h1>
        <h2 class="sub-heading font">🪙 Striving Entrepreneur / Developer 💻</h2>
      </div>
    </div>
    <div class="links row">
      <!-- <div class="col-12 heading">Personal</div> -->
      <a href="https://www.jarrodp.dev" target="_blank">
        <button class="col-12 link-btn">Landing Page</button>
      </a>
      <a href="https://www.linkedin.com/in/jarrodpayton" target="_blank">
        <button class="col-12 link-btn" action="https://www.w3docs.com/" target="_blank">
          LinkedIn
        </button>
      </a>
      <a href="https://www.instagram.com/jarrod_l_p/" target="_blank">
        <button class="col-12 link-btn">Instagram</button>
      </a>
      <a
        href="https://www.snapchat.com/add/jarrodlpay?share_id=DGUgNTkFk9E&locale=en-US"
        target="_blank"
      >
        <button class="col-12 link-btn">Snap</button>
      </a>
      <a href="https://github.com/Jarrod-Payton" target="_blank">
        <button class="col-12 link-btn">Github</button>
      </a>
      <!-- <div class="col-12 heading">Professional</div> -->
    </div>
  </div>
</template>
<script>
export default {
  name: 'LinkTree'
}
</script>
<style scoped>
.page {
  height: 100vh;
  overflow-x: hidden;
  background: linear-gradient(to bottom, rgba(0, 0, 0, 0.3) 0%, rgba(0, 0, 0, 0.7) 75%, #000 100%),
    url('../assets/img/bg-masthead.jpg');
  background-position: center;
  background-repeat: no-repeat;
  background-attachment: scroll;
  background-size: cover;
}

.profile-pic {
  width: 100px;
  height: 100px;
  border-radius: 50%;
  margin-bottom: 1rem !important;
  margin-top: 1rem !important;
}
.name {
  font-size: 20px;
  color: white;
  font-style: oblique;
}
.sub-heading {
  font-size: 14px;
  color: white;
}
.font {
  font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu,
    Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}

.links {
  margin: 2rem 10px 0px;
  margin-top: 2rem;
}
.heading {
  text-align: center;
  margin: 1rem;
  color: white;
  font-size: 16px;
  font-weight: bolder;
}
.link-btn {
  margin: 0px 0px 10px;
  padding: 10px 20px;
  background-color: gray;
  color: #ffffff;
  border-radius: 10px;
  box-shadow: 0 2px 4px rgba(59, 59, 59, 0.308);
  text-decoration: none;
  font-weight: bold;
  opacity: 0.6;
}

a {
  margin: 0px;
  padding: 0px;
  text-decoration: none;
  color: #ffffff;
  font-weight: bold;
  background-color: none;
}
a:visited {
  margin: 0px;
  padding: 0px;
  text-decoration: none;
  color: #ffffff;
  font-weight: bold;
  background-color: none;
}

/* Optional: Hover and focus styles */
.link-btn:hover,
.link-btn:focus {
  opacity: 1;
}
</style>
