# Vinewood Touge Race Track for QBCore

Short preview lap: https://streamable.com/ux2eyc

Installation:
1. Open your phone, go to the racing app, then create race. Type in 'Vinewoood Touge' as the track name.
2. Add at least two random placeholder checkpoints (these will be replaced in the database later).
3. Save the race and exit your game.
4. Open HeidiSQL > your QBCore database > lapraces table > data tab.
5. Replace the 'checkpoints' & 'distance' data in the 'Vinewoood Touge' row to the one you've downloaded.
6. You don't need to mess with 'id', 'records', 'creator', and 'raceid'.
7. Start your server, open up the racing app, then start 'Vinewoood Touge'.
8. It's a sprint race so you'll just need to set the laps to 0.

All the credit for the track goes to GTAWiseGuy who created the routes and turns. I only recreated it for QBCore, through video footage from Twitch streams.

![FiveM_b2060_GTAProcess_FAfR8RsJ5Y (Custom)](https://user-images.githubusercontent.com/11475502/126076693-1ec25f67-b812-4263-bbef-448a587a1fb6.jpg)
