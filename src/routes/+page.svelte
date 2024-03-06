<script>
  import "./app.css";
  import Bottom from "../lib/components/bottom.svelte";
  import Right from "../lib/components/right.svelte";
</script>

<main class="font-league m-0">
  <div class="side-container flex">
    <div class="relative w-[90%]">
        <div class="absolute header flex items-center top-4 left-4 z-10">
            <a href="/home">
                <img src="images/logo.svg" alt="" />
            </a>
            <div class="menu ml-8 flex text-white text-lg">
                <ul class="flex">
                    <li class="mr-8">
                        <a href="/home">home</a>
                    </li>
                    <li class="mr-8">
                        <a href="/about">shop</a>
                    </li>
                    <li class="mr-8">
                        <a href="/services">about</a>
                    </li>
                    <li>
                        <a href="/portfolio">contact</a>
                    </li>
                </ul>
            </div>
        </div>
        <div class="main-image w-full md:w-[100%]">
            <img src="/images/desktop-image-hero-1.jpg" alt="" />
        </div>
    </div>
    <div class="left-top">
        <Right />
    </div>
  </div>
  <Bottom />
</main>

