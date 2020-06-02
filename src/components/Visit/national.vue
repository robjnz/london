<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <H2 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span>  The National Gallery</H2>
      <g-link href="https://bit.ly/3eFkpoT" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1591109173/national_nxwlnj.jpg"
          alt   = "the national gallery"
      /></g-link>
      <p class="text-blue-200">
        Trafalgar Square<br /> London



        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "https://bit.ly/3gNVeSY"
          target = "_blank"
        >
          WC2N 5DN
        </g-link>
      </p>
      
      <h5 class=" mb-4 text-2xl text-pink-300">Closed</h5>
      
      <!--
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
       Thurs 19 March
      
      </p>
      -->
      <article class="text-blue-200">
   Houses over 2,600 paintings........
<input id="read-more-national-1" class="read-more-national" type="checkbox">

  <div class="read-more-content">
<br />
 ....
</div>
<label class="read-more-national-label text-red-700 hover:text-white" for="read-more-national-1">Read </label>
</article>
      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "https://bit.ly/3eFkpoT"
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
.read-more-national {
  display: none;
}
.read-more-national-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-national-label:after {
  content: "More";
  display: inline-block;
}
.read-more-national:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-national:checked + .read-more-content + .read-more-national-label:after {
  content: "Less";
}
</style>
