<script>
  import herobg from "$lib/img/hero-bg.png";
  import herobottomround from "$lib/img/hero-bottom-round.png";
  import herooverlay from "$lib/img/hero-overlay.png";
  import heropersons from "$lib/img/hero-persons.png";
  import herotopright from "$lib/img/hero-top-right.png";
</script>

<div class="px-8 pb-8">
  <div class="h-[80vh] w-full rounded-3xl relative overflow-hidden">
    <!-- Base background image with darker blue overlay -->
    <div class="absolute inset-0 w-full h-full">
      <img
        src={herobg}
        alt="Background"
        class="absolute inset-0 w-full h-full object-cover"
      />
      <!-- Dark blue overlay to achieve #218BEC color -->
      <div
        class="absolute inset-0 bg-[#218BEC] opacity-70 mix-blend-multiply"
      ></div>
    </div>
    <!-- Overlay image with darker blue filter -->
    <div class="absolute inset-0 w-full h-full">
      <img
        src={herooverlay}
        alt="Overlay"
        class="absolute inset-0 w-full h-full object-cover"
      />
      <!-- Additional dark blue tint for overlay -->
      <div
        class="absolute inset-0 bg-[#218BEC] opacity-40 mix-blend-overlay"
      ></div>
    </div>
    <!-- Top right element - made slightly transparent -->
    <img
      src={herotopright}
      alt="Top Right"
      class="absolute top-0 right-0 w-auto h-auto opacity-80"
    />
    <!-- Persons image - only moved right -->
    <img
      src={heropersons}
      alt="Persons"
      class="absolute inset-0 w-full h-full object-contain translate-x-75 scale-125"
    />
    <!-- Bottom round element -->
    <div class="absolute -bottom-5 w-full">
      <!-- Original image with yellow tint filter -->
      <img src={herobottomround} alt="Bottom Round" class="w-full" />
    </div>
    <!-- Text Content Container -->
    <div class="absolute inset-0 flex items-center">
      <div class="ml-16 max-w-lg z-10">
        <!-- Heading -->
        <h1 class="text-5xl font-bold text-white mb-4">
          Spoed Loodgieter, Elektricien of Slotenmaker Nodig? Wij Helpen Direct!
        </h1>
        <!-- Undertext / Description -->
        <p class="text-xl text-gray-100 mb-8">
          Buitengesloten of groot loodgietersprobleem? Onze experts zijn altijd
          bereikbaar.
        </p>
        <!-- Button - Fixed with flex display -->
        <a
          href="tel:0219830438"
          class="bg-yellow-300 hover:bg-yellow-500 text-gray-900 font-bold py-4.5 px-8 transition duration-300 mb-4 rounded-xl inline-flex items-center gap-2"
        >
          <svg
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
        <!-- Small text under button -->
        <p class="text-sm text-gray-200 max-w-md">
          24/7 beschikbaar, neem op elk moment contact met ons op.
        </p>
      </div>
    </div>
  </div>
</div>
