# Ever Present Living Style Guide Pattern Library

Putting your Living Style Guide in the browser makes it easily available to the whole team. A Living Style Guide saves time, facilitates communication, and documents the visual language for both designers and developers.

## Sample JS Pattern

```javascript
function displayMsg( sMsg ){
    //    System Tray Notification
    console.log( sMsg );
    if (!("Notification" in window)) {
        console.log('Notification API not supported.');
        return;
    } else if (Notification.permission === "granted") {
        // If it's okay let's create a notification
        audioSuccessSound();
                var notification = new Notification( Nowish(), {icon: "http://neodigm.github.io/ever-present-living-style-guide-site/img/ever-present-living-style-guide.png", body: sMsg} );
    } else if (Notification.permission !== "denied") {
        // Otherwise, we need to ask the user for permission

        Notification.requestPermission(function (permission) {
            // If the user accepts, let's create a notification
            if (permission === "granted") {
                var notification = new Notification( Nowish(), {icon: "http://neodigm.github.io/ever-present-living-style-guide-site/img/ever-present-living-style-guide.png", body: sMsg} );
            }
        });
    }
}
```

## Sample UX asset

[https://github.com/neodigm/ever-present-living-style-guide-ltdc/blob/master/img/usability-heuristics.jpg?raw=true](https://thescottkrause.com/categories/ux/)

#
[Portfolio Blog](https://www.theScottKrause.com) |
[🦄 Résumé](https://thescottkrause.com/Arcanus_Scott_C_Krause_2020.pdf) |
[NPM](https://www.npmjs.com/~neodigm) |
[Github](https://github.com/neodigm) |
[LinkedIn](https://www.linkedin.com/in/neodigm24/) |
[Gists](https://gist.github.com/neodigm?direction=asc&sort=created) |
[Salesforce](https://trailblazer.me/id/skrause) |
[Code Pen](https://codepen.io/neodigm24) |
[Machvive](https://machvive.com/) |
[Arcanus 55](https://www.arcanus55.com/) |
[Repl](https://repl.it/@neodigm) |
[Twitter](https://twitter.com/neodigm24) |
[Keybase](https://keybase.io/neodigm) |
[Docker](https://hub.docker.com/u/neodigm) |
[W3C](https://www.w3.org/users/123844)
#

<p align="center">
  <a target="_blank" href="https://thescottkrause.com/d3_datavis_skills.html">
  <img src="https://repository-images.githubusercontent.com/178555357/2b6ad880-7aa0-11ea-8dde-63e70187e3e9" title="D3js Skills with Audio">
  </a>
</p>
