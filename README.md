# StoryArc Aerial

Lead generation site for StoryArc Aerial, a cinematic and FPV aerial videography business in Omaha, Nebraska.

## Status

Staging build on GitHub Pages. Search indexing is off on purpose (meta robots noindex plus a blocking robots.txt) until launch on storyarcaerial.com.

## Positioning

For businesses, events, and other film and videography companies. Differentiation: anyone can buy a drone off the shelf and record pictures and video; almost none understand videography, storytelling, and fitting aerial work into an overall production process. StoryArc Aerial is the cinematic and FPV specialist that does.

## Files

- index.html — homepage (hero, services, difference, filmmaker highlight, process, safety band, selected work placeholders, quote form)
- services.html — detailed services with per service calls to action
- filmmakers.html — production partner page: creative team integration, deliverables, FAQ, production consult call to action
- safety.html — safety and rules page: airspace, venue rules, people, weather, privacy, the right to say no (process based; no credential or insurance claims)
- quote.html — dedicated quote page; the form preselects project type from a ?type= link parameter (business, event, flythrough, production)
- hero-showreel.jpg, work-venue.jpg, work-brand.jpg, work-event.jpg — generated placeholder images (2026-11-10), standing in until real footage stills are ready
- robots.txt — blocks crawlers during staging; replace with an allowing version at launch

## Quote form

Submits through FormSubmit to the owner's inbox; the address is assembled in JavaScript at submit time so it never appears in the page source or anywhere on the public site. The endpoint activates on the first submission via a confirmation email.

## Launch checklist

- Buy storyarcaerial.com and point DNS at GitHub Pages
- Remove the noindex meta tag and replace robots.txt
- Swap the generated placeholder images for the real showreel and stills
- Add final contact details and service area notes
