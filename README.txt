WESTBOUND - upload the contents of this folder to your web root.

index.html          The hub (map, clocks, climate, country list, paperwork,
                    flight planner). Self-contained: the planner and vaccine
                    panels are embedded, so it works on its own.
flights.html        Stand-alone flight planner (same as the embedded one)
vaccines.html       Stand-alone vaccine checklist (same as the embedded one)
countries/          One page per country, japan.html, korea.html, ... portugal.html.
                    Each country card on index.html links here, and each
                    country page links back to index.html.
countries/_deferred/taiwan.html       Taiwan (off the route for now)
countries/_duplicates/bhutan-alt.html  Second Bhutan draft, not linked

Note: planner ticks and vaccine checkboxes are saved in each browser,
so they won't sync between your phone and laptop.
