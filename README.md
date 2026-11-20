# Zarek's card: card.zarekjohnson.com

## What's in this folder
* index.html: the card page
* zarek.jpg, og.jpg, favicon.png, qr.png: images (og.jpg is the preview that shows when the link is texted)
* zarek.vcf: the contact file the "Save my contact" button downloads
* CNAME: tells GitHub Pages to answer on card.zarekjohnson.com

## Put it live (one time, about 15 minutes)
1. On github.com, create a new public repository named `card`.
2. Click "uploading an existing file" and drag in every file from this folder. Commit.
3. In the repo, open Settings, then Pages. Under "Build and deployment" pick "Deploy from a branch", branch `main`, folder `/ (root)`. Save.
4. Still in Pages, put `card.zarekjohnson.com` in Custom domain and save.
5. Where you bought zarekjohnson.com, add a DNS record:
   * Type: CNAME
   * Host / Name: card
   * Value / Points to: YOURGITHUBUSERNAME.github.io
6. When GitHub shows the domain as verified, tick "Enforce HTTPS". The certificate can take a little while to show up.

Using a different address? Change it in three places: the CNAME file, the two og: lines at the top of index.html, and the "My card" line in zarek.vcf.

## The personal link
Add the person's first name, and what they told you they want:

card.zarekjohnson.com/?n=Kahn&w=Waterfront+lots+in+Treasure+Island

* n = first name. The page opens with "Kahn, good talking with you."
* w = what they want, with + between words. The page shows "Keeping an eye out for you: ..."
* Leave both off for a general link (Facebook bio, email signature, cards at events).
