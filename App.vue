<template>
  <div id="app">
    <div class="container">
      <IntroHeader />
      <hr />
      <Summary>
        <p>
          As an industry veteran with over 20 years experience, my experience and interest has run the gamut from user interaction design, through web development and front-end engineering, soware engineering, to systems administration, soware architecture,
          and horizontally scale-able server infrastructures, along with the project management experience to pull it all together.
        </p>
        <p>I'm currently specializing in Laravel , Vue , React and/or WordPress projects that may require extensive experience with core internal APIs, Plugin development, or deep integrations with other products and services.</p>
        <p>
          <em>I love what I do.</em>
        </p>
      </Summary>
    </div>
  </div>
</template>
<script>
import IntroHeader from "./components/IntroHeader";
import Summary from "./components/Summary";

export default {
  components: {
    IntroHeader,
    Summary,
  },
};
</script>
<style lang="css">
@import url("https://unpkg.com/chota@latest");
:root {
  --bg-color: #ffffff;
  --bg-secondary-color: #f3f3f6;
  --color-primary: #447;
  --color-lightGrey: #d2d6dd;
  --color-grey: #747681;
  --color-darkGrey: #3f4144;
  --color-error: #d43939;
  --color-success: #28bd14;
  --grid-maxWidth: 120rem;
  --grid-gutter: 2rem;
  --font-size: 1.6rem;
  --font-color: #333333;
  --font-family-sans: sans-serif;
  --font-family-mono: monaco, "Consolas", "Lucida Console", monospace;
  --grid-maxWidth: 890px;
}

body.dark {
  --bg-color: #000;
  --bg-secondary-color: #131316;
  --font-color: #f5f5f5;
  --color-grey: #ccc;
  --color-darkGrey: #777;
}

.container {
  margin-top: 60px;
  width: var(--grid-maxWidth);
}
</style>
