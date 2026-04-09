react-native-attendance-app

ABOUT
A React Native attendance application implementing functional and class components with lifecycle methods for managing student presence.

ReadMe
# React Native Attendance App

This project is a simple attendance application built using React Native. It is developed as part of a Mobile Programming practical assignment focusing on component structure and lifecycle methods.

## Description
The application allows users to input a class code and confirm their attendance. It displays attendance status along with real-time information, demonstrating how state and lifecycle work in React Native.

## Features
- Input class code
- Attendance confirmation
- Real-time digital clock
- Student profile display
- Attendance status result
- Input validation

## Learning Objectives
- Understand the difference between Functional Component and Class Component
- Implement data passing using props
- Apply lifecycle methods:
  - componentDidMount()
  - componentDidUpdate()
  - componentWillUnmount()

## Tech Stack
- React Native
- Expo
- JavaScript

## How to Run
1. Install dependencies:
   npm install

2. Start the project:
   npx expo start

3. Run on device using Expo Go

## Project Structure
- App.js → main application (state & lifecycle)
- components/ → reusable functional components
- assets/ → images and resources
- package.json → project configuration

## System Overview
The application uses:
- Functional Components for UI rendering
- Class Component for managing state and logic
- Lifecycle methods to handle initialization, updates, and cleanup processes

## Workflow
1. User opens the application
2. User enters class code
3. User confirms attendance
4. System processes input
5. Attendance status is displayed with timestamp

## Output
- Student profile information
- Class code input form
- Attendance confirmation result
- Real-time attendance time

## Notes
- This application runs using Expo Go
- No external database is used
- Focus is on lifecycle implementation in React Native

## Author
- Gumelar Akhirul
