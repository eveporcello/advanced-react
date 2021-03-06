# Advanced React Links

## Instructor Info

- **Eve Porcello**: [Twitter](https://twitter.com/eveporcello) | [Email](mailto:eve@moonhighway.com)
- **Moon Highway Training**: [Moon Highway Website](https://www.moonhighway.com) | [Mailing List](http://bit.ly/moonhighway) | [Articles](https://www.moonhighway.com/articles)

## React Hooks

- [Toggle Challenge - Solution](https://codesandbox.io/s/toggle-challenge-wvdbj)

### Star Rating

- Five Stars Rendered - ([run it](https://codesandbox.io/s/learning-react-star-rating-1-h7byq?file=/src/StarRating.js))
- Star Component with Props - ([run it](https://codesandbox.io/s/learning-react-star-rating-2-zbkuu?file=/src/App.js))
- Star Component with State - ([run it](https://codesandbox.io/s/learning-react-star-rating-3-tpmr9?file=/src/StarRating.js))
- Completed Star Component - ([run it](https://codesandbox.io/s/learning-react-star-rating-4-gxvb5?file=/src/Star.js))
- Advanced Star Component - ([run it](https://codesandbox.io/s/learning-react-star-rating-5-86ngm?file=/src/StarRating.js))

### Color Organizer

- Feature: Display Color Data - ([run it](https://codesandbox.io/s/learning-react-color-organizer-1-5r8tr?file=/src/App.js))
- Features: Remove Color, Rate Color - ([run it](https://codesandbox.io/s/learning-react-color-organizer-2-iytxb?file=/src/App.js))
- Feature: Add Color Component with Refs - ([run it](https://codesandbox.io/s/learning-react-color-organizer-3-kkyn0?file=/src/AddColorForm.js))
- Refactor: Add Color Controlled Component - ([run it](https://codesandbox.io/s/learning-react-color-organizer-4-sudge?file=/src/AddColorForm.js))

### Custom Hooks

- Refactor: `useInput` hook - ([run it](https://codesandbox.io/s/learning-react-color-organizer-5-umj5q?file=/src/hooks.js))
- Feature: Adding a Color to State - ([run it](https://codesandbox.io/s/learning-react-color-organizer-6-ewxpp?file=/src/App.js))
- Refactor: Colors In Context - ([run it](https://codesandbox.io/s/learning-react-color-organizer-7-lg9y3?file=/src/index.js))
- Refactor: `useColors` hook - ([run it](https://codesandbox.io/s/learning-react-color-organizer-8-jqchd?file=/src/ColorProvider.js))
- BONUS: Color Organizer App (with emotion css)- ([run it](https://codesandbox.io/s/learning-react-color-organizer-9-ypf8r?file=/src/ColorList.js))

### useReducer

- Checkbox with `useState` - ([run it](https://codesandbox.io/s/learning-react-usereducer-1-ef229?file=/src/App.js))
- Checkbox with `toggle` - ([run it](https://codesandbox.io/s/learning-react-usereducer-2-oqy23?file=/src/App.js))
- Checkbox with `useReducer` - ([run it](https://codesandbox.io/s/learning-react-usereducer-3-mht63?file=/src/App.js))
- Increment number with `useReducer` - ([run it](https://codesandbox.io/s/learning-react-usereducer-4-b1yxs?file=/src/App.js))

### useReducer to handle Complex State

- `useState` with objects - ([run it](https://codesandbox.io/s/learning-react-usereducer-complex-1-k7ibz?file=/src/App.js))
- `useReducer` with objects - ([run it](https://codesandbox.io/s/learning-react-usereducer-complex-2-ewue8?file=/src/App.js))
- legacy `setState` with `useReducer` - ([run it](https://codesandbox.io/s/learning-react-usereducer-complex-3-2wldd?file=/src/App.js))

## xstate and State Machines

- [xstate Visualizer](https://xstate.js.org/viz/)
- [tahoeTravelMachine Visualized](https://xstate.js.org/viz/?gist=978291ab7a65607bafb58dcdaf65a65d)
- [Tahoe Travel Machine](https://github.com/eveporcello/xstate-examples)
- [Code Sandbox Start](https://codesandbox.io/s/dazzling-shape-k60q4?file=/src/App.js)

## Flux & Redux

- [Slides](https://docs.google.com/presentation/d/1lpIO_rH70Xrh1idiyJIgePIaQdONJVXkVpsDNd1UjaQ/edit?usp=sharing)
- [Activity Start](https://github.com/eveporcello/counter)
- [Activity Start: CodeSandbox](https://codesandbox.io/s/quiet-hooks-giwtk)
- [Activity Finished](https://github.com/eveporcello/counter/tree/complete)
- [Finished Tests](https://gist.github.com/eveporcello/f4b8f2e733c621cb4723cebb5745df84)

## GraphQL

### GraphQL Query Language

- [Query Language Slides](https://slides.com/moonhighway/graphql-intro/)
- [Snowtooth Playground](https://snowtooth.moonhighway.com)
- [Pet Library Playground](https://pet-library.moonhighway.com)
- [Moon Highway Vote Playground](http://vote.moonhighway.com)
- [Github GraphQL Explorer](https://developer.github.com/v4/explorer/)
- [Lab Instructions](https://slides.com/moonhighway/snowtooth-query-lab/)

### GraphQL Schema Definition Language

- [Slides for Reference](https://slides.com/moonhighway/schema-definition-language/)
- [Schema Design Cheat Sheet](https://github.com/sogko/graphql-schema-language-cheat-sheet)

### Example GraphQL APIs

- [Snowtooth API](https://github.com/graphqlworkshop/snowtooth-api/tree/complete)
- [Pet Library API](https://github.com/MoonHighway/pet-library)

### Apollo Client

#### Simple Requests

- curl Request

```sh
curl -X POST \
     -H "Content-Type: application/json" \
     --data '{ "query": "{allLifts{name}}" }' \
     http://snowtooth.moonhighway.com
```

- [Fetch Sample](https://codesandbox.io/s/n3jro0o4n0)
- [graphql-request](https://codesandbox.io/s/4qzq5z2vz0)

### React & Apollo

- [Snowtooth UI Start Files](https://github.com/graphqlworkshop/snowtooth-ui)
- [Snowtooth UI Finished Files](https://github.com/graphqlworkshop/snowtooth-ui/tree/complete)

### The Dependency Array

- Too many effects - ([run it](https://codesandbox.io/s/learning-react-useeffect-4-w723e?file=/src/App.js))
- Effect Dependencies - ([run it](https://codesandbox.io/s/learning-react-useeffect-5-uqol2?file=/src/App.js))
- Any Key to Render - ([run it](https://codesandbox.io/s/learning-react-useeffect-6-eg5w4?file=/src/App.js))
- Array Dependency issue - ([run it](https://codesandbox.io/s/learning-react-useeffect-7-3xo59?file=/src/App.js))
- `useMemo` - ([run it](https://codesandbox.io/s/learning-react-useeffect-8-w62wg?file=/src/App.js))
- Function Dependency issue - ([run it](https://codesandbox.io/s/learning-react-useeffect-9-yil9d?file=/src/App.js))
- `useCallback` - ([run it](https://codesandbox.io/s/learning-react-useeffect-10-e9im3?file=/src/App.js))


## Next Steps

- [Pet Library with Relay](https://github.com/eveporcello/pet-library-demo)
- [Fullstack Error Handling with GraphQL](https://blog.apollographql.com/full-stack-error-handling-with-graphql-apollo-5c12da407210)
- [Apollo Federation](https://egghead.io/playlists/getting-started-with-apollo-federation-60ad0165)
- [TypeScript & Apollo CLI - Finished Project + Instructions](https://github.com/graphqlworkshop/snowtooth-typescript)


## End of Class Questions

1. Integration Testing - What are best practices for testing integration?

- [Integration Testing with Testing Library](https://dev.to/francodalessio/writing-an-integration-test-with-react-testing-library-1eo3)

2. HOCs

- [HOC Overview](https://reactjs.org/docs/higher-order-components.html)
- [HOC Testing]()

3. Upcoming Changes to React

- [React Blog](https://reactjs.org/blog/all.html/)
- [Forums, News, Support](https://reactjs.org/community/support.html)
- [React Podcast](https://reactpodcast.simplecast.com/)
- [ui.dev Newsletter](https://bytes.dev/)
- [Server Components](https://reactjs.org/blog/2020/12/21/data-fetching-with-react-server-components.html)

4. Other Courses

- [Apollo Course](https://odyssey.apollographql.com/?utm_source=blog&utm_medium=sidebar&utm_campaign=blog_sidebar)
- [How to GraphQL](https://howtographql.com)
- [React Security](https://courses.reactsecurity.io/courses/react-security-fundamentals)
- [Functional JavaScript - FE Masters](https://frontendmasters.com/courses/functional-first-steps/)
- [State Machines & React - FE Masters](https://frontendmasters.com/courses/xstate-react/)
- [State Management - FE Masters](https://frontendmasters.com/courses/pure-react-state/)
- [Redux with Hooks - egghead](https://egghead.io/playlists/redux-with-react-hooks-8a37)
- [Shareable Hooks - egghead](https://egghead.io/courses/shareable-custom-hooks-in-react)
