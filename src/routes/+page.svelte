<script>
  import ynguyen from '$lib/assets/ynguyen.webp';
  import vido from '$lib/assets/vietdoan.webp';
  import loc from '$lib/assets/loc.webp';
</script>

<svelte:head>
  <title>SuperBo's tech blog</title>
  <meta name="description" content="Personal blog of SuperBo">
</svelte:head>

<!-- Outer Div -->
<div class="font-inter mx-auto w-full md:w-3/5 px-0 flex-auto bg-white">
  <!-- Top Line -->
  <header id="top-line" class="flex flex-row justify-between">
    <div class="text-5xl">
      <span class="font-light">See what we’ve<span><br>
      <span class="font-semibold">written lately</span>
    </div>
    <div class="text-right">
      <ul class="flex flex-row justify-center -space-x-5 overflow-visible">
        <li class="z-20">
          <a href="#">
            <img class="rounded-full w-20 h-20 border-4 border-white hover:-translate-y-1 duration-200" src={ynguyen} alt="user image" />
          </a>
        </li>
        <li class="z-10">
          <a href="https://imvido.com/">
            <img class="rounded-full w-20 h-20 border-4 border-white hover:-translate-y-1 duration-200" src={vido} alt="user image" />
          </a>
        </li>
        <li class="z-0">
          <a href="#">
            <img class="rounded-full w-20 h-20 border-4 border-white hover:-translate-y-1 duration-200" src={loc} alt="user image" />
          </a>
        </li>
      </ul>
      <span class="mr-2">Meet our authors</span>
    </div>
  </header>
  <!-- Blogs Summary -->
  <section id="blogs-summary">
    <article class="pt-6 flex flex-col">
      <h2 class="text-xl font-semibold">How I killed bug</h2>
      <p class="content">
        The tremendous adventure to kill Bug in Hollow Knight.
      </p>
      <span class="text-right italic">Dec 15th, 2022</span>
    </article>
    <article class="pt-6 flex flex-col">
      <h2 class="text-xl font-semibold">My path to Parsing SQL</h2>
      <p>
        Test Content Summary.
      </p>
      <span class="text-right italic">Dec 1st, 2022</span>
    </article>
  </section>
</div>
