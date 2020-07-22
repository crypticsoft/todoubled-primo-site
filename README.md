# Built with [primo](https://primo.so)
This is a demo of the [primo.so](https://primo.so) service for the common use case of developing small, static driven sites. Ideally, this can be extended with dynamic data from potentially API endpoints.

Since this interface comes with [Tailwindcss](https://tailwindcss.com/), I'll be exploring this framework along side of building custom user interfaces with web components. The concept and difference here is that the primo interface allows for rapid component generation with custom field that use mustache templating. Unlike say, creating a library of ReactJS components, these are tied to a given site.

## Tailwindcss [blocks](https://mertjf.github.io/tailblocks/)
This is an experiment of taking common layouts and creating component blocks with fields that users can easily edit within the browser.
The workflow might look something like:
- Develop the site structure and navigation based on a given site needs
- Create the page layouts based on designer mockups using tailwindcss blocks as the foundation
- Extend the tailwind configuration and site styling to meet the site theme and customization needs
