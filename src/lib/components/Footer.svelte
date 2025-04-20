<script>
  import herobg from "$lib/img/hero-bg.png";
  import herooverlay from "$lib/img/hero-overlay.png";
</script>

<div class="container mx-auto px-4 md:px-8 py-12 bg-blue-500">
  <div class="h-[60vh] md:h-[30vh] w-full rounded-3xl relative overflow-hidden">
    <div class="absolute inset-0 w-full h-full">
      <img
        src={herobg}
        alt="Background"
        class="absolute inset-0 w-full h-full object-cover"
      />
      <div
        class="absolute inset-0 bg-[#218BEC] opacity-70 mix-blend-multiply"
      ></div>
    </div>
    <div class="absolute inset-0 w-full h-full">
      <img
        src={herooverlay}
        alt="Overlay"
        class="absolute inset-0 w-full h-full object-cover"
      />
      <div
        class="absolute inset-0 bg-[#218BEC] opacity-40 mix-blend-overlay"
      ></div>
    </div>
    <div class="absolute inset-0 flex items-center">
      <div
        class="w-full px-4 sm:px-8 md:px-16 flex flex-col md:flex-row justify-between items-start md:items-center z-10 gap-8"
      >
        <div class="max-w-xl">
          <h2 class="text-3xl md:text-4xl font-bold text-white mb-4">
            Noodgeval? Wij staan 24/7 voor u klaar!
          </h2>
          <p class="text-lg text-gray-100">
            Of het nu gaat om een lekkage, stroomstoring of slotprobleem onze
            professionals komen direct naar u toe.
          </p>
        </div>
        <div class="max-w-md">
          <a
            href="tel:0219830438"
            class="bg-yellow-300 hover:bg-yellow-500 text-gray-900 font-bold py-4 px-8 transition duration-300 mb-4 rounded-xl inline-flex items-center gap-2"
          >
            <svg
              class="hidden lg:flex"
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              ><path
                fill="currentColor"
                d="M6.62 10.79c1.44 2.83 3.76 5.14 6.59 6.59l2.2-2.2c.27-.27.67-.36 1.02-.24c1.12.37 2.33.57 3.57.57c.55 0 1 .45 1 1V20c0 .55-.45 1-1 1c-9.39 0-17-7.61-17-17c0-.55.45-1 1-1h3.5c.55 0 1 .45 1 1c0 1.25.2 2.45.57 3.57c.11.35.03.74-.25 1.02z"
              /></svg
            >
            Bel Direct: +31 6 1234 5678
          </a>
          <p class="text-sm text-gray-100">
            24/7 beschikbaar, elk moment van de dag.
          </p>
        </div>
      </div>
    </div>
  </div>
</div>
<footer
  class="footer sm:footer-horizontal footer-center text-white bg-blue-500 p-4"
>
  <aside>
    <p>
      Copyright © {new Date().getFullYear()} - Alle rechten voorbehouden. SpoedSpecialist
    </p>
  </aside>
</footer>

