# Modern CSS Boilerplate

This project is a no bullshit CSS boilerplate using modern style authoring techniques. It covers all html elements and uses smart selectors to avoid style overrides. It has an implementation of a basic style system and uses variables for common values. The typography is calcuated using a modular scale and the spacing system is build on the base line height.

I've included some suggested selectors and basic styles for common UI elements, like buttons, as well as some commented out features like adding an icon on out-bound links or links that open a PDF. Each selector was designed to create the least amount of friction when building new UIs and encourage accessible markup. If you'd like to read more about the selector process, check out my [blog post](https://www.mattmcadams.com/thoughts/smart-selectors). Or [read through the source](https://github.com/MattMcAdams/CSS-Boilerplate/blob/master/index.css), its just over 1200 lines with a lot of blank lines and comments.

I've been using this boilerplate for a while, making small tweaks and bug fixes as I've adapted it to work with many different projects. It's a breeze to build on and easy to edit. Rip out what you don't want, it's all throughly commented, and add in what you need.

## A Work in Progress

The idea is that you can add in whatever utilities or components your project needs, this is just meant to be a really small thing to get started. Because its still a work in progress, and I'm still working through the scope of the project and what it needs to do, I may change add or remove classes or variables.

IF I add components, they'll be in the optional `_components` file and the idea is to offer a suggestion on how the component should be marked up for accessibility, and then to enfore that markup with CSS. This is highly opinionated, but I'll do a lot of reseach before I add anything in. You can decide if you want/need the components or not. Components may be wholy outside the scope of the project though, I haven't decided yet.

You'll also see various comments throughout the code `TEMP`, `TODO`, Etc. I plan to eventually move these things to issues or something to keep better track of, but for now you'll have to explore the source if you want an idea of what a roadmap might look like.

In the future, I'd like to explore animations, print styles, better fallbacks for things like IE11 (which is currently unsupported), and newer CSS features like logical properties, leading trim, and aspect ratio.

## Build

While not necessary, you _can_ customize what ends up in the index.css by adjusting the concatenation build script, or removing/adding any css files to the /src directory. The build script only combines the css files into a single index.css, so there are no dependencies. I do not plan to use SCSS or create more complicated buids.

If you want to take everything, just download index.css, or copy and paste the source code into your project. Whatever floats your boat.

## Questions, Concerns, Contact, Etc.

If you'd like to talk to me about CSS, or some of the decisions made here, feel free to reach out at mattmcadams@outlook.com or [open an issue](https://github.com/MattMcAdams/CSS-Boilerplate/issues).

## Contributing

I'm not really looking for contributors at the moment, especially since I haven't really decided on the scope. Let me know if you want to get involved though and we can chat about it. If you see a bug or want to offer feedback, you're welcome to open an issue and let me know. I mostly built this for myself and my own projects, but if theres enough interest I'll look into setting up some public guidelines and stuff.

## License

Free to use, go for it, have fun. Specifically this is licesned under The Unlicense.
