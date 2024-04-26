# StrathVueApp
This is a university platform for students and people interested in learning about the institution. It details the learning offering that of the instutiution and enables students to register for courses .

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```

## Screenshots of StrathVueApp
Navigation bar
!![Screenshot (251)](https://github.com/bow-gwa/StrathVueApp-Bow-gwa/assets/151015273/531382da-bebf-4b6c-bc83-9b898d8caeec)
Home Page
![Screenshot (250)](https://github.com/bow-gwa/StrathVueApp-Bow-gwa/assets/151015273/82ca27bc-b7a3-4fe4-9898-c4b209ae5ff0)

Courses page
![Screenshot (249)](https://github.com/bow-gwa/StrathVueApp-Bow-gwa/assets/151015273/bb0f1512-b28c-4b66-b11d-d48604a77778)


### Run End-to-End Tests with [Nightwatch](https://nightwatchjs.org/)

```sh
# When using CI, the project must be built first.
npm run build

# Runs the end-to-end tests
npm run test:e2e
# Runs the tests only on Chrome
npm run test:e2e -- --env chrome
# Runs the tests of a specific file
npm run test:e2e -- tests/e2e/example.js
# Runs the tests in debug mode
npm run test:e2e -- --debug
```
    
### Run Headed Component Tests with [Nightwatch Component Testing](https://nightwatchjs.org/guide/component-testing/introduction.html)
  
```sh
npm run test:unit
npm run test:unit -- --headless # for headless testing
```
