<template>
  <main class="relative">
    <NavbarComponent class="my-5 w-full"></NavbarComponent>
    <section>
      <div class="carousel-slider">
        <div class="carousel-inner-slider">
          <input
            class="carousel-open-slider"
            type="radio"
            id="carousel-1-slider"
            name="carousel-slider"
            aria-hidden="true"
            hidden=""
            checked="checked"
          />
          <div class="carousel-item-slider">
            <div class="relative h-sm carousel1 ">
              <div class="flex justify-end mr-48">
                <img
                  src="../assets/images/carousel1.svg"
                  alt=""
                  class="w-mdl"
                />
              </div>
              <figcaption class="absolute bottom-52 left-48">
                <p class="text-lg">Design Inspiration</p>
                <h3 class="text-5xl">
                  A design created to <br />
                  excite people
                </h3>
              </figcaption>
            </div>
          </div>
          <input
            class="carousel-open-slider"
            type="radio"
            id="carousel-2-slider"
            name="carousel-slider"
            aria-hidden="true"
            hidden=""
          />

          <div class="carousel-item-slider">
            <div class="h-sm carousel3 flex justify-center items-center">
              <figcaption class="">
                <p class="text-lg text-center">Design Inspiration</p>
                <h3 class="text-5xl text-center">
                  A data tracking <br />
                  starts here.
                </h3>
              </figcaption>
            </div>
          </div>
          <input
            class="carousel-open-slider"
            type="radio"
            id="carousel-3-slider"
            name="carousel-slider"
            aria-hidden="true"
            hidden=""
          />
          <div class="carousel-item-slider">
            <div class="h-sm carousel2">
              <figcaption class="absolute bottom-52 left-48">
                <p class="text-lg">Design Inspiration</p>
                <h3 class="text-5xl">
                  Build your data, <br />
                  wherever you are.
                </h3>
              </figcaption>
            </div>
          </div>
          <label
            for="carousel-3-slider"
            class="carousel-control-slider prev control-1-slider border-l-2 text-xs border-gray-900 ml-20"
            >Prev</label
          >
          <label
            for="carousel-2-slider"
            class="carousel-control-slider next control-1-slider border-r-2 text-xs border-gray-900 mr-20"
            >Next</label
          >
          <label
            for="carousel-1-slider"
            class="carousel-control-slider prev control-2-slider border-l-2 text-xs border-gray-900 ml-20"
            >Prev</label
          >
          <label
            for="carousel-3-slider"
            class="carousel-control-slider next control-2-slider border-r-2 text-xs border-gray-900 mr-20"
            >Next</label
          >
          <label
            for="carousel-2-slider"
            class="carousel-control-slider prev control-3-slider border-l-2 text-xs border-gray-900 ml-20"
            >Prev</label
          >
          <label
            for="carousel-1-slider"
            class="carousel-control-slider next control-3-slider border-r-2 text-xs border-gray-900 mr-20"
            >Next</label
          >
          <ol class="carousel-indicators-slider">
            <li>
              <label for="carousel-1-slider" class="carousel-bullet-slider"
                >•</label
              >
            </li>
            <li>
              <label for="carousel-2-slider" class="carousel-bullet-slider"
                >•</label
              >
            </li>
            <li>
              <label for="carousel-3-slider" class="carousel-bullet-slider"
                >•</label
              >
            </li>
          </ol>
        </div>
      </div>
    </section>

    <!-- <section class="relative h-md">
        <navbar-component></navbar-component>
        <div class="absolute w-full h-full">
            <div class="h-full carousel2"></div>
            <div class="h-full carousel3"></div>
        </div>
        <div class="flex h-xs px-10">
            <div class="flex items-center">
                 <button class="border-l-4 p-6 border-gray-900">
                    Prev
                </button>
            </div>
            <div class="flex-grow relative">
                <div class="absolute h-xs w-full flex justify-end items-start">
                    <img class="" src="..\assets\images\carousel1.svg" alt="">
                </div>
                <div class="flex items-end h-xs w-96">
                    <div>
                        <div>Design Inspiration</div>
                        <div class="font-bold text-4xl mt-4">A design created to excite people</div>
                        <div>
                            <button class="bg-gray-900 text-white p-4 mt-4">Project Details.</button>
                        </div>
                    </div>
                </div>
            </div>
            <div class="flex items-center">
                <button class="border-r-4 p-6 border-gray-900">
                    Next
                </button>
            </div>
        </div>
        <div class="flex justify-center mt-10">
            <div id="carusel1" class="w-24 h-1.5 bg-gray-700 mx-4"></div>
            <div id="carusel2" class="w-24 h-1.5 bg-gray-700 mx-4"></div>
            <div id="carusel3" class="w-24 h-1.5 bg-gray-700 mx-4"></div>
        </div>
    </section> -->

    <div
      class="relative pt-16 pb-32 flex content-center items-center justify-center"
      style="min-height: 75vh;"
    >
      <div
        class="absolute top-0 w-full h-full bg-center bg-cover"
        style='background-image: url("https://images.unsplash.com/photo-1557804506-669a67965ba0?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=crop&amp;w=1267&amp;q=80");'
      >
        <span
          id="blackOverlay"
          class="w-full h-full absolute opacity-75 bg-black"
        ></span>
      </div>
      <div class="container relative mx-auto">
        <div class="items-center flex flex-wrap">
          <div class="w-full lg:w-6/12 px-4 ml-auto mr-auto text-center">
            <div class="pr-12">
              <h1 class="text-white font-semibold text-5xl">
                Your story starts with us.
              </h1>
              <p class="mt-4 text-lg text-gray-300">
                Data science is an inter-disciplinary field that uses scientific
                methods, processes, algorithms and systems to extract knowledge
                and insights from structured and unstructured data, and apply
                knowledge and actionable insights from
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- RESUME -->
    <section class="bg-gray-100 md:p-10 py-12" id="about">
      <div class="flex flex-wrap items-center">
        <div class="w-full md:w-4/12 px-4 mr-auto ml-auto">
          <div class="relative flex flex-col min-w-0 w-full mb-6">
            <img alt="..." src="../assets/images/Resume.svg" />
          </div>
        </div>
        <div class="w-full md:w-5/12 px-4 mr-auto ml-auto text-left">
          <h3 class="text-2xl md:text-4xl mb-2 font-bold leading-normal">
            My Resume
          </h3>
          <p class="text-base md:text-sm font-normal mt-4 mb-4 text-gray-700">
            Data science is an inter-disciplinary field that uses scientific
            methods, processes, algorithms and systems to extract knowledge and
            insights from structured and unstructured data, and apply knowledge
            and actionable insights from
          </p>
          <a
            href="#"
            class="font-medium text-xs text-gray-800 mt-2 inline-flex"
          >
            Download CV
            <svg
              class="ml-4 -mt-2"
              width="2"
              height="33"
              viewBox="0 0 2 33"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <line
                x1="1"
                y1="1"
                x2="1"
                y2="32"
                stroke="#1F1F1F"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
            </svg>
          </a>
        </div>
      </div>
    </section>

    <!-- PROFILE -->
    <section class="py-8 md:py-0 h-content" id="about">
      <div class="md:flex justify-between items-center">
        <div class="w-full md:w-5/12 px-4 md:pl-16 text-left">
          <h3 class="text-2xl md:text-4xl mb-2 font-bold">About Me</h3>
          <p class="text-base md:text-sm font-normal mt-4 mb-4 text-gray-700">
            Data science is an inter-disciplinary field that uses scientific
            methods, processes, algorithms and systems to extract knowledge and
            insights from structured and unstructured data, and apply knowledge
            and actionable insights from
          </p>
          <a href="" class="font-medium text-xs text-gray-800 mt-2 inline-flex">
            Read More
            <svg
              class="ml-4 -mt-2"
              width="2"
              height="33"
              viewBox="0 0 2 33"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <line
                x1="1"
                y1="1"
                x2="1"
                y2="32"
                stroke="#1F1F1F"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
              /></svg
          ></a>
        </div>
        <div
          class="relative w-full md:w-7/12 px-4 h-168 flex items-center justify-center"
        >
          <img
            class="absolute -z-10 top-0 right-0 w-100 h-full object-cover "
            src="../assets/images/background.png"
            alt=""
          />
          <div class="md:px-2 xl:px-0">
            <div class="flex justify-center md:justify-end">
              <img
                alt="..."
                src="../assets/images/pro-img.png"
                class="z-10 w-10/12 md:w-64 lg:w-80 xl:w-96 md:mr-4"
              />
              <!-- <img alt="..." src="..\assets\images\pro-img.png" class="z-10 w-10/12 md:w-96"> -->
            </div>
            <div
              class="mt-4 flex justify-center md:justify-start md:-mt-32 lg:-mt-40"
            >
              <div class="pl-4 py-2 bg-black w-10/12 md:w-xxs lg:w-xs xl:w-sm ">
                <p
                  class="text-sm md:text-base font-normal text-white text-left"
                >
                  Ada-Ihueze
                </p>
                <p
                  class="text-sm md:text-base font-normal text-white text-left"
                >
                  Data Scientist
                </p>
              </div>
            </div>
            <div class="mt-4 flex ml-10 md:ml-0 justify-start md:pl-4 text-xl">
              <img
                src="../assets/images/sign.svg"
                alt=""
                class="w-24 lg:w-32"
              />
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- ABOUT -->
    <section class="bg-gray-100 pb-16 w-full" id="about">
      <div class="lg:p-20 px-4 text-left">
        <p class="text-base md:uppercase font-semibold">Capabilities</p>
        <h3 class="font-bold text-base text-3xl lg:text-5xl">
          A design created to <br />
          excite people
        </h3>
      </div>

      <div class="block md:flex items-center">
        <!--Main Col-->
        <div class="pro-img w-full md:w-3/5 md:h-72 lg:w-7/12"></div>

        <!--Img Col-->
        <div
          class="w-full lg:h-400-px md:h-600-px  md:w-2/5 lg:w-5/12 bg-white"
        >
          <!-- Big profile image for side bar (desktop) -->
          <div class="p-4 md:p-4 text-left">
            <div class="flex mx-auto block">
              <div
                class="avg-img block rounded-full shadow-xl mx-2 h-14 w-14"
              ></div>
              <h6 class="text-base font-semibold pt-4">My Specialties</h6>
            </div>
            <p
              class="pt-4 text-2xl md:text-4xl font-bold flex lg:justify-start"
            >
              I work in the fields of Data science and Manipulation
            </p>
            <!-- <p class="pt-2 text-gray-600 text-base font-semibold md:justify-start">Natural Language Processing</p>
                    <p class="pt-3 text-base font-normal">Data science is an inter-disciplinary field that uses scientific methods,
                        processes, algorithms and systems to extract knowledge and insights</p>
                    <p class="pt-2 text-gray-600 text-base font-semibold md:justify-start">Computer Vision</p>
                    <p class="pt-3 text-base font-normal">Data science is an inter-disciplinary field that uses scientific methods,
                        processes, algorithms and systems to extract knowledge and insights</p>
                    <p class="pt-2 text-gray-600 text-base font-semibold md:justify-start">Data Analytics</p>
                    <p class="pt-3 text-base font-normal">Data science is an inter-disciplinary field that uses scientific methods,
                        processes, algorithms and systems to extract knowledge and insights</p> -->
            <!-- <div class="wrapper">
                        <div class="accordion" @click="toggle">
                            <h2 class="title">

                            </h2>
                            <slot name="title"></slot>
                        </div>
                        <div v-show="show" class="content">
                            <slot name="content"></slot>
                        </div>

                    </div> -->
            <!-- <div class="accordion">
                        <div class="wrapper">
                            <div class="accordion-item" >
                                <div>
                                    <h3 @click="toggle" class="accordion-title">Title A1</h3>
                                    <div v-show="contentVisible" class="accordion-content">albatross</div>
                                </div>
                            </div>
                            <div class="accordion-item" >
                                <div>
                                    <h3 @click="toggle" class="accordion-title">Title A1</h3>
                                    <div v-show="contentVisible" class="accordion-content">albatross</div>
                                </div>
                            </div>
                            <div class="accordion-item" >
                                <div>
                                    <h3 @click="toggle" class="accordion-title">Title A1</h3>
                                    <div v-show="contentVisible" class="accordion-content">albatross</div>
                                </div>
                            </div>
                        </div>
                    </div> -->

            <div class="mb-1 w-full p-2 pt-1 overflow-hidden">
              <span
                id="1"
                class="pt-2 text-gray-600 text-base font-semibold md:justify-start cursor-pointer"
                @click="showSpecialty"
                >Natural Language Processing</span
              >
              <div
                :class="
                  specialty == 1
                    ? 'transition duration-1000 ease-in-out delay-100'
                    : 'hidden'
                "
                class="overflow-hidden leading-normal"
              >
                <p class="pt-3 text-base font-normal">
                  Data science is an inter-disciplinary field that uses
                  scientific methods, processes, algorithms and systems to
                  extract knowledge and insights
                </p>
              </div>
            </div>
            <div class="mb-1 w-full p-2 pt-1 overflow-hidden">
              <span
                id="2"
                class="inline-flex pt-2 text-gray-600 text-base font-semibold md:justify-start cursor-pointer"
                @click="showSpecialty"
                >Computer Vision</span
              >
              <div
                :class="
                  specialty == 2
                    ? 'transition duration-1000 ease-in-out delay-100'
                    : 'hidden'
                "
                class="overflow-hidden leading-normal"
              >
                <p class="pt-3 text-base font-normal">
                  Data science is an inter-disciplinary field that uses
                  scientific methods, processes, algorithms and systems to
                  extract knowledge and insights
                </p>
              </div>
            </div>
            <div class="mb-1 w-full p-2 pt-1 overflow-hidden">
              <span
                id="3"
                class="inline-flex pt-2 text-gray-600 text-base font-semibold md:justify-start cursor-pointer"
                @click="showSpecialty"
                >Data Analytics</span
              >
              <div
                :class="
                  specialty == 3
                    ? 'transition duration-1000 ease-in-out delay-100'
                    : 'hidden'
                "
                class="overflow-hidden leading-normal"
              >
                <p class="pt-3 text-base font-normal">
                  Data science is an inter-disciplinary field that uses
                  scientific methods, processes, algorithms and systems to
                  extract knowledge and insights
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- PORTFOLIO -->
    <section
      class="hidden md:flex items-center w-full justify-center"
      id="portfolio"
    >
      <div class="md:flex md:items-center md:w-9/12 w-full h-2xl md:h-screen">
        <div
          class="port-crd shadow-xl rounded-md bg-white z-20 mb-8 md:w-3/5 md:mb-none transition duration-500 ease-in-out transform hover:-translate-y-1 hover:scale-110"
        >
          <div class="p-5 text-left">
            <p class="text-base font-semibold mb-2">Data Analytics</p>
            <h5 class="text-2xl md:text-4xl font-bold mb-2">
              Analyzing and managing data for decisions
            </h5>
            <p class="mb-4 text-base font-normal">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure
              sequi tenetur, voluptatibus harum consequuntur alias quaerat
              excepturi temporibus nisi commodi, ex, ratione quae soluta! Saepe
              alias dolores dolorem assumenda totam?
            </p>
          </div>
          <img src="../assets/images/slide1.png" class="" alt="" />
        </div>
        <div
          class="port-crd shadow-xl rounded-md bg-white z-10 hover:z-50 mb-8 md:w-3/5 md:mb-none md:-ml-32 transition duration-500 ease-in-out transform hover:-translate-y-1 hover:scale-110"
        >
          <div class="p-5 text-center md:text-left">
            <p class="text-base font-semibold mb-2">Computer Vision</p>
            <h5 class="text-xl md:text-4xl font-bold mb-2">
              Using Computer vision to combat retail fraud
            </h5>
            <p class="mb-4 text-base font-normal">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure
              sequi tenetur, voluptatibus harum consequuntur alias quaerat
              excepturi temporibus nisi commodi, ex, ratione quae soluta!al
              Saepe alias dolores dolorem assumenda totam?
            </p>
          </div>
          <img src="../assets/images/slide2.png" class="" alt="" />
        </div>
        <div
          class="port-crd shadow-lg rounded-md bg-white hover:z-50 mb-8 md:w-3/5 md:mb-none md:-ml-32 transition duration-500 ease-in-out transform hover:-translate-y-1 hover:scale-110"
        >
          <div class="p-5 text-center md:text-left">
            <p class="text-base font-semibold mb-2">
              Natural Language Processing
            </p>
            <h5 class="text-xl md:text-4xl font-bold mb-2">
              Streamlining Tech Support with NLP
            </h5>
            <p class="mb-4 text-base font-normal">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure
              sequi tenetur, voluptatibus harum consequuntur alias quaerat
              excepturi temporibus nisi commodi, ex, ratione quae soluta! Saepe
              alias dolores dolorem assumenda totam?
            </p>
          </div>
          <img src="../assets/images/slide3.png" class="" alt="" />
        </div>
      </div>
    </section>

    <section>
      <div class="carousel sm:carousel md:hidden relative shadow-2xl bg-white">
        <div class="carousel-inner relative overflow-hidden w-full">
          <input
            class="carousel-open"
            type="radio"
            id="carousel-1"
            name="carousel"
            aria-hidden="true"
            hidden=""
            checked="checked"
          />
          <div class="carousel-item absolute opacity-0">
            <div
              class="port-crd shadow-xl rounded-md bg-white mb-8 md:w-3/5 md:mb-none"
            >
              <div class="p-5 text-left">
                <p class="text-base font-semibold mb-2">Data Analytics</p>
                <h5 class="text-2xl md:text-4xl font-bold mb-2">
                  Analyzing and managing data for decisions
                </h5>
                <p class="mb-4 text-base font-normal">
                  Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure
                  sequi tenetur, voluptatibus harum consequuntur alias quaerat
                  excepturi temporibus nisi commodi, ex, ratione quae soluta!
                  Saepe alias dolores dolorem assumenda totam?
                </p>
              </div>
              <img src="../assets/images/slide1.png" class="" alt="" />
            </div>
          </div>
          <label
            ref="slideThree"
            for="carousel-3"
            class="prev opacity-0 control-1 w-10 h-10 ml-2 md:ml-10 absolute cursor-pointer hidden text-3xl font-bold text-black hover:text-white rounded-full bg-white hover:bg-blue-700 leading-tight text-center z-10 inset-y-0 left-0 my-auto"
            >‹</label
          >
          <label
            ref="slideTwo"
            for="carousel-2"
            class="next opacity-0 control-1 w-10 h-10 mr-2 md:mr-10 absolute cursor-pointer hidden text-3xl font-bold text-black hover:text-white rounded-full bg-white hover:bg-blue-700 leading-tight text-center z-10 inset-y-0 right-0 my-auto"
            >›</label
          >

          <!--Slide 2-->
          <input
            class="carousel-open"
            type="radio"
            id="carousel-2"
            name="carousel"
            aria-hidden="true"
            hidden=""
          />
          <div class="carousel-item absolute opacity-0">
            <div
              class="port-crd shadow-xl rounded-md bg-white  mb-8 md:w-3/5 md:mb-none md:-ml-32"
            >
              <div class="p-5 text-center md:text-left">
                <p class="text-base font-semibold mb-2">Computer Vision</p>
                <h5 class="text-xl md:text-4xl font-bold mb-2">
                  Using Computer vision to combat retail fraud
                </h5>
                <p class="mb-4 text-base font-normal">
                  Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure
                  sequi tenetur, voluptatibus harum consequuntur alias quaerat
                  excepturi temporibus nisi commodi, ex, ratione quae soluta!al
                  Saepe alias dolores dolorem assumenda totam?
                </p>
              </div>
              <img src="../assets/images/slide2.png" class="" alt="" />
            </div>
          </div>
          <label
            ref="slideOne"
            for="carousel-1"
            class="prev opacity-0 control-2 w-10 h-10 ml-2 md:ml-10 absolute cursor-pointer hidden text-3xl font-bold text-black hover:text-white rounded-full bg-white hover:bg-blue-700 leading-tight text-center z-10 inset-y-0 left-0 my-auto"
            >‹</label
          >
          <label
            ref="slideThree"
            for="carousel-3"
            class="next opacity-0 control-2 w-10 h-10 mr-2 md:mr-10 absolute cursor-pointer hidden text-3xl font-bold text-black hover:text-white rounded-full bg-white hover:bg-blue-700 leading-tight text-center z-10 inset-y-0 right-0 my-auto"
            >›</label
          >

          <!--Slide 3-->
          <input
            class="carousel-open"
            type="radio"
            id="carousel-3"
            name="carousel"
            aria-hidden="true"
            hidden=""
          />
          <div class="carousel-item absolute opacity-0">
            <div
              class="port-crd shadow-lg rounded-md bg-white mb-8 md:w-3/5 md:mb-none md:-ml-32"
            >
              <div class="p-5 text-center md:text-left">
                <p class="text-base font-semibold mb-2">
                  Natural Language Processing
                </p>
                <h5 class="text-xl md:text-4xl font-bold mb-2">
                  Streamlining Tech Support with NLP
                </h5>
                <p class="mb-4 text-base font-normal">
                  Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure
                  sequi tenetur, voluptatibus harum consequuntur alias quaerat
                  excepturi temporibus nisi commodi, ex, ratione quae soluta!
                  Saepe alias dolores dolorem assumenda totam?
                </p>
              </div>
              <img src="../assets/images/slide3.png" class="" alt="" />
            </div>
          </div>
          <label
            ref="slideTwo"
            for="carousel-2"
            class="prev opacity-0 control-3 w-10 h-10 ml-2 md:ml-10 absolute cursor-pointer hidden text-3xl font-bold text-black hover:text-white rounded-full bg-white hover:bg-blue-700 leading-tight text-center z-10 inset-y-0 left-0 my-auto"
            >‹</label
          >
          <label
            ref="slideOne"
            for="carousel-1"
            class="next opacity-0 control-3 w-10 h-10 mr-2 md:mr-10 absolute cursor-pointer hidden text-3xl font-bold text-black hover:text-white rounded-full bg-white hover:bg-blue-700 leading-tight text-center z-10 inset-y-0 right-0 my-auto"
            >›</label
          >

          <!-- Add additional indicators for each slide-->
          <ol class="carousel-indicators">
            <li class="inline-block mr-3">
              <label
                for="carousel-1"
                class="carousel-bullet cursor-pointer block text-4xl text-white hover:text-blue-700"
                >•</label
              >
            </li>
            <li class="inline-block mr-3">
              <label
                for="carousel-2"
                class="carousel-bullet cursor-pointer block text-4xl text-white hover:text-blue-700"
                >•</label
              >
            </li>
            <li class="inline-block mr-3">
              <label
                for="carousel-3"
                class="carousel-bullet cursor-pointer block text-4xl text-white hover:text-blue-700"
                >•</label
              >
            </li>
          </ol>
        </div>
      </div>
    </section>

    <!-- END PORTFOLIO-->

    <!-- CONTACT -->
    <section id="contact" class="h-content px-4 md:p-20 bg-gray-100 h-5/6">
      <h6 class="font-semibold text-base md:text-lg mb-2 pt-4 text-left">
        Project Collaboration
      </h6>
      <div class="flex flex-col md:flex-row justify-between">
        <h2 class="text-3xl md:text-5xl font-bold text-left">
          Got a project? Let’s talk.
        </h2>
        <button
          class="bg-black text-white active:bg-black font-normal uppercase text-xs px-6 py-3 shadow hover:shadow-lg outline-none focus:outline-none mr-1 mb-1 ease-linear transition-all duration-150"
          type="button"
        >
          Contact me
        </button>
      </div>
      <div
        class="mx-auto lg:mx-0 w-full pt-3 border-b-2 border-black opacity-25"
      ></div>
      <p class="text-black md:w-2/5 mt-4 text-left">
        Have a question? Need information about advertising? You've come to the
        right place. Have a question? Need information about advertising? You've
        come to the right place
      </p>
    </section>
    <!-- END CONTACT -->

    <!-- SOCIAL MEDIA -->
    <section class="soc-img md:p-20 px-5 h-full relative">
      <h6 class="font-semibold text-base md:text-lg mb-2 pt-4 text-left">
        Social Media
      </h6>
      <h3 class="font-bold text-3xl md:text-5xl mb-2 pt-4 text-left">
        Let's Connect
      </h3>
      <div class="container py-2 lg:mt-12">
        <div class="flex flex-wrap -m-1 md:-m-2">
          <div class="flex flex-wrap w-full md:w-1/3">
            <div class="w-full p-1 md:p-2">
              <div
                id="medium"
                class="flex justify-between border-2 border-gray-500 bg-gray-100 p-4"
              >
                <div id="med-text">
                  <h3 class="font-bold text-xl md:text-2xl">Medium</h3>
                  <p class="text-sm md:text-base font-md">Case Study</p>
                </div>
                <div id="icon text-5xl">
                  <img src="../assets/images/medium.svg" />
                </div>
              </div>
            </div>
          </div>
          <div class="flex flex-wrap w-full md:w-1/3">
            <div class="w-full p-1 md:p-2">
              <div
                id="medium"
                class="flex justify-between border-2 border-gray-500 bg-gray-100 p-4"
              >
                <div id="med-text">
                  <h3 class="font-bold text-xl md:text-2xl">Hashnode</h3>
                  <p class="text-sm md:text-base font-md">Articles</p>
                </div>
                <div id="icon">
                  <img src="../assets/images/hashnode.svg" />
                </div>
              </div>
            </div>
          </div>
          <div class="flex flex-wrap w-full md:w-1/3">
            <div class="w-full p-1 md:p-2">
              <div
                id="medium"
                class="flex justify-between border-2 border-gray-500 bg-gray-100 p-4"
              >
                <div id="med-text">
                  <h3 class="font-bold text-xl md:text-2xl">Github</h3>
                  <p class="text-sm md:text-base font-md">Codes</p>
                </div>
                <div id="icon">
                  <img src="../assets/images/github.svg" />
                </div>
              </div>
            </div>
          </div>
          <div class="flex flex-wrap w-full md:w-1/3">
            <div class="w-full p-1 md:p-2">
              <div
                id="medium"
                class="flex justify-between border-2 border-gray-500 bg-gray-100 p-4"
              >
                <div id="med-text">
                  <h3 class="font-bold text-xl md:text-2xl">Twitter</h3>
                  <p class="text-sm md:text-base font-md">Random</p>
                </div>
                <div id="icon">
                  <img src="../assets/images/twitter.svg" />
                </div>
              </div>
            </div>
          </div>
          <div class="flex flex-wrap w-full md:w-1/3">
            <div class="w-full p-1 md:p-2">
              <div
                id="medium"
                class="flex justify-between border-2 border-gray-500 bg-gray-100 p-4"
              >
                <div id="med-text">
                  <h3 class="font-bold text-xl md:text-2xl">LinkedIn</h3>
                  <p class="text-sm md:text-base font-md">Professional</p>
                </div>
                <div id="icon">
                  <img src="../assets/images/linkedin.svg" />
                </div>
              </div>
            </div>
          </div>
          <div class="flex flex-wrap w-full md:w-1/3">
            <div class="w-full p-1 md:p-2">
              <div
                id="medium"
                class="flex justify-between border-2 border-gray-500 bg-gray-100 p-4"
              >
                <div id="med-text">
                  <h3 class="font-bold text-xl md:text-2xl">Mail</h3>
                  <p class="text-sm md:text-base font-md">Me@me.mail.com</p>
                </div>
                <div id="icon">
                  <img src="../assets/images/mail.svg" />
                </div>
              </div>
            </div>
          </div>
        </div>
        <!-- <div>
                <back-to-top class="scroll-btn transform rotate-90 inline-flex">Back To Top <svg class="-ml-8 transform rotate-90" width="2" height="50" viewBox="0 0 2 50" fill="none" xmlns="http://www.w3.org/2000/svg">
<rect x="2" y="50" width="2" height="50" rx="1" transform="rotate(-180 2 50)" fill="#333333"/>
</svg>
</back-to-top>
            </div> -->
      </div>
      <div class="absolute md:bottom-32 md:right-0 hidden md:flex">
        <div class="transform md:-mt-28 md:-mr-16">
          <svg
            width="2"
            height="50"
            viewBox="0 0 2 50"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <rect
              x="2"
              y="50"
              width="2"
              height="50"
              rx="1"
              transform="rotate(-180 2 50)"
              fill="#333333"
            />
          </svg>
        </div>
        <div
          class="transform rotate-90 text-2xl cursor-pointer"
          @click="backToTop"
        >
          Back to Top
        </div>
      </div>
    </section>

    <FooterComponent />
  </main>
</template>

<script>
import NavbarComponent from "../components/Navbar.vue";
import FooterComponent from "../components/Footer.vue";
//  import { Carousel, Slide } from 'vue-carousel';
// import BackToTop from 'vue-backtotop'

export default {
  name: "Landing",
  data: function() {
    return {
      specialty: 0
      //   contentVisible: true
    };
  },
  mounted() {
    this.slider();
  },
  methods: {
    //   toggle: function(){
    //       this.contentVisible = !this.contentVisible
    //   }
    showSpecialty: function(e) {
      let value = Number(e.target.id);
      if (this.specialty == value) {
        this.specialty = 0;
      } else {
        this.specialty = value;
      }
    },
    backToTop() {
      window.scroll({
        top: 0,
        behavior: "smooth"
      });
    },
    slider() {
      let current = 1;
      setInterval(() => {
        if (screen.width < 768) {
          if (current == 1) {
            this.$refs.slideTwo.click();
            current = 2;
          } else if (current == 2) {
            this.$refs.slideThree.click();
            current = 3;
          } else if (current == 3) {
            this.$refs.slideOne.click();
            current = 1;
          }
        }
      }, 3000);
    }
  },
  components: {
    NavbarComponent,
    FooterComponent
    //   Carousel,
    //  Slide,
    // BackToTop
  }
};
</script>

<style>
.carousel1 {
  /* background: url('../assets/images/carousel1.svg'); */
  background-repeat: no-repeat;
}

.carousel2 {
  background: url("../assets/images/carousel2.svg");
  background-repeat: no-repeat;
  background-size: cover;
}
.carousel3 {
  background: url("../assets/images/hand-world.svg");
  background-repeat: no-repeat;
  background-size: cover;
}
.avg-img {
  background: url("../assets/images/avatar.jpeg");
}
.pro-img {
  background: url("../assets/images/code.png");
}
#portfolio {
  background: url("../assets/images/frame14.svg");
  background-repeat: no-repeat;
}
.soc-img {
  background-image: url("../assets/images/frame24.svg");
  background-repeat: no-repeat;
  background-size: cover;
}

.h-400-px {
  height: 400px;
}
.h-600-px {
  height: 600px;
}
.h-1620-px {
  height: 1620px;
}

.carousel-open:checked + .carousel-item,
.carousel-open-slider:checked + .carousel-item-slider {
  position: static;
  opacity: 100;
}
.carousel-item {
  -webkit-transition: opacity 0.6s ease-out;
  transition: opacity 0.6s ease-out;
}
#carousel-1:checked ~ .control-1,
#carousel-1-slider:checked ~ .control-1-slider,
#carousel-2:checked ~ .control-2,
#carousel-2-slider:checked ~ .control-2-slider,
#carousel-3:checked ~ .control-3,
#carousel-3-slider:checked ~ .control-3-slider {
  display: block;
}
.carousel-indicators,
.carousel-indicators-slider {
  list-style: none;
  margin: 0;
  padding: 0;
  position: absolute;
  bottom: 2%;
  left: 0;
  right: 0;
  text-align: center;
  z-index: 10;
}
#carousel-1:checked
  ~ .control-1
  ~ .carousel-indicators
  li:nth-child(1)
  .carousel-bullet,
#carousel-2:checked
  ~ .control-2
  ~ .carousel-indicators
  li:nth-child(2)
  .carousel-bullet,
#carousel-3:checked
  ~ .control-3
  ~ .carousel-indicators
  li:nth-child(3)
  .carousel-bullet {
  color: #2b6cb0; /*Set to match the Tailwind colour you want the active one to be */
}
/*     HERO     */
.carousel-slider {
  position: relative;
  margin-top: 26px;
}

.carousel-inner-slider {
  position: relative;
  overflow: hidden;
  width: 100%;
}

.carousel-item-slider {
  position: absolute;
  opacity: 0;
  -webkit-transition: opacity 0.6s ease-out;
  transition: opacity 0.6s ease-out;
}

.carousel-item-slider img {
  display: block;
  height: auto;
  max-width: 100%;
}

.carousel-control-slider {
  color: #000;
  cursor: pointer;
  display: none;
  height: 40px;
  line-height: 35px;
  position: absolute;
  top: 50%;
  -webkit-transform: translate(0, -50%);
  cursor: pointer;
  -ms-transform: translate(0, -50%);
  transform: translate(0, -50%);
  text-align: center;
  width: 40px;
  z-index: 10;
}

.carousel-control-slider.prev {
  left: 2%;
}

.carousel-control-slider.next {
  right: 2%;
}

/* .carousel-control-slider:hover {
    color: #aaaaaa;
} */

.carousel-indicators-slider li {
  display: inline-block;
  margin: 0 5px;
}

.carousel-bullet-slider {
  color: #000;
  cursor: pointer;
  display: block;
  font-size: 35px;
}

.carousel-bullet-slider:hover {
  color: #aaaaaa;
}

#carousel-1-slider:checked
  ~ .control-1
  ~ .carousel-indicators-slider
  li:nth-child(1)
  .carousel-bullet-slider,
#carousel-2-slider:checked
  ~ .control-2
  ~ .carousel-indicators-slider
  li:nth-child(2)
  .carousel-bullet-slider,
#carousel-3:checked
  ~ .control-3
  ~ .carousel-indicators-slider
  li:nth-child(3)
  .carousel-bullet-slider {
  color: #428bca;
}
</style>
