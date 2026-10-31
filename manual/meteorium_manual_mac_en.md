# Meteorium for Mac — User Manual (Free Edition)

Meteorium is an astronomy app that renders the "dust trails" behind meteor
showers — the ribbons of comet dust left along a comet's orbit — in 3D, from
real orbital computation. This app ships the **60,000 dust grains of
eight trails (1079, 1209, 1344, 1478, 1609, 1736, 1862 and 1992)** released by
109P/Swift-Tuttle, the parent comet of the Perseids.

The Mac edition shows exactly the same computation and the same features as the
iPhone / iPad edition, in a macOS window. **This manual covers only what is
specific to the Mac.** For the features themselves, see the
[common manual](index.html).

- Requires **macOS 15.6 or later** (universal app: Apple silicon and Intel)
- All computation on your device, with no data collection and no ads (it goes online only to fetch the published datasets)
- Same App as the iPhone / iPad edition, so it runs on all your devices under
  the same Apple ID at no extra cost

---

## 1. The window and its layout

![Layout](img/fig_mac_overview.jpg)

Meteorium opens as an ordinary macOS window. Drag any edge to resize it — the
3D view follows the window.

| Where | What |
|---|---|
| Centre | 3D view (drag to rotate, wheel / trackpad to zoom) |
| Top right | EN/JP (language), ⓘ (show / hide the panel) |
| Right panel | Dataset, dust-trail legend, display options, viewpoints, particles |
| Bottom bar | Date and time (UT), date entry, Today, viewpoint, time controls |

**Difference from the iPhone:** when the window opens at least 900 pixels wide,
the right panel starts out open (on iPhone you open it with the ⓘ button). Both
the panel and the bottom bar can be dragged around the window by their grip, and
the grip at the bottom of the panel adjusts its length.

- The green button (or `control` + `⌘` + `F`) goes full screen. The larger the
  display, the easier it is to read the three-dimensional structure of the trails
- Narrowing the window below 640 pixels switches to the tall iPhone layout
- The **▼** button at the top right of the bottom bar folds the bar away
  (**▲** brings it back)

## 2. Mouse and trackpad

| Gesture | Action |
|---|---|
| Drag | Rotate the view |
| Scroll wheel | Zoom in / out |
| Two-finger swipe (trackpad) | Zoom in / out |
| Pinch (trackpad) | Zoom in / out |
| Drag a grip | Move the panel or the bottom bar |

In the ground view (section 5) dragging looks around the sky and scrolling
changes the field of view — narrow for a telephoto look, wide for a
wide-angle one.

## 3. Keyboard

Everything can be done with the mouse alone, but these keys are available on the
Mac:

| Key | Action |
|---|---|
| `←` / `→` | Scroll the **dust-trail cross-section** left / right (only while the forecast window is open) |
| `⌘` + `W` | Close the window |
| `⌘` + `Q` | Quit Meteorium |
| `control` + `⌘` + `F` | Toggle full screen |

Click the date field to type a date directly, in `YYYY-MM-DD` form.

## 4. The meteor shower forecast

![Forecast](img/fig_mac_forecast.jpg)

This app ships the **2026 forecast for the Perseids**. Press "Forecast"
in the right panel and a window opens with the ZHR profile on top and the
dust-trail cross-section below.

- Upper chart: the NASA MEM model (the annual background) and this model's
  result, with each dust trail's contribution in its own colour
- Lower chart: where the Earth cuts through the trails, with the grains
  scattered around the encounter point and their 1σ / 2σ error ellipses
- The "Ecliptic plane X–Y" button opens the geometry in a separate window,
  which you can zoom and drag

The Mac's larger display makes the tick labels and annotations easy to read, and
`←` / `→` pans the cross-section while you inspect the detail.

The bundled forecasts are the 2026 Perseids and the Leonids for 2030-2035, the
latter computed as in the manuscript submitted to Icarus, each year from a
dataset matched to that encounter's epoch. See the common manual for the
citation.

## 5. The meteor show in the ground view

![Ground view](img/fig_mac_ground.jpg)

Choosing the "Ground" viewpoint puts you on the ground, looking towards the
radiant. On dates inside the activity period (Perseids: Jul 17 – Aug 24) meteors
stream out of the radiant, rendered at the equivalent of ZHR = 5,000.

On a large display it is much harder to miss the rarer events — fireballs,
persistent trains and meteor clusters. Go full screen, let time run, and it
doubles as a screen saver.

## 6. Differences from the iPhone / iPad edition

| | iPhone / iPad | Mac |
|---|---|---|
| Rotate | One-finger drag | Mouse drag |
| Zoom | Pinch | Wheel / two-finger swipe / pinch |
| Panel at launch | Folded (ⓘ opens it) | Open when at least 900 px wide |
| Display size | Fixed by the device | Resizable window, full screen |
| Screen rotation | Re-lays out for portrait / landscape | None (follows the window size) |
| Keyboard | Date entry only | Date entry + cross-section scrolling |

The bundled data, the computation and everything shown are identical on every
platform.

## 7. If something goes wrong

- **Sluggish rendering** — lower "Particles shown" in the right panel to 25% or
  10%. Making the window smaller, or leaving full screen, also helps
- **The view stays black** — resize the window once. If that does not help, quit
  with `⌘` + `Q` and start the app again
- **An update does not seem to take effect** — after updating from the App
  Store, quit the app completely (`⌘` + `Q`) and launch it again

---
© Meteorium, Avellsky
