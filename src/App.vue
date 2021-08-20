<template>
<div class="topbar"></div>
<div class="row">
  <Picture />
  <Header />
</div>
<Content>
  <div class="summary col-xl-8 col-lg-8 col-md-8 col-sm-12 col-xs-12">
    <h2 class="section-title">PERSONAL SUMMARY</h2>
    <p>I am a highly motivated frontend engineer with 1+ years experience in building static & dynamic websites, single page applications (SPAs) and decentralized finance (DeFi) applications on the blockchain. I am a quick learner, I'm able to adapt to a new environment and work under pressure while liaising with other departments involved in development and meeting targets. I contribute extensively to team work and always display a willing and helpful manner. I am able to follow clear instructions, work unsupervised and work as a part of a team carrying out duties as required, however, I will ask for help and review when needed.
    </p>
  
    <h2 class="section-title">EXPERIENCE</h2>
    <p>
      <b>Kingdom Envoy (Religious Organization) February 2020 - present</b>: I volunteered for the role of webmaster to build a website for the church I fellowship with, working with a modified free website theme, but currently implementing a new design I made with FIGMA.<br>Tools & Technologies: <b>HTML, CSS, Bootstrap4, JavaScript, VueJS, PHP, NodeJS</b> <br>Roles: Webmaster • E-connect Member
    </p>
    <p>
      <b>ALX-Holberton Software Engineering</b>: In my first trimester, I succesfully completed a printf() function project in C as well as other modules and projects we were tasked to make.<br>Tools & Technologies: <b>HTML, CSS, JavaScript, C</b> <br>Roles: Software Engineer • Memeber (The Room)
    </p>
    <p>
      <b>HNG Internship August 2021</b>: Frontend Development track
    </p>
    <p>
      <b>Junior Developers Group March 2021 - present</b>: I work along in a SCRUM team, building our team page, team dashboard, sleep calculator, as well as other projects decided upon by us during Friday evening meetings.<br>Tools & Technologies: <b>HTML, CSS, JavaScript</b> <br>Roles: Frontend Developer • UI / UX Designer • Member
    </p>
    <p>
      <b>Binance 8weeks Africa Master Class Team Project (COINPOOL: Decentralized Crowd Lending) 31st January - 24th April, 2021</b>: On this, we (my team) worked on a crowd lending platform where people joined together in groups of ten or more and staked their assets (cryptocurrencies) , modeled after the traditional Osusu popular in Africa. <br>Tools & Technologies: <b>HTML, CSS, Bootstrap4, JavaScript, Web3.js, Solidity</b> <br>Roles in project: Frontend Developer • Backend Developer (Solidity) • UI / UX Designer
    </p>
  </div>
</Content>

<Content>
  <div class="row">
    <div class="location col-xl-4 col-lg-4 col-md-4 col-sm-12 col-xs-12">
      <h2 class="section-title">HOBBIES</h2>
        <p>Gaming</p>
        <p>Virtual Conferences & TED Talks</p>
        <p>Reading</p>
        <p><a href="https://discord.gg/3meUsdrER9">Southern Code</a>: Southern code is my own way of giving back to my locality(society) by guiding people on the web developer path using The Odin Project as preferred model</p>
      
      <h2 class="section-title">TOOLS & TECHNOLOGIES</h2>
        <ul>
          <li>HTML/CSS/JAVASCRIPT/VUEJS/SOLIDITY</li><br>
          <li>GITHUB/CODEPEN/REPLIT</li><br>
          <li>JIRA/TRELLO/CONFLUENCE/SLACK</li><br>
          <li>ADOBE XD/FIGMA</li><br>
          <li>ADOBE PHOTOSHOP</li><br>
          <li>MICROSOFT OFFICE</li><br>
          <li>VISUAL STUDIO</li><br>
          <li>VISUAL STUDIO CODE/REMIX IDE/BSC IDE</li><br>
          <li>GOOGLE ANALYTICS</li><br>
          <li>LIGHTHOUSE</li>
        </ul>
      
      <h2 class="section-title">CERTIFICATION AND AWARDS</h2>
        <ul>
          <li><p><b>B.Sc, Medical Biochemistry and Genetics</b><br>Delta State University, Abraka, Nigeria</p></li>
          <li><p><b>Certified Blockchain Developer</b> Certification from Binance verifiable on the <a href="https://drive.google.com/file/d/10_jDr3F6Jv20wIPB_rnaAbD5ctP_-Sgc/view">blockchain</a></p></li>
          <li><p><b>Certificate of participation</b> <a href="https://drive.google.com/file/d/10dxKMPpXiPRVVuqaweaupMrVxC5TuoxP/view?usp=drivesdk">TH.0 FINTECH ’21 HACKATHON</a></p></li>
        </ul>
    </div>
  </div>
</Content>
<div class="row">
  <div class="footer col-xl-12 col-lg-12 col-md-12 col-sm-12 col-xs-12">
    <p><a href="https://zuri.team/"><img class="footerimg" src="./assets/zuri.png"></a> <a href="https://ingressive.org/"><img class="footerimg" src="./assets/i4G.png"></a> <a href="https://internship.zuri.team/"><img class="footerimg" src="./assets/hng.png"></a></p>
  </div>
</div>
</template>

<script>
import Header from './components/Header.vue'
import Content from './components/Content.vue'
import Picture from './components/Picture.vue'

export default {
  name: 'App',
  components: { Header, Content, Picture }
}
</script>