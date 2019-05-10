<template>
  <div id="Projects" class="section white">
    <div class="container">
      <div class="row">
        <h2 class="header col s12 indigo-text center sec-head">
          My Projects
          <small>Here's a sneak peak into some of the projects I've enjoyed working on.</small>
        </h2>
      </div>

      <div class="row no-margin">
        <div class="col s12 m6 center">
          <img class="responsive-img" src="../assets/imgs/webshop.jpg" alt="webshop">
        </div>
        <div class="col s12 m6">
          <h4 class="blue-text">Webshop</h4>
          <p>
            Nicolas cage is an example of a webshop design, that features a custom responsive design.
            It is built from scratch with html, css.
            Nicolas cage is a multiple pages website that contains:
            Frontpage - Product view page - Product detail page - Admin login page.
          </p>
        </div>
      </div>
      <hr>
      <div class="row no-margin">
        <div class="col s12 m6 center">
          <img class="responsive-img" src="../assets/imgs/donate.jpg" alt="Donate DK">
        </div>
        <div class="col s12 m6">
          <h4 class="blue-text">Donate DK</h4>
          <p>
            A responsive website that aim to raise awareness and increase the number of organ donors in Denmark.
            Donate DK was created and designed by Google Material Design
            Exampels of some used elements: Cards to present the stories, modal for showing full stories, and form elements like: Checkboxes and datepicker.
          </p>
        </div>
      </div>
      <hr>
      <div class="row no-margin">
        <div class="col s12 m6 center">
          <img class="responsive-img" src="../assets/imgs/info.jpg" alt="Infographic">
        </div>
        <div class="col s12 m6">
          <h4 class="blue-text">Infographic</h4>
          <p>
            A nice, quick, and clear representation of information about Black friday 2017 in Denmark.
            It was first designed using illustrator to be used as a printed infographic material.
            Then, the design has been changed a bit to be converted into an interactive website.
            The website is built with sass, with some js features like: Scrollify
            to make the nice and smooth scroll between the tab’s content.
          </p>
        </div>
      </div>
      <hr>
      <div class="row no-margin">
        <div class="col s12 m6 center">
          <img class="responsive-img" src="../assets/imgs/proj-seo.jpg" alt="SEO-info">
        </div>
        <div class="col s12 m6">
          <h4 class="blue-text">SEO-info</h4>
          <p>
            Seo-info is an informative one page website, created with the use of google Materialize to explain Search Engine Optimization, its key elements and why it is important when developing web sites.
            on-page SEO has been applied to the website and it is connected to Google Analytics to track visitors.
          </p>
          <a href="http://seo-info.000webhostapp.com/" target="_blank">Preview</a>
        </div>
      </div>
      <hr>
      <div class="row no-margin">
        <div class="col s12 m6 center">
          <img class="responsive-img" src="../assets/imgs/lunar.jpg" alt="Lunar Minds">
        </div>
        <div class="col s12 m6">
          <h4 class="blue-text">Lunar Minds</h4>
          <p>
            An interactive, responsive website for kids to educate them about the solar system.
            The website is a single page site, yet it supports multiple pages of content using some CSS techniques to minimize HTTP requests.
            Lunar minds is a responsive website
          </p>
          <a href="http://lunarminds.000webhostapp.com/" target="_blank">Preview</a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import webshop from "../assets/imgs/webshop.jpg";
import donate from "../assets/imgs/donate.jpg";
import info from "../assets/imgs/info.jpg";
import lunar from "../assets/imgs/lunar.jpg";
import projSeo from "../assets/imgs/proj-seo.jpg";
export default {
  name: "Projects"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
