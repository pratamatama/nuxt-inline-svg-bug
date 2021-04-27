<template>
  <div class="fixed inset-0 z-40 p-8 overflow-y-auto">
    <ul class="pt-32">
      <li class="mb-4 last:mb-0">
        <NuxtLink
          to="/"
          exact
          class="font-bold text-4xl capitalize"
          active-class="font-bold text-4xl capitalize text-blue-600"
          >home</NuxtLink
        >
      </li>
      <li class="mb-4 last:mb-0">
        <NuxtLink
          to="/gallery"
          class="font-bold text-4xl capitalize"
          active-class="font-bold text-4xl capitalize text-blue-600"
          >gallery</NuxtLink
        >
      </li>
      <li class="mb-4 last:mb-0">
        <NuxtLink
          to="/services"
          class="font-bold text-4xl capitalize"
          active-class="font-bold text-4xl capitalize text-blue-600"
          >services</NuxtLink
        >
      </li>
      <li class="mb-4 last:mb-0">
        <NuxtLink
          to="/catalog"
          class="font-bold text-4xl capitalize"
          active-class="font-bold text-4xl capitalize text-blue-600"
          >catalog</NuxtLink
        >
      </li>
      <li class="mb-4 last:mb-0">
        <NuxtLink
          to="/career"
          class="font-bold text-4xl capitalize"
          active-class="font-bold text-4xl capitalize text-blue-600"
          >career</NuxtLink
        >
      </li>
    </ul>
    <div class="pt-12 text-gray-500">
      <span>Company Name</span>
      <p class="pt-2">Company Address</p>
    </div>
    <div class="pt-12 text-gray-500">
      <a
        href="https://twitter.com/prisma_id"
        target="_blank"
        class="inline-block mr-4 last:mr-0"
      >
        <IconTwitter class="w-6 h-6" />
      </a>
      <a
        href="https://facebook.com/prisma_id"
        target="_blank"
        class="inline-block mr-4 last:mr-0"
      >
        <IconFacebook class="w-6 h-6" />
      </a>
      <a
        href="https://instagram.com/prisma_id"
        target="_blank"
        class="inline-block mr-4 last:mr-0"
      >
        <IconInstagram class="w-6 h-6" />
      </a>
      <a
        href="https://linkedin.com/prisma_id"
        target="_blank"
        class="inline-block mr-4 last:mr-0"
      >
        <IconLinkedin class="w-6 h-6" />
      </a>
    </div>
  </div>
</template>
