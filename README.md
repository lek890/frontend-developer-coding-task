# Moebel.de Frontend developer coding task

## Brief

The goal is to create a weather app, that shows the weather forecast for a given city. We recommend to either use https://openweathermap.org/api or create a mock api, for instance via https://github.com/typicode/json-server

Please fork this repository and apply your solution into it. Once you are done you can share it with us. We are expecting you to finish this task in one week. Please read this document before starting to work on your solution. If you think you will not be able to deliver the solution in time, you can contact us and ask for more time.

**Details**

- The initial city can either be hardcoded or resolved via browser api
- Days should start at the current day and the next four days should be shown (so five days altogether)
- Background gradient should change based on temperatur:
  - Teal shades for less than 15°C
  - Orange shades for greater or equal than 15°C
- The content should have a blur effect when the city input field gets focused
- In case there is no result for a given city name, an error message should be shown. There are no design specifications for this error message. It's on you to create and style this in a suitable way

## Design

Abstract: https://share.goabstract.com/d9d21d66-c748-4877-adf2-7c511d0812d7

Icons: https://github.com/erikflowers/weather-icons/tree/master/svg

Font: https://fonts.google.com/specimen/Roboto?query=roboto

## Tech Stack

- React (UI Library)
- Typescript (Language)
- Styled Components (Styling)
- Jest (Test runner)
- React Testing Library (Testing)
- Rxjs (Optional)
- Ramda (Optional)
- Storybook (Optional)

> Note: Please stick with React's internal APIs to handle state management.
> Prefer function components and hooks over class components

## Checklist

- [ ] Create a background component that changes based on given tempreture
- [ ] Create icon components out of svgs
- [ ] Create ui components for the rest
- [ ] Setup weather api (or implement a mock server)
- [ ] Wire city input with the api
- [ ] Create a component for listing weekly weather forecast
- [ ] Wire that component with the api

## Acceptance Criteria

- Using Typescript is mandatory.
- Test coverage should be above 90%.
- The app should be working and buildable with no errors.
- There should be individual commits with meaningful commit messages for every step. (Not for every change/update)
