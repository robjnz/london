<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <H2 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
           <i class="fas fa-arrow-alt-circle-crystalV"></i>
        </span> Crystal Palace Park</H2>
      <g-link href="https://bit.ly/2UGgiSc" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1586018315/crystal_dbrf8g.jpg"
          fluid-grow
          alt = "Crystal Palace Park"
      /></g-link>
      <p class="text-blue-200">
        Thicket Road<br />London 

        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "https://bit.ly/2UIr8Y4"
          target = "_blank"
        >
          SE19 2GA
        </g-link>
      </p>
      
      <!--<h5 class=" mb-4 text-2xl text-pink-300">Closed</h5>-->
      <br />
      <!--
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
       Thurs 19 March
      
      </p>
      -->
      <article class="text-blue-200">
  South London park with<br /> full-size model dinosaurs..... 
  <input id="read-more-crystalV-1" class="read-more-crystalV" type="checkbox">
  <div class="read-more-content">
        an outdoor concert stage,<br />  a maze children's farm<br /> and playground.<br /> including a lake which<br /> is valuable for water birds. 

  </div>
  <label class="read-more-crystalV-label text-red-700 hover:text-white" for="read-more-crystalV-1">Read </label>
</article>
      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "https://bit.ly/2UGgiSc"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>

<style>


.read-more-content {
  max-height: 0;
  overflow  : hidden;
  transition: max-height .5s ease;
}
.read-more-crystalV {
  display: none;
}
.read-more-crystalV-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-crystalV-label:after {
  content: "More";
  display: inline-block;
}
.read-more-crystalV:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-crystalV:checked + .read-more-content + .read-more-crystalV-label:after {
  content: "Less";
}
</style>
