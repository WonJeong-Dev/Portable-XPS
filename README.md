# Portable XPS Analyzer

Browser-based analysis of X-ray photoelectron spectroscopy (XPS) data — reading,
background subtraction, peak fitting with uncertainties, quantification, survey
identification, charge correction, and more. No installation, no account, no server.

**▶ Live app: https://wonjeong-dev.github.io/Portable-XPS/**

## Features

- **Read** VGD, VAMAS (.vms/.npl), Avantage (.xls/.xlsx/.avg), and text/CSV spectra
- **Backgrounds** — Linear, Shirley, Smart (Avantage-style), Tougaard, spline, active
- **Peak fitting** with multiple line shapes, doublets, constraints, and multi-start search
- **Uncertainties** via covariance and Monte Carlo
- **Quantification** (at%) with Scofield / ALTHERMO1 sensitivity factors and transmission correction
- **Charge correction** (C 1s / Au 4f), **survey element identification**, **Auger parameter**
- **Series / ARXPS / Imaging / Processing** workspaces
- Light and dark themes; works on desktop and phone

## Privacy

Everything runs **locally in your browser**. Spectra you open are read on your own
computer and are **never uploaded** anywhere. Work in progress is kept in the browser;
use **Save work** to export a project file.

## Usage

- Open the live link above, **or**
- Download `index.html` from this repository and open it in any modern browser.

Then **Open files** (or drag and drop) a measurement's spectra — including C 1s — and
use **Auto suggest → Fit**, then the Quantification and Results tabs.

## License

**All rights reserved.** See [LICENSE](LICENSE). The code is public for use and
evaluation; copying, modifying, or redistributing it requires written permission.

## Author

© 2026 **WonJeong Yu**, KAIST.
