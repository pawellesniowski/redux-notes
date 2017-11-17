## The first princile of Redux is to represent the whole state of your app as a single javascript object. 
We have one huge store, which holds the whole app state. 
## 

## Instalation in app
  npm i --save redux react-redux

## Steps to set redux:
  0. Create file constans.js in src.
      const DO_SOMETHING = "DO_SOMETHING"
  1. Action (plain object)
      {
        type: DO_SOMETHING, // imported from constans.js
        payload: 
      }
  2. Action Creator (function which returns Action)
      function(){
        return {
          type: DO_SOMETHING,
          payload:
        }
      }
  3.
