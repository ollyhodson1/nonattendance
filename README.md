# Luke Pale Wellbeing Escalation Simulation

This is a GitHub-ready static app for the first Luke Pale activity, where students respond to non-attendance from a wellbeing perspective.

## How to publish on GitHub Pages

1. Unzip this file.
2. Upload the whole folder contents to a GitHub repository.
3. Go to `Settings` → `Pages`.
4. Under `Build and deployment`, choose `Deploy from a branch`.
5. Select:
   - Branch: `main`
   - Folder: `/docs`
6. Save.

GitHub will give you the link after it deploys.

## Files

- `docs/index.html` — the page GitHub Pages opens
- `docs/styles.css` — styling
- `docs/data.js` — inbox emails, contacts, timeline items and staff placeholders
- `docs/helpers.js` — validation, time and email helper functions
- `docs/app.js` — app behaviour

## Simulation flow

1. Initial pop-up explains that Luke Pale has not arrived on placement.
2. Students complete a horizontal escalation-order task:
   - Check whether Luke has contacted anyone
   - Try to contact Luke directly
   - Escalate to relevant practice/university people
3. Students check three staff members on shift.
4. Time advances by five minutes.
5. Students attempt to contact Luke directly.
6. Time advances by five minutes.
7. Students learn there is no phone number in the sPRD.
8. Students return to Mail and click New Mail.
9. Students send a wellbeing-focused escalation email.
10. Time advances by two hours.
11. Two unread emails appear:
    - PEF acknowledgement from Chris Doogan
    - Final reply from Becca Richardson with Blackboard code **6621**

## Contacts used

- Daniel Vaughan-Davies <daniel.vaughan-davies@salford.example>
- Chris Doogan <chris.doogan@salford.example>
- Becca Richardson <becca.richardson@salford.example>
- Luke Pale <luke.pale@salford.example> appears in Becca’s reply.

## v2 bug fixes

- Staff speech bubbles now appear above the placeholder images, in italic speech marks.
- The next step no longer appears immediately after clicking Samira; a Next button appears only after all three staff responses have been opened.
- Becca Richardson’s email now appears above Chris Doogan’s email because it is the most recent message.
