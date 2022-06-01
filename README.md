## 1. What is React? What are its features.
 #### React was created by Jordane Walke , a software engineer at facebook in the year 2011 and it was deployed first at the facebook newsfeed and later it was used in facebook and instagram. React is a open source front end js library . It follows the component based approach for building reusable  UI components speacially for single page application and it is used for developing interactive view layer of web and mobile application.
---
## Feature of React
#### I. Virual Dom
#### II. One Way Data Binding
#### III. Reusable Component
#### IV. JSX(Javascript Syntex Extention)
#### V. Performance

---
 ## 2. Explain Virtual DOM.
 #### DOM is a document object model, created by converting HTML CSS and JS Real DOM, which is an object which gets created whenever any React application gets loaded on the screen for the first time., whenever React components gets mounted on the screen for the first time. Now when any user makes any changes on the screen like button click because of which the state variable will get updated so in this case the changes will not directly go to Real DOM , instead in react we have concept known Virtual DOM. So we are having two virtual doms, one virtual dom gets created at the time of mounting of react component so it is a copy of your real dom. Another virtual dom is the dom which contains the new changes, updated state variables values. Now these two virtual doms will get compared with each other and will check for the new changes. this complete procedure is known as diffing algorithm. Now the new changes will be updated in your Real dom. this procedure is known as Recoinciliation.
---

## 3.Explain Diffing Algorithm
#### React, Angular or Veu
#### LIbray or framework
#### Library is a set of reusable functions used by computer programme and framework is a piece of code that dictates the architecture of a project , code calls the library but in framework , framework calls the code. in libray we can control the data flow by methods but in framework we dont have any control of the data flow framework decides how the dat awill flow that is nothing but frameworks callls the code. and in perfornmance wise react is having higher performance over angular and veu and community support and also react is having the easy learning curve and react is having SPA(Single page application) .
---
## 4. Class component vs functional component
         
#### 1. Class Component uses the Lifecycle methods where as in functional component have HOOKs
#### 2. Functional component are also called stateless component while class component is called statefull component and there is no render function while in functional there is return  
#### 3. functional component accepts props as argument but props and state can be accepted in class components
#### 4. Functinal Componenrs are easty to read as they have less code but the class components have complex code structure and hard to write.
#### 5. In class component we uses the "this " keyword but in functional we dont need the keyword
---
## 5. Stateless vs Statefull
#### :- Stateless component does not hold or manage state While statefu;ll component can hold or manage state, Stateless component are easy to understand but the statefull component it is complex as compared to the stateless components. Stateless component does not work with react lifecycles but whreas statefull work with lifecycle methods. Stateless can not be reused while can be used in case of statefull component.Stateless compnent is also known as functional component. Statefull is known as class component
  ---        
## 6. What are the different phases of React components lifecycle?
#### :- In ReactJS, every component creation process involves various lifecycle methods. These lifecycle methods are termed as component's lifecycle. These lifecycle methods are not very complicated and called at various points during a component's life. The lifecycle of the component is divided into four phases. They are:
### 1.	Initial Phase
### 2.	Mounting Phase
### 3.	Updating Phase
### 4.	Unmounting Phase
### Each phase contains some lifecycle methods that are specific to the particular phase.
---

## 7. What is Single Page Application or SPA Explain the difference between SPA and MPA
#### :- in terms of speed and performance SPA no reloading is needed that is equal to high speed and responsivenss
#### :- MPA which is having slow speed and performanceis affected by reloading
#### :- according to coding reusable code for SPA
#### :- MPA needs to coding from scratch
#### :- according to maintenance SPA is fast and easy maintenance
#### :- for MPA maintenance required for each page
#### :- accordingto SEO SPA is having limited optimization
#### :- according to user experience SPA is very smooth and friendly
#### :- MPA user experienceis bad
#### :- there is no loading time required for SPA
#### :- SPA secures only endpoints
#### :- MPA secures end to end
---
## 8. Differentiate between states and props.
#### :- stat changes can be asynchronous
#### :- props can be readonly
#### :- props can be accessed by child components
#### :- stat cant be accessed by child components
#### :- props are used to communication between components
#### :- stats can be used to change render dynamic chnages within the component
#### :- props are immutable
#### :- stats is mutable
#### :- props are external and controls by Whatever render the component
#### :- stat is internal and controls by react component itself
   ---      
## 9. Explain props drilling concept and state uplifting
#### :- props drilling is a basically a situation in the same data is been sent to sent it almost every due to the requirement in the final level
#### :- when we have to share the same data across multiple child components then define the data into the parent.
#### :- every component in react has its own state because of These sometimes data can be reabundant and inconsistent so by liftingup the state of the parent component as a singlesource of the truth and pass the data of the children in its parent.
---
## 10 What do you know about controlled and  ncontrolled components?
#### :- In the React component data is controlledby the React component or parent component
#### :- in the uncontrolled componentdata is controlledby DOM itself.
#### :- control components allows validation control
#### :- uncontrolled component doesn't allow validation control
#### :- in control component it has better control over the forms and data
#### :- in uncontrolled component limit control over the forms and data.
---
## 11. What is React Router?
#### :- react router is a standard library for routing in react it enable the navigation among the views of various components in react application.it allow changing the browser URL
#### :- react router plays an important role to display multiple views in a SPA