<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <H2 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Battersea Park Zoo</H2>
      <g-link href="https://bit.ly/3aSVJHP" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1586360410/batterseazoo_tyndsx.jpg"
          alt   = "Battersea Park Children’s Zoo"
      /></g-link>
      <p class="text-blue-200">
   Chelsea Bridge Gate<br />Battersea London

        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "https://bit.ly/2UUOHNj"
          target = "_blank"
        >
         SW11 4NJ
        </g-link>
      </p>
      
      <h5 class=" mb-4 text-base text-orange-300">
        <br />
      Adults: £9.95 <br />Children: £7.95 <br />Family: £32.50
<br /><br />
      Opening Times: <br />Mon To Sun <br />10am To 5.30pm
      <br />Required To Book Online
      <br /><br />
       <g-link
        class  = "text-red-700 hover:text-white"
        to     = "https://bit.ly/2NFRLIz"
        target = "_blank"
      >
       Feeding Times
      </g-link>
      

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

          Battersea Park Children’s Zoo...... 
<input id="read-more-batterseazoo-1" class="read-more-batterseazoo" type="checkbox">
  <div class="read-more-content">

In there collection is<br /> black-capped squirrel monkey <br />and the Emperor tamarin monkey.
  </div>
<label class="read-more-batterseazoo-label text-red-700 hover:text-white" for="read-more-batterseazoo-1">Read </label>
</article>
      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "https://bit.ly/3aSVJHP"
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
.read-more-batterseazoo {
  display: none;
}
.read-more-batterseazoo-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-batterseazoo-label:after {
  content: "More";
  display: inline-block;
}
.read-more-batterseazoo:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-batterseazoo:checked + .read-more-content + .read-more-batterseazoo-label:after {
  content: "Less";
}
</style>
