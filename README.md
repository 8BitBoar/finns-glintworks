# Finn's Glintworks

Business tool for Finley "Finn" Anderson — harvesting, drying and selling Glint from a lighthouse on Krakoa — in one HTML page.

The page is public (GitHub Pages). Everything that's yours — strains, cards, clients and the save — lives in a **private** repo, `finns-glintworks-data`, the same split as Finn's Facets & Finds.

## Setup

1. **Create two repos** on GitHub under `8BitBoar`:
   - `finns-glintworks` — **public**. Upload `index.html` and this README.
   - `finns-glintworks-data` — **private**. Upload `strains.json`, `cards.json`, `factions.json`, the `card-icons/` folder and its README. (`save.json` is created by the page on first connect.)
2. **Turn on Pages** for `finns-glintworks`: Settings → Pages → Deploy from a branch → `main` / root. The page will be at `https://8bitboar.github.io/finns-glintworks/`.
3. **Make a fine-grained token** limited to `finns-glintworks-data` with **Contents: Read and write**. (You can't reuse the Finn's Facets token unless you add this repo to it.)
4. Open the page → **Settings** → owner `8BitBoar`, repo `finns-glintworks-data`, branch `main`, paste the token → **Save & connect**.

The two tools keep separate saves, so both can be open in the same browser.

## Daily loop

1. **Sea** — tap a node, sail out (pay its fuel), harvest plants by hand (15 min each). Wet buds go into the harvest tanks (100). Color tags tilt which strains turn up; each plant has a small chance to be a mono strain you haven't found, and Planar Seam nodes guarantee one. Weather, the 7-day forecast, Hull and sinking work as in the docs.
2. **Return home** — loads the drying racks (2 × 50 buds). Common buds dry in 1 day, up to 5 for Mythic Rare. What doesn't fit waits in the tanks.
3. **Glintworks** — dried buds land in the Humidor (200 buds, freshness locked; buy more Humidors at Hallmark's for 150 Cr each). If it's full they wait loose: full freshness for 3 days, then −5% a day.
4. **Tide Pool** — at sea, tap **Keep it whole** after harvesting a plant and it settles in the tide pool (10 plants) when you dock. Cross two wild or Established plants (30 min): a known recipe adds 20% toward Established; a pair with no recipe gives a Colorless dead end. Once Established, a strain sells, spreads into the wild, and its crosses give plants you can harvest. Crosses are how mutations are discovered.
5. **Orders** — jars (small 5 / jar 15 / extra large 40 buds), cartridges (3 buds + a shell + an optional flavor drop), pens (fill the included cartridge, then assemble body, mouthpiece, band and a mana core) and refills. Pack, send. Restock at **Hallmark's** (arrives in 2–4 days); a new pen-part design costs 50 Cr to tool once.
6. **End Day** — racks dry, pens wear out and refill requests roll, parcels arrive, factions roll for orders, nodes refresh. The 1st is bills day: salary, dues, boat upkeep and Emma's 20%. Both permits renew on the opening-day anniversary.

## Perk Cards

- 10% of every sale (after the faction's cut) becomes Perk Points. Packs cost 25 PP, then +5 for each one bought. Each Level also gives a free pack; a new game starts with a 3-card starter pack.
- Cards live in `cards.json` in the data repo, icons in its `card-icons/` folder.

## Coming next

- **Round 3:** chests and Collectables, the Curio Room, the Survey and the Salon, and the rest of the card list.

## Credits

The footer links to a full **Credits & licenses** page: strains reinterpret *Magic: The Gathering* cards (unofficial fan content); Whale Shark icon by T. Kiefer Robertson from the Noun Project (CC BY 3.0); card-icon credits from `cards.json`.
