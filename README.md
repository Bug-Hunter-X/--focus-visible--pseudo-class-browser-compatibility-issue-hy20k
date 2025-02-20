# :focus-visible Pseudo-class Browser Compatibility

This repository demonstrates a common CSS issue related to the `:focus-visible` pseudo-class and provides a solution for better cross-browser compatibility.

The `:focus-visible` pseudo-class is intended to improve the user experience by only showing focus styles when the user is actually focusing on an element using a keyboard or assistive technology. However, older browsers do not support this feature.

**The bug:**  In older browsers, focus styles are displayed whether or not the user is using keyboard navigation or assistive technology, potentially creating a cluttered visual interface.

**The solution:**  The solution uses JavaScript to detect if an element is programmatically focused (e.g., by JavaScript) or by the user, applying focus styles accordingly.