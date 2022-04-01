# react-native-learning

# Setup
- https://reactnative.dev/docs/environment-setup
- npv version: 
- npm install 


# debug
- install simulator - https://stackoverflow.com/questions/63218262/unable-to-install-android-emulator-hypervisor-driver-for-amd-processor

introduction of jsx

attributes in jsx ----https://www.codecademy.com/courses/react-101/lessons/react-jsx-intro/exercises/attributes-in-jsx
nested jsx --- https://www.codecademy.com/courses/react-101/lessons/react-jsx-intro/exercises/nested-jsx
jsx outer elements ---- https://www.codecademy.com/courses/react-101/lessons/react-jsx-intro/exercises/jsx-outer-elements
Rendaring jsx --- https://www.codecademy.com/courses/react-101/lessons/react-jsx-intro/exercises/render-jsx
                  ReactDOM.render(<h1>Hello world</h1>, 
                  document.getElementById('app'));
                  
                   ReactDOM.render() I ----https://www.codecademy.com/courses/react-101/lessons/react-jsx-intro/exercises/reactdom-render-i
                   ReactDOM.render() II ---- https://www.codecademy.com/courses/react-101/lessons/react-jsx-intro/exercises/reactdom-render-ii
                   
Passing a Variable to ReactDOM.render() ----  https://www.codecademy.com/courses/react-101/lessons/react-jsx-intro/exercises/reactdom-render-variabl
E.g const toDoList = (
  <ol>
    <li>Learn React</li>
    <li>Become a Developer</li>
  </ol>
);
 
ReactDOM.render(
  toDoList, 
  document.getElementById('app')
);
