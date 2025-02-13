# Asynchronous State Updates in React useState

This repository demonstrates a common misunderstanding in React regarding the asynchronous nature of state updates with `useState`.  The example shows how logging the state immediately after an update will output the *previous* state value, not the updated one.  The solution provides a corrected approach using functional updates and useEffect for logging changes after the state is actually updated.
