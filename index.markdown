---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---


<style>
li {
    padding: 0.25rem;
}

.album {
  min-height: 30rem; /* Can be removed; just added for demo purposes */
  padding-top: 3rem;
  padding-bottom: 3rem;
  background-color: #f7f7f7;
}

.card {
  float: left;
  width: 45%;
  padding: .75rem;
  margin-bottom: 2rem;
  border: 0;
}

.card > img {
  margin-bottom: .75rem;
}

.card-text {
  font-size: 85%;
}
</style>

<h2><u>Projects</u></h2>

<div class="album text-muted">
<div class="container">
<div class="row">
<div class="card">

<img alt="scratchpad image"
style="height: 280px; width: 100%; display: block;"
src="/images/scratchpad.png"
data-holder-rendered="true">

<p class="card-text">
<a href="https://scratch-pad-app.herokuapp.com/" target="_blank">Scratchpad App</a>
is a light-weight web application that allows you to type quick notes into the app.
<br/>
Dont fear - The app will auto-save your notes for you into the browser in case you 
lose connection or accidentally close the page.
</p>
<p class="card-text">
App is hosted on Heroku using Docker Containers to manage a lightweight .Net Core 3.1
site using jQuery to auto-save the scratchpad text. 
<a href="https://github.com/LuisFuentes/ScratchPadApp" target="_blank">Source</a>
</p>

</div>

<div class="card">
<img alt="dating app image"
style="height: 280px; width: 100%; display: block;"
src="/images/datingapp.jpg"
data-holder-rendered="true">

<p class="card-text">
A Dating App website created to learn more about Angular v8 & .NET Core.
</p>
<p class="card-text">
Currently supports user registration and login using JWT (JSON Web Tokens) to authenticate from Angular
client to .NET Core REST API.
<a href="https://github.com/LuisFuentes/DatingApp" target="_blank">Source</a>
</p>

</div>
</div>
</div>
</div>

<h2><u>
Experience
</u></h2>
<p>

<b>Software Engineer</b> - Aegis Treatment Centers, LLC.
<p><i>April 2014 - Present</i></p>

<ul><li>
.NET software development of Aegis Electronic Medical Records (PHASE) system used to  support over ten thousand active patients of the largest narcotics addiction treatment programs in California.

</li><li>
Designs new full stack software solutions including front-end user interface designs, database tables, views, & stored procedure designs, back-end business logic implementation, and integration of software for clinical staff users.

</li><li>
Maintains codebase and debugs problems submitted through the Aegis IT HelpDesk system. Manages code changes through JIRA and SVN version control

</li><li>
Provides daily on-call and email technical support to assist over 700 clinical staff at over 30 clinics throughout California.

</li></ul>
</p>

<p>

<b>Software Engineer</b> - UCLA, Department of Molecular and Medical Pharmacology
<p><i>September 2013 - February 2014</i></p>


<ul><li>
Development of a new
<a href="https://github.com/LuisFuentes/pyelixys"><i>Python web application</i></a>
to support
<a href="https://sofie.com/radiochemistry">Elixys</a>,
an autonomous radio-synthesizer device that performs complex combinations of  radiosynthesis of over 20 individual radioactive reagents.

</li><li>
Created shell & python scripts to perform automated testing to stress-test software & hardware.
</li></ul>
</p>