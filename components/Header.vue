<template>
  <div
    class="fixed w-full p-6 bg-white dark:bg-slate-800* dark:text-white* shadow-sm h-20 flex justify-between items-center"
  >
    <div class="logo flex items-center gap-1 text-2xl">
      <span><img src="~/assets/images/logo-uxe.svg" alt="" /></span> UXE Library
    </div>
    <div class="content flex items-center gap-4">
      <!-- <div class="navigation">
        <ul class="flex gap-6">
          <li><a href="">Get Started</a></li>
          <li><a href="">Installation</a></li>
          <li><a href="">Components</a></li>
          <li><a href="">Contact UXE</a></li>
        </ul>
      </div> -->
      <div class="searchbar">
        <label class="relative block">
          <span class="sr-only">Search</span>
          <span class="absolute inset-y-0 left-0 flex items-center pl-2">
            <img src="~/assets/images/icon/icon-search.svg" alt="" />
          </span>
          <input
            class="placeholder:text-slate-400 block bg-gray-100 w-96 rounded-md py-2 pl-9 pr-3 shadow-sm focus:outline-none sm:text-sm"
            placeholder="Search for anything..."
            type="text"
            name="search"
          />
        </label>
      </div>
      <div class="icon">
        <img src="~/assets/images/icon/icon-light.svg" alt="" />
      </div>
      <div class="icon">
        <img src="~/assets/images/icon/icon-notif.svg" alt="" />
      </div>
      <div class="profile text-base flex gap-2 items-center">
        <span>
          <img src="~/assets/images/avatar-male.png" alt="" />
        </span>
        Hi Abink
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>