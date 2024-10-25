<script lang="ts">
  let elemCarousel: HTMLDivElement;
  let currentIndex = 0;

  import cosmicsplash from "$lib/assets/cosmicsplash.png";
  import cosmicpricing from "$lib/assets/cosmicpricing.png";
  import cosmicvideos from "$lib/assets/cosmicvideos.png";

  const images = [cosmicsplash, cosmicpricing, cosmicvideos];

  function updateCarousel() {
    elemCarousel.scroll(elemCarousel.clientWidth * currentIndex, 0);
  }

  function carouselLeft(): void {
    currentIndex = currentIndex === 0 ? images.length - 1 : currentIndex - 1;
    updateCarousel();
  }

  function carouselRight(): void {
    currentIndex = currentIndex === images.length - 1 ? 0 : currentIndex + 1;
    updateCarousel();
  }
</script>

<main>
  <div class="container mx-auto px-32 py-8">
    <h2 class="text-2xl font-bold mt-8 mb-4">Cosmic Boogeyman Website</h2>
    <hr class="border-t-2 border-gray-300" />

    <!-- Portfolio Item -->
    <div class="mb-8">
      <div class="card">
        <div class="p-4 m-8 grid grid-cols-1 items-center">
          <!-- Full Images -->
          <div
            bind:this={elemCarousel}
            class="snap-x snap-mandatory scroll-smooth flex overflow-x-auto"
          >
            {#each images as image, index}
              <div
                class="snap-center max-w-full flex justify-center items-center p-4"
                style="display: {currentIndex === index ? 'flex' : 'none'}"
              >
                <img
                  class="max-w-full max-h-full object-contain"
                  src={image}
                  alt={`Cosmic Image ${index + 1}`}
                  loading="lazy"
                />
              </div>
            {/each}
          </div>
          <!-- Arrows Container -->
          <div class="flex justify-center">
            <!-- Button: Left -->
            <button
              type="button"
              class="btn-icon variant-filled-surface hover:bg-primary-500 transition duration-300"
              on:click={carouselLeft}
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="2em"
                height="2em"
                viewBox="0 0 24 24"
                {...$$props}
              >
                <path
                  fill="white"
                  d="M10.05 16.94v-4h8.92l.03-2.01h-8.95V6.94l-5 5Z"
                />
              </svg>
            </button>
            <!-- Button: Right -->
            <button
              type="button"
              class="btn-icon variant-filled-surface hover:bg-primary-500 transition duration-300 ml-4"
              on:click={carouselRight}
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="2em"
                height="2em"
                viewBox="0 0 24 24"
                {...$$props}
              >
                <path
                  fill="white"
                  d="M14 16.94v-4H5.08l-.03-2.01H14V6.94l5 5Z"
                />
              </svg>
            </button>
          </div>
        </div>
      </div>
    </div>
    <h2 class="text-2xl font-bold mt-8 mb-4">Cosmic Boogeyman Website</h2>
    <hr class="border-t-2 border-gray-300" />
    <h3 class="text-md font-semibold mt-4 mb-2">
      HTML/CSS using Sveltekit and Tailwind
    </h3>
    <p class="text-md mb-4 text-gray-300">
      I made this website for a tarot reader who asked me to make them a website
      for their youtube channel to allow people to book online readings with
      them and view their videos.
    </p>

    <!-- Project Details -->
    <div class="mb-8">
      <h3 class="h3 font-semibold mt-4 mb-2">Project Details</h3>
      <p class="text-lg mb-2 font-semibold">Type: Solo Project</p>
      <p class="text-lg mb-2 font-semibold">My Roles:</p>
      <dl class="list-dl">
        <div>
          <span class="badge bg-secondary-500 rounded-full"
            ><svg
              xmlns="http://www.w3.org/2000/svg"
              width="2em"
              height="2em"
              viewBox="0 0 24 24"
              {...$$props}
            >
              <path
                fill="white"
                d="M3 17.25V21h3.75L17.81 9.93l-3.75-3.75zm19.61 1.11l-4.25 4.25l-5.2-5.2l1.77-1.77l1 1l2.47-2.48l1.42 1.42L18.36 17l1.06 1l1.42-1.4zm-16-7.53L1.39 5.64l4.25-4.25L7.4 3.16L4.93 5.64L6 6.7l2.46-2.48l1.42 1.42l-1.42 1.41l1 1zM20.71 7c.39-.39.39-1 0-1.41l-2.34-2.3c-.37-.39-1.02-.39-1.41 0l-1.84 1.83l3.75 3.75z"
              />
            </svg></span
          >
          <span class="flex-auto">
            <dt>Designer</dt>
            <dd class="text-gray-300">
              Created the visual design and layout for the website, ensuring a
              cohesive and appealing aesthetic.
            </dd>
          </span>
        </div>
        <div>
          <span class="badge bg-secondary-500 rounded-full"
            ><svg
              xmlns="http://www.w3.org/2000/svg"
              width="2em"
              height="2em"
              viewBox="0 0 24 24"
              {...$$props}
            >
              <path
                fill="white"
                d="m12.89 3l1.96.4L11.11 21l-1.96-.4zm6.7 9L16 8.41V5.58L22.42 12L16 18.41v-2.83zM1.58 12L8 5.58v2.83L4.41 12L8 15.58v2.83z"
              />
            </svg></span
          >
          <span class="flex-auto">
            <dt>Programmer</dt>
            <dd class="text-gray-300">
              Developed the front-end functionality using Svelte, implementing
              interactive elements like the image carousel or interactive video
              cards.
            </dd>
          </span>
        </div>
        <div>
          <span class="badge bg-secondary-500 rounded-full"
            ><svg
              xmlns="http://www.w3.org/2000/svg"
              width="2em"
              height="2em"
              viewBox="0 0 24 24"
              {...$$props}
            >
              <path
                fill="white"
                d="M16.509 16.845c.147-.507.09-.971-.155-1.316c-.225-.316-.605-.499-1.062-.52l-8.66-.113a.16.16 0 0 1-.133-.07a.2.2 0 0 1-.02-.156a.24.24 0 0 1 .203-.156l8.736-.113c1.035-.049 2.16-.886 2.554-1.913l.499-1.302a.27.27 0 0 0 .014-.168a5.689 5.689 0 0 0-10.937-.584a2.58 2.58 0 0 0-1.794-.498a2.56 2.56 0 0 0-2.223 3.18A3.634 3.634 0 0 0 0 16.751q.002.264.035.527a.174.174 0 0 0 .17.148h15.98a.22.22 0 0 0 .204-.155zm2.757-5.564c-.077 0-.161 0-.239.011c-.056 0-.105.042-.127.098l-.337 1.174c-.148.507-.092.971.154 1.317c.225.316.605.498 1.062.52l1.844.113c.056 0 .105.026.133.07a.2.2 0 0 1 .021.156a.24.24 0 0 1-.204.156l-1.92.112c-1.042.049-2.159.887-2.553 1.914l-.141.358c-.028.072.021.142.099.142h6.597a.174.174 0 0 0 .17-.126a5 5 0 0 0 .175-1.28a4.74 4.74 0 0 0-4.734-4.727"
              />
            </svg></span
          >
          <span class="flex-auto">
            <dt>Backend Developer</dt>
            <dd class="text-gray-300">
              Integrated backend services, including data fetching from
              Cloudflare DB, and populating the database with the Youtube API to
              support dynamic content.
            </dd>
          </span>
        </div>
      </dl>
    </div>
  </div>
</main>
