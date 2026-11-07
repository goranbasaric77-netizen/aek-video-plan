# AEK Video Analysis Planner
Live: https://goranbasaric77-netizen.github.io/aek-video-plan/


Planiranje video analize po mikrociklusu: individualni video (igraci) i grupni video (linije tima).
Ista osnova kao AEK Set Plays (index.html + manifest + service worker), bez backenda.
Podaci se cuvaju u localStorage na telefonu/racunaru (kljucevi aek-video-v1 i aek-video-lists).

- Tap na celiju: planirano (P) -> uradjeno (✓) -> obrisano.
- Tap na ime igraca ili linije: promena imena ili uklanjanje (istorija ostaje).
- Tap na igraca u traci "Players" ili u History: istorija igraca.
- Pri prvom otvaranju svi igraci su bez videa. Ako je na istom uredjaju koriscen Set Plays, preuzima se samo spisak igraca i linija.

Ponovna objava: git add -A; git commit -m "Update"; git push (Pages se osvezi za 1-2 minuta).
Pri svakoj novoj verziji u sw.js promeni CACHE na danasnji datum.
