<script>
  import logo from '$lib/images/logos/HL_Logo-Colour50.webp';
	import logo_fallback from '$lib/images/logos/HL_Logo-White50.png';

</script>
<header class="bg-white p-2 md:flex">
  <div class="bg-green-200">
    <picture>
      <source srcset={logo} type="image/webp" />
      <img src={logo_fallback} alt="HomesLondon Logo" width="50"/>
    </picture>
  </div>
  <div class="bg-blue-200 flex-grow"></div>
  <div class="bg-red-200 pt-3 text-center">Greg McCarvell, Broker</div>
</header>
