<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <H2 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span>  Westminster Abbey</H2>
      <g-link href="https://bit.ly/2AM1Fp7" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1591522027/westminster_x0xrfa.jpg"
          alt   = "westminster abbey"
      /></g-link>
      <p class="text-blue-200">
20 Dean's Yard<br />London



        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "https://bit.ly/3czrk1q"
          target = "_blank"
        >
          SW1P 3PA
        </g-link>
      </p>
      
      <h5 class=" mb-4 text-2xl text-pink-300"></h5>
      
      <!--
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
       Thurs 19 March
      
      </p>
      -->
      <article class="text-blue-200">
    The Abbey has been the <br />coronation church since 1066........
<input id="read-more-westminster-1" class="read-more-westminster" type="checkbox">

  <div class="read-more-content">
<br />
 It's the final resting place of 17 monarchs.<br /><br /> The church we see today<br /> was begun by Henry III in 1245.<br /><br /> It’s one of the most important <br />Gothic buildings in the country,<br /> and has the medieval shrine <br />of an Anglo-Saxon saint at its heart.
</div>
<label class="read-more-westminster-label text-red-700 hover:text-white" for="read-more-westminster-1">Read </label>
</article>
      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "https://bit.ly/2AM1Fp7"
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
.read-more-westminster {
  display: none;
}
.read-more-westminster-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-westminster-label:after {
  content: "More";
  display: inline-block;
}
.read-more-westminster:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-westminster:checked + .read-more-content + .read-more-westminster-label:after {
  content: "Less";
}
</style>
