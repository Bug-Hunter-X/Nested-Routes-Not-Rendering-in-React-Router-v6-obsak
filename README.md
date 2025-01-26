# React Router v6 Nested Route Rendering Issue

This repository demonstrates a common issue encountered when working with nested routes in React Router v6.  The problem is that nested route components fail to render, leaving the nested route section of the UI blank despite the parent route rendering correctly.

## Problem Description

The provided code implements basic nested routing using `BrowserRouter`, `Routes`, and `Route` components. However, when attempting to navigate to a nested URL, the nested components don't render.  The parent component displays, but the nested content remains empty.

## Solution

The solution involves ensuring correct usage of the `useParams` hook and a potential adjustment of the route path structure, as demonstrated in the `bugSolution.js` file. This fixes the issue and allows the nested components to render successfully.