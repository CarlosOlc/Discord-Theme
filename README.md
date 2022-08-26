/**
 * @name Uchiha Itachi - Red Theme
 * @author Cyber
 * @version 1.0.0
 * @description Uchiha Itachi - Red Theme. A theme modification from Frosted Glass.
 * @authorId 266696001945862155
*/

@import url("https://discordstyles.github.io/FrostedGlass/dist/FrostedGlass.css");

/* BlackBox tags */
@import url('https://monstrousdev.github.io/themes/addons/user-tags.css');

/* Old Windows titlebar - remove this @import if you wish to use default titlebar */
@import url("https://gibbu.github.io/BetterDiscord-Themes/addons/windows-titlebar.css");

:root {
  /* Background image variables */
  --background-image: url('https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/1c820940-c463-479e-b413-d4ff929ece41/d73x7r3-8c8310f8-06c8-4dc0-8d60-5adda06c9abc.jpg/v1/fill/w_1024,h_576,q_75,strp/itachi_uchiha_wallpaper_by_sixpathsrinnegan_d73x7r3-fullview.jpg?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7ImhlaWdodCI6Ijw9NTc2IiwicGF0aCI6IlwvZlwvMWM4MjA5NDAtYzQ2My00NzllLWI0MTMtZDRmZjkyOWVjZTQxXC9kNzN4N3IzLThjODMxMGY4LTA2YzgtNGRjMC04ZDYwLTVhZGRhMDZjOWFiYy5qcGciLCJ3aWR0aCI6Ijw9MTAyNCJ9XV0sImF1ZCI6WyJ1cm46c2VydmljZTppbWFnZS5vcGVyYXRpb25zIl19.ft2da6Jw1MLPmjqO6ipWivV8N8ZcP6lzR-cJCycVhM0'); /* Main background image | URL MUST BE A DIRECT LINK (ending in .jpg, .jpeg, .png, .gif) */
  --background-image-blur: 5px; /* Blur intensity of --background-image | Must end in px | DEFAULT: 5px */
  --background-image-size: cover; /* Size of the background image | DEFAUT: cover | OPTIONS: cover, contain */
  --background-image-position: center; /* Position of background image | DEAFULT: center | OPTIONS: top, right, bottom, left, center */

  /* Popout & Modal variables */
  --popout-modal-image: var(--background-image); /* Background image for popouts and modals | URL MUST BE A DIRECT LINK (ending in .jpg, .jpeg, .png, .gif) */
  --popout-modal-blur: 5px; /* Blur intensity of --popout-modal-image | Must end in px | DEFAULT: 5px */
  --popout-modal-size: cover; /* Size of the popout/modal image | DEFAUT: cover | OPTIONS: cover, contain */
  --popout-modal-position: center; /* Position of popout/modal image | DEAFULT: center | OPTIONS: top, right, bottom, left, center */

  /* Home image variables */
  --home-button-image: url('https://steamuserimages-a.akamaihd.net/ugc/930436490146099487/B1D02E2DB315A8A7F676E55D74F97EFCC0D50742/?imw=512&&ima=fit&impolicy=Letterbox&imcolor=%23000000&letterbox=false'); /* Home button image | URL MUST BE A DIRECT LINK (ending in .jpg, .jpeg, .png, .gif) */
  --home-button-size: cover; /* Size of the home button image | DEFAUT: cover */
  --home-button-position: center; /* Position of home button image | DEAFULT: center */

  /* Brightness variables */
  --serverlist-brightness: 0.8; /* Brightness for serverlist | 0 - 1 (decimals allowed) | DEFAULT: 0.8 */
  --left-brightness: 0.7; /* Channels and DM list brightness | 0 - 1 (decimals allowed) | DEFAULT: 0.8 */
  --middle-brightness: 0.5; /* Chat brightness | 0 - 1 (decimals allowed) | DEFAULT: 0.6 */
  --right-brightness: 0.6; /* Members and Now Playing brightness | 0 - 1 (decimals allowed) | DEFAULT: 0 */
  --popout-modal-brightness: 0.75; /* Brightness for popouts and modals | 0 - 1 (decimals allowed) | DEFAULT: 0.75 */

  /* Gradient variables */
  --gradient-primary: 255,0,0; /* DEFAULT: 103,58,183 */
  --gradient-secondary: 100,0,20; /* DEFAULT: 63,81,181 */
  --gradient-direction: 320deg; /* DEFAULT: 320deg */

  /* Tint variables */
  --tint-colour: 255,51,159; /* Colour of tint | DEAFULT: 255,51,159 */
  --tint-brightness: 0; /* Brightness of --tint-colour | 0 - 1 (decimals allowed) | DEFAULT: 0 */

  /* Other variables */
  --window-padding: 20px; /* Spacing around the Discord window | DEFAULT: 20px */
  --window-roundness: 10px; /* Roundness of Discord | DEFAULT: 10px */
  --scrollbar-colour: rgba(50, 199, 167, 0.05); /* DEFAULT: rgba(255,255,255,0.05) */
  --link-colour: #00aeff; /* DEFAULT: #00b0f4 */
  --show-gift-gif-buttons: none; /* Show buttons: block | Hide buttons: none | DEFAULT: none */
  --white: rgba(228, 15, 15, 0.425);
  /*
    Visit https://fonts.google.com and select one to your liking.
    Now just follow this tutorial: https://imgur.com/a/CNbw7xC
  */
  --font: 'Whitney';

  /* Do not touch */
  --update-notice-1: none;
}
