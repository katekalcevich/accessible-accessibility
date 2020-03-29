# Digital accessibility testing tools

Tools to help you test for accessibility barriers. When you create digital content in an accessible way, more people can use your documents, website or app.

Accessibility is a team sport—everyone has a part to play. A robust web accessibility testing process could involve:

- writers checking if content is written in plain language
- designers checking if text colours have enough contrast and fonts are easy-to-read;  and including tab/reading order in their design specifications
- developers checking that interactive elements can be used with a screen reader and speech input
- devops checking for accessibility errors as part of continuous integration
- QA doing a final check using WAVE, tabbing through all elements with a keyboard and confirming that pages work when zoomed 200%

There&#39;s more testing you can do than what I&#39;ve listed above, but this is a great starting point and you can build on it once you&#39;ve mastered the basics of accessibility.

Here are my favourite accessibility testing tools, grouped by type.

## Automated WCAG compliance testing

### Automation / Integration

Add these tools to your environment to test for accessibility barriers during development. They check the Web Content Accessibility Guidelines and highlight compliance errors.

- [Pa11y: command-line accessibility testing interface](https://pa11y.org/)
- [Automated Accessibility Testing Tool (AATT)](https://github.com/paypal/AATT)
- [Tenon: API-first, automated accessibility testing tool](https://tenon.io/)
- [Integrating Tenon](https://tenon.io/getcode.php)

### Browser extensions

Use these free tools to test web pages for accessibility barriers. They check the Web Content Accessibility Guidelines and highlight compliance errors.

- [Axe (Chrome and Firefox)](https://www.deque.com/axe/axe-for-web/)
The Axe extension highlights errors on screen, explains what caused the error and how to fix it. Axe is great for toggling between the element on screen and the source code.
- [Easy Accessibility Testing with aXe (3.5 minute video)](https://youtu.be/FW1giWW5M9I)
- [WAVE (Chrome and Firefox)](https://wave.webaim.org/extension/)
The WAVE extension highlights errors on screen, explains what caused the error and how to fix it. WAVE allows you to turn the page styles off and to help narrow down exactly where an error is.
- [WAVE Help](https://wave.webaim.org/help)
- [tota11y: an accessibility visualization toolkit (all browsers)](https://khan.github.io/tota11y/)
The tota11y extension allows you to check one group of errors at a time (headings, contrast, links, etc.). It highlights errors on screen, displays the relevant code and has tips for fixing the errors.
- [taba11y (Chrome)](https://chrome.google.com/webstore/detail/taba11y/aocppmckdocdjkphmofnklcjhdidgmga?hl=en)
The taba11y extension tabs through all focusable elements on a page and numbers them, so you can check tab order without tabbing through everything yourself.

### Documents

- [Use the accessibility checker to find accessibility issues (web page)](https://support.office.com/en-us/article/Use-the-Accessibility-Checker-to-find-accessibility-issues-a16f6de0-2f39-4a2b-8bd8-5ad801426c7f) OR
[Use the Office accessibility checker (1 min video)](https://support.office.com/en-us/article/make-your-content-accessible-to-everyone-with-the-accessibility-checker-38059c2d-45ef-4830-9797-618f0e96f3ab)
- [Create and verify PDF accessibility (web page)](https://helpx.adobe.com/ca/acrobat/using/create-verify-pdf-accessibility.html)

### Mobile apps

- [Testing for Accessibility on OS X](https://developer.apple.com/library/archive/documentation/Accessibility/Conceptual/AccessibilityMacOSX/OSXAXTestingApps.html)
- [Accessibility scanner (Android)](https://play.google.com/store/apps/details?id=com.google.android.apps.accessibility.auditor&amp;hl=en_CA)

## Manual testing tools

### Low vision

- [WCAG Color contrast checker (Chrome)](https://chrome.google.com/webstore/detail/wcag-color-contrast-check/plnahcmalebffmaghcpcmpaciebdhgdf?hl=en)
All the browser extensions check colour contrast. The WCAG color contrast checker _only_ checks colour contrast, nothing else. It will tell you if colours meet AA or AAA requirements for regular or large text. The colour picker tool lets you select colours on screen and test them.
- Check your font size—is it at least 16px?
- Zoom in 200%—does everything reflow so you can read without scrolling?

### Paid webinars and courses

- [Web Accessibility Testing, Part 1: Screen Readers ($45 USD, 1 hour webinar)](https://dequeuniversity.com/curriculum/courses/screenreaders)
- [Web Accessibility Testing, Part 2: Basic Methods and Tools ($45 USD, 1 hour webinar)](https://dequeuniversity.com/curriculum/courses/testingmethods)
- [Testing Websites and Documents with Screen Reading Technologies ($435 CAD, 1 day online or in person course): MacOS](http://eliquo.ca/en/training/course.php?crs=EWAW211) OR [Windows](http://eliquo.ca/en/training/course.php?crs=EWAW210)
- [Testing Websites and Documents with Screen Reading Technologies on Mobile for iOS and Android ($435 CAD, 1 day online or in person course)](http://eliquo.ca/en/training/course.php?crs=EWAW213)

### Screen readers

- [Using JAWS (with Internet Explorer on Wind](https://webaim.org/articles/jaws/)[ws)](https://webaim.org/articles/jaws/)[to Evaluate Web Accessibility](https://webaim.org/articles/jaws/)
JAWS is free to use in 40 minute demo mode. You&#39;ll need to restart your computer every 40 minutes to continue using it.
- [Using NVDA (with Firefox on Windows) to Evaluate Web Accessibility](https://webaim.org/articles/nvda/)
NVDA is free to use, but they accept donations to support the continued improvement of the tool.
- [Using VoiceOver (with Safari on](https://webaim.org/articles/voiceover/)[Mac)](https://webaim.org/articles/voiceover/)[to Evaluate Web Accessibility](https://webaim.org/articles/voiceover/)
VoiceOver comes with the MacOS. You can turn it on in Settings > Accessibility.

### Speech input

These videos help you to understand how Dragon Naturally Speaking works. It&#39;s the most popular tool for using a computer with your voice. If you don&#39;t want to buy Dragon, you can use [Windows Speech Recognition](https://www.windowscentral.com/how-set-speech-recognition-windows-10) or [Mac Dictation](https://support.apple.com/en-ca/HT210539) instead.

- [Browsing the web (2 minute video)](https://www.youtube.com/watch?v=ncACrtT_3ig)
- [Following links in web pages (3 minute video)](https://www.youtube.com/watch?v=f9fK-Fk6GrI)
- [Emulating the mouse (3 minute video)](https://youtu.be/iOSObinq7a4)
- [Internet forms (3 minute video)](https://www.youtube.com/watch?v=bmObC7ktNmc)

### Writing

- [Headings Map (Chrome)](https://chrome.google.com/webstore/detail/headingsmap/flbjommegcjonpdmenkdiocclhjacmbi?hl=en)
The Headings Map extension shows all headings on a page and their level.
- [Hemingway](http://www.hemingwayapp.com/)
The Hemingway web app checks the reading level of your writing and makes suggestions on how to simplify the text.
