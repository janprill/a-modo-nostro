<template>
  <Layout>
    <div>
      <navbar-component></navbar-component>
      <main>
        <div
          class="relative pt-16 pb-32 flex content-center items-center justify-center font-serif"
          style="min-height: 75vh;"
        >
          <div
            class="absolute top-0 w-full h-full bg-center bg-cover"
            style='background-image: url("https://images.unsplash.com/photo-1542834369-f10ebf06d3e0?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=crop&amp;w=1267&amp;q=80");'
          >
            <span
              id="blackOverlay"
              class="w-full h-full absolute opacity-50 bg-black"
            ></span>
          </div>
          <div class="container relative mx-auto">
            <div class="items-center flex flex-wrap">
              <div class="w-full px-4 mx-auto text-center">
                <div class="pr-12">
                  <h1 class="text-white font-semibold text-6xl font-marker">
                    A Modo Nostro
                  </h1>
                  <p class="mt-4 text-2xl text-gray-200 font-serif font-bold">
                    Mit der Familie original italienische Pizza und Pasta 
                    nach Hause bestellen und genießen.
                  </p>
                </div>
                <div class="border max-w-3xl mx-auto rounded shadow mt-8 p-6">
                  <p class="mt-4 text-lg text-gray-200 font-serif">
                    Jetzt unter 87 44 83 telefonisch bestellen!  
                  </p>
                  <p class="mt-4 text-lg text-gray-200 font-serif">
                    Wir sind täglich bis auf Mittwochs von 17.30-22.00 Uhr für Euch da.
                    Sonntags von 11.30 - 16.00 Uhr.
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div
            class="top-auto bottom-0 left-0 right-0 w-full absolute pointer-events-none overflow-hidden"
            style="height: 70px; transform: translateZ(0px);"
          >
            <svg
              class="absolute bottom-0 overflow-hidden"
              xmlns="http://www.w3.org/2000/svg"
              preserveAspectRatio="none"
              version="1.1"
              viewBox="0 0 2560 100"
              x="0"
              y="0"
            >
              <polygon
                class="text-gray-300 fill-current"
                points="2560 0 2560 100 0 100"
              ></polygon>
            </svg>
          </div>
        </div>
        <section class="pb-20 bg-gray-300 -mt-24">
          <div class="container mx-auto px-4">
            <div class="flex flex-wrap">
              <div class="lg:pt-12 pt-6 w-full md:w-4/12 px-4 text-center">
                <div
                  class="relative flex flex-col min-w-0 break-words bg-white w-full mb-8 shadow-lg rounded-lg"
                >
                  <div class="px-4 py-5 flex-auto">
                    <div
                      class="text-white p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-green-400"
                    >
                      <i class="fas fa-award"></i>
                    </div>
                    <h6 class="text-xl font-semibold">Pizza</h6>
                    <p class="mt-2 mb-4 text-gray-600">
                      Ein wenig text zur pizza. Lorem ipsum dolor sit, amet consectetur adipisicing elit. Tenetur error dicta id est ipsum exercitationem? Amet sint temporibus animi, ratione totam iste voluptate est quae deleniti, tempora eveniet nobis rerum!
                    </p>
                  </div>
                </div>
              </div>
              <div class="w-full md:w-4/12 px-4 text-center">
                <div
                  class="relative flex flex-col min-w-0 break-words bg-white w-full mb-8 shadow-lg rounded-lg"
                >
                  <div class="px-4 py-5 flex-auto">
                    <div
                      class="text-white p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-gray-100"
                    >
                      <i class="fas fa-retweet"></i>
                    </div>
                    <h6 class="text-xl font-semibold">Pasta</h6>
                    <p class="mt-2 mb-4 text-gray-600">
                      Informatives zur Pasta. Lorem, ipsum dolor sit amet consectetur adipisicing elit. Magnam adipisci tempora eum iure minus autem dicta, commodi pariatur, dolores repellendus nisi cumque non quod qui quisquam nostrum eveniet assumenda corrupti?
                    </p>
                  </div>
                </div>
              </div>
              <div class="pt-6 w-full md:w-4/12 px-4 text-center">
                <div
                  class="relative flex flex-col min-w-0 break-words bg-white w-full mb-8 shadow-lg rounded-lg"
                >
                  <div class="px-4 py-5 flex-auto">
                    <div
                      class="text-white p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-red-500"
                    >
                      <i class="fas fa-fingerprint"></i>
                    </div>
                    <h6 class="text-xl font-semibold">Rustikales</h6>
                    <p class="mt-2 mb-4 text-gray-600">
                      Informationen zu den rustikalen Gerichten. Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quod nisi labore molestiae dolorum sint totam enim aliquam laborum officiis neque, quasi nesciunt blanditiis. Officiis inventore aliquid voluptatem, libero expedita voluptatum!
                    </p>
                  </div>
                </div>
              </div>
            </div>
            <div class="flex flex-wrap items-center mt-32">
              <div class="w-full md:w-5/12 px-4 mr-auto ml-auto">
                <div
                  class="text-gray-600 text-center inline-flex items-center justify-center w-16 h-16 mb-6 shadow-lg rounded-full bg-gray-100"
                >
                  <img class="rounded-full" src="/images/svb.jpg"  />
                </div>
                <h3 class="text-3xl mb-2 font-semibold leading-normal">
                  "a modo nostro". Die italienische Gastronomie am Tennisplatz des SVB
                </h3>
                <p
                  class="text-lg font-light leading-relaxed mt-4 mb-4 text-gray-700"
                >
                  Lorem ipsum dolor sit amet consectetur adipisicing elit. Repudiandae pariatur laudantium ut quo sequi doloribus veniam corrupti similique error molestias quos reprehenderit impedit provident, sunt, saepe reiciendis quia magni delectus.
                </p>
                <p
                  class="text-lg font-light leading-relaxed mt-0 mb-4 text-gray-700"
                >
                  Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nam alias, recusandae ipsam sit iusto quis commodi eius, voluptate, rem dolor architecto cum esse corporis eum. Iure a laboriosam illum cum.
                </p>
              </div>
              <div class="w-full md:w-4/12 px-4 mr-auto ml-auto">
                <img
                  alt="..."
                  class="max-w-full rounded-lg shadow-lg"
                  src="https://images.unsplash.com/photo-1556761223-4c4282c73f77?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=crop&amp;w=634&amp;q=80"
                />
              </div>
            </div>
          </div>
        </section>
        <section class="relative py-20">
          <div
            class="bottom-auto top-0 left-0 right-0 w-full absolute pointer-events-none overflow-hidden -mt-20"
            style="height: 80px; transform: translateZ(0px);"
          >
            <svg
              class="absolute bottom-0 overflow-hidden"
              xmlns="http://www.w3.org/2000/svg"
              preserveAspectRatio="none"
              version="1.1"
              viewBox="0 0 2560 100"
              x="0"
              y="0"
            >
              <polygon
                class="text-white fill-current"
                points="2560 0 2560 100 0 100"
              ></polygon>
            </svg>
          </div>
          <div class="container mx-auto px-4">
            <div class="items-center flex flex-wrap">
              <div class="w-full md:w-4/12 ml-auto mr-auto px-4">
                <img
                  alt="..."
                  class="max-w-full rounded-lg shadow-lg"
                  src="https://images.unsplash.com/photo-1545016803-a7e357a737e4?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=crop&amp;w=634&amp;q=80"
                />
              </div>
              <div class="w-full md:w-5/12 ml-auto mr-auto px-4">
                <div class="md:pr-12">
                  <div
                    class="text-gray-600 text-center inline-flex items-center justify-center w-16 h-16 mb-6 shadow-lg rounded-full bg-gray-100"
                  >
                    <img class="rounded-full" src="/images/svb.jpg"  />
                  </div>
                  <h3 class="text-3xl font-semibold">So ticken wir</h3>
                  <p class="mt-4 text-lg leading-relaxed text-gray-600">
                    Unsere Gäste mögen uns und unser Essen weil, Lorem ipsum dolor sit, amet consectetur adipisicing elit. At sequi dolorem, debitis excepturi tenetur neque quaerat repellendus voluptas earum ex tempore accusantium modi voluptates? Modi rerum neque eligendi ad tempore.
                  </p>
                  <ul class="list-none mt-6">
                    <li class="py-2">
                      <div class="flex items-center">
                        <div>
                          <span
                            class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-pink-600 bg-pink-200 mr-3"
                            ><i class="fas fa-fingerprint"></i
                          ></span>
                        </div>
                        <div>
                          <h4 class="text-gray-600">
                            Mit liebe gekocht.
                          </h4>
                        </div>
                      </div>
                    </li>
                    <li class="py-2">
                      <div class="flex items-center">
                        <div>
                          <span
                            class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-pink-600 bg-pink-200 mr-3"
                            ><i class="fab fa-html5"></i
                          ></span>
                        </div>
                        <div>
                          <h4 class="text-gray-600">
                            Frische Zutaten
                          </h4>
                        </div>
                      </div>
                    </li>
                    <li class="py-2">
                      <div class="flex items-center">
                        <div>
                          <span
                            class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-pink-600 bg-pink-200 mr-3"
                            ><i class="far fa-paper-plane"></i
                          ></span>
                        </div>
                        <div>
                          <h4 class="text-gray-600">
                            Ehrliche Preise
                          </h4>
                        </div>
                      </div>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </section>
        <section class="pt-20 pb-48">
          <div class="container mx-auto px-4">
            <div class="flex flex-wrap justify-center text-center mb-24">
              <div class="w-full lg:w-6/12 px-4">
                <h2 class="text-4xl font-semibold">Wir sind für Euch da</h2>
                <p class="text-lg leading-relaxed m-4 text-gray-600">
                  In der Krise ist es schön, ein Stück Normalität zu haben. Wir halten die 
                  Flagge vom "a modo nostro" hoch und freuen uns über jede Bestellung.
                </p>
              </div>
            </div>
            <div class="flex flex-wrap justify-center text-center">
              <div class="w-full md:w-6/12 lg:w-3/12 lg:mb-0 mb-12 px-4">
                <div class="px-6">
                  <img
                    alt="..."
                    src="/images/icons/chef-hat.png"
                    class="shadow-lg rounded-full max-w-full mx-auto"
                    style="max-width: 120px;"
                  />
                  <div class="pt-6 text-center">
                    <h5 class="text-xl font-bold">Angelo</h5>
                    <p class="mt-1 text-sm text-gray-500 uppercase font-semibold">
                      a modo nostro
                    </p>
                  </div>
                </div>
              </div>
              <div class="w-full md:w-6/12 lg:w-3/12 lg:mb-0 mb-12 px-4">
                <div class="px-6">
                  <img
                    alt="..."
                    src="/images/icons/chef-hat.png"
                    class="shadow-lg rounded-full max-w-full mx-auto"
                    style="max-width: 120px;"
                  />
                  <div class="pt-6 text-center">
                    <h5 class="text-xl font-bold">Lars</h5>
                    <p class="mt-1 text-sm text-gray-500 uppercase font-semibold">
                      a modo nostro
                    </p>
                  </div>
                </div>
              </div>

            </div>
          </div>
        </section>
        <section class="pb-20 relative block bg-gray-900">
          <div
            class="bottom-auto top-0 left-0 right-0 w-full absolute pointer-events-none overflow-hidden -mt-20"
            style="height: 80px; transform: translateZ(0px);"
          >
            <svg
              class="absolute bottom-0 overflow-hidden"
              xmlns="http://www.w3.org/2000/svg"
              preserveAspectRatio="none"
              version="1.1"
              viewBox="0 0 2560 100"
              x="0"
              y="0"
            >
              <polygon
                class="text-gray-900 fill-current"
                points="2560 0 2560 100 0 100"
              ></polygon>
            </svg>
          </div>

          <div class="container mx-auto px-4 lg:pt-24 lg:pb-64">
            <div class="flex flex-wrap text-center justify-center text-white">
              <div class="w-full lg:w-6/12 px-4">
                <h2 class="text-4xl font-semibold text-white">Unsere Karte</h2>
                <p>
                  TODO: Gerichte mit Preisen auflisten
                </p>
                <p class="mt-4 text-lg text-gray-200 font-serif">
                  Jetzt unter 87 44 83 telefonisch bestellen!  
                </p>
                <p class="mt-4 text-lg text-gray-200 font-serif">
                  Wir sind täglich bis auf Mittwochs von 17.30-22.00 Uhr für Euch da.
                  Sonntags von 11.30 - 16.00 Uhr.
                </p>
              </div>
            </div>
          </div>
        </section>

      </main>
      <footer-component></footer-component>
    </div>
  </Layout>
</template>
<script>
import NavbarComponent from "../components/Navbar.vue";
import FooterComponent from "../components/Footer.vue";
export default {
  name: "landing-page",
  components: {
    NavbarComponent,
    FooterComponent
  }
}
</script>
