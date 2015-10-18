The <div> tags are not actual DOM nodes; they are instantiations of React div components. You can think of these as markers or pieces of data that React knows how to handle. React is safe. We are not generating HTML strings so XSS protection is the default.

You do not have to return basic HTML. You can return a tree of components that you (or someone else) built. This is what makes React composable: a key tenet of maintainable frontends.
