# Setup Steps from Tutorial 6 to 7
This guide will show you the steps to perform if you are working from Tutorial 6 source code.

# Update iOS Pod
Due to the iOS platform update, we need to update the iOS pod module. Issue the following command to update the Pods.

```
cd ios && pod update && cd ..
```

# Components to install
We need to install a few modules to enable Redux engine.

1. redux
2. react-redux
3. redux-logger
4. redux-promise-middleware
5. redux-thunk

```
yarn add redux \
react-redux \
redux-logger \
redux-promise-middleware \
redux-thunk \ 
immutable
```
