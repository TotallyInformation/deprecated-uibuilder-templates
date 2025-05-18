# deprecated-uibuilder-templates

A small collection of templates for [UIBUILDER for Node-RED](https://github.com/TotallyInformation). These used to be included in the UIBUILDER installation but are now outdated and no longer included. They were removed from the UIBUILDER package in version 7.3.0.

Please note that these templates are deprecated and are no longer maintained. They are provided here for reference only.

To use them, you should copy the appropriate folder to the instance root folder of your UIBUILDER node. This is typically located at `~/.node-red/uibuilder/<url>` in your Node-RED installation.

## Templates

The last update to these templates was in December 2024.

* `esm-vue3-nobuild` - A Vue v3 template that includes a Vue module but does not require a build step. Uses the ESM uib client library.

* `iife-vue3-nobuild` - A Vue v3 template that includes a Vue module but does not require a build step. Uses the IIFE uib client library. Note that there is an updated version of this template [TotallyInformation/uib-template-iife-vue3-nobuild](https://github.com/TotallyInformation/uib-template-iife-vue3-nobuild) which is still maintained and accessible via the UIBUILDER template manager.

* `vue2-bootstrap` - A simple template using Vue 2 and Bootstrap-Vue v2. It demonstrates the various basic features you are likely to want in a simple, dynamic, data-driven user interface that uses the help of the VueJS v2 and bootstrap-vue front-end framework libraries. It includes display of control and standard messages to/from Node-RED as well as a simple form with submission back to Node-RED.

* `vue2-simple` - A much simpler version of the above with minimal code to act as a starting point for your own development.

There was a time when VueJS seemed to be the right framework to use to support UIBUILDER. However, the UIBUILDER project has moved on and now supports a much wider range of frameworks and libraries. Indeed, HTML, CSS and JavaScript have matured sufficiently that it is now possible to create very sophisticated user interfaces without the need for a framework at all. This is especially true with the introduction of Web Components and the Shadow DOM. As a result, these templates are no longer maintained and are provided here for reference only.

UIBUILDER continues to support the use of any front-end framwork but does not require one. As such, maintenance of these templates is a distraction from the main UIBUILDER project.

## License

This project is licensed under the Apache 2.0 License. See the [LICENSE](LICENSE) file for details.

You may use the code in this repository however you like, but please note that it is provided "as is" without any warranty of any kind. The author is not responsible for any damage or loss caused by the use of this code.
