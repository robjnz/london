<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <H2 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> St. Paul's Cathedral</H2>
      <g-link href="https://bit.ly/3abjhqv" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1586945496/pauls_mhypeg.jpg"
          alt   = "St. Pauls Cathedral"
      /></g-link>
      <p class="text-blue-200">
      St. Paul's Churchyard<br /> London 


        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "https://bit.ly/2RFn8p5"
          target = "_blank"
        >
          EC4M 8AD
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
The cathedral is one of the most <br />recognisable sights of London......
<input id="read-more-pauls-1" class="read-more-pauls" type="checkbox">

  <div class="read-more-content">
<br />
 It sits on Ludgate Hill <br /> at the highest point of the City of London<br /> and is a Grade I listed building. 
 </div>
<label class="read-more-pauls-label text-red-700 hover:text-white" for="read-more-pauls-1">Read </label>
</article>
      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "https://bit.ly/3abjhqv"
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
.read-more-pauls {
  display: none;
}
.read-more-pauls-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-pauls-label:after {
  content: "More";
  display: inline-block;
}
.read-more-pauls:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-pauls:checked + .read-more-content + .read-more-pauls-label:after {
  content: "Less";
}
</style>
