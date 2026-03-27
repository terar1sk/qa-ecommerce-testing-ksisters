## Title
Header - Long user name (100 characters) breaks layout and overlaps navigation elements

## Description
The system allows a user name with up to 100 characters.
However, when such a name is displayed in the header, the layout breaks and overlaps other elements.
The user name is not properly truncated or constrained, which causes UI elements (icons and navigation) to shift overlap.
This results in poor visual appearance and may affect usability.

## Steps to Reproduce
1. Open https://ksisters.sk/
2. Register or log in with a user name containing 100 characters
3. Navigate to the main page
4. Observe the header area

## Expected Result
The user name should be displayed correctly without breaking the layout.
Long text should be truncated, limited, or handled responsively.

## Actual Result
* User name with 100 characters is displayed in full without truncation
* The text overflows the header area
* Header layout breaks
* Navigation elements and icons are shifted or overlapped

## Environment
* URL: https://ksisters.sk/
* OS: Windows 11
* Browser: Google Chrome (latest version)
* Device: Desktop

## Attachments
### Header layout with long user name (100 characters)
![Header layout break](../assets/screenshots/header-long-username-layout-break.png)

### Video reproduction
[Watch video](../assets/recordings/header-long-username-layout-break.mp4)

## Severity / Priority
Severity: Medium
Priority: Medium