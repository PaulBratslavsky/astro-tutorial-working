## Code Snippets

**Home Page**

```astro
---

---

<html lang="en">
  <head>
    <meta charset="utf-8" />
    <link rel="icon" type="image/svg+xml" href="/favicon.svg" />
    <meta name="viewport" content="width=device-width" />
    <meta name="generator" content={Astro.generator} />
    <title>Astro</title>
  </head>
  <body>
    <section class="nav-section">
      <nav
        class="relative px-6 py-6 flex justify-between items-center bg-white w-3/4 mx-auto"
      >
        <a class="text-3xl font-bold leading-none" href="/">
          <svg
            width="113"
            height="48"
            viewBox="0 0 113 48"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <rect
              x="19.1501"
              y="19.1667"
              width="13.5529"
              height="13.5529"
              transform="rotate(-135 19.1501 19.1667)"
              fill="#059669"></rect>
            <rect
              x="9.56674"
              y="28.75"
              width="13.5529"
              height="13.5529"
              transform="rotate(-135 9.56674 28.75)"
              fill="#34D399"></rect>
            <rect
              x="28.7335"
              y="47.9167"
              width="13.5529"
              height="13.5529"
              transform="rotate(-135 28.7335 47.9167)"
              fill="#34D399"></rect>
            <rect
              x="9.56674"
              y="47.9167"
              width="13.5529"
              height="13.5529"
              transform="rotate(-135 9.56674 47.9167)"
              fill="#34D399"></rect>
            <rect
              x="28.7335"
              y="28.75"
              width="13.5529"
              height="13.5529"
              transform="rotate(-135 28.7335 28.75)"
              fill="#34D399"></rect>
            <path
              d="M38.3169 38.3333L28.7335 28.7499L38.3169 19.1666V29.5486V38.3333Z"
              fill="#059669"></path>
            <path
              d="M-0.0166321 19.1667L9.56675 28.75L-0.0166321 38.3334V27.9514V19.1667Z"
              fill="#059669"></path>
            <path
              d="M55.5589 35L63.7509 12.6H68.3589L76.5509 35H72.1989L70.4069 29.816H61.6709L59.8469 35H55.5589ZM62.7909 26.616H69.2869L66.0229 17.304L62.7909 26.616ZM84.8499 35C83.1859 35 81.8526 34.5947 80.8499 33.784C79.8473 32.9733 79.3459 31.5333 79.3459 29.464V22.552H76.6259V19.128H79.3459L79.8259 14.872H83.4419V19.128H87.7299V22.552H83.4419V29.496C83.4419 30.264 83.6019 30.7973 83.9219 31.096C84.2633 31.3733 84.8393 31.512 85.6499 31.512H87.6339V35H84.8499ZM93.4547 16.664C92.708 16.664 92.0893 16.44 91.5987 15.992C91.1293 15.544 90.8947 14.9787 90.8947 14.296C90.8947 13.6133 91.1293 13.0587 91.5987 12.632C92.0893 12.184 92.708 11.96 93.4547 11.96C94.2013 11.96 94.8093 12.184 95.2787 12.632C95.7693 13.0587 96.0147 13.6133 96.0147 14.296C96.0147 14.9787 95.7693 15.544 95.2787 15.992C94.8093 16.44 94.2013 16.664 93.4547 16.664ZM91.4067 35V19.128H95.5027V35H91.4067ZM106.338 35.384C104.93 35.384 103.693 35.16 102.626 34.712C101.559 34.2427 100.706 33.6027 100.066 32.792C99.4259 31.9813 99.0419 31.0427 98.9139 29.976H103.042C103.17 30.5947 103.511 31.128 104.066 31.576C104.642 32.0027 105.378 32.216 106.274 32.216C107.17 32.216 107.821 32.0347 108.226 31.672C108.653 31.3093 108.866 30.8933 108.866 30.424C108.866 29.7413 108.567 29.2827 107.97 29.048C107.373 28.792 106.541 28.5467 105.474 28.312C104.791 28.1627 104.098 27.9813 103.394 27.768C102.69 27.5547 102.039 27.288 101.442 26.968C100.866 26.6267 100.397 26.2 100.034 25.688C99.6713 25.1547 99.4899 24.504 99.4899 23.736C99.4899 22.328 100.045 21.144 101.154 20.184C102.285 19.224 103.863 18.744 105.89 18.744C107.767 18.744 109.261 19.1813 110.37 20.056C111.501 20.9307 112.173 22.136 112.386 23.672H108.514C108.279 22.4987 107.394 21.912 105.858 21.912C105.09 21.912 104.493 22.0613 104.066 22.36C103.661 22.6587 103.458 23.032 103.458 23.48C103.458 23.9493 103.767 24.3227 104.386 24.6C105.005 24.8773 105.826 25.1333 106.85 25.368C107.959 25.624 108.973 25.912 109.89 26.232C110.829 26.5307 111.575 26.9893 112.13 27.608C112.685 28.2053 112.962 29.0693 112.962 30.2C112.983 31.1813 112.727 32.0667 112.194 32.856C111.661 33.6453 110.893 34.264 109.89 34.712C108.887 35.16 107.703 35.384 106.338 35.384Z"
              fill="#111827"></path>
          </svg>
        </a>
        <div class="lg:hidden">
          <button class="navbar-burger flex items-center text-green-600 p-3">
            <svg
              class="block h-4 w-4 fill-current"
              viewBox="0 0 20 20"
              xmlns="http://www.w3.org/2000/svg"
            >
              <title>Mobile menu</title>
              <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"></path>
            </svg>
          </button>
        </div>
        <ul
          class="hidden absolute top-1/2 left-1/2 transform -translate-y-1/2 -translate-x-1/2 lg:flex lg:mx-auto lg:flex lg:items-center lg:w-auto lg:space-x-6"
        >
          <li>
            <a class="text-sm text-gray-400 hover:text-gray-500" href="/"
              >Home</a
            >
          </li>
          <li>
            <a class="text-sm text-gray-400 hover:text-gray-500" href="about">About</a>
          </li>
          <li>
            <a class="text-sm text-gray-400 hover:text-gray-500" href="blog"
              >Blog</a
            >
          </li>
        </ul>
        <a
          class="hidden lg:inline-block py-2 px-6 bg-green-500 hover:bg-green-600 text-sm text-white font-bold rounded-l-xl rounded-t-xl transition duration-200"
          href="#">Learn More</a
        >
      </nav>
      <div
        class="hidden navbar-menu fixed top-0 left-0 bottom-0 w-5/6 max-w-sm z-50"
      >
        <div class="navbar-backdrop fixed inset-0 bg-gray-800 opacity-25"></div>
        <nav
          class="relative flex flex-col py-6 px-6 h-full w-full bg-white border-r overflow-y-auto"
        >
          <div class="flex items-center mb-8">
            <a class="mr-auto text-3xl font-bold leading-none" href="/">
              <svg
                width="113"
                height="48"
                viewBox="0 0 113 48"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <rect
                  x="19.1501"
                  y="19.1667"
                  width="13.5529"
                  height="13.5529"
                  transform="rotate(-135 19.1501 19.1667)"
                  fill="#059669"></rect>
                <rect
                  x="9.56674"
                  y="28.75"
                  width="13.5529"
                  height="13.5529"
                  transform="rotate(-135 9.56674 28.75)"
                  fill="#34D399"></rect>
                <rect
                  x="28.7335"
                  y="47.9167"
                  width="13.5529"
                  height="13.5529"
                  transform="rotate(-135 28.7335 47.9167)"
                  fill="#34D399"></rect>
                <rect
                  x="9.56674"
                  y="47.9167"
                  width="13.5529"
                  height="13.5529"
                  transform="rotate(-135 9.56674 47.9167)"
                  fill="#34D399"></rect>
                <rect
                  x="28.7335"
                  y="28.75"
                  width="13.5529"
                  height="13.5529"
                  transform="rotate(-135 28.7335 28.75)"
                  fill="#34D399"></rect>
                <path
                  d="M38.3169 38.3333L28.7335 28.7499L38.3169 19.1666V29.5486V38.3333Z"
                  fill="#059669"></path>
                <path
                  d="M-0.0166321 19.1667L9.56675 28.75L-0.0166321 38.3334V27.9514V19.1667Z"
                  fill="#059669"></path>
                <path
                  d="M55.5589 35L63.7509 12.6H68.3589L76.5509 35H72.1989L70.4069 29.816H61.6709L59.8469 35H55.5589ZM62.7909 26.616H69.2869L66.0229 17.304L62.7909 26.616ZM84.8499 35C83.1859 35 81.8526 34.5947 80.8499 33.784C79.8473 32.9733 79.3459 31.5333 79.3459 29.464V22.552H76.6259V19.128H79.3459L79.8259 14.872H83.4419V19.128H87.7299V22.552H83.4419V29.496C83.4419 30.264 83.6019 30.7973 83.9219 31.096C84.2633 31.3733 84.8393 31.512 85.6499 31.512H87.6339V35H84.8499ZM93.4547 16.664C92.708 16.664 92.0893 16.44 91.5987 15.992C91.1293 15.544 90.8947 14.9787 90.8947 14.296C90.8947 13.6133 91.1293 13.0587 91.5987 12.632C92.0893 12.184 92.708 11.96 93.4547 11.96C94.2013 11.96 94.8093 12.184 95.2787 12.632C95.7693 13.0587 96.0147 13.6133 96.0147 14.296C96.0147 14.9787 95.7693 15.544 95.2787 15.992C94.8093 16.44 94.2013 16.664 93.4547 16.664ZM91.4067 35V19.128H95.5027V35H91.4067ZM106.338 35.384C104.93 35.384 103.693 35.16 102.626 34.712C101.559 34.2427 100.706 33.6027 100.066 32.792C99.4259 31.9813 99.0419 31.0427 98.9139 29.976H103.042C103.17 30.5947 103.511 31.128 104.066 31.576C104.642 32.0027 105.378 32.216 106.274 32.216C107.17 32.216 107.821 32.0347 108.226 31.672C108.653 31.3093 108.866 30.8933 108.866 30.424C108.866 29.7413 108.567 29.2827 107.97 29.048C107.373 28.792 106.541 28.5467 105.474 28.312C104.791 28.1627 104.098 27.9813 103.394 27.768C102.69 27.5547 102.039 27.288 101.442 26.968C100.866 26.6267 100.397 26.2 100.034 25.688C99.6713 25.1547 99.4899 24.504 99.4899 23.736C99.4899 22.328 100.045 21.144 101.154 20.184C102.285 19.224 103.863 18.744 105.89 18.744C107.767 18.744 109.261 19.1813 110.37 20.056C111.501 20.9307 112.173 22.136 112.386 23.672H108.514C108.279 22.4987 107.394 21.912 105.858 21.912C105.09 21.912 104.493 22.0613 104.066 22.36C103.661 22.6587 103.458 23.032 103.458 23.48C103.458 23.9493 103.767 24.3227 104.386 24.6C105.005 24.8773 105.826 25.1333 106.85 25.368C107.959 25.624 108.973 25.912 109.89 26.232C110.829 26.5307 111.575 26.9893 112.13 27.608C112.685 28.2053 112.962 29.0693 112.962 30.2C112.983 31.1813 112.727 32.0667 112.194 32.856C111.661 33.6453 110.893 34.264 109.89 34.712C108.887 35.16 107.703 35.384 106.338 35.384Z"
                  fill="#111827"></path>
              </svg>
            </a>
            <button class="navbar-close">
              <svg
                class="h-6 w-6 text-gray-400 cursor-pointer hover:text-gray-500"
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M6 18L18 6M6 6l12 12"></path>
              </svg>
            </button>
          </div>
          <div>
            <ul>
              <li class="mb-1">
                <a
                  class="block p-4 text-sm font-semibold text-gray-400 hover:bg-green-50 hover:text-green-600 rounded"
                  href="/">Home</a
                >
              </li>
              <li class="mb-1">
                <a
                  class="block p-4 text-sm font-semibold text-gray-400 hover:bg-green-50 hover:text-green-600 rounded"
                  href="about">About</a
                >
              </li>
              <li class="mb-1">
                <a
                  class="block p-4 text-sm font-semibold text-gray-400 hover:bg-green-50 hover:text-green-600 rounded"
                  href="blog">Blog</a
                >
              </li>
            </ul>
          </div>
          <div class="mt-auto">
            <div class="pt-6">
              <a
                class="block px-4 py-3 mb-2 leading-loose text-xs text-center text-white font-semibold bg-green-600 hover:bg-green-700 rounded-l-xl rounded-t-xl"
                href="#">Learn More</a
              >
            </div>
            <p class="my-4 text-xs text-center text-gray-400">
              <span>© 2020 All rights reserved.</span>
            </p>
          </div>
        </nav>
      </div>
    </section>

    <section class="relative overflow-hidden">
      <div class="relative bg-gray-50 pt-12 lg:pt-20 pb-12 md:pb-24">
        <div class="container mx-auto px-4 w-3/4">
          <div class="flex flex-wrap -mx-4">
            <div
              class="w-full lg:w-1/2 px-4 mb-12 md:mb-20 lg:mb-0 flex items-center"
            >
              <div class="w-full text-center lg:text-left">
                <div class="max-w-md mx-auto lg:mx-0">
                  <h2 class="mb-3 text-4xl lg:text-5xl font-bold font-heading">
                    <span>Build & Launch without problems</span>
                  </h2>
                </div>
                <div class="max-w-sm mx-auto lg:mx-0">
                  <p class="mb-6 text-gray-400 leading-loose">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Pellentesque efficitur nisl sodales egestas lobortis.
                  </p>
                  <div>
                    <a
                      class="inline-block mb-3 lg:mb-0 lg:mr-3 w-full lg:w-auto py-2 px-6 leading-loose bg-green-600 hover:bg-green-700 text-white font-semibold rounded-l-xl rounded-t-xl transition duration-200"
                      href="#">Get Started</a
                    ><a
                      class="inline-block w-full lg:w-auto py-2 px-6 leading-loose font-semibold bg-white hover:bg-gray-50 rounded-l-xl rounded-t-xl transition duration-200"
                      href="#">How it works</a
                    >
                  </div>
                </div>
              </div>
            </div>
            <div class="w-full lg:w-1/2 px-4 flex items-center justify-center">
              <div class="relative" style="z-index: 0;">
                <img
                  class="h-128 w-full max-w-lg object-cover rounded-3xl md:rounded-br-none"
                  src="https://images.unsplash.com/photo-1462826303086-329426d1aef5?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&auto=format&fit=crop&w=1050&q=80"
                  alt=""
                />
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section>
      <div class="py-20">
        <div class="container mx-auto px-4 w-3/4">
          <div class="mb-16 max-w-md mx-auto text-center">
            <span class="text-green-600 font-bold"
              >Dolor sit amet consectutar</span
            >
            <h2 class="text-4xl md:text-5xl font-bold">
              Build & Launch without problems
            </h2>
          </div>
          <div class="flex flex-wrap -mx-4">
            <div class="mb-12 lg:mb-0 w-full md:w-1/2 lg:w-1/4 px-4">
              <h4 class="mb-4 text-2xl font-bold font-heading">
                Lorem ipsum dolor sit amet consectutar
              </h4>
              <p class="text-gray-500 leading-loose">
                Fusce quam tellus, placerat eu metus ut, viverra aliquet purus.
                Suspendisse potenti. Nulla non nibh feugiat.
              </p>
            </div>
            <div class="mb-12 lg:mb-0 w-full md:w-1/2 lg:w-1/4 px-4">
              <h4 class="mb-4 text-2xl font-bold font-heading">
                Ut congue nec leo eget aliquam
              </h4>
              <p class="text-gray-500 leading-loose">
                Ut tempus tellus ac nisi vestibulum tempus. Nunc tincidunt
                lectus libero, ac ultricies augue elementum at.
              </p>
            </div>
            <div class="mb-12 lg:mb-0 w-full md:w-1/2 lg:w-1/4 px-4">
              <h4 class="mb-4 text-2xl font-bold font-heading">
                Proin fringilla eleifend justo pellentesque
              </h4>
              <p class="text-gray-500 leading-loose">
                Donec ut ligula nunc. Mauris blandit vel est et facilisis.
                Integer sapien felis, aliquet at posuere et, porttitor quis
                ligula.
              </p>
            </div>
            <div class="w-full md:w-1/2 lg:w-1/4 px-4">
              <h4 class="mb-4 text-2xl font-bold font-heading">
                Morbi sagittis ligula sit amet elit maximus
              </h4>
              <p class="text-gray-500 leading-loose">
                Duis ut facilisis orci. Morbi lacinia nunc a augue eleifend, sed
                placerat ex faucibus. Duis ante arcu, pretium ac luctus
                vulputate.
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>
  </body>
</html>

<style></style>

<script></script>
```

**About Page**

```astro
---

---

<html lang="en">
  <head>
    <meta charset="utf-8" />
    <link rel="icon" type="image/svg+xml" href="/favicon.svg" />
    <meta name="viewport" content="width=device-width" />
    <meta name="generator" content={Astro.generator} />
    <title>Astro</title>
  </head>
  <body>
    <section class="nav-section">
      <nav
        class="relative px-6 py-6 flex justify-between items-center bg-white w-3/4 mx-auto"
      >
        <a class="text-3xl font-bold leading-none" href="/">
          <svg
            width="113"
            height="48"
            viewBox="0 0 113 48"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <rect
              x="19.1501"
              y="19.1667"
              width="13.5529"
              height="13.5529"
              transform="rotate(-135 19.1501 19.1667)"
              fill="#059669"></rect>
            <rect
              x="9.56674"
              y="28.75"
              width="13.5529"
              height="13.5529"
              transform="rotate(-135 9.56674 28.75)"
              fill="#34D399"></rect>
            <rect
              x="28.7335"
              y="47.9167"
              width="13.5529"
              height="13.5529"
              transform="rotate(-135 28.7335 47.9167)"
              fill="#34D399"></rect>
            <rect
              x="9.56674"
              y="47.9167"
              width="13.5529"
              height="13.5529"
              transform="rotate(-135 9.56674 47.9167)"
              fill="#34D399"></rect>
            <rect
              x="28.7335"
              y="28.75"
              width="13.5529"
              height="13.5529"
              transform="rotate(-135 28.7335 28.75)"
              fill="#34D399"></rect>
            <path
              d="M38.3169 38.3333L28.7335 28.7499L38.3169 19.1666V29.5486V38.3333Z"
              fill="#059669"></path>
            <path
              d="M-0.0166321 19.1667L9.56675 28.75L-0.0166321 38.3334V27.9514V19.1667Z"
              fill="#059669"></path>
            <path
              d="M55.5589 35L63.7509 12.6H68.3589L76.5509 35H72.1989L70.4069 29.816H61.6709L59.8469 35H55.5589ZM62.7909 26.616H69.2869L66.0229 17.304L62.7909 26.616ZM84.8499 35C83.1859 35 81.8526 34.5947 80.8499 33.784C79.8473 32.9733 79.3459 31.5333 79.3459 29.464V22.552H76.6259V19.128H79.3459L79.8259 14.872H83.4419V19.128H87.7299V22.552H83.4419V29.496C83.4419 30.264 83.6019 30.7973 83.9219 31.096C84.2633 31.3733 84.8393 31.512 85.6499 31.512H87.6339V35H84.8499ZM93.4547 16.664C92.708 16.664 92.0893 16.44 91.5987 15.992C91.1293 15.544 90.8947 14.9787 90.8947 14.296C90.8947 13.6133 91.1293 13.0587 91.5987 12.632C92.0893 12.184 92.708 11.96 93.4547 11.96C94.2013 11.96 94.8093 12.184 95.2787 12.632C95.7693 13.0587 96.0147 13.6133 96.0147 14.296C96.0147 14.9787 95.7693 15.544 95.2787 15.992C94.8093 16.44 94.2013 16.664 93.4547 16.664ZM91.4067 35V19.128H95.5027V35H91.4067ZM106.338 35.384C104.93 35.384 103.693 35.16 102.626 34.712C101.559 34.2427 100.706 33.6027 100.066 32.792C99.4259 31.9813 99.0419 31.0427 98.9139 29.976H103.042C103.17 30.5947 103.511 31.128 104.066 31.576C104.642 32.0027 105.378 32.216 106.274 32.216C107.17 32.216 107.821 32.0347 108.226 31.672C108.653 31.3093 108.866 30.8933 108.866 30.424C108.866 29.7413 108.567 29.2827 107.97 29.048C107.373 28.792 106.541 28.5467 105.474 28.312C104.791 28.1627 104.098 27.9813 103.394 27.768C102.69 27.5547 102.039 27.288 101.442 26.968C100.866 26.6267 100.397 26.2 100.034 25.688C99.6713 25.1547 99.4899 24.504 99.4899 23.736C99.4899 22.328 100.045 21.144 101.154 20.184C102.285 19.224 103.863 18.744 105.89 18.744C107.767 18.744 109.261 19.1813 110.37 20.056C111.501 20.9307 112.173 22.136 112.386 23.672H108.514C108.279 22.4987 107.394 21.912 105.858 21.912C105.09 21.912 104.493 22.0613 104.066 22.36C103.661 22.6587 103.458 23.032 103.458 23.48C103.458 23.9493 103.767 24.3227 104.386 24.6C105.005 24.8773 105.826 25.1333 106.85 25.368C107.959 25.624 108.973 25.912 109.89 26.232C110.829 26.5307 111.575 26.9893 112.13 27.608C112.685 28.2053 112.962 29.0693 112.962 30.2C112.983 31.1813 112.727 32.0667 112.194 32.856C111.661 33.6453 110.893 34.264 109.89 34.712C108.887 35.16 107.703 35.384 106.338 35.384Z"
              fill="#111827"></path>
          </svg>
        </a>
        <div class="lg:hidden">
          <button class="navbar-burger flex items-center text-green-600 p-3">
            <svg
              class="block h-4 w-4 fill-current"
              viewBox="0 0 20 20"
              xmlns="http://www.w3.org/2000/svg"
            >
              <title>Mobile menu</title>
              <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"></path>
            </svg>
          </button>
        </div>
        <ul
          class="hidden absolute top-1/2 left-1/2 transform -translate-y-1/2 -translate-x-1/2 lg:flex lg:mx-auto lg:flex lg:items-center lg:w-auto lg:space-x-6"
        >
          <li>
            <a class="text-sm text-gray-400 hover:text-gray-500" href="/"
              >Home</a
            >
          </li>
          <li>
            <a class="text-sm text-gray-400 hover:text-gray-500" href="about"
              >About</a
            >
          </li>
          <li>
            <a class="text-sm text-gray-400 hover:text-gray-500" href="blog"
              >Blog</a
            >
          </li>
        </ul>
        <a
          class="hidden lg:inline-block py-2 px-6 bg-green-500 hover:bg-green-600 text-sm text-white font-bold rounded-l-xl rounded-t-xl transition duration-200"
          href="#">Learn More</a
        >
      </nav>
      <div
        class="hidden navbar-menu fixed top-0 left-0 bottom-0 w-5/6 max-w-sm z-50"
      >
        <div class="navbar-backdrop fixed inset-0 bg-gray-800 opacity-25"></div>
        <nav
          class="relative flex flex-col py-6 px-6 h-full w-full bg-white border-r overflow-y-auto"
        >
          <div class="flex items-center mb-8">
            <a class="mr-auto text-3xl font-bold leading-none" href="/">
              <svg
                width="113"
                height="48"
                viewBox="0 0 113 48"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <rect
                  x="19.1501"
                  y="19.1667"
                  width="13.5529"
                  height="13.5529"
                  transform="rotate(-135 19.1501 19.1667)"
                  fill="#059669"></rect>
                <rect
                  x="9.56674"
                  y="28.75"
                  width="13.5529"
                  height="13.5529"
                  transform="rotate(-135 9.56674 28.75)"
                  fill="#34D399"></rect>
                <rect
                  x="28.7335"
                  y="47.9167"
                  width="13.5529"
                  height="13.5529"
                  transform="rotate(-135 28.7335 47.9167)"
                  fill="#34D399"></rect>
                <rect
                  x="9.56674"
                  y="47.9167"
                  width="13.5529"
                  height="13.5529"
                  transform="rotate(-135 9.56674 47.9167)"
                  fill="#34D399"></rect>
                <rect
                  x="28.7335"
                  y="28.75"
                  width="13.5529"
                  height="13.5529"
                  transform="rotate(-135 28.7335 28.75)"
                  fill="#34D399"></rect>
                <path
                  d="M38.3169 38.3333L28.7335 28.7499L38.3169 19.1666V29.5486V38.3333Z"
                  fill="#059669"></path>
                <path
                  d="M-0.0166321 19.1667L9.56675 28.75L-0.0166321 38.3334V27.9514V19.1667Z"
                  fill="#059669"></path>
                <path
                  d="M55.5589 35L63.7509 12.6H68.3589L76.5509 35H72.1989L70.4069 29.816H61.6709L59.8469 35H55.5589ZM62.7909 26.616H69.2869L66.0229 17.304L62.7909 26.616ZM84.8499 35C83.1859 35 81.8526 34.5947 80.8499 33.784C79.8473 32.9733 79.3459 31.5333 79.3459 29.464V22.552H76.6259V19.128H79.3459L79.8259 14.872H83.4419V19.128H87.7299V22.552H83.4419V29.496C83.4419 30.264 83.6019 30.7973 83.9219 31.096C84.2633 31.3733 84.8393 31.512 85.6499 31.512H87.6339V35H84.8499ZM93.4547 16.664C92.708 16.664 92.0893 16.44 91.5987 15.992C91.1293 15.544 90.8947 14.9787 90.8947 14.296C90.8947 13.6133 91.1293 13.0587 91.5987 12.632C92.0893 12.184 92.708 11.96 93.4547 11.96C94.2013 11.96 94.8093 12.184 95.2787 12.632C95.7693 13.0587 96.0147 13.6133 96.0147 14.296C96.0147 14.9787 95.7693 15.544 95.2787 15.992C94.8093 16.44 94.2013 16.664 93.4547 16.664ZM91.4067 35V19.128H95.5027V35H91.4067ZM106.338 35.384C104.93 35.384 103.693 35.16 102.626 34.712C101.559 34.2427 100.706 33.6027 100.066 32.792C99.4259 31.9813 99.0419 31.0427 98.9139 29.976H103.042C103.17 30.5947 103.511 31.128 104.066 31.576C104.642 32.0027 105.378 32.216 106.274 32.216C107.17 32.216 107.821 32.0347 108.226 31.672C108.653 31.3093 108.866 30.8933 108.866 30.424C108.866 29.7413 108.567 29.2827 107.97 29.048C107.373 28.792 106.541 28.5467 105.474 28.312C104.791 28.1627 104.098 27.9813 103.394 27.768C102.69 27.5547 102.039 27.288 101.442 26.968C100.866 26.6267 100.397 26.2 100.034 25.688C99.6713 25.1547 99.4899 24.504 99.4899 23.736C99.4899 22.328 100.045 21.144 101.154 20.184C102.285 19.224 103.863 18.744 105.89 18.744C107.767 18.744 109.261 19.1813 110.37 20.056C111.501 20.9307 112.173 22.136 112.386 23.672H108.514C108.279 22.4987 107.394 21.912 105.858 21.912C105.09 21.912 104.493 22.0613 104.066 22.36C103.661 22.6587 103.458 23.032 103.458 23.48C103.458 23.9493 103.767 24.3227 104.386 24.6C105.005 24.8773 105.826 25.1333 106.85 25.368C107.959 25.624 108.973 25.912 109.89 26.232C110.829 26.5307 111.575 26.9893 112.13 27.608C112.685 28.2053 112.962 29.0693 112.962 30.2C112.983 31.1813 112.727 32.0667 112.194 32.856C111.661 33.6453 110.893 34.264 109.89 34.712C108.887 35.16 107.703 35.384 106.338 35.384Z"
                  fill="#111827"></path>
              </svg>
            </a>
            <button class="navbar-close">
              <svg
                class="h-6 w-6 text-gray-400 cursor-pointer hover:text-gray-500"
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M6 18L18 6M6 6l12 12"></path>
              </svg>
            </button>
          </div>
          <div>
            <ul>
              <li class="mb-1">
                <a
                  class="block p-4 text-sm font-semibold text-gray-400 hover:bg-green-50 hover:text-green-600 rounded"
                  href="/">Home</a
                >
              </li>
              <li class="mb-1">
                <a
                  class="block p-4 text-sm font-semibold text-gray-400 hover:bg-green-50 hover:text-green-600 rounded"
                  href="about">About</a
                >
              </li>
              <li class="mb-1">
                <a
                  class="block p-4 text-sm font-semibold text-gray-400 hover:bg-green-50 hover:text-green-600 rounded"
                  href="blog">Blog</a
                >
              </li>
            </ul>
          </div>
          <div class="mt-auto">
            <div class="pt-6">
              <a
                class="block px-4 py-3 mb-2 leading-loose text-xs text-center text-white font-semibold bg-green-600 hover:bg-green-700 rounded-l-xl rounded-t-xl"
                href="#">Learn More</a
              >
            </div>
            <p class="my-4 text-xs text-center text-gray-400">
              <span>© 2020 All rights reserved.</span>
            </p>
          </div>
        </nav>
      </div>
    </section>

    <section class="bg-gray-50">
      <div
        class="container mx-auto h-[calc(100vh-100px)] px-4 flex justify-center items-center"
      >
        <div class="mb-6 w-full lg:w-1/2 px-4">
          <div
            class="flex flex-wrap items-center bg-white rounded shadow overflow-hidden"
          >
            <img
              class="w-full lg:w-1/3 h-80 object-cover"
              src="https://images.unsplash.com/photo-1580852300654-03c803a14e24?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=600&q=80"
              alt=""
            />
            <div class="w-full lg:w-2/3 lg:pl-6 p-4">
              <h4 class="mb-2 text-2xl font-bold font-heading">Danny Bailey</h4>
              <p class="mb-4 text-gray-500 leading-loose">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed
                vitae felis at ante bibendum mollis et et mauris.
              </p>
              <div class="flex">
                <a class="mr-3" href="#">
                  <svg
                    width="22"
                    height="22"
                    viewBox="0 0 22 22"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      fill-rule="evenodd"
                      clip-rule="evenodd"
                      d="M20 5.63381C19.3743 5.91106 18.7029 6.09908 17.9975 6.18303C18.7178 5.75172 19.2691 5.06761 19.5304 4.25494C18.8548 4.65436 18.1091 4.94439 17.3144 5.10161C16.6781 4.42281 15.7731 4 14.7692 4C12.8432 4 11.2816 5.56158 11.2816 7.48647C11.2816 7.75947 11.3124 8.02611 11.3719 8.28108C8.474 8.13553 5.90431 6.74711 4.18444 4.63736C3.88381 5.15153 3.71278 5.75064 3.71278 6.39017C3.71278 7.60014 4.32892 8.66775 5.26375 9.29236C4.69222 9.27325 4.15469 9.11603 3.68411 8.85469V8.89825C3.68411 10.5873 4.88664 11.997 6.48114 12.3178C6.189 12.3964 5.88094 12.44 5.56225 12.44C5.33706 12.44 5.11928 12.4177 4.90575 12.3752C5.34978 13.7615 6.63731 14.7696 8.16278 14.7972C6.96981 15.7321 5.46558 16.2876 3.83178 16.2876C3.55028 16.2876 3.273 16.2706 3 16.2398C4.54353 17.231 6.376 17.8089 8.3455 17.8089C14.7607 17.8089 18.2674 12.4952 18.2674 7.88697L18.2557 7.4355C18.9409 6.94681 19.5336 6.33281 20 5.63381Z"
                    ></path>
                    <mask
                      id="mask0"
                      mask-type="alpha"
                      maskUnits="userSpaceOnUse"
                      x="3"
                      y="4"
                      width="17"
                      height="14"
                    >
                      <path
                        fill-rule="evenodd"
                        clip-rule="evenodd"
                        d="M20 5.63381C19.3743 5.91106 18.7029 6.09908 17.9975 6.18303C18.7178 5.75172 19.2691 5.06761 19.5304 4.25494C18.8548 4.65436 18.1091 4.94439 17.3144 5.10161C16.6781 4.42281 15.7731 4 14.7692 4C12.8432 4 11.2816 5.56158 11.2816 7.48647C11.2816 7.75947 11.3124 8.02611 11.3719 8.28108C8.474 8.13553 5.90431 6.74711 4.18444 4.63736C3.88381 5.15153 3.71278 5.75064 3.71278 6.39017C3.71278 7.60014 4.32892 8.66775 5.26375 9.29236C4.69222 9.27325 4.15469 9.11603 3.68411 8.85469V8.89825C3.68411 10.5873 4.88664 11.997 6.48114 12.3178C6.189 12.3964 5.88094 12.44 5.56225 12.44C5.33706 12.44 5.11928 12.4177 4.90575 12.3752C5.34978 13.7615 6.63731 14.7696 8.16278 14.7972C6.96981 15.7321 5.46558 16.2876 3.83178 16.2876C3.55028 16.2876 3.273 16.2706 3 16.2398C4.54353 17.231 6.376 17.8089 8.3455 17.8089C14.7607 17.8089 18.2674 12.4952 18.2674 7.88697L18.2557 7.4355C18.9409 6.94681 19.5336 6.33281 20 5.63381Z"
                        fill="white"></path>
                    </mask>
                    <g mask="url(#mask0)"> </g>
                  </svg>
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </body>
</html>

<style></style>

<script></script>



```

**Blog Page\***

```astro
---

---

<html lang="en">
  <head>
    <meta charset="utf-8" />
    <link rel="icon" type="image/svg+xml" href="/favicon.svg" />
    <meta name="viewport" content="width=device-width" />
    <meta name="generator" content={Astro.generator} />
    <title>Astro</title>
  </head>
  <body>
    <section class="nav-section">
      <nav
        class="relative px-6 py-6 flex justify-between items-center bg-white w-3/4 mx-auto"
      >
        <a class="text-3xl font-bold leading-none" href="/">
          <svg
            width="113"
            height="48"
            viewBox="0 0 113 48"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <rect
              x="19.1501"
              y="19.1667"
              width="13.5529"
              height="13.5529"
              transform="rotate(-135 19.1501 19.1667)"
              fill="#059669"></rect>
            <rect
              x="9.56674"
              y="28.75"
              width="13.5529"
              height="13.5529"
              transform="rotate(-135 9.56674 28.75)"
              fill="#34D399"></rect>
            <rect
              x="28.7335"
              y="47.9167"
              width="13.5529"
              height="13.5529"
              transform="rotate(-135 28.7335 47.9167)"
              fill="#34D399"></rect>
            <rect
              x="9.56674"
              y="47.9167"
              width="13.5529"
              height="13.5529"
              transform="rotate(-135 9.56674 47.9167)"
              fill="#34D399"></rect>
            <rect
              x="28.7335"
              y="28.75"
              width="13.5529"
              height="13.5529"
              transform="rotate(-135 28.7335 28.75)"
              fill="#34D399"></rect>
            <path
              d="M38.3169 38.3333L28.7335 28.7499L38.3169 19.1666V29.5486V38.3333Z"
              fill="#059669"></path>
            <path
              d="M-0.0166321 19.1667L9.56675 28.75L-0.0166321 38.3334V27.9514V19.1667Z"
              fill="#059669"></path>
            <path
              d="M55.5589 35L63.7509 12.6H68.3589L76.5509 35H72.1989L70.4069 29.816H61.6709L59.8469 35H55.5589ZM62.7909 26.616H69.2869L66.0229 17.304L62.7909 26.616ZM84.8499 35C83.1859 35 81.8526 34.5947 80.8499 33.784C79.8473 32.9733 79.3459 31.5333 79.3459 29.464V22.552H76.6259V19.128H79.3459L79.8259 14.872H83.4419V19.128H87.7299V22.552H83.4419V29.496C83.4419 30.264 83.6019 30.7973 83.9219 31.096C84.2633 31.3733 84.8393 31.512 85.6499 31.512H87.6339V35H84.8499ZM93.4547 16.664C92.708 16.664 92.0893 16.44 91.5987 15.992C91.1293 15.544 90.8947 14.9787 90.8947 14.296C90.8947 13.6133 91.1293 13.0587 91.5987 12.632C92.0893 12.184 92.708 11.96 93.4547 11.96C94.2013 11.96 94.8093 12.184 95.2787 12.632C95.7693 13.0587 96.0147 13.6133 96.0147 14.296C96.0147 14.9787 95.7693 15.544 95.2787 15.992C94.8093 16.44 94.2013 16.664 93.4547 16.664ZM91.4067 35V19.128H95.5027V35H91.4067ZM106.338 35.384C104.93 35.384 103.693 35.16 102.626 34.712C101.559 34.2427 100.706 33.6027 100.066 32.792C99.4259 31.9813 99.0419 31.0427 98.9139 29.976H103.042C103.17 30.5947 103.511 31.128 104.066 31.576C104.642 32.0027 105.378 32.216 106.274 32.216C107.17 32.216 107.821 32.0347 108.226 31.672C108.653 31.3093 108.866 30.8933 108.866 30.424C108.866 29.7413 108.567 29.2827 107.97 29.048C107.373 28.792 106.541 28.5467 105.474 28.312C104.791 28.1627 104.098 27.9813 103.394 27.768C102.69 27.5547 102.039 27.288 101.442 26.968C100.866 26.6267 100.397 26.2 100.034 25.688C99.6713 25.1547 99.4899 24.504 99.4899 23.736C99.4899 22.328 100.045 21.144 101.154 20.184C102.285 19.224 103.863 18.744 105.89 18.744C107.767 18.744 109.261 19.1813 110.37 20.056C111.501 20.9307 112.173 22.136 112.386 23.672H108.514C108.279 22.4987 107.394 21.912 105.858 21.912C105.09 21.912 104.493 22.0613 104.066 22.36C103.661 22.6587 103.458 23.032 103.458 23.48C103.458 23.9493 103.767 24.3227 104.386 24.6C105.005 24.8773 105.826 25.1333 106.85 25.368C107.959 25.624 108.973 25.912 109.89 26.232C110.829 26.5307 111.575 26.9893 112.13 27.608C112.685 28.2053 112.962 29.0693 112.962 30.2C112.983 31.1813 112.727 32.0667 112.194 32.856C111.661 33.6453 110.893 34.264 109.89 34.712C108.887 35.16 107.703 35.384 106.338 35.384Z"
              fill="#111827"></path>
          </svg>
        </a>
        <div class="lg:hidden">
          <button class="navbar-burger flex items-center text-green-600 p-3">
            <svg
              class="block h-4 w-4 fill-current"
              viewBox="0 0 20 20"
              xmlns="http://www.w3.org/2000/svg"
            >
              <title>Mobile menu</title>
              <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"></path>
            </svg>
          </button>
        </div>
        <ul
          class="hidden absolute top-1/2 left-1/2 transform -translate-y-1/2 -translate-x-1/2 lg:flex lg:mx-auto lg:flex lg:items-center lg:w-auto lg:space-x-6"
        >
          <li>
            <a class="text-sm text-gray-400 hover:text-gray-500" href="/"
              >Home</a
            >
          </li>
          <li>
            <a class="text-sm text-gray-400 hover:text-gray-500" href="about"
              >About</a
            >
          </li>
          <li>
            <a class="text-sm text-gray-400 hover:text-gray-500" href="blog"
              >Blog</a
            >
          </li>
        </ul>
        <a
          class="hidden lg:inline-block py-2 px-6 bg-green-500 hover:bg-green-600 text-sm text-white font-bold rounded-l-xl rounded-t-xl transition duration-200"
          href="#">Learn More</a
        >
      </nav>
      <div
        class="hidden navbar-menu fixed top-0 left-0 bottom-0 w-5/6 max-w-sm z-50"
      >
        <div class="navbar-backdrop fixed inset-0 bg-gray-800 opacity-25"></div>
        <nav
          class="relative flex flex-col py-6 px-6 h-full w-full bg-white border-r overflow-y-auto"
        >
          <div class="flex items-center mb-8">
            <a class="mr-auto text-3xl font-bold leading-none" href="/">
              <svg
                width="113"
                height="48"
                viewBox="0 0 113 48"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <rect
                  x="19.1501"
                  y="19.1667"
                  width="13.5529"
                  height="13.5529"
                  transform="rotate(-135 19.1501 19.1667)"
                  fill="#059669"></rect>
                <rect
                  x="9.56674"
                  y="28.75"
                  width="13.5529"
                  height="13.5529"
                  transform="rotate(-135 9.56674 28.75)"
                  fill="#34D399"></rect>
                <rect
                  x="28.7335"
                  y="47.9167"
                  width="13.5529"
                  height="13.5529"
                  transform="rotate(-135 28.7335 47.9167)"
                  fill="#34D399"></rect>
                <rect
                  x="9.56674"
                  y="47.9167"
                  width="13.5529"
                  height="13.5529"
                  transform="rotate(-135 9.56674 47.9167)"
                  fill="#34D399"></rect>
                <rect
                  x="28.7335"
                  y="28.75"
                  width="13.5529"
                  height="13.5529"
                  transform="rotate(-135 28.7335 28.75)"
                  fill="#34D399"></rect>
                <path
                  d="M38.3169 38.3333L28.7335 28.7499L38.3169 19.1666V29.5486V38.3333Z"
                  fill="#059669"></path>
                <path
                  d="M-0.0166321 19.1667L9.56675 28.75L-0.0166321 38.3334V27.9514V19.1667Z"
                  fill="#059669"></path>
                <path
                  d="M55.5589 35L63.7509 12.6H68.3589L76.5509 35H72.1989L70.4069 29.816H61.6709L59.8469 35H55.5589ZM62.7909 26.616H69.2869L66.0229 17.304L62.7909 26.616ZM84.8499 35C83.1859 35 81.8526 34.5947 80.8499 33.784C79.8473 32.9733 79.3459 31.5333 79.3459 29.464V22.552H76.6259V19.128H79.3459L79.8259 14.872H83.4419V19.128H87.7299V22.552H83.4419V29.496C83.4419 30.264 83.6019 30.7973 83.9219 31.096C84.2633 31.3733 84.8393 31.512 85.6499 31.512H87.6339V35H84.8499ZM93.4547 16.664C92.708 16.664 92.0893 16.44 91.5987 15.992C91.1293 15.544 90.8947 14.9787 90.8947 14.296C90.8947 13.6133 91.1293 13.0587 91.5987 12.632C92.0893 12.184 92.708 11.96 93.4547 11.96C94.2013 11.96 94.8093 12.184 95.2787 12.632C95.7693 13.0587 96.0147 13.6133 96.0147 14.296C96.0147 14.9787 95.7693 15.544 95.2787 15.992C94.8093 16.44 94.2013 16.664 93.4547 16.664ZM91.4067 35V19.128H95.5027V35H91.4067ZM106.338 35.384C104.93 35.384 103.693 35.16 102.626 34.712C101.559 34.2427 100.706 33.6027 100.066 32.792C99.4259 31.9813 99.0419 31.0427 98.9139 29.976H103.042C103.17 30.5947 103.511 31.128 104.066 31.576C104.642 32.0027 105.378 32.216 106.274 32.216C107.17 32.216 107.821 32.0347 108.226 31.672C108.653 31.3093 108.866 30.8933 108.866 30.424C108.866 29.7413 108.567 29.2827 107.97 29.048C107.373 28.792 106.541 28.5467 105.474 28.312C104.791 28.1627 104.098 27.9813 103.394 27.768C102.69 27.5547 102.039 27.288 101.442 26.968C100.866 26.6267 100.397 26.2 100.034 25.688C99.6713 25.1547 99.4899 24.504 99.4899 23.736C99.4899 22.328 100.045 21.144 101.154 20.184C102.285 19.224 103.863 18.744 105.89 18.744C107.767 18.744 109.261 19.1813 110.37 20.056C111.501 20.9307 112.173 22.136 112.386 23.672H108.514C108.279 22.4987 107.394 21.912 105.858 21.912C105.09 21.912 104.493 22.0613 104.066 22.36C103.661 22.6587 103.458 23.032 103.458 23.48C103.458 23.9493 103.767 24.3227 104.386 24.6C105.005 24.8773 105.826 25.1333 106.85 25.368C107.959 25.624 108.973 25.912 109.89 26.232C110.829 26.5307 111.575 26.9893 112.13 27.608C112.685 28.2053 112.962 29.0693 112.962 30.2C112.983 31.1813 112.727 32.0667 112.194 32.856C111.661 33.6453 110.893 34.264 109.89 34.712C108.887 35.16 107.703 35.384 106.338 35.384Z"
                  fill="#111827"></path>
              </svg>
            </a>
            <button class="navbar-close">
              <svg
                class="h-6 w-6 text-gray-400 cursor-pointer hover:text-gray-500"
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M6 18L18 6M6 6l12 12"></path>
              </svg>
            </button>
          </div>
          <div>
            <ul>
              <li class="mb-1">
                <a
                  class="block p-4 text-sm font-semibold text-gray-400 hover:bg-green-50 hover:text-green-600 rounded"
                  href="/">Home</a
                >
              </li>
              <li class="mb-1">
                <a
                  class="block p-4 text-sm font-semibold text-gray-400 hover:bg-green-50 hover:text-green-600 rounded"
                  href="about">About</a
                >
              </li>
              <li class="mb-1">
                <a
                  class="block p-4 text-sm font-semibold text-gray-400 hover:bg-green-50 hover:text-green-600 rounded"
                  href="blog">Blog</a
                >
              </li>
            </ul>
          </div>
          <div class="mt-auto">
            <div class="pt-6">
              <a
                class="block px-4 py-3 mb-2 leading-loose text-xs text-center text-white font-semibold bg-green-600 hover:bg-green-700 rounded-l-xl rounded-t-xl"
                href="#">Learn More</a
              >
            </div>
            <p class="my-4 text-xs text-center text-gray-400">
              <span>© 2020 All rights reserved.</span>
            </p>
          </div>
        </nav>
      </div>
    </section>

    <section>
      <div class="py-20 bg-gray-50 min-h-[calc(100vh-100px)]">
        <div class="container mx-auto px-4 w-full lg:w-3/4">
          <div class="flex gap-4 flex-wrap">
            <div class="flex flex-wrap -mx-3">
              <div class="mb-4 lg:mb-0 w-full lg:w-1/4 px-3">
                <img
                  class="w-full h-full object-cover rounded"
                  src="https://images.unsplash.com/photo-1578509395623-a34c97f15379?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&auto=format&fit=crop&w=968&q=80"
                  alt=""
                />
              </div>
              <div class="w-full lg:w-3/4 px-3">
                <a class="hover:underline" href="#">
                  <h3 class="mb-1 text-2xl font-bold font-heading">
                    Morbi scelerisque nulla et lectus dignissim eleifend nulla
                    eu nulla a metus
                  </h3>
                </a>
                <div class="mb-2 flex items-center text-sm">
                  <a
                    class="text-green-600 hover:underline hover:text-green-700"
                    href="#">John Doe</a
                  >
                  <span class="text-gray-400 mx-2">•</span>
                  <span class="text-gray-400">24 Jan, 2021</span>
                </div>
                <p class="text-gray-500">
                  Quisque id sagittis turpis. Nulla sollicitudin rutrum eros eu
                  dictum...
                </p>
              </div>
            </div>
            <div class="flex flex-wrap -mx-3">
              <div class="mb-4 lg:mb-0 w-full lg:w-1/4 px-3">
                <img
                  class="w-full h-full object-cover rounded"
                  src="https://images.unsplash.com/photo-1578509395623-a34c97f15379?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&auto=format&fit=crop&w=968&q=80"
                  alt=""
                />
              </div>
              <div class="w-full lg:w-3/4 px-3">
                <a class="hover:underline" href="#">
                  <h3 class="mb-1 text-2xl font-bold font-heading">
                    Morbi scelerisque nulla et lectus dignissim eleifend nulla
                    eu nulla a metus
                  </h3>
                </a>
                <div class="mb-2 flex items-center text-sm">
                  <a
                    class="text-green-600 hover:underline hover:text-green-700"
                    href="#">John Doe</a
                  >
                  <span class="text-gray-400 mx-2">•</span>
                  <span class="text-gray-400">24 Jan, 2021</span>
                </div>
                <p class="text-gray-500">
                  Quisque id sagittis turpis. Nulla sollicitudin rutrum eros eu
                  dictum...
                </p>
              </div>
            </div>
            <div class="flex flex-wrap -mx-3">
              <div class="mb-4 lg:mb-0 w-full lg:w-1/4 px-3">
                <img
                  class="w-full h-full object-cover rounded"
                  src="https://images.unsplash.com/photo-1578509395623-a34c97f15379?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&auto=format&fit=crop&w=968&q=80"
                  alt=""
                />
              </div>
              <div class="w-full lg:w-3/4 px-3">
                <a class="hover:underline" href="#">
                  <h3 class="mb-1 text-2xl font-bold font-heading">
                    Morbi scelerisque nulla et lectus dignissim eleifend nulla
                    eu nulla a metus
                  </h3>
                </a>
                <div class="mb-2 flex items-center text-sm">
                  <a
                    class="text-green-600 hover:underline hover:text-green-700"
                    href="#">John Doe</a
                  >
                  <span class="text-gray-400 mx-2">•</span>
                  <span class="text-gray-400">24 Jan, 2021</span>
                </div>
                <p class="text-gray-500">
                  Quisque id sagittis turpis. Nulla sollicitudin rutrum eros eu
                  dictum...
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </body>
</html>

<style></style>

<script></script>

```
