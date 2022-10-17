<template>
  <div
    class="text-right pt-40 pr-3 sm:pr-32"
    data-aos="fade-left"
    data-aos-duration="500"
    data-aos-delay="300"
  >
    <h1 class="text-3xl font-semibold">⚙️ Projects</h1>

    <div class="w-72 py-3 right">
      <hr class="style-three" />
    </div>

    <p class="text-lg mt-4 pb-4 text-gray-300">
      All projects can be found on github with documentation.
    </p>
    <a href="http://github.com/jakub200CZ" target="_blank">
      <button class="cssbuttons-io">
        <span
          ><svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
            <path d="M0 0h24v24H0z" fill="none"></path>
            <path
              d="M24 12l-5.657 5.657-1.414-1.414L21.172 12l-4.243-4.243 1.414-1.414L24 12zM2.828 12l4.243 4.243-1.414 1.414L0 12l5.657-5.657L7.07 7.757 2.828 12zm6.96 9H7.66l6.552-18h2.128L9.788 21z"
              fill="currentColor"
            ></path>
          </svg>
          GitHub</span
        >
      </button>
    </a>

    <!-- <a href="#" target="_blank" rel="noopener"
      ><button class="learn-more">
        <span class="circle" aria-hidden="true">
          <span class="icon arrow"></span>
        </span>
        <span class="button-text">Soon</span>
      </button></a
    > -->
  </div>

  <!-- Link: https://www.getrevue.co/profile/jakubsedlacek04news -->
</template>

<style scoped>
/* From uiverse.io by @adamgiebl */
.cssbuttons-io {
  position: relative;
  font-family: inherit;
  font-weight: 500;
  font-size: 18px;
  height: 2em;
  letter-spacing: 0.05em;
  border: none;
  background: linear-gradient(to right, #2e2e2e, #343434);
  color: ghostwhite;
  overflow: hidden;
}

.cssbuttons-io svg {
  width: 1.2em;
  height: 1.2em;
  margin-right: 0.5em;
}

.cssbuttons-io span {
  position: relative;
  z-index: 10;
  transition: color 0.4s;
  display: inline-flex;
  align-items: center;
  padding: 0.2em 1.2em 0.2em 1.05em;
}

.cssbuttons-io::before,
.cssbuttons-io::after {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: 0;
}

.cssbuttons-io::before {
  content: "";
  background: #000;
  width: 120%;
  left: -10%;
  transform: skew(30deg);
  transition: transform 0.4s cubic-bezier(0.3, 1, 0.8, 1);
}

.cssbuttons-io:hover::before {
  transform: translate3d(100%, 0, 0);
}

.cssbuttons-io:active {
  transform: scale(0.95);
}

button {
  position: relative;
  display: inline-block;
  cursor: pointer;
  outline: none;
  border: 0;
  vertical-align: middle;
  text-decoration: none;
  background: transparent;
  padding: 0;
  font-size: inherit;
  font-family: inherit;
}

button.learn-more {
  width: 12rem;
  height: auto;
}

button.learn-more .circle {
  transition: all 0.45s cubic-bezier(0.65, 0, 0.076, 1);
  position: relative;
  display: block;
  margin: 0;
  width: 3rem;
  height: 3rem;
  background: #fff;
  border-radius: 1.625rem;
}

button.learn-more .circle .icon {
  transition: all 0.45s cubic-bezier(0.65, 0, 0.076, 1);
  position: absolute;
  top: 0;
  bottom: 0;
  margin: auto;
  background: #121212;
}

button.learn-more .circle .icon.arrow {
  transition: all 0.45s cubic-bezier(0.65, 0, 0.076, 1);
  left: 0.625rem;
  width: 1.125rem;
  height: 0.125rem;
  background: none;
}

button.learn-more .circle .icon.arrow::before {
  position: absolute;
  content: "";
  top: -0.29rem;
  right: 0.0625rem;
  width: 0.625rem;
  height: 0.625rem;
  border-top: 0.125rem solid #121212;
  border-right: 0.125rem solid #121212;
  transform: rotate(45deg);
}

button.learn-more .button-text {
  transition: all 0.45s cubic-bezier(0.65, 0, 0.076, 1);
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  padding: 0.75rem 0;
  margin: 0 0 0 1.85rem;
  color: #fff;
  font-weight: 700;
  line-height: 1.6;
  text-align: center;
  text-transform: uppercase;
}

button:hover .circle {
  width: 100%;
}

button:hover .circle .icon.arrow {
  background: #fff;
  transform: translate(1rem, 0);
}

button:hover .button-text {
  color: #121212;
}

@media screen and (max-width: 640px) {
  .right {
    position: absolute;
    right: 0;
    padding-right: 12px;
  }
}
</style>