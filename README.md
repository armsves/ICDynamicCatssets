ost NFT's point to off-chain assets using a static route and needed to be changed in case of need, with this project the assets will be generated dynamically on the server with the logic required.

I used the ic-pluto crate to create a static GET route and changed it to render an SVG according to logic, right now just the last number of the timestamp to show the concept of the project.

The main idea is to have a map with the NFT list that you can point to, then you can edit the logic "switch" and also include http_outcalls for it with a no-code solution so you don't have to edit any code to change your assets logic.

Image you want your NFT to have clouds when it's cloudy in a particular city, or have rain, you can do it with an http_outcall to a weather forecast API and then with that logic just change the image of the NFT with the SSR.
