# Modern CSS Boilerplate

This project rethinks the CSS boilerplate using modern style authoring techniques. It covers (almost) all html elements and has a few goals:

- Use frictionless selectors to avoid style overrides
- Encourage better markup using attribute selectors
- Provide a bare-bones style token system for consistency
- Setup often overlooked quality of life tweaks, like `scroll-margin-top`
- Provide examples for common design patterns & features, like link icons for out-bound links and PDFs

If you'd like to read more about the selector process, check out my [blog post](https://www.mattmcadams.com/thoughts/smart-selectors). The best way to get to know the project and its features is to [read through the source](https://github.com/MattMcAdams/CSS-Boilerplate/blob/master/index.css), its just over 1200 lines with a lot of blank lines and comments.

I've been using this boilerplate for a while, making small tweaks and bug fixes as I've adapted it to work with many different projects. It's a breeze to build on and easy to edit. Rip out what you don't want, it's all thoroughly commented, and add in what you need.

## A Work in Progress

The idea is that you can add in whatever utilities or components your project needs, this is just meant to be a really small thing to get started. Because its still a work in progress, and I'm still working through the scope of the project and what it needs to do, things will change.

## Build

While not necessary, you _can_ customize what ends up in the index.css by adjusting the concatenation build script, or removing/adding any css files to the /src directory. The build script only combines the css files into a single index.css, so there are no dependencies. I do not plan to use SCSS or create more complicated builds.

## Questions, Concerns, Contact, Etc

If you'd like to talk to me about CSS, or some of the decisions made here, feel free to reach out at mattmcadams@outlook.com or [open an issue](https://github.com/MattMcAdams/CSS-Boilerplate/issues).

## Contributing

I'm not really looking for contributors at the moment, especially since I haven't really decided on the scope. Let me know if you want to get involved though and we can chat about it. If you see a bug or want to offer feedback, you're welcome to open an issue and let me know. I mostly built this for myself and my own projects.

## License

Free to use, go for it, have fun. Specifically this is licensed under [The Unlicense](https://github.com/MattMcAdams/CSS-Boilerplate/blob/master/LICENSE).
