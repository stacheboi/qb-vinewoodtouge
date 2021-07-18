# Vinewood Touge Race Track for QBCore

Short preview lap: https://streamable.com/ux2eyc

Map overview: https://i.imgur.com/2oE7Per.jpg

Installation:
1. Open your phone, go to the racing app, then create race. Type in 'Vinewoood Touge' as the track name.
2. Add at least two random placeholder checkpoints (these will be replaced in the database later).
3. Save the race and exit your game.
4. Open HeidiSQL > your QBCore database > lapraces table > data tab.
5. Replace the 'checkpoints' & 'distance' data in the 'Vinewoood Touge' row to the one you've downloaded.
6. You don't need to mess with 'id', 'records', 'creator', and 'raceid'.
7. Start your server, open up the racing app, then start 'Vinewoood Touge'.

All the credit for the track goes to GTAWiseGuy who created the routes and turns. I only recreated it for QBCore, through video footage from Twitch streams.
