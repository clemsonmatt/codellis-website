<template>
  <div class="pb-20">
    <img
      alt="Logo"
      src="../assets/logo-23-horizontal.png"
      class="w-1/3 mx-auto md:w-1/4 lg:w-1/6"
    />
    <div class="container mx-auto my-20">
      <h1 class="hero">Custom applications</h1>
      <h1 class="hero">for your business</h1>
      <p class="w-full mx-auto my-10 text-2xl md:w-3/4 lg:w-1/2">
        Why use software that doesn't work for your business? Build a tool designed around your
        specific needs.
      </p>
      <a
        href="mailto:matt@codellis.com?subject=Codellis - Schedule my FREE consultation"
        class="btn-custom"
        >Schedule a free consultation</a
      >
    </div>
  </div>

  <div class="py-20 shadow-2xl bg-slate-50 shadow-slate-800">
    <div class="container mx-auto">
      <h1 class="section">Services</h1>
      <hr class="w-1/12 mx-auto my-10 border-slate-800" />
      <div class="card">
        <div class="grid grid-cols-2 gap-4">
          <div class="my-auto">
            <h3 class="mb-5 text-3xl font-semibold" id="service-website">Websites</h3>
            <ul class="text-xl">
              <li>Build a brand to help your business stand out.</li>
              <li>Analytics to help you increase productivity.</li>
            </ul>
          </div>
          <div>
            <img alt="Logo" src="../assets/icons/website.png" class="w-1/3 mx-auto" />
          </div>
        </div>
      </div>
      <div class="mt-10 card">
        <div class="grid grid-cols-2 gap-4">
          <div>
            <img alt="Logo" src="../assets/icons/mobile.png" class="w-1/3 mx-auto" />
          </div>
          <div class="my-auto">
            <h3 class="mb-5 text-3xl font-semibold" id="service-mobile">Mobile Apps</h3>
            <ul class="text-xl">
              <li>Make your product easy to use.</li>
              <li>iOS &amp; Android.</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="mt-10 card">
        <div class="grid grid-cols-2 gap-4">
          <div class="my-auto">
            <h3 class="mb-5 text-3xl font-semibold" id="service-enterprise">Enterprise Software</h3>
            <ul class="text-xl">
              <li>Create software designed for your business.</li>
              <li>Move your paper process to a digital format.</li>
            </ul>
          </div>
          <div>
            <img alt="Logo" src="../assets/icons/cloud.png" class="w-1/3 mx-auto" />
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="bg-dark">
    <div class="py-10 bg-white shadow-2xl shadow-slate-800">
      <div class="container mx-auto my-20">
        <h1 class="section">How it works</h1>
        <hr class="w-1/12 mx-auto my-10 border-slate-800" />
        <h4 class="mb-5 text-3xl font-semibold uppercase">Process</h4>
        <div class="grid gap-4 md:grid-cols-3">
          <div class="card">
            <h3 class="lg:text-xl text-slate-400">Step 1</h3>
            <h3 class="mb-5 text-2xl font-semibold md:text-xl lg:text-3xl">Planning</h3>
            <p class="text-lg">
              Let's figure out how to get your idea into a real working product.
            </p>
          </div>
          <div class="card">
            <h3 class="lg:text-xl text-slate-400">Step 2</h3>
            <h3 class="mb-5 text-2xl font-semibold md:text-xl lg:text-3xl">Implementation</h3>
            <p class="text-lg">
              An iterative process where communication and reviews are essential.
            </p>
          </div>
          <div class="card">
            <h3 class="lg:text-xl text-slate-400">Step 3</h3>
            <h3 class="mb-5 text-2xl font-semibold md:text-xl lg:text-3xl">Commercialization</h3>
            <p class="text-lg">
              Once you are happy with the product, let's deploy it to the world!
            </p>
          </div>
        </div>
        <hr class="w-1/12 mx-auto my-10 border-slate-800" />
        <h4 class="mb-5 text-3xl font-semibold uppercase">Pricing</h4>
        <div class="grid gap-4 mb-12 md:grid-cols-2">
          <div class="card">
            <h3 class="mb-5 text-2xl font-semibold md:text-xl lg:text-3xl">Fixed</h3>
            <p class="text-lg">
              Best for smaller projects. Here we will define the scope of the project and find a
              price that works for everyone.
            </p>
          </div>
          <div class="card">
            <h3 class="mb-5 text-2xl font-semibold md:text-xl lg:text-3xl">Phased</h3>
            <p class="text-lg">
              Larger projects can be broken down into a multi-stage release process. Here we can
              price each phase according to the work needed.
            </p>
          </div>
        </div>
        <a
          href="mailto:matt@codellis.com?subject=Codellis - Schedule my FREE consultation"
          class="btn-custom"
          >Schedule a free consultation</a
        >
      </div>
    </div>

    <div class="py-10">
      <div class="container mx-auto">
        <div class="grid grid-cols-2 gap-10 text-white md:gap-6 md:grid-cols-4">
          <div class="col-span-2">
            <img alt="Logo" src="../assets/logo-23-horizontal-white.png" class="w-1/2 mx-auto" />
          </div>
          <div class="my-auto text-right md:text-left">
            <h4 class="mb-2 text-xl font-semibold uppercase">Services</h4>
            <ul>
              <li><a href="#service-website">Website</a></li>
              <li><a href="#service-mobile">Mobile Apps</a></li>
              <li><a href="#service-enterprise">Enterprise Software</a></li>
            </ul>
          </div>
          <div class="my-auto text-left">
            <h4 class="mb-2 text-xl font-semibold uppercase">Contact</h4>
            <ul>
              <li><a href="tel:+18642479619">(864) 247-9619</a></li>
              <li>
                <a href="mailto:matt@codellis.com?subject=Codellis - Schedule my FREE consultation"
                  >matt@codellis.com</a
                >
              </li>
              <li>&copy; codellis</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
