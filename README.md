## react-theme-paperbase ##
This project extends [Create React App](https://github.com/facebook/create-react-app). We add routing and styling to the template to make launching your app even easier.

* Paperbase handles styling
* React-Router handles routing

**Paperbase** is a React theme curated by the folks at [Material-UI](https://material-ui.com/premium-themes/).

 * [Paperbase demo](https://material-ui.com/premium-themes/paperbase/) at Material-UI.
 * [Paperbase source](https://github.com/mui-org/material-ui/tree/master/docs/src/pages/premium-themes/paperbase) at git

**React Router** is the standard routing library for React.

 * [React Router](https://reacttraining.com/react-router)

## Getting Started ##

Open a BASH prompt and navigate to the location where your app will live.

1. Create a new folder to hold your app.

  `mkdir my-app`

2. Clone this project to your new folder.

  `git clone https://github.com/ckriewall/react-theme-paperbase.git`

3. Start the App

  `yarn start`

## File Structure ##

 * `src\components`: React components containing the app content
 * `src\theme`: MUI components providing site structure and styles
 * `src\theme\Content`: default content provided by Paperbase
 * `src\theme\Header`: top navbar
 * `src\theme\Navigator`: collapsing left navbar
 * `src\theme\Paperbase`: root document of the Paperbase theme. Calls Header and Navigator components

## Routing ##
Routing is implemented in the Navigator component. The `categories` variable contains two Link Categories. Customize the links by passing values to any object in categories.children:

 * **id**: link text (e.g. "New Page")
 * **icon**: any imported [Material-UI icon](https://material.io/icons/)
 * **targetUrl**: path of the new route (e.g. "/newpage")

## Component Layout ##

 ![layout](https://i.imgur.com/1B2ii5A.png)
