<template>
    <section class="bg-white w-full mt-8" id="contact">
    <div class="lg:py-16 px-4 mx-auto max-w-screen-md">
      <h2
        class="mb-2 text-4xl tracking-tight font-extrabold text-center text-[var(--palette-dark)]"
      >
        Contact
      </h2>
      <p
        class="mb-4 lg:mb-16 font-light text-center text-[var(--palette-grey)] sm:text-xl"
      >
        Have a question? Ask them in the form below
      </p>
      <form action="#" class="space-y-8 flex flex-col">
        <div>
          <label
            for="email"
            class="block mb-2 text-sm font-medium text-[var(--palette-dark)]"
            >Your email</label
          >
          <input
            type="email"
            id="email"
            class="shadow-sm bg-white border border-[var(--palette-light)] text-[var(--palette-grey)] text-sm rounded-lg focus:ring-[var(--palette-dark)] focus:border-[var(--palette-dark)] block w-full p-2.5"
            required
          />
        </div>
        <div>
          <label
            for="subject"
            class="block mb-2 text-sm font-medium text-[var(--palette-dark)]"
            >Subject</label
          >
          <input
            type="text"
            id="subject"
            class="shadow-sm bg-white border border-[var(--palette-light)] text-[var(--palette-grey)] text-sm rounded-lg focus:ring-[var(--palette-dark)] focus:border-[var(--palette-dark)] block w-full p-2.5"
            required
          />
        </div>
        <div class="sm:col-span-2">
          <label
            for="message"
            class="block mb-2 text-sm font-medium text-[var(--palette-dark)]"
            >Your message</label
          >
          <textarea
            id="message"
            rows="6"
            class="shadow-sm bg-white border border-[var(--palette-light)] text-[var(--palette-grey)] text-sm rounded-lg focus:ring-[var(--palette-dark)] focus:border-[var(--palette-dark)] block w-full p-2.5"
          ></textarea>
        </div>
        <button
          type="submit"
          class="py-3 px-5 text-sm self-center font-medium text-center text-[var(--palette-lightest)] rounded-lg bg-[var(--palette-dark)] sm:w-fit hover:bg-[var(--palette-light)] focus:ring-4 focus:outline-none focus:ring-[var(--palette-dark)]"
        >
          Send message
        </button>
      </form>
    </div>
  </section>
</template>