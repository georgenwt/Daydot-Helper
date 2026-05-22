This is an offline-capable, standalone web application built using HTML, CSS, and Vanilla JavaScript. It is designed to be deployed as a Progressive Web App (PWA) on a dedicated store device (like an old smartphone or a Raspberry Pi touchscreen).

1. Premium "Liquid Glass" UI (Glassmorphism)

Matte Glitter Background: A deep Costa burgundy radial gradient layered with a high-definition SVG noise filter (color-dodge). It features a scroll-reactive interactive light that refracts through the grain as the user scrolls.

Frosted Glass Panels: All UI elements sit on translucent glass cards utilizing backdrop-filter: blur(20px) saturate(140%) with subtle 1px inner edge highlights for a realistic 3D glass edge.

Fluid Spring Animations: Every interaction (tapping, scrolling, expanding) utilizes bouncy cubic-bezier animations. Product cards load via a staggered, scroll-triggered cascade (using IntersectionObserver).

2. Smart Search Engine

Fuzzy Typo Matching: Uses a Levenshtein Distance algorithm to instantly calculate typos and misspellings (e.g., finding "Caramel" when you type "carmell").

Shortcode & Time Queries: Users can search purely by number or shortcode (e.g., typing 12, 12w, or 12 weeks immediately pulls up all 12-week items; 24 pulls up 24-hour items).

Dynamic Dropdown: A floating glass overlay populates instantly with top matches and mini Daydot stickers.

Sticky & Responsive: The search bar shrinks and becomes more translucent as the user scrolls down the page, maximizing screen space while remaining accessible.

3. Matte Vinyl Daydot Stickers

Perfect Square Ratio: The date calculations generate 1:1 aspect ratio stickers that visually mimic physical matte vinyl labels.

Industry Color Coding: Automatically assigns the correct solid color based on the target day of the week (e.g., Blue = Mon, Yellow = Tue, Red = Wed).

High-Readability Formats: Calculates strict mathematical DD/MM date formats and auto-converts exact times into a 12-hour AM/PM format.

4. Optimized Layout

Mobile-First Symmetry: The grid mathematically aligns to the screen size.

8-Item Quick Reference: A 2x4 grid at the top of the page featuring oversized Daydot stickers for the most common intervals (24h, 48h, 3 days, 5 days, 4 weeks, 6 weeks, 8 weeks, 12 weeks, 3 months).

The Product Database & Shelf Life Library

Below is the complete, hard-coded library of products, their calculated shelf lives, and the hidden search keywords attached to them.

Powders

HOT CHOCOLATE POWDER: 4 Weeks (28 days)

FRAPPÉ POWDER: 12 Weeks (84 days)

MATCHA POWDER: 3 Months

HYFOAMER POWDER: 8 Weeks (56 days)

Syrups & Sauces

CARAMEL: 12 Weeks (84 days)

VANILLA: 12 Weeks (84 days)

HAZELNUT: 12 Weeks (84 days)

CINNAMON BUN: 12 Weeks (84 days)

SF CARAMEL: 12 Weeks (84 days)

SF VANILLA: 12 Weeks (84 days)

SF GINGERBREAD: 12 Weeks (84 days)

SPICED CHAI: 3 Months

MONIN SUGAR FREE: 3 Months

CANE SUGAR SYRUP: 3 Months

WHITE CHOCOLATE SAUCE: 12 Weeks (84 days)

SALTED CARAMEL SAUCE: 12 Weeks (84 days)

STRAWBERRY SAUCE: 12 Weeks (84 days)

MANGO SAUCE: 12 Weeks (84 days)

CHOCOLATE CARAMEL SAUCE: 12 Weeks (84 days)

MONIN WHITE PEACH SYRUP: 3 Months

MONIN JASMINE SYRUP: 3 Months

CHERRY VANILLA SAUCE: 8 Weeks (56 days)

UBE FLAVOUR SYRUP: 6 Weeks (42 days)

HAZELNUT CRÈME FLAVOUR SAUCE: 8 Weeks (56 days)

AGAVE FLAVOURED SYRUP: 60 Days

Coffee, Teas & Toppings

OPEN MOCHA ITALIA COFFEE BAGS: 48 Hours (2 days) (Includes Time)

COSTA INSTANT COFFEE: 4 Weeks (28 days)

CAPPUCCINO DUSTING: 4 Weeks (28 days)

MANGO BUBBLES: 4 Weeks (28 days)

FRUIT COOLER BASES: 5 Days (4 days)

MARSHMALLOWS: Varies (Special Text: "SEE BAG FOR BEST BEFORE")

TEA & INFUSIONS: 3 Months (Consolidated group covering English Breakfast, Earl Grey, Mint, Berry, Green, Spiced Apple, Mellow Mango, Citrus Zing)

CINNAMON STICKS: 6 Months

LEMON SLICES: 4 Weeks (28 days)

ORANGE SLICES: 4 Weeks (28 days)

FREEZE DRIED STRAWBERRY PIECES: 21 Days

FREEZE DRIED DRAGON FRUIT PIECES: 21 Days

FREEZE DRIED LIME PIECES: 6 Months

Chilled Prep & Liquids

CHILLED WATER IN JUG: 24 Hours (1 day) (Includes Time)

PREPARED MATCHA IN SQUEEZY BOTTLE: 48 Hours (2 days) (Includes Time)

ALL REFRESHER CONCENTRATES: 10 Days

Dairy Alternatives & Cream

DAIRY ALTERNATIVES / LIGHT WHIP (OPEN CARTON): 5 Days (4 days)

PREPARED LIGHT WHIP / WHIPPED CREAM IN CANISTERS: 24 Hours (1 day) (Includes Time)

WHIPPING CREAM (OPEN CARTON / BOTTLE): 3 Days (2 days)
