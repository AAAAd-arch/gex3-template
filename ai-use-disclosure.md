# AI Use Disclosure

**Course:** Programming #4 (2026)  
**Assignment:** Graded Exercise #3 - Ghibli Park Itinerary Builder  
**Student Name:** Yan Yitian  
**Student ID:** 2312516  


## AI USE DISCLOSURE

AI, with the help of LLM tools, was used for following purposes:

### Purpose 1: Understanding and Implementing Asynchronous Data Fetching in Vue 3 Lifecycle
**Where it was used:** Inside the `mounted()` lifecycle hook and the asynchronous `loadPlaces()` method in the script block.
**Why it was used:** To properly understand how to fetch external data from `ghibli_park.json` asynchronously using the modern `fetch()` API and `async/await` syntax, and safely update the reactive `places` array when the component mounts without blocking rendering or causing timing bugs.

### Purpose 2: Explaining Layout De-coupling and Preventing Background Image Distortion
**Where it was used:** Designing the CSS layout rules for the main container (`#app`), the accordion wrapper, and background slices (`.accordion-button`).
**Why it was used:** To diagnose a severe layout bug where changing header dimensions unexpectedly shrank or stretched accordion background images, distorting character ratios. AI was used to explain the interaction between `fit-content` width and child items under Flexbox alignment rules, providing structural layout concepts that were then implemented independently to fix the stretching issue.
