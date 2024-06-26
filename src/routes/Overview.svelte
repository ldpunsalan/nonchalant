<script>
  import Card from "./Card.svelte";
</script>

<main>
  <section id="overview" class="pt-32">
    <div
      class="flex xs:flex-col sm:flex-row items-center justify-center space-x-4"
    >
      <div>
        <svg
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          stroke-width="1.5"
          stroke="var(--color-theme-2)"
          class="size-12"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="m2.25 15.75 5.159-5.159a2.25 2.25 0 0 1 3.182 0l5.159 5.159m-1.5-1.5 1.409-1.409a2.25 2.25 0 0 1 3.182 0l2.909 2.909m-18 3.75h16.5a1.5 1.5 0 0 0 1.5-1.5V6a1.5 1.5 0 0 0-1.5-1.5H3.75A1.5 1.5 0 0 0 2.25 6v12a1.5 1.5 0 0 0 1.5 1.5Zm10.5-11.25h.008v.008h-.008V8.25Zm.375 0a.375.375 0 1 1-.75 0 .375.375 0 0 1 .75 0Z"
          />
        </svg>
      </div>
      <div>
        <h1
          class="font-bold bg-clip-text text-transparent bg-gradient-to-r from-[#89b4fa] to-[#cba6f7]"
        >
          Overview
        </h1>
      </div>
    </div>
    <div class="flex flex-col">
      <Card class="flex">
        <p class="text-center">
          The Philippine real estate market is influenced by factors like
          economic growth, infrastructure development, and population density.
          There is a pressing issue of housing affordability, particularly in
          urban areas, where real estate prices continue to rise — making
          homeownership increasingly inaccessible for the masses. This has led
          to housing insecurity, forced evictions, informal settlements, and
          social exclusion, exacerbating inequalities and hindering sustainable
          urban development.
        </p>
      </Card>
      <div class="flex xs:flex-col sm:flex-row">
        <Card>
          <div class="flex items-center space-x-2">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="var(--color-theme-1)"
              class="size-6"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M3 3v1.5M3 21v-6m0 0 2.77-.693a9 9 0 0 1 6.208.682l.108.054a9 9 0 0 0 6.086.71l3.114-.732a48.524 48.524 0 0 1-.005-10.499l-3.11.732a9 9 0 0 1-6.085-.711l-.108-.054a9 9 0 0 0-6.208-.682L3 4.5M3 15V4.5"
              />
            </svg>
            <h2>Objective</h2>
          </div>
          <p>
            The aim is to assess the affordability of housing, state of urban
            planning and economic health of the different regions in the
            country.
          </p>
        </Card>
        <Card>
          <div class="flex items-center space-x-2">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="var(--color-theme-1)"
              class="size-6"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M9.879 7.519c1.171-1.025 3.071-1.025 4.242 0 1.172 1.025 1.172 2.687 0 3.712-.203.179-.43.326-.67.442-.745.361-1.45.999-1.45 1.827v.75M21 12a9 9 0 1 1-18 0 9 9 0 0 1 18 0Zm-9 5.25h.008v.008H12v-.008Z"
              />
            </svg>
            <h2>Problem</h2>
          </div>
          <p>
            Affordable housing is increasingly becoming a problem amidst the
            rising prices of real estate in across the country.
          </p>
        </Card>
        <Card>
          <div class="flex items-center space-x-2">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="var(--color-theme-1)"
              class="size-6"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M12 9v3.75m9-.75a9 9 0 1 1-18 0 9 9 0 0 1 18 0Zm-9 3.75h.008v.008H12v-.008Z"
              />
            </svg>

            <h2>Solution</h2>
          </div>
          <p>
            Pinpoint areas where housing is becoming inaccessible and expensive
            through a statistical comparative analysis of real estate prices and
            the price-to-floor area ratio among property types across different
            Philippine cities.
          </p>
        </Card>
      </div>
      <div class="flex xs:flex-col sm:flex-row">
        <Card>
          <div class="flex items-center space-x-2">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="var(--color-theme-1)"
              class="size-6"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M15 12H9m12 0a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z"
              />
            </svg>
            <h2>Null Hypothesis</h2>
          </div>
          <p>
            There is no significant difference between prices of similar types
            of real estate in highly urbanized cities compared to non-highly
            urbanized areas.
          </p>
        </Card>
        <Card>
          <div class="flex items-center space-x-2">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="var(--color-theme-1)"
              class="size-6"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M12 9v6m3-3H9m12 0a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z"
              />
            </svg>

            <h2>Alternative Hypothesis</h2>
          </div>
          <p>
            Real estate in more highly urbanized cities of the Philippines are
            more expensive than their counterparts in non-highly urbanized areas
            of the country.
          </p>
        </Card>
      </div>
    </div>
  </section>
</main>

<style>
</style>
