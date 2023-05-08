<template>
  <nav
      class="bg-white fixed w-full z-30 top-0 left-0 border-b border-[var(--palette-light)]"
    >
      <div
        class="max-w-screen-xl flex flex-wrap items-center justify-between mx-auto p-4"
      >
        <a href="#" class="flex items-center">
          <span
            class="self-center text-2xl font-semibold whitespace-nowrap"
            >Anna Kowalska</span
          >
        </a>
        <button
          data-collapse-toggle="navbar-default"
          type="button"
          class="inline-flex items-center p-2 ml-3 text-sm text-[var(--palette-dark)] rounded-lg md:hidden hover:bg-[var(--palette-lightest)] focus:outline-none focus:ring-2 focus:ring-[var(--palette-lightest)]"
          aria-controls="navbar-default"
          aria-expanded="false"
        >
          <span class="sr-only">Open main menu</span>
          <svg
            class="w-6 h-6"
            aria-hidden="true"
            fill="currentColor"
            viewBox="0 0 20 20"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              fill-rule="evenodd"
              d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z"
              clip-rule="evenodd"
            ></path>
          </svg>
        </button>
        <div class="hidden w-full md:block md:w-auto" id="navbar-default">
          <ul
            class="font-medium flex flex-col p-4 md:p-0 mt-4 border border-[var(--palette-lightest)] rounded-lg bg-gray-50 md:flex-row md:space-x-8 md:mt-0 md:border-0 md:bg-white"
          >
            <li>
              <a
                href="#home"
                class="block py-2 pl-3 pr-4 text-[var(--palette-dark)] rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-[var(--palette-light)] md:p-0"
                >Home</a
              >
            </li>
            <li>
              <a
                href="#gallery"
                class="block py-2 pl-3 pr-4 text-[var(--palette-dark)] rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-[var(--palette-light)] md:p-0"
                >Gallery</a
              >
            </li>
            <li>
              <a
                href="#pricing"
                class="block py-2 pl-3 pr-4 text-[var(--palette-dark)] rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-[var(--palette-light)] md:p-0"
                >Pricing</a
              >
            </li>
            <li>
              <a
                href="#contact"
                class="block py-2 pl-3 pr-4 text-[var(--palette-dark)] rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-[var(--palette-light)] md:p-0"
                >Contact</a
              >
            </li>
          </ul>
        </div>
      </div>
    </nav>
</template>