# Browser Extension Security Report - Elevate Labs Task 7

## Task Overview
- **Objective**: Review and secure browser extensions for Day 7 of the Elevate Labs Cybersecurity Internship (July 4, 2025).
- **Tool Used**: Firefox Add-ons Manager on Ubuntu.
- **Goal**: Identify and remove suspicious/unused extensions, assess risks, and document findings.

## Extension Review Process

1. **Opened Add-ons Manager**:
   - Launched Firefox
   - Navigated to `Extensions and themes`.
   - Screenshot: `Screenshots/Installed-exts.png`

2. **Reviewed Installed Extensions**:
   - **Chessvision.ai**: Chess engine, permissions for accessing data for all websites, 5-star reviews on addons.mozilla.org. (24 reviews)
   - **CleanULRs**: Remove tracking elements from URLs, permissions for Access of data for all websites, Download files and read and modigy the browser's download history, access browser tabs and activity during navigation, 4.5 star reviews by 373 users.
   - **Facebook Container**: Broad permissions (all site data), 1063 reviews, rarely used.
   - **Privacy Badger**: Privacy Protection, Minimal permissions, 5 star reviews by 542 users.

3. **Checked Permissions and Reviews**:
   - Used Firefox’s **Details** tab and [addons.mozilla.org](https://addons.mozilla.org).
   - **Findings**:
     - CleanURLs and Privacy Badger: Reputable, necessary permissions.
     - Facebook Container: Don't use at all and broad permissions.

4. **Identified Suspicious/Unused Extensions**:
   - **Suspicious**: No suspicious extension
   - **Unused**: Facebook Container (rarely used).

5. **Removed Extensions**:
   - Removed via **Add-ons and Themes**:
     - Facebook Container
   - Screenshot: `Screenshots/removed_extensions.png`

6. **Restarted Browser**:
   - Tested performance: Browsed `example.com`, faster load times, no pop ups.

7. **Risks of Malicious Extensions**:
   - **Data Theft**: Steal cookies, passwords, or history.
   - **Malware**: Inject scripts or download payloads.
   - **Ad Injection**: Insert ads or redirect searches.
   - **Privacy**: Track activity without consent.
   - **Source**: [OWASP](https://owasp.org), [Mozilla Security Blog](https://blog.mozilla.org/security).

## Summary
- **Actions Taken**: Removed one extensions (Facebook Container) due to less usage of that extension and broad permissions.
- **Outcome**: Improved browser performance, reduced security risks.
- **Best Practices**:
  - Install extensions only from trusted sources (e.g., addons.mozilla.org).
  - Review permissions regularly.
  - Disable unused extensions.
  - Monitor browser behavior for anomalies.

## Learnings
- **Browser Security**: Extensions can be attack vectors if not vetted.
- **Risk Mitigation**: Regular reviews and minimal extensions enhance safety.
- **Next Steps**: Explore extension sandboxing and privacy-focused browsers.

## Files Included
- `Screenshots/Installed-exts.png`: Initial add-ons list.
- `Screenshots/removedextensions_.png`: extension removal.
- `browser_extension_report.md`: This report.
- `README.md`: Task overview.

## Portfolio
This task is part of my Elevate Labs internship portfolio: [Elevate-Labs-Internship-Tasks](https://github.com/Nucl3arAt0m/Elevate-Labs-Internship-Tasks).
