# React Debugging Sample Application

## Overview

This is a simple React application used to demonstrate the process of debugging components using React Developer Tools.

## Components

- `Counter`: Manages the counter state and renders buttons for incrementing and decrementing the counter.
- `Display`: Receives the counter value as a prop and displays it.

## Debugging Process

1. **Initial Setup**:
   - Set up the application with basic components and state management.
   - Installed React Developer Tools.
2. **Inspecting Components**:
   - Inspected the `Counter` and `Display` components using the React Developer Tools.
3. **Identifying the Issue**:
   - Discovered that the `Display` component received a function (`setCount`) instead of a number (`count`).
4. **Fixing the Issue**:
   - Corrected the prop passed to `Display` in `Counter` to ensure it received the correct `count` value.
5. **Verification**:
   - Confirmed that the application works as expected and that the `count` state is correctly passed and displayed.

## Conclusion

The React Developer Tools is a powerful tool that allows developers to inspect, debug, and optimize their React components. This project demonstrated how to use the tool to identify and resolve issues within a React application.
