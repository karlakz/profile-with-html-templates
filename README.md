# profile-with-html-templates

## Table of contents

  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Author](#author)

### Built with

- Custom Elements
- Shadow DOM
- HTML Templates

### What I learned

- Web components are created using new technologies: customElements, shadow DOM, html templates;
- HTML custom elements, which are not standard HTML5 elements, should be registered using JavaScript `window.customElements.define("element-name", ElementClassName)` method;
- Each custom element has a JavaScript class associated with it;
- Custom Element Life Cycle contains the following methods: **connectedCallback, disconnectedCallback, adoptedCallback, attributeChangedCallback, observedAttributes**;
- Shadow DOM is hidden from the rest of the DOM tree. It is attached to the shadow host, which is a node in the visible DOM tree. This shadow host is a shadow root from which the rest of the tree branches;
- HTML Templates are flexible templates that can be used in multiple places of the web page with different content or data without immediately showing it to the user. 


### Continued development

- I need to practice creating web components with customElements, Shadow DOM and HTML Templates.

## Author

- GitHub - [profile-with-html-templates](https://github.com/karlakz/profile-with-html-templates)
- Website URL - [Live URL](https://profile-using-templates-karlakz.netlify.app/)
