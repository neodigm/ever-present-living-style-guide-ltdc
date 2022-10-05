# Ever Present Living Style Guide Pattern Library

Putting your Living Style Guide in the browser makes it easily available to the whole team. A Living Style Guide saves time, facilitates communication, and documents the [visual language](https://www.theScottKrause.com/tags/curated/) for both designers and developers.

[UX Usability Heuristics | HE](https://www.thescottkrause.com/categories/ux/)

## Sample JavaScript Pattern

```javascript
function displayMsg( sMsg ){  //  www.TheScottKrause.com
    //    System Tray Notification
    console.log( sMsg );
    if (!("Notification" in window)) {
        console.log('Notification API not supported.');
        return;
    } else if (Notification.permission === "granted") {
        // If it's okay let's create a notification
        audioSuccessSound();
                let notification = new Notification( Nowish(), {icon: "http://neodigm.github.io/ever-present-living-style-guide-site/img/ever-present-living-style-guide.png", body: sMsg} );
    } else if (Notification.permission !== "denied") {
        // Otherwise, we need to ask the user for permission

        Notification.requestPermission(function (permission) {
            // If the user accepts, let's create a notification
            if (permission === "granted") {
                let notification = new Notification( Nowish(), {icon: "http://neodigm.github.io/ever-present-living-style-guide-site/img/ever-present-living-style-guide.png", body: sMsg} );
            }
        });
    }
}
```

## [UX Heuristics | HE ](https://thescottkrause.com/emerging_tech/ux-usability-heuristics/)

<p align="center">
  <a target="_blank" href="https://www.thescottkrause.com/categories/ux/">
  <img src="https://thescottkrause.com/emerging_tech/ux-usability-heuristics_tn.webp" title="DataVis 🚀 Micro Frontend 🚀 PWA">
  </a>
</p>

#
[Portfolio Blog](https://www.theScottKrause.com) |
[🦄 Résumé](https://thescottkrause.com/Arcanus_Scott_C_Krause_2022.pdf) |
[NPM](https://www.npmjs.com/~neodigm) |
[Github](https://github.com/neodigm) |
[LinkedIn](https://www.linkedin.com/in/neodigm55/) |
[Gists](https://gist.github.com/neodigm?direction=asc&sort=created) |
[Salesforce](https://trailblazer.me/id/skrause) |
[Code Pen](https://codepen.io/neodigm24) |
[Machvive](https://machvive.com/) |
[Arcanus 55](https://www.arcanus55.com/) |
[Repl](https://repl.it/@neodigm) |
[Twitter](https://twitter.com/neodigm24) |
[Keybase](https://keybase.io/neodigm) |
[Docker](https://hub.docker.com/u/neodigm) |
[W3C](https://www.w3.org/users/123844) |
[InfoSec](https://arcanus55.medium.com/offline-vs-cloud-password-managers-51b1fbebe301)
#

<p align="center">
  <a target="_blank" href="https://thescottkrause.com/d3_datavis_skills.html">
  <img src="https://repository-images.githubusercontent.com/178555357/2b6ad880-7aa0-11ea-8dde-63e70187e3e9" title="D3js Skills with Audio">
  </a>
</p>

<p align="center">
  <a target="_blank" href="https://www.thescottkrause.com">
    <img src="https://neodigm.github.io/pan-fried-monkey-fisticuffs/thescottkrause_contact_card.png" title="TypeScript ⚡ WASM ✨ NestJS">
  </a>
</p>
