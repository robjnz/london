<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <H2 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span>  Southwark Cathedral</H2>
      <g-link href="https://bit.ly/2LJ92Qm" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1590074590/southwarkcath_v6l56f.jpg"
          alt   = "Southwark Cathedral"
      /></g-link>
      <p class="text-blue-200">
        London Bridge<br /> Soutwark London 



        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "https://bit.ly/2WSVxnE"
          target = "_blank"
        >
          SE1 9DA
        </g-link>
      </p>
      
      <h5 class=" mb-4 text-2xl text-pink-300">Open</h5>
      <h5 class=" mb-4 text-lg text-pink-300">For personal prayer and devotion </h5>
      
      <!--
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
       Thurs 19 March
      
      </p>
      -->
      <article class="text-blue-200">
  The Cathedral and Collegiate Church <br />of St Saviour and St Mary Overie.......
<input id="read-more-soutwarkcath-1" class="read-more-soutwarkcath" type="checkbox">

  <div class="read-more-content">
<br />
  The present building retains <br />the basic form of the <br />Gothic structure built <br />between 1220 and 1420.

</div>
<label class="read-more-soutwarkcath-label text-red-700 hover:text-white" for="read-more-soutwarkcath-1">Read </label>
</article>
      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "https://bit.ly/2LJ92Qm"
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
.read-more-soutwarkcath {
  display: none;
}
.read-more-soutwarkcath-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-soutwarkcath-label:after {
  content: "More";
  display: inline-block;
}
.read-more-soutwarkcath:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-soutwarkcath:checked + .read-more-content + .read-more-soutwarkcath-label:after {
  content: "Less";
}
</style>
