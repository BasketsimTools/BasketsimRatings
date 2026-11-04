**Basketsim Ratings**

This Chrome Manifest extension displays `SUM`, `PG`, `SG`, `SF`, `PF` and `C` on `basketsim.net/players`, `basketsim.net/players/<ID>`, and Basketsim transfer-market results at `basketsim.net/market`.

**Installation in Chrome**
Download and extract the ZIP file.
Open `chrome://extensions`.
Enable Developer mode in the top-right corner.
Click Load unpacked.
Select the extracted basketsim-ratings folder.
Open or refresh `https://basketsim.net/players` or any player profile.

**Formulas**
The extension uses only the whole-number skills displayed in the HTML. `SUM` adds Handling, Quickness, Passing, Dribbling, Rebounds, Positioning, Shooting, Freethrows and Defense. WR/Work rate and XP/Experience are not used.

PG = Handling + Quickness + Passing + Defense
SG = Dribbling + Quickness + Defense + Shooting
SF = Shooting + Positioning + Defense + Passing
PF = Passing + Rebounds + Positioning + Defense
C = Quickness + Defense + Rebounds + Positioning

The extension works entirely locally, without a backend or additional permissions. It does not send data or modify Basketsim data.
