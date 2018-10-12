
# Notes on accessibility

Digital accessibility refers to the practice of building digital content and applications that can be used by a wide range of people, including individuals who have visual, motor, auditory, speech, or cognitive disabilities.

There is also a strong business case for accessibility: studies show that accessible websites have better search results, they reach a bigger audience, they’re SEO friendly, have faster download times, they encourage good coding practices, and they always have better usability.

> Designing a product from scratch
> that meets the requirements for accessibility
> shouldn’t add additional cost and effort.
> but fixing a site that is already inaccessible may require considerable effort.


Content/IA

Structured information

Use labels or instructions with form fields and inputs

Write useful alternative text for your images and other non-text content


Visual Designer

Add enough color contrast
See WCAG 1.4.3 Minimum Contrast (AA)

Don’t use color alone to make critical information understandable


Design usable focus states
See WCAG 2.4.7 Focus Visible (AA)

Use labels or instructions with form fields and inputs
See WCAG 4.1.2 Name, Role, Value (A)

Write useful alternative text for your images and other non-text content
See WCAG 1.1.1 Non-text Content (A)


Developers

Use correct markup on your content 

Support keyboard navigation


Business Analysts


Get an Accessibility Audit. Use an audit service to find out if your product works with assistive technologies and meets WCAG 2.0 level AA.
Use the audit results to fix problems and do another test.



# Useful tools

  - WebAIM Color Contrast Checker: 
https://webaim.org/resources/contrastchecker/

Great contrast color checker that gives you results in real time for regular and large text.

  - Inclusive Components: 

A pattern library in the form of a blog, with a focus on inclusive design. Each post explores a common interface component and comes up with a better, more robust and accessible version of it.






Color Oracle: A free color blindness simulator for Windows, Mac, and Linux. It shows you in real time what people with common color vision impairments see.

Vox Product Accessibility Guidelines: A comprehensive checklist for designers, engineers, and project managers.

AXE Google Chrome Extension: Test any site for accessibility violations using the Chrome inspector.

Contrast: A macOS app for quick access to WCAG color contrast ratios.


https://uxdesign.cc/designing-for-accessibility-is-not-that-hard-c04cc4779d94





Aligned to WCAG



When I teach accessibility classes internally, I have a top 10 list of WCAG requirements and they align nicely with your list of 7, but yours are in English and mine are in W3-speak. To match up my list with yours (using your numbers):

1.4.3 Minimum Contrast (AA)
(didn’t have on my list, although it was sort of grouped into #6)
2.4.7 Focus Visible (AA)
4.1.2 Name, Role, Value (A)
1.1.1 Non-text Content (A)
1.3.1 Info and Relationships (A)
2.1.1 Keyboard (A)
I also had:

2.4.4 Link Purpose (In Context) (A) (make your link text understandable on its own)
3.2.2 On Input (A) (don’t do weird things when an object’s value changes)
3.3.1 Error Identification (A) (make sure all errors are conveyed to screen readers)
1.4.4 Resize Text (Zooming) (AA) (make sure the page reflows nicely if the font size is bumped up)


