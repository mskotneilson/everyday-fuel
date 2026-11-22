# Everyday Fuel

A lightweight, mobile-friendly nutrition and Speediance workout tracker.

## What it does

- Quick protein and meal check-ins, including unpredictable work lunches
- Fridge/freezer backup-meal inventory for work
- Reusable grocery list for Walmart or Sam's Club shopping
- Easy family dinner planning
- Upper/lower four-day workout tracking
- Offline access after the first successful load

## Use it on your phone

Once GitHub Pages has been enabled for this repository (Settings > Pages > Deploy from a branch, `main`, `/ (root)`), open:

https://mskotneilson.github.io/everyday-fuel/

In Chrome on Android, use the three-dot menu > **Add to Home screen** or **Install app**.

## Data storage and privacy

This is a static web app. It has **no login, database, server-side records or automatic multi-device sync**. Meals, inventory, workouts and settings are stored in your browser's local storage on the device and website origin where you use it. Other visitors don't see your records.

Use **Settings > Download backup** periodically. Clearing site data, switching browsers/devices, or changing the site address can otherwise lose the tracking data. Restore a backup using **Settings > Restore backup**.

Meal protein estimates are editable. The default 140 g protein goal is a placeholder and should be individualized after measurements. Shopping links open retailers but don't place orders.

## Technical notes

The static site includes `index.html`, `manifest.webmanifest`, `sw.js`, and 192px/512px install icons. No build step or external dependencies required.
