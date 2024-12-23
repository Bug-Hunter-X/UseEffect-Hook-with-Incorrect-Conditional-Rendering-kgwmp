# useEffect Hook with Incorrect Conditional Rendering

This repository demonstrates a common error in React's `useEffect` hook where incorrect conditional rendering logic leads to unexpected behavior. The issue occurs when a condition inside the `useEffect` callback is not correctly handling the initial render or state updates.

## Problem

The `useEffect` hook is used to perform side effects based on changes in the component's state. However, in this example, the conditional rendering logic inside `useEffect` does not correctly handle the initial render where `count` is 0.

## Solution

The solution is to refactor the conditional rendering logic within `useEffect` to explicitly handle the initial render or to use a more robust approach to control the side effect execution.