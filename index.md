---
title: deep thinking hour
---
<html lang="{{ page.lang | default: site.lang | default: 'en' }}">
<head>
  <meta charset="utf-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <!-- include favicon -->
  <link rel="icon" href="/assets/images/favicon.png">
  <link rel="stylesheet" href="/assets/css/style.css">
  <link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/gh/dreampulse/computer-modern-web-font@master/fonts.css">

</head>

  <body class="text-emerald-950 font-dm text-lg bg-violet-500 bg-gradient-to-r from-violet-500 to-emerald-300 tracking-tighter overscroll-contain">

    <header class="relative flex flex-row items-center justify-between h-24 mt-16 mx-64">
      <div class="flex flex-row">
        <!-- <p class="text-4xl font-black -tracking-widest px-2">dth</p> -->
        <div class="flex flex-col text-4xl -space-y-2 font-bold">
          <p>deep</p>
          <p>thinking</p>
          <p>hour</p>
        </div>
      </div>

      <!-- sponsors -->
      <div class="flex flex-row space-x-4 uppercase font-light">
        <div class="flex flex-row items-center justify-center h-16">
          <!--          <img src="/assets/images/github.png" alt="GitHub" class="w-16 h-16">-->
                    <p>VISLab</p>
                  </div>
        <div class="flex flex-row items-center justify-center h-16">
<!--          <img src="/assets/images/github.png" alt="GitHub" class="w-16 h-16">-->
          <p>University of Amsterdam</p>
        </div>
        <div class="flex flex-row items-center justify-center h-16">
<!--          <img src="/assets/images/github.png" alt="GitHub" class="w-16 h-16">-->
          <p>ELLIS</p>
        </div>
      </div>
    </header>

    <hr class="mx-64 border-b-2 border-neutral-800 rounded-md">

    <!-- hero -->
    <div class="flex flex-col justify-center mx-64 my-24 space-y-4">
      <p class="text-7xl font-black">a series of talks on Deep Learning by experts from industry and academia</p>
      <p class="text-2xl font-extralight font-serif italic">hosted at university of amsterdam</p>
    </div>

    <hr class="mx-64 border-b-2 border-neutral-800  rounded-md">

    <div class="flex flex-col mx-64 my-8 justify-between">
      <p class="text-xl font-black">upcoming events</p>

      <!-- events container -->
      <div class="flex flex-col space-y-24">

        {% include_relative _events/past/rianne-vd-berg.html %}

      </div>
      <!-- event container end -->

    </div>

    <div class="flex flex-col mx-64 my-8 justify-between">
      <p class="text-xl font-black">past events</p>

      <!-- events container -->
      <div class="flex flex-col space-y-24">

        {% include_relative _events/past/rianne-vd-berg.html %}
        {% include_relative _events/past/panel-model-v-scale.html %}


      </div>
      <!-- event container end -->

    </div>

    <!-- content -->
    <div class="flex flex-col items-center justify-center">
    </div>


  </body>

</html>
