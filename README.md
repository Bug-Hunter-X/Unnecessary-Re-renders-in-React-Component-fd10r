# Unnecessary Re-renders in React Component

This example demonstrates an issue where a React component re-renders unnecessarily after every state update.  The `useEffect` hook logs a message to the console on each render, illustrating the excessive re-renders. This can lead to performance problems in more complex applications.

The solution shows how to optimize the component to prevent unnecessary re-renders.