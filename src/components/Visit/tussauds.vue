<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <H2 class="text-2xl text-blue-200"
        ><span class="text-pink-300">
          <i class="fas fa-landmark"></i>
        </span>
       Madame Tussauds
</H2
      >
      <g-link href="https://bit.ly/2Dl68jE" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1594373044/tussauds_sjqsqj.jpg"
          fluid-grow
          alt = "Madame Tussauds"
      /></g-link>
      <p class="text-blue-200">
        Marylebone Road<br />London

        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "https://bit.ly/2Dl7eMi"
          target = "_blank"
        >
          NW1 5LR
        </g-link>
      </p>

       <h5 class="text-2xl text-pink-300">Closed</h5>
       <!--
     <h5 class=" mb-4 text-base text-orange-300">
        <br />
      Adults: £32.50 <br />Concession £29.25 <br />Children: £21.12 
<br /><br />
-->
   <!--
      Opening Times: <br />Mon To Sun<br />
      Morning 10am To 2pm <br /> Afternoon 2pm To 6pm <br />Required To Book Online<br />

      </h5>
      -->
       <h5 class=" mb-4 text-2xl text-green-300"></h5>
      <article class="text-blue-200">
   Wax replicas of famous celebrities<br /> & historic icons in themed galleries.....
  <input id="read-more-tussauds-1" class="read-more-tussauds" type="checkbox">
  
  <div class="read-more-content">
    <br />
   Royals, World Leaders, <br />A-List celebrities & Sports 
  </div>
  <label class="read-more-tussauds-label text-red-700 hover:text-white" for="read-more-tussauds-1">Read </label>
</article>
      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "https://bit.ly/2Dl68jE"
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
.read-more-tussauds {
  display: none;
}
.read-more-tussauds-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-tussauds-label:after {
  content: "More";
  display: inline-block;
}
.read-more-tussauds:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-tussauds:checked + .read-more-content + .read-more-tussauds-label:after {
  content: "Less";
}
</style>
