<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <H2 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span>  Design Museum</H2>
      <g-link href="https://bit.ly/3f4lcAQ" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1588233239/design_vpzeri.jpg"
          alt   = " Design Museum"
      /></g-link>
      <p class="text-blue-200">
     
      224 - 238 Kensington High Street<br />London

 

        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "https://bit.ly/2yf3NVf"
          target = "_blank"
        >
          W8 6AG
        </g-link>
      </p>
      
      <h5 class=" mb-4 text-2xl text-pink-300">Reopens 31 July</h5>
      
      <!--
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
       Thurs 19 March
      
      </p>
      -->
      <article class="text-blue-200">
 The Design Museum devoted to <br />contemporary design......
<input id="read-more-design-1" class="read-more-design" type="checkbox">

  <div class="read-more-content">
<br />
 in every form from<br /> covers product, industrial,<br /> graphic, fashion <br />and architectural design.
</div>
<label class="read-more-design-label text-red-700 hover:text-white" for="read-more-design-1">Read </label>
</article>
      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "https://bit.ly/3f4lcAQ"
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
.read-more-design {
  display: none;
}
.read-more-design-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-design-label:after {
  content: "More";
  display: inline-block;
}
.read-more-design:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-design:checked + .read-more-content + .read-more-design-label:after {
  content: "Less";
}
</style>
