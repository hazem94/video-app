[![Netlify Status](https://api.netlify.com/api/v1/badges/955504db-c3f8-47e1-86fe-0a68bd762d20/deploy-status)](https://app.netlify.com/sites/media-surfer/deploys)

  
# Media Surfer
This is a Media "Movies, Series" App by Hazem. W

# How to install
*  You need to have `git` & `yarn` installed in your machine.
1. Dowload the project from Github.
2. Go to the main folder and hit `yarn install` to install the dependencies.

# Used packages
* `reach-router` for routing.
* `axio` for API requests.
* `bootstrap` for UI.
* `prop-types` for type checking.
* `react-toastify` for notification.
* `redux` for state management.
* `redux-logger` & `redux-thunk` as redux enhancers.
* `redux-form` for managing the forms. 

# Project Structure
- `src/actions/` for redux action methods.
- `src/api/` for everything related to API calls, URLs.
-  `src/components/` for all general components 'both class & functional'.
- `src/constants/` for all constants e.g. route names, actionTypes, global strings 'tokenName' ...etc.
- `src/form/` for general and reusable forms, form validators, formNames,  andform rendering files.
- `src/helpers/` for helper functions e.g. localStorage related methods, strings, numbers, ...etc.
- `src/reducers/` for reducers.

## Followed React Patterns
- In the implementation I followed:
	1. `Container Viewer Pattern` to split manipulating the state from the view layer for easier debugging and more resusable components.
	2. `Decorated Components` to wrap the components with `reduc-form`.

## Design System
- It's a general file used for global styling, colors, font sizes, ...etc.

## Styling with `CSS`
- For this purpose, you can add your own `CSS` code in `index.css` or `app.css`.
