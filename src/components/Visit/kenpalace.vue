<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <H2 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span>  Kensington Palace</H2>
      <g-link href="https://bit.ly/2S3ZPW7" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1587828374/kenpalace_dffnar.jpg"
          alt   = "Kensington Palace"
      /></g-link>
      <p class="text-blue-200">
     
      Kensington Gardens<br />Kensington London


  <g-link
          class  = "text-red-700 hover:text-white"
          to     = "https://bit.ly/3eNxtcx"
          target = "_blank"
        >
          W8 4PX
        </g-link>
      
      <h5 class=" mb-4 text-2xl text-pink-300">Reopens 30 July</h5>
      
      <!--
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
       Thurs 19 March
      
      </p>
      -->
      <article class="text-blue-200">
 Royal palace and gardens, with exhibits<br /> on former residents.......
<input id="read-more-kenpalace-1" class="read-more-kenpalace" type="checkbox">

  <div class="read-more-content">
<br />
like Queen Victoria and Princess Diana.
</div>
<label class="read-more-kenpalace-label text-red-700 hover:text-white" for="read-more-kenpalace-1">Read </label>
</article>
      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "https://bit.ly/2S3ZPW7"
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
.read-more-kenpalace {
  display: none;
}
.read-more-kenpalace-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-kenpalace-label:after {
  content: "More";
  display: inline-block;
}
.read-more-kenpalace:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-kenpalace:checked + .read-more-content + .read-more-kenpalace-label:after {
  content: "Less";
}
</style>
