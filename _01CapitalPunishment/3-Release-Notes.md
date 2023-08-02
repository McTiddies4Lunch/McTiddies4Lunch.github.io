---
layout: default
title: Release Notes
nav_order: 3
description: Release Notes
---

<div> 

<!-- Lightweight client-side loader that feature-detects and load polyfills only when necessary -->
<script src="https://cdn.jsdelivr.net/npm/@webcomponents/webcomponentsjs@2/webcomponents-loader.min.js"></script>

<!-- Load the element definition -->
<script type="module" src="https://cdn.jsdelivr.net/gh/zerodevx/zero-md@1/src/zero-md.min.js"></script>

<!-- Simply set the `src` attribute to your MD file and win -->
<zero-md src="https://raw.githubusercontent.com/TheMrNewVegas/TTWTrueVegas/main/Releases.md">
  <template>
    <!-- Define your own styles inside a `<style>` tag -->
    <style>
      h1,
	  h2,
	  h3,
      h4,
	  h5,
	  h6, {
		  margin-top: 0;
		  margin-bottom: 1em;
		  font-weight: 500;
		  color: #f5f6fa;
      }
	  
	  body {
		  font-family: system-ui, -apple-system, blinkmacsystemfont, "Segoe UI";
		  font-size: inherit;
		  line-height: 1.4;
		  color: #e6e1e8;
		  overflow-wrap: break-word;
      }
	  li {
		  margin: 0.25em 0;
	  }
	  a {
		  color: #CBC3E3;
		  text-decoration: none;
		}

    </style>
  </template>
</zero-md>

</div>
