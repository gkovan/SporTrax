# Heart Rate Zones (5-Zone Model)

## Overview
The 5 heart rate zones are typically **dynamic**, especially on modern devices like the Apple Watch. They are calculated based on your personal data and can update over time.

---

## Heart Rate Zones

![Heart Rate Zones Chart](https://upload.wikimedia.org/wikipedia/commons/3/3a/Heart_rate_zones.png)

- **Zone 1:** 50–60% (Very light)
- **Zone 2:** 60–70% (Fat burn / base)
- **Zone 3:** 70–80% (Aerobic)
- **Zone 4:** 80–90% (Threshold)
- **Zone 5:** 90–100% (Max effort)

---

## Are Zones Static or Dynamic?

**Dynamic (default):**
- Automatically calculated using your personal data
- Adjust as your age or fitness changes
- Based on estimated or measured max heart rate

**Static (optional):**
- Users can manually define fixed ranges

---

## How Zones Are Determined

### 1. Max Heart Rate (HRmax)

Common formula:
- HRmax ≈ 220 − age

Alternative:
- HRmax ≈ 208 − (0.7 × age)

---

### 2. Zone Boundaries

Each zone is a percentage of HRmax.

**Example (Age 54 → HRmax ≈ 166 bpm):**
- Zone 1: 83–100 bpm
- Zone 2: 100–116 bpm
- Zone 3: 116–133 bpm
- Zone 4: 133–150 bpm
- Zone 5: 150–166 bpm

---

### 3. Heart Rate Reserve (Advanced)

More accurate method using:
- Resting HR and Max HR

Formula (Karvonen Method):
Target HR = ((HRmax − Resting HR) × %Intensity) + Resting HR

---

## Practical Insight

For apps like a tennis tracker:
- Wrist-based HR can spike during play
- Consider allowing:
  - Custom HRmax input
  - Auto-adjustment based on observed peak HR

---

## Notes

- Apple Watch calculates zones automatically but allows manual overrides
- Zones are tied to Apple ID and personal health data
