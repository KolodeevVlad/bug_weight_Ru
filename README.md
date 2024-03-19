# Impact Level

## Installation for Google Chrome:

1. Download the repository
2. Open [chrome://extensions/]
3. Enable developer mode
4. Click "Load unpacked extension"
5. Choose the folder with the application

## How does the error weight calculation work??
The weight (priority) is calculated using the formula: mass * critical * block, where:

#### Mass - How widespread the issue is.
- 1 Single bug
- 2 Affects a group of users
- 3 Affects most users
#### Block - How much the bug blocks user flow.
- 1 Not blocking
- 2 Blocking, but there is a workaround
- 3 Blocking
#### Critical - How critical the area of the application where the bug was found is.
- 1 not critical
- 3 critical

Maximum value - 27, minimum - 1
