# SAVE MARLEY · No New Dog

## Adding photos
Put your photos in the `photos` folder with these names (JPG):

| File | Where it shows up |
|---|---|
| marley-1.jpg | Big hero photo at the top |
| marley-2.jpg | "Meet the Candidate" portrait |
| marley-3.jpg – marley-5.jpg | The three photos inside the letter to Missy |
| marley-6.jpg | Campaign trail: on a walk |
| marley-7.jpg | Campaign trail: playing fetch |
| marley-8.jpg | Campaign trail: resting |
| dad.jpg | Marius headshot (Science of Marley animation) |
| mom.jpg | Shirley headshot (Science of Marley animation) |
| dino.jpg / nino.jpg | The opposing candidates in "Meet the Opposition" (already included) |
| marley-face.jpg | Marley headshot, the "result" of the animation |

Headshots are cropped into circles, so square-ish photos with the face centered work best.

Any missing photo shows a striped placeholder, so you can add them a few at a time.
Captions are in `index.html`, so search for `<figcaption>` to change them.
Landscape-ish photos look best. Large phone photos work, but shrinking them to about 1600px wide makes the page load faster.

## Putting it on Cloudflare Pages (free)
1. Log in at dash.cloudflare.com and go to **Workers & Pages**, then **Create**, then **Pages**, then **Upload assets**.
2. Name the project, for example `savemarley`. That gives you a `.pages.dev` link right away.
3. Drag in this whole folder (index.html plus the photos folder) and click **Deploy**.
4. To update it later, open the project, click **Create new deployment**, and upload the folder again.

## Hooking up savemarley.org
1. In the Pages project, open **Custom domains** and click **Set up a custom domain**.
2. Enter `savemarley.org` and follow the prompts. If the domain is registered with Cloudflare (or its DNS is moved to Cloudflare), this is a few clicks. Otherwise Cloudflare shows a DNS record to add at your registrar.
3. Optional: add `www.savemarley.org` the same way.
