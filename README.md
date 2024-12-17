# React useEffect Cleanup Function Bug
This repository demonstrates a common bug related to the cleanup function in React's `useEffect` hook.  The example shows how a missing dependency or an incorrectly configured `useEffect` hook will not execute the cleanup function as expected. This often leads to memory leaks or unexpected behavior when components unmount.

## Bug Description
The provided code demonstrates a scenario where the cleanup function within a `useEffect` hook is not called when it should be. This happens because of an incorrect use of the dependency array.