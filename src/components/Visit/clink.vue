<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <H2 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span>  Clink Prison Museum </H2>
      <g-link href="https://bit.ly/2LQZOkS" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1590226180/clink_fmnh59.jpg"
          alt   = "Clink Prison Museum"
      /></g-link>
      <p class="text-blue-200">
        1 Clink Street <br />Southwark London 



        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "https://bit.ly/3gfGKef"
          target = "_blank"
        >
          SE1 9DG
        </g-link>
      </p>
      
      <h5 class=" mb-4 text-2xl text-pink-300"></h5>
        <h5 class=" mb-4 text-base text-orange-300">
        
      Adults: £8.50 <br />Concession £6.50 <br />Children: £6.50 
<br />Family: £24.20<br /><br />
   
      Opening Times: <br />Mon To Sun<br />
      10am To 9pm  <br />Required To Book Online<br />

      

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
   The Clink Prison dates back to 1144 <br />making it one of England’s oldest.......
<input id="read-more-clink-1" class="read-more-clink" type="checkbox">

  <div class="read-more-content">
<br />
   and most notorious prisons.<br /><br />There are opportunities to view <br />archaeological artefacts, <br />experience the sights, sounds <br />and smells of the prison.

</div>
<label class="read-more-clink-label text-red-700 hover:text-white" for="read-more-clink-1">Read </label>
</article>
      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "https://bit.ly/2LQZOkS"
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
.read-more-clink {
  display: none;
}
.read-more-clink-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-clink-label:after {
  content: "More";
  display: inline-block;
}
.read-more-clink:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-clink:checked + .read-more-content + .read-more-clink-label:after {
  content: "Less";
}
</style>
