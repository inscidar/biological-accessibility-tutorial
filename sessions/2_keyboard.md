---
layout: page
title: "Hands-on session 2: Testing the keyboard accessibility of biomedical data resources (Give tasks to groups)"
permalink: /keyboard/
---

# Testing the keyboard accessibility of biomedical data resources (An introduction)

---
Why might researchers care?
## Keyboard-accessible websites are easier to navigate, query, cite, teach from, and trust.
Research benefits when everyone can use the same resources.

---

Guideline 2.1 Keyboard Accessible

“Make all functionality available from a keyboard.”

- Keyboard accessibility is a fundamental accessibility requirement.

---

##### Keyboard accessibility:
# *Essential* for some. *Useful* for all.

---

### Keyboard operability
***"Can I do this without a mouse?"***

* All interactive elements must be reachable by keyboard (e.g., filters, dropdowns, buttons, links).
* Focus order should follow the visual and logical structure of the page.

    * Essential for users with motor impairments or who cannot use a mouse
    * Useful for anyone in no-mouse situations (e.g., demonstrations, screen reader navigation, custom setups)

---

##### Disambiguation:
## Keyboard operability vs screen reader support
* **Keyboard operability** means all interactive elements are reachable and usable with keystroke inputs (Tab, Shift+Tab, Enter, Space, Arrow keys, key-code shortcuts) via a keyboard interface.
* **Screen reader support** adds ARIA roles and semantic HTML for meaningful auditory output.

> You can have one without the other—but both are needed for full accessibility.
> This session focuses on keyboard operability.

---

To improve keyboard accessibility:
* **Reduce mobility and dexterity barriers** through full keyboard operability.
* **Reduce perceptual and cognitive barriers** through predictable tab order, focus indicators, logical DOM structure, and simple key combinations.
* **Reduce technical barriers** by ensuring interactive components such as menus, buttons, and filters respond to Tab and Arrow keys.

Accessible tools work not only for people with disabilities, but also for power users, screen reader users, and those navigating via keyboard in teaching, demos, or remote access settings.

---

## Keystroke input technologies include:
- Standard keyboard
- On-screen keyboard
- Braille keyboard
- Switch access device
- Voice navigation system
- Eye-tracking software (with keyboard emulation)
- Headless browser
- Remapped input device (e.g., game controller)
- Custom hardware

---

### Logical DOM order
***"Is the navigation flow predictable?"***

* The tab order should follow the visual order (top to bottom, left to right).
* Avoid skipping key elements or getting trapped inside components.

* Essential for screen reader users and anyone relying on keyboard shortcuts
* Useful for maintaining flow and reducing disorientation for all users

---

### Keyboard operabiity
***"Can I do this without a mouse?"***
- All interactive elements must be reachable by keyboard (e.g., filters, dropdowns, buttons, links) and have visible focus indicators.
- Essential for users with motor impairments or who cannot use a mouse
- Useful for anyone in no-mouse situations (e.g., demonstrations, screen reader navigation, custom setups)

---

## Example

- Attempting to create a data visualization on [Voyager 2](https://voyager-keyboard-demo.github.io)
- Finding kidney datasets for donors over the age of 65 on [HuBMAP](https://portal.hubmapconsortium.org)



---

## Basic “first pass” keyboard accessibility testing checklist:
- Tab through every control and menu.
- Check that the focus order matches the reading/viewing
order.
- Use keyboard only to complete key workflows.
- Ensure that visibly-hidden elements do not receive focus.
- Use [WebAIM: keyboard accessibility tutorial](https://webaim.org/techniques/keyboard/) as resource while
keyboard testing.

---

### Success Criterion 2.1.1 Keyboard (Level A)

“All functionality of the content is operable through a keyboard interface without requiring specific timings for individual keystrokes, except where the underlying function requires input that depends on the path of the user's movement and not just the endpoints.”

-- Web Content Accessibility Guidelines (WCAG) 2.1

---

### Success Criterion 2.1.2 No Keyboard Trap (Level A)

“If keyboard focus can be moved to a component of the page using a keyboard interface, then focus can be moved away from that component using only a keyboard interface, and, if it requires more than unmodified arrow or tab keys or other standard exit methods, the user is advised of the method for moving focus away.”

-- Web Content Accessibility Guidelines (WCAG) 2.1

---

### Success Criterion 2.1.4 Character Key Shortcuts (Level A)

If a keyboard shortcut is implemented in content using only letter (including upper- and lower-case letters), punctuation, number, or symbol characters, then at least one of the following is true:

- Can turn off
- Can remap
- Active only on focus

-- Web Content Accessibility Guidelines (WCAG) 2.1

---

# Hands-on testing activity (Breakout rooms)

- On [HuBMAP](https://portal.hubmapconsortium.org/) (https://portal.hubmapconsortium.org/), find kidney datasets for donors over the age of 65.
    - First, find the datasets how you normally would.
    - Then, use keyboard input only. No mouse.
- Use WebAIM: keyboard testing table as resource for common keyboard interactions.

