# SA-Testing
Testing Board For The Sound Agreements Project

[test 2](#test-2)

# Test

You might not see anything wrong in the component. It registers the scroll event in the mounted hook and un-registers it in the destroyed. They call a handleScroll methods that perform the scroll position check and calls the handleScrollChange method to change the color, depending on the status argument.

Right now the scrolling functionality is inside the Colorful component. However, we could take out the mounted and destroyed hooks and the handleScroll methods in order to reuse them in other components.

Let's see different ways to do that.

Component Inheritance
First let's start by moving the scroll-related behaviour into its own component Scroll.js:

export default {
  methods: {
    handleScroll() {
      if (window.scrollY > window.innerHeight) {
        this.handleScrollChange("out");
      } else {
        this.handleScrollChange("in");
      }
    }
  },
  mounted() {
    window.addEventListener("scroll", this.handleScroll);
  },
  destroyed() {
    window.removeEventListener("scroll", this.handleScroll);
  }
};
As you can see, this Scroll component expects a handleScrollChange to exist, which we implement in the child component, meaning that this component must be extended and cannot work on its own.

Since it only includes JavaScript, we can write it in a .js file, but it could be a .vue file as well if needed. Just keep in mind that only the JavaScript part of a .vue file will be inherited.

Then, in the Colorful component, let's remove all the component behaviour that we moved out and import the Scroll file using the extends component option:

# test 2
