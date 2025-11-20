## Please NOTE I have manually tried to convert the android project into IOS. I have never done or code in swift before. I made a research and manual created these files using notePad++,Another issue is I dont have a MAC-BOOK/laptop to create such apps. But Im looking forward to buy one soon and create more projects in IOS.

## Thank you...Happy coding

## Features

## Functional Requirements

Email + password input

Input validation

Login button enabling/disabling

Authentication with simulated asynchronous delay

Error handling

Failure counter with lockout state after 3 invalid attempts

Offline detection (no login calls allowed)

Optional "Remember Me" toggle (token persisted)

iOSLoginApp/
 ├─ iOSLoginAppApp.swift
 ├─ Login/
 │   ├─ View/LoginView.swift
 │   ├─ ViewModel/LoginViewModel.swift
 │   ├─ Model/LoginState.swift
 │   ├─ Service/AuthService.swift
 │   ├─ Service/NetworkMonitor.swift
 │
 ├─ Tests/
 │   ├─ LoginViewModelTests.swift
 │   ├─ LoginViewUITests.swift
 
 ## Test Scenarios (Android & iOS)
 
### Unit Tests

Scenario	Expected
Validation	Button disabled when inputs are invalid
Success	ViewModel triggers navigation
Failures	Counter increments after bad login
Lockout	After 3 failures, login disabled
Offline	Login prevented, offline message shown
Remember Me	Token stored on success when enabled

### Technology Stack

iOS

Swift

SwiftUI

MVVM

Combine

XCTest
