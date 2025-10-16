# Kashirons Mobile App – BroBrain (SQA Testing Report)

## Project Overview
This repository documents the Software Quality Assurance (SQA) testing process for the **Kashirons Mobile App** – a Flutter-based mobile application prototype developed by BroBrain. As an SQA Engineer, I conducted UI flow testing aligned with the provided Figma designs. The focus was on validating the user interface (UI) without API integration, checking functional flows, and identifying bugs.

- **Testing Scope**: UI/UX validation, functional flow testing per Figma wireframes.
- **Tools Used**: Figma for design reference, Notion for bug tracking, Flutter app for testing.
- **Outcome**: Bugs reported via Notion SQA Bug Tracker, assigned to the Flutter developer team for resolution. This repo archives the bug reports, testing notes, and status updates.

### Figma Design Reference
The app's UI was tested against this Figma prototype:  
[![Figma Prototype](https://www.figma.com/design/LNjgJX3njbhdHtybu0WyY7/kashirons-%7C%7C-webgenious0-%7C%7C-FO62EF5392748?node-id=804-24216&amp;p=f&amp;t=F2XkGkAzKPltiZnw-0)](https://www.figma.com/design/LNjgJX3njbhdHtybu0WyY7/kashirons-%7C%7C-webgenious0-%7C%7C-FO62EF5392748?node-id=804-24216&amp;p=f&amp;t=F2XkGkAzKPltiZnw-0)

### Original Bug Tracker
Bugs were initially tracked in Notion: [SQA Bug Tracker](https://www.notion.so/28ca27313a3e80228f4eefda7d08a1b5?v=28ca27313a3e81c3b14b000c062e2920&amp;source=copy_link).

## Bug Reports
Below is a comprehensive table summarizing all identified bugs, including reproduction steps, results, and resolution status. Severity levels: Critical (app crash/blocker), High (major UX issue), Medium (functional gap), Low (minor visual). Priority: P1 (Immediate), P2 (High), P3 (Medium), P4 (Low).

| Bug ID | Features | Bug Title | Severity | Priority | Issue Labels | Description | Bug Type | Steps to Reproduce | Actual Result | Expected Result | Screenshot | Dev Status | Resolution Date | Date Reported |
|--------|----------|-----------|----------|----------|---------------|-------------|----------|--------------------|---------------|-----------------|------------|------------|------------------|---------------|
| [TBD-001] | [e.g., Login Screen] | [e.g., Button Misalignment on Login] | Medium | P2 | UI, Layout | [Brief description of the alignment issue causing overlap on smaller screens.] | Layout Bug | 1. Open app on iOS simulator (iPhone SE).<br>2. Navigate to Login screen.<br>3. Resize window to simulate small device. | Button overlaps text field. | Button aligns below text field with 8px margin per Figma. | [Attach screenshot URL or embed: ![Bug Screenshot](path/to/screenshot.png)] | Fixed | [e.g., 2025-10-15] | [e.g., 2025-10-10] |
| [TBD-002] | [e.g., Dashboard] | [e.g., Navigation Bar Overflow] | High | P1 | Navigation, Responsive | [Description of nav bar text overflowing on landscape mode.] | Responsive Bug | 1. Launch app on Android emulator.<br>2. Rotate to landscape.<br>3. Tap Dashboard tab. | Text clips outside bounds. | Text wraps or truncates with ellipsis per Figma responsive guidelines. | [Attach screenshot URL or embed: ![Bug Screenshot](path/to/screenshot.png)] | In Progress | - | [e.g., 2025-10-12] |

*Note: Replace `[TBD-XXX]` with actual Bug IDs from Notion. Embed actual screenshots by uploading them to the repo (e.g., `/screenshots/bug-001.png`) and updating the Markdown links. Add/remove rows as per your full Notion tracker.*

## Testing Methodology
1. **UI Flow Validation**: Compared app screens and interactions to Figma prototypes for layout, typography, colors, and animations.
2. **Functional Testing**: Simulated user journeys (e.g., login → dashboard → profile) on iOS/Android emulators/devices.
3. **Bug Reporting**: Logged issues in Notion with full details; assigned to Flutter devs.
4. **Regression Testing**: Verified fixes post-resolution.

## Key Metrics
- Total Bugs Reported: 5 (example; update with actual count).
- Resolved: 3/5.
- Average Resolution Time: 4 days.

## Next Steps
- Full API integration testing (post-UI fixes).
- Automated UI tests with tools like Appium.
- Performance benchmarking.

## Contributing
This repo is for documentation. If you're part of the BroBrain team, feel free to fork and add updates. Pull requests welcome for bug status updates!

## License
MIT License – Feel free to use for similar SQA projects.

---

*Repository created by [Your GitHub Username] – SQA Engineer @ BroBrain*  
*Last Updated: October 16, 2025*
