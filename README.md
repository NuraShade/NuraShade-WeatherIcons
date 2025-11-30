# 🌤️ NuraShade Weather Icons

<div align="center">

![License](https://img.shields.io/badge/License-CC%20BY--ND%204.0-blue.svg)
![Format](https://img.shields.io/badge/Format-SVG%20%7C%20PNG-green.svg)
![Icons](https://img.shields.io/badge/Icons-15-orange.svg)

**A beautiful, modern collection of weather icons for your projects**

[Features](#-features) • [Icon Preview](#-icon-preview) • [Usage](#-usage) • [License](#-license)

</div>

---

## ✨ Features

- 🎨 **15 Unique Weather Icons** - Comprehensive coverage of common weather states plus fallback
- 📐 **Dual Format Support** - Available in both SVG (vector) and PNG (raster) formats
- 🌓 **Day & Night Variants** - Separate icons for daytime and nighttime conditions
- 🎯 **Optimized & Clean** - Lightweight SVG files with gradient fills for visual depth
- 💼 **Production Ready** - Perfect for weather apps, dashboards, widgets, and websites

---

## 🌈 Icon Preview

### ☀️ Clear Conditions
| Icon | Day | Night |
|------|-----|-------|
| **Clear** | `ClearDay.svg` | `ClearNight.svg` |
| **Mainly Clear** | `MainlyClearDay.svg` | `MainlyClearNight.svg` |
| **Partly Cloudy** | `PartlyCloudyDay.svg` | `PartlyCloudyNight.svg` |

### ☁️ Cloudy & Foggy
| Icon | File |
|------|------|
| **Overcast** | `Overcast.svg` |
| **Foggy (Day)** | `FoggyDay.svg` |
| **Foggy (Night)** | `FoggyNight.svg` |

### 🌧️ Precipitation
| Icon | File |
|------|------|
| **Drizzle** | `Drizzle.svg` |
| **Rain** | `Rain.svg` |
| **Freezing Rain** | `FreezingRain.svg` |
| **Snow** | `Snow.svg` |
| **Thunderstorm** | `ThunderStorm.svg` |

### ❓ Fallback
| Icon | File |
|------|------|
| **Not Available** | `NA.svg` |

---

## 📦 What's Included

```
NuraShade-WeatherIcons/
├── svg/                    # Vector format icons
│   ├── ClearDay.svg
│   ├── ClearNight.svg
│   ├── Drizzle.svg
│   ├── FoggyDay.svg
│   ├── FoggyNight.svg
│   ├── FreezingRain.svg
│   ├── MainlyClearDay.svg
│   ├── MainlyClearNight.svg
│   ├── NA.svg
│   ├── Overcast.svg
│   ├── PartlyCloudyDay.svg
│   ├── PartlyCloudyNight.svg
│   ├── Rain.svg
│   ├── Snow.svg
│   └── ThunderStorm.svg
│
├── png/                    # Raster format icons
│   ├── ClearDay.png
│   ├── ClearNight.png
│   ├── Drizzle.png
│   ├── FoggyDay.png
│   ├── FoggyNight.png
│   ├── FreezingRain.png
│   ├── MainlyClearDay.png
│   ├── MainlyClearNight.png
│   ├── NA.png
│   ├── Overcast.png
│   ├── PartlyCloudyDay.png
│   ├── PartlyCloudyNight.png
│   ├── Rain.png
│   ├── Snow.png
│   └── ThunderStorm.png
│
└── LICENSE.md
```

---

## 🚀 Usage

### HTML
```html
<!-- Using SVG -->
<img src="path/to/svg/ClearDay.svg" alt="Clear Day" width="64" height="64">

<!-- Using PNG -->
<img src="path/to/png/Rain.png" alt="Rain" width="64" height="64">
```

### CSS
```css
.weather-icon {
  width: 64px;
  height: 64px;
  background-image: url('path/to/svg/PartlyCloudyDay.svg');
  background-size: contain;
  background-repeat: no-repeat;
}
```

### JavaScript/React
```jsx
import ClearDayIcon from './svg/ClearDay.svg';

function WeatherWidget() {
  return <img src={ClearDayIcon} alt="Clear Day" />;
}
```

### Rainmeter
```ini
[WeatherIcon]
Meter=Image
ImageName=#@#icons/png/ClearDay.png
W=64
H=64
```

---

## 🎨 Design Details

- **Color Palette**: Vibrant gradients with carefully selected color stops
- **Stroke Width**: Consistent stroke weights for visual harmony
- **ViewBox**: Standard 64×64 viewBox for easy scaling
- **Gradients**: Linear gradients for depth and modern aesthetics
- **File Size**: Optimized SVG files (average ~1-2KB per icon)

---

## 📋 Icon Mapping Guide

Use this table to map weather codes to icons:

| Weather Condition | WMO Code* | Icon File |
|-------------------|-----------|-----------|
| Clear sky (day) | 0 | `ClearDay.svg` |
| Clear sky (night) | 0 | `ClearNight.svg` |
| Mainly clear (day) | 1 | `MainlyClearDay.svg` |
| Mainly clear (night) | 1 | `MainlyClearNight.svg` |
| Partly cloudy (day) | 2 | `PartlyCloudyDay.svg` |
| Partly cloudy (night) | 2 | `PartlyCloudyNight.svg` |
| Overcast | 3 | `Overcast.svg` |
| Fog (day) | 45, 48 | `FoggyDay.svg` |
| Fog (night) | 45, 48 | `FoggyNight.svg` |
| Drizzle | 51, 53, 55 | `Drizzle.svg` |
| Rain | 61, 63, 65, 80, 81, 82 | `Rain.svg` |
| Freezing rain | 56, 57, 66, 67 | `FreezingRain.svg` |
| Snow | 71, 73, 75, 77, 85, 86 | `Snow.svg` |
| Thunderstorm | 95, 96, 99 | `ThunderStorm.svg` |
| Data unavailable | N/A | `NA.svg` |

*WMO Weather interpretation codes (as used by Open-Meteo and similar APIs)

---

## 📄 License

This project is licensed under **CC BY-ND 4.0** (Creative Commons Attribution–NoDerivatives 4.0 International).

### ✅ You are free to:
- **Share** — Copy and redistribute the icons in any medium or format for any purpose, even commercially

### 📌 Under the following terms:
- **Attribution** — You must give appropriate credit to NuraShade, provide a link to the license, and indicate if changes were made
- **NoDerivatives** — You may not distribute modified versions of these icons

### ⚠️ Additional Restrictions:
- You may not sell, re-license, or redistribute these icons as your own or as part of another collection without written permission from NuraShade

### Attribution Example:
```
Icons by NuraShade — Used under CC BY-ND 4.0
https://github.com/NSTechBytes/NuraShade-WeatherIcons
```

Full license text: https://creativecommons.org/licenses/by-nd/4.0/

---

## 🤝 Contributing

While modifications cannot be redistributed due to the NoDerivatives clause, we welcome:
- 🐛 Bug reports
- 💡 Feature suggestions
- 📖 Documentation improvements
- ⭐ Stars and feedback!

---

## 🌟 Acknowledgments

Created with ❤️ by **NuraShade**

Copyright © 2025 NuraShade. All rights reserved.

---

<div align="center">

**If you find these icons useful, please consider giving this repository a ⭐!**

</div>
