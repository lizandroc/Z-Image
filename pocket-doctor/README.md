# Pocket Doctor

A single-file, offline health companion: interactive human anatomy, a searchable
guide to time-tested natural remedies, and a private patient portal with
expandable vital charts, a full-body evaluation, and check-in reminders.

Open `index.html` in any browser — phone or desktop. No build step, no server,
no account. Everything is saved on the device in `localStorage`; nothing is sent
anywhere. On first load a demo profile ("Alex") is seeded so the charts and
dashboard aren't empty.

## What's inside

- **Patient portal & dashboard** — multiple on-device profiles (e.g. family
  members), a wellness-score hero, "due now" reminders, and vital tiles with
  trend sparklines and healthy/watch/elevated/urgent status.
- **Expandable vital charts** — blood pressure, resting heart rate, blood oxygen,
  temperature, weight, and fasting glucose. Each card expands to an SVG line chart
  with a crosshair tooltip, a shaded healthy range, 7/30/90-day/all range filters,
  a table view, and one-tap logging.
- **Interactive body map** — a clickable illustrated figure. Tap a region (brain,
  heart, lungs, gut, liver, kidneys, joints, immune/skin) for what it is, what it
  does, common concerns, everyday care, matched natural remedies, and clear
  "when to see a doctor" red-flags.
- **Natural remedy guide** — ~29 remedies across Western herbal, Ayurveda,
  Traditional Chinese Medicine, and home/food traditions. Each is honestly labeled
  (well-studied / supportive evidence / traditional use) with how it's taken, why
  it may help, and safety cautions. Searchable and filterable.
- **Full-body evaluation & report** — a 12-question self-check that produces a
  0–100 wellness score, a system-by-system breakdown, tailored natural
  recommendations, and a printable report.
- **Check-in reminders** — a full-body cadence (BP, weigh-in, heart rate,
  evaluation, hydration, movement, annual physical) with due badges; logging a
  vital auto-completes its reminder.

## Design notes

- Responsive and mobile-first, with a bottom tab bar and safe-area insets.
- Light and dark themes, following the viewer's system preference.
- Chart colors and contrast follow an accessible, colorblind-safe palette;
  identity is carried by legends, labels, and a table view — never color alone.

## Important

Pocket Doctor is general wellness **education**, not a medical device. It does not
diagnose or treat, and it does not replace a licensed clinician. Natural remedies
can interact with medications and conditions. For anything urgent or persistent,
contact a healthcare professional.
