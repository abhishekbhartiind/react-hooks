###### React Hooks

Redux is cumbersome especially bcog on every page, like some wiring like use that connect, mapStateToProps & mapDispatchToProps

Store: Has to be declared global
Reducer:  it performs an action type and return ...state and global state to components.. initialsize as rootReducer
Action: Method performed, called by components and dispatch change state data with passing type to reducer 

--------------------------------

Hooks: New Redux

It quite simplify redux into small code.

```
yarn add react react-redux@next redux@next

```
USE useSelector, useDispatch library from react-redux, it return state with dispatch on type 

```
import {useSelector, useDispatch} from 'react-redux'

```


