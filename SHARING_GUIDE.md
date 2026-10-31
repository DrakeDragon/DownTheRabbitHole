# Share the fall

## Player controls

After a run, the ending screen prepares a portrait PNG containing the game name, your hero, the realm, and your actual run results.

- Share My Run opens native sharing where supported. If image-file sharing is unavailable, the game offers text sharing or a copied invitation.
- Save Image downloads or opens the PNG so you can post it manually.
- Copy Invite copies the challenge text and public game URL. A selectable text dialog is provided if clipboard access fails.
- Play Link lets you supply a public URL when you are playing a downloaded file. When playing from your published site, the current public address is used automatically.
- Fall Again starts a new run. Tapping or scrolling elsewhere on the result page does not restart it.

If sharing is cancelled, the game retains the card and does not automatically download or copy anything as a side effect. Image preparation finishes before native image sharing is attempted.

## Public game address

A local file, localhost, or a preview address cannot invite someone to your copy of the game. Use your deployed GitHub Pages URL or custom domain instead. In the ending screen, choose Play Link and paste that address. The override is stored on that browser only; Use Current Site removes it.

The link validator accepts public HTTP/HTTPS addresses, strips query strings and fragments, and rejects common local addresses and credential-bearing URLs. It does not verify that a user-entered website exists or hosts this game, so check your public address before posting it.

## Website link-preview image

Upload the complete release, including:

- index.html
- assets/social-preview.png

The HTML includes Open Graph and social-card metadata pointing to the relative image path. For the most reliable preview behavior, after deployment change both image entries to the exact absolute public image URL:

```html
<meta property="og:image" content="https://YOUR-PUBLIC-SITE/assets/social-preview.png">
<meta name="twitter:image" content="https://YOUR-PUBLIC-SITE/assets/social-preview.png">
```

The domain/path above is an example, not a working game URL. For a repository Pages site, include its repository path before `/assets/`. You may also add an `og:url` entry for the exact public game page once it is known.

Preview caches belong to the receiving platform. A changed image or title may take time to appear. The static website preview advertises the game; it does not show individual run scores. Individual PNG cards are generated separately in the game.

## Share-image sizes

| Image | Dimensions | Purpose |
| --- | --- | --- |
| Run result PNG | 1080 × 1350 | Portrait result card with personal run statistics |
| Website preview | 1200 × 630 | General game branding for link previews |

The native share payload includes the branded caption and public play link with the image where supported. Some receiving apps ignore captions or support only text sharing. Save Image plus Copy Invite is the manual fallback.

## Privacy and limitations

Cards are rendered locally using embedded game art. No card-upload backend is added. The player explicitly chooses the share destination. Scores remain local and are not server-verified. A share dialog completing does not prove a post was published. Native sharing and clipboard permissions vary by device/browser; test on your intended devices before a public launch.

## Encore action bar

Share My Run and Fall Again now remain fixed at the bottom of the ending screen while the poster and rewards scroll. The existing share, save-image, copy-invite and public-link behavior is unchanged.
