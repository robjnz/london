<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <H2 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span>  Tate Britain</H2>
      <g-link href="https://bit.ly/3gs9HDM" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1590747139/britain_gf0xpc.jpg"
          alt   = "Tate Britain"
      /></g-link>
      <p class="text-blue-200">
        Millbank<br />London 





        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "https://bit.ly/3ewHg60"
          target = "_blank"
        >
          SW1P 4RG
        </g-link>
      </p>
      
      <h5 class=" mb-4 text-2xl text-pink-300">Reopens 27 July</h5>
      <h5 class=" mb-4 text-base text-orange-300">
     
      Admission free<br />
      Required To Book Online
<br />
  
      

      </h5>
      
      <!--
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
       Thurs 19 March
      
      </p>
      -->
      <article class="text-blue-200">
   British art from the <br />16th century.......
<input id="read-more-britain-1" class="read-more-britain" type="checkbox">

  <div class="read-more-content">
<br />
 including modern and contemporary art.
</div>
<label class="read-more-britain-label text-red-700 hover:text-white" for="read-more-britain-1">Read </label>
</article>
      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "https://bit.ly/3gs9HDM"
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
.read-more-britain {
  display: none;
}
.read-more-britain-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-britain-label:after {
  content: "More";
  display: inline-block;
}
.read-more-britain:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-britain:checked + .read-more-content + .read-more-britain-label:after {
  content: "Less";
}
</style>
