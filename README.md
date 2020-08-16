# NextJsTutorial

Following this tutorial [here](https://nextjs.org/learn/basics/create-nextjs-app/setup)

## Running Locally

Run `npm run dev` in solution directory

## Static Rendering vs. Server Side Rendering

[Here](https://nextjs.org/learn/basics/data-fetching/two-forms) is the link that goes into details.

My understanding:
  - Static Rendering is good for pages that can be built once and served per request and doesn't need to change
  - Server Side is good for pages that change per requests
  - Essentially, static rendering will result in the same page per request, no matter the origin of the request, server side will process the request and render a page per request
  - Static is faster since it can be cached in the CDN and should be used as default
  - NextJs allows for hybrid apps that use both depending on the page
