# RNS Presentations

I am in the process of learning about the [Reticulum Network Stack (RNS)](https://github.com/markqvist/reticulum)

What better idea is there, than to produce presentations about a subject you are not familiar with :-) Please feel free to like, dislike or discuss.


## Take a Look
To view the presentations, please visit [RNS Presentations](https://r8io.github.io/rns-presentations)

To move through the presentation use the `left arrow` and `right arrow` keys of your keyboard. On some slides the `down arrow` key can used to show further information. For a quick overview press `esc` and a thumbnail view of the slides will appear.


## About
The presentations are written with [AsciiDoc](https://docs.asciidoctor.org/asciidoc/latest/) markup language. [Asciidoctor reveal.js](https://docs.asciidoctor.org/reveal.js-converter/latest/) is used to transform AsciiDoc files into HTML5 presentations.


### View Offline
The presentations can also be viewed offline. All the necessary files are contained within the `source` directory, ready for use after download. 

Just click on the `.html` file of the presentation you like to see. At the moment there is only _one_ introductory presentation.


### Contribute
If you think these kind of presentations could be helpful for the [Reticulum](https://github.com/markqvist) project, you might consider to help improve existing presentations or come up with your own ones.

In order to do that a couple of things need to be done:
- Install [Nodejs and Node Packet Manager (NPM)](https://nodejs.dev/en/download/)
- Fork this git repo to use it as a template
- Go to the `source` directory inside your local copy of the repo
- To modify an existing presentation:
  - Modify the content of the `001-introduction.adoc` file as needed
  - Convert the `001-introduction.adoc` file into HTML slides
    - `$ npx asciidoctor-revealjs 001-introduction.adoc`
  - A new file `001-introduction.html` with the HTML slides was generated 
- To write a new presentation:
  - Delete the `001-introduction.html` file
  - Rename the `001-introduction.adoc` file to `<presentation-name>.adoc`
  - Modify the content of the `<presentation-name>.adoc` file as needed
  - Convert the `<presentation-name>.adoc` file into HTML slides
    - `$ npx asciidoctor-revealjs <presentation-name>.adoc`
  - A new file `<presentation-name>.html` with the HTML slides was generated 
