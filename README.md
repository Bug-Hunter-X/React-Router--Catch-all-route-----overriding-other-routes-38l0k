# React Router Catch-all Route Issue

This repository demonstrates a common issue in React Router v6 where a catch-all route (`*`) prevents other routes from working correctly. The `*` route, intended for 404 handling, always matches before any other routes due to its placement.  

The solution involves moving the catch-all route to the end of the `Routes` component to ensure it only matches if no other routes match.