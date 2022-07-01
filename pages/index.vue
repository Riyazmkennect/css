<template>
  <div>
    <header></header>
  
    <section>
      <aside></aside>
      <main>
        <div></div>
        <div></div>
      </main>
    </section>
     <section class="block">
        <div class="b"></div>
        <div class="b"></div>
        <div class="b"></div>
         <div class="b"></div>
        <div class="b"></div>
        <div class="b"></div>
      </section>
      <div class="btm"></div>
  </div>
</template>
<style>
header{
  background-color: black;
  height: 100px;

  flex-wrap: wrap;
}
section{
  height: auto;
  display: flex;
  flex-wrap:wrap ;

}
aside{
  background-color: rgb(156, 138, 173);
  flex: 0.4;
  height: 70vh;
  margin: 1px;
}
main{
  height: 70vh;
  flex: 0.6;
 
}
main div{
  background-color: rgb(46, 46, 85);
  height: 35vh;
  flex: 0.3;
  margin: 1px;
}
.btm{
  background-color: rgb(114, 62, 62);
  flex: 1;
  height: 100px;
  

}
.block{
  height: 40vh;
  display: flex;
  flex: 0.2;
  flex-wrap: wrap;
 
}
.block .b{
  margin: 1px;
  flex-wrap: wrap;
  flex: 0.2;
  height: 258px;
  background-color: rgb(65, 61, 61);
}


@media(max-width:800px){
  header{
    flex: 100%;
    max-width: 600px;
  }
   section{
    flex: 100%;
    max-width: 600px;
  }
   aside{
    flex: 100%;
    max-width: 600px;
  }
   main{
    flex: 100%;
    max-width: 600px;
  }
   main div{
    flex: 100%;
    max-width: 600px;
  }
   .block {
    flex: 100%;
    max-width: 600px;
  }
   .block .b{
    flex: 100%;
    max-width: 600px;
  }
  .btm{
    flex: 100%;
    max-width: 600px;
  }

}
</style>