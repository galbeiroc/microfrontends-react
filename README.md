# Microfrontends with React
About this course. Build incredibly scalable apps with a microfronted architecture.

## Major Categories of Integration

### Build-Time Integration
#### Complile-Time Integration
*Before* container get loaded in the browser, it gets access.
Build-Time Integrations give the container access to a child's app source **before** it is loaded in the browser.

### Run-Time Integration
#### Client-Side Integration
Run-Time integrations give the container access to a child's app source **before** it is loaded in the browser.

### Server Integration

* Designate one app as the Host (CONTAINER) and one as the Remote (PRODUCTS).
* In the Remote, decide which modules (files) we want to make available to the project.
* Set Module Federation Plugin to *expose* those files.
* In the Host, decide which files we want to get from the Remote.
