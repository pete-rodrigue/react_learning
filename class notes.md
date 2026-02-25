# class notes


To create a new project, run `npx create-react-app [name of the project]`

To run the code and show the web page in a browser, cd into the project folder and run `npm start`. (If you haven't added anything to the)

The project files you want to edit mostly live in the "src" subfolder of your project folder. Below are some of the files in that src folder.

In practice, once you start building, you'll mainly work in `App.js` and create a components folder alongside these files to organize your own components.

* `index.js` The entry point of your app. This is where React mounts your app onto the HTML page — specifically it grabs the `<div id="root">` in public/index.html and renders your app inside it. You rarely need to edit this file.
* `app.js` The root component of your app. It's the top-level component that all other components sit inside. This is where you'll spend most of your time early on, and where you'd set up routing or your main layout.
* `App.test.js` A basic test file for the App component, using Jest and React Testing Library. It comes with one simple test out of the box. You'd add more tests here as your app grows.
* `index.css` Global styles that apply across your whole app. Things like CSS resets, font settings, or body/html defaults go here.
* `reportWebVitals.js` An optional utility for measuring your app's performance (load speed, responsiveness, etc.). Unless you need performance monitoring, you can ignore it. It won't affect how your app works.
* `setupTests.js` Runs before your tests to set up the testing environment. It imports @testing-library/jest-dom which gives you helpful matchers like toBeInTheDocument(). You generally don't need to touch this file.





