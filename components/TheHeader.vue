<template>
  <header class="flex h-24 items-center py-4">
    <div class="container mx-auto flex items-center">
      <!-- Mobile -->
      <div class="flex w-full items-center justify-between xl:hidden">
        <NuxtLink to="/">
          <NuxtImg class="h-[44px] w-[85px]" src="/images/logo-small.svg" />
        </NuxtLink>
        <NuxtImg
          class="h-12 w-12 cursor-pointer"
          src="/images/burger-menu.svg"
        />
      </div>
      <!-- End -->
      <!-- Desktop -->
      <div class="hidden w-full items-center justify-between xl:flex">
        <NuxtLink to="/">
          <NuxtImg
            class="h-[60px] w-[251px] xl:w-[200px]"
            src="/images/logo-full-white.svg"
          />
        </NuxtLink>
        <div class="relative cursor-pointer">
          <div class="flex items-center">
            <NuxtImg
              class="mr-[12px] h-[21px] w-[21px]"
              src="/images/flag-usa.svg"
            ></NuxtImg>
            <span class="font-inter text-white">Импорт из США</span>
            <NuxtImg
              class="ml-5 h-3 w-3 xl:ml-2"
              src="/images/chevron-down.svg"
            ></NuxtImg>
          </div>
        </div>
        <nav class="flex">
          <NuxtLink class="pr-9 font-inter text-white xl:pr-4" to="/"
            >Аукционы</NuxtLink
          >
          <NuxtLink class="pr-9 font-inter text-white xl:pr-4" to="/"
            >В наличии</NuxtLink
          >
          <NuxtLink class="pr-9 font-inter text-white xl:pr-4" to="/"
            >Доставка</NuxtLink
          >
          <NuxtLink class="pr-9 font-inter text-white xl:pr-4" to="/"
            >Отзывы</NuxtLink
          >
          <NuxtLink class="pr-9 font-inter text-white xl:pr-4" to="/"
            >FAQ</NuxtLink
          >
          <NuxtLink class="font-inter text-white" to="/">Контакты</NuxtLink>
        </nav>
        <div class="flex flex-col">
          <div class="flex items-center">
            <NuxtImg
              src="/images/whatsapp-icon.svg"
              class="mr-2 h-6 w-6"
            ></NuxtImg>
            <span class="text-lg text-white">+7 961 539 29 29</span>
          </div>
          <div class="mt-2 flex items-center">
            <NuxtImg
              src="/images/telegram-icon.svg"
              class="mr-2 h-6 w-6"
            ></NuxtImg>
            <span class="text-sm font-bold text-[#979797]"
              >Заказать звонок</span
            >
          </div>
        </div>
        <NuxtImg
          src="/images/user-round.svg"
          class="h-12 w-12 cursor-pointer"
        ></NuxtImg>
      </div>
      <!-- End -->
    </div>
  </header>
</template>

<script setup></script>

<style module></style>
