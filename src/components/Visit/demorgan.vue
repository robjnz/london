<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <H2 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> De Morgan Foundation</H2>
      <g-link href="https://bit.ly/34mGepg" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1586358398/demorgan_x5rtvu.jpg"
          alt   = "De Morgan Foundation"
      /></g-link>
      <p class="text-blue-200">
    Down Lane Compton<br /> Guildford surrey

        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "https://bit.ly/2y2m73K"
          target = "_blank"
        >
          GU3 1DQ
        </g-link>
      </p>
      
      <h5 class=" mb-4 text-2xl text-pink-300">Reopens 3 August</h5>
        <h5 class=" mb-4 text-base text-orange-300">
        
   
      <!--Opening Times: <br />Mon To Sun<br />
      10am To 9pm  -->
      <br />Required To Book Online<br />
      Tickets will go on sale on Monday 20th July

      

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

          Museum of Arts <br />and Crafts paintings..... 
<input id="read-more-demorgan-1" class="read-more-demorgan" type="checkbox">
  <div class="read-more-content">

and ceramics by <br />William and Evelyn De Morgan.  </div>
 <label class="read-more-demorgan-label text-red-700 hover:text-white" for="read-more-demorgan-1">Read </label>
</article>
      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "https://bit.ly/34mGepg"
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
.read-more-demorgan {
  display: none;
}
.read-more-demorgan-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-demorgan-label:after {
  content: "More";
  display: inline-block;
}
.read-more-demorgan:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-demorgan:checked + .read-more-content + .read-more-demorgan-label:after {
  content: "Less";
}
</style>
