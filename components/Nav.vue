<template>
  <ul>
    <li>
      <NuxtLink to="/"><span class="icon">
          <svg class="svg-inline--fa fa-heart fa-w-16 fa-fw" aria-hidden="true" focusable="false" data-prefix="fas"
            data-icon="heart" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" data-fa-i2svg="">
            <path fill="currentColor"
              d="M462.3 62.6C407.5 15.9 326 24.3 275.7 76.2L256 96.5l-19.7-20.3C186.1 24.3 104.5 15.9 49.7 62.6c-62.8 53.6-66.1 149.8-9.9 207.9l193.5 199.8c12.5 12.9 32.8 12.9 45.3 0l193.5-199.8c56.3-58.1 53-154.3-9.8-207.9z">
            </path>
          </svg>
        </span><span class="menu">Home</span></NuxtLink>
    </li>
    <li>
      <NuxtLink to="/obituaries"><span class="icon">
          <svg class="svg-inline--fa fa-map fa-w-18 fa-fw" aria-hidden="true" focusable="false" data-prefix="fas"
            data-icon="map" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512" data-fa-i2svg="">
            <path fill="currentColor"
            d="M447.1 0h-384c-35.25 0-64 28.75-64 63.1v287.1c0 35.25 28.75 63.1 64 63.1h96v83.98c0 9.836 11.02 15.55 19.12 9.7l124.9-93.68h144c35.25 0 64-28.75 64-63.1V63.1C511.1 28.75 483.2 0 447.1 0zM464 352c0 8.75-7.25 16-16 16h-160l-80 60v-60H64c-8.75 0-16-7.25-16-16V64c0-8.75 7.25-16 16-16h384c8.75 0 16 7.25 16 16V352z">
            </path>
          </svg>
        </span><span class="menu">Obituary and Tributes</span></NuxtLink>
    </li>
    <li>
      <NuxtLink to="/order-of-service"><span class="icon">
          <svg class="svg-inline--fa fa-map fa-w-18 fa-fw" aria-hidden="true" focusable="false" data-prefix="fas"
            data-icon="map" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512" data-fa-i2svg="">
            <path fill="currentColor"
              d="M0 117.66v346.32c0 11.32 11.43 19.06 21.94 14.86L160 416V32L20.12 87.95A32.006 32.006 0 0 0 0 117.66zM192 416l192 64V96L192 32v384zM554.06 33.16L416 96v384l139.88-55.95A31.996 31.996 0 0 0 576 394.34V48.02c0-11.32-11.43-19.06-21.94-14.86z">
            </path>
          </svg>
        </span><span class="menu">Service</span></NuxtLink>
    </li>
    <li>
      <NuxtLink to="/live-stream"><span class="icon">
          <svg class="svg-inline--fa fa-youtube fa-w-18 fa-fw" aria-hidden="true" focusable="false" data-prefix="fab"
            data-icon="youtube" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512" data-fa-i2svg="">
            <path fill="currentColor"
              d="M549.655 124.083c-6.281-23.65-24.787-42.276-48.284-48.597C458.781 64 288 64 288 64S117.22 64 74.629 75.486c-23.497 6.322-42.003 24.947-48.284 48.597-11.412 42.867-11.412 132.305-11.412 132.305s0 89.438 11.412 132.305c6.281 23.65 24.787 41.5 48.284 47.821C117.22 448 288 448 288 448s170.78 0 213.371-11.486c23.497-6.321 42.003-24.171 48.284-47.821 11.412-42.867 11.412-132.305 11.412-132.305s0-89.438-11.412-132.305zm-317.51 213.508V175.185l142.739 81.205-142.739 81.201z">
            </path>
          </svg>
        </span><span class="menu"><span>Service </span>Livestream</span></NuxtLink>
    </li>
    <li>
      <NuxtLink to="/poem"><span class="icon">
          <svg class="svg-inline--fa fa-map fa-w-18 fa-fw" aria-hidden="true" focusable="false" data-prefix="fas"
            data-icon="map" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512" data-fa-i2svg="">
            <path fill="currentColor"
              d="M373.1 24.97C401.2-3.147 446.8-3.147 474.9 24.97L487 37.09C515.1 65.21 515.1 110.8 487 138.9L289.8 336.2C281.1 344.8 270.4 351.1 258.6 354.5L158.6 383.1C150.2 385.5 141.2 383.1 135 376.1C128.9 370.8 126.5 361.8 128.9 353.4L157.5 253.4C160.9 241.6 167.2 230.9 175.8 222.2L373.1 24.97zM440.1 58.91C431.6 49.54 416.4 49.54 407 58.91L377.9 88L424 134.1L453.1 104.1C462.5 95.6 462.5 80.4 453.1 71.03L440.1 58.91zM203.7 266.6L186.9 325.1L245.4 308.3C249.4 307.2 252.9 305.1 255.8 302.2L390.1 168L344 121.9L209.8 256.2C206.9 259.1 204.8 262.6 203.7 266.6zM200 64C213.3 64 224 74.75 224 88C224 101.3 213.3 112 200 112H88C65.91 112 48 129.9 48 152V424C48 446.1 65.91 464 88 464H360C382.1 464 400 446.1 400 424V312C400 298.7 410.7 288 424 288C437.3 288 448 298.7 448 312V424C448 472.6 408.6 512 360 512H88C39.4 512 0 472.6 0 424V152C0 103.4 39.4 64 88 64H200z" />
          </svg> </span><span class="menu"> Debby Turns Sixty: a prose poem</span></NuxtLink>
    </li>
    <li>
      <NuxtLink to="/gallery"><span class="icon">
          <svg class="svg-inline--fa fa-images fa-w-18 fa-fw" aria-hidden="true" focusable="false" data-prefix="fas"
            data-icon="images" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512" data-fa-i2svg="">
            <path fill="currentColor"
              d="M480 416v16c0 26.51-21.49 48-48 48H48c-26.51 0-48-21.49-48-48V176c0-26.51 21.49-48 48-48h16v208c0 44.112 35.888 80 80 80h336zm96-80V80c0-26.51-21.49-48-48-48H144c-26.51 0-48 21.49-48 48v256c0 26.51 21.49 48 48 48h384c26.51 0 48-21.49 48-48zM256 128c0 26.51-21.49 48-48 48s-48-21.49-48-48 21.49-48 48-48 48 21.49 48 48zm-96 144l55.515-55.515c4.686-4.686 12.284-4.686 16.971 0L272 256l135.515-135.515c4.686-4.686 12.284-4.686 16.971 0L512 208v112H160v-48z">
            </path>
          </svg>
        </span><span class="menu">Gallery</span></NuxtLink>
    </li>
    <li>
      <NuxtLink to="/charity-donation"><span class="icon">
          <svg class="svg-inline--fa fa-hands-helping fa-w-20 fa-fw" aria-hidden="true" focusable="false"
            data-prefix="fas" data-icon="hands-helping" role="img" xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 640 512" data-fa-i2svg="">
            <path fill="currentColor"
              d="M488 192H336v56c0 39.7-32.3 72-72 72s-72-32.3-72-72V126.4l-64.9 39C107.8 176.9 96 197.8 96 220.2v47.3l-80 46.2C.7 322.5-4.6 342.1 4.3 357.4l80 138.6c8.8 15.3 28.4 20.5 43.7 11.7L231.4 448H368c35.3 0 64-28.7 64-64h16c17.7 0 32-14.3 32-32v-64h8c13.3 0 24-10.7 24-24v-48c0-13.3-10.7-24-24-24zm147.7-37.4L555.7 16C546.9.7 527.3-4.5 512 4.3L408.6 64H306.4c-12 0-23.7 3.4-33.9 9.7L239 94.6c-9.4 5.8-15 16.1-15 27.1V248c0 22.1 17.9 40 40 40s40-17.9 40-40v-88h184c30.9 0 56 25.1 56 56v28.5l80-46.2c15.3-8.9 20.5-28.4 11.7-43.7z">
            </path>
          </svg>
        </span><span class="menu"><span>Charity </span>Donations</span></NuxtLink>
    </li>
  </ul>

</template>

<style>

</style>
