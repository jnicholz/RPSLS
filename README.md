# RPSLS

Library's allowed
socket.io (both)
axios (both)
lodash (both)
helmet (server)
morgan (server)
mongoose (server)
cors (server) (use it selectively, judiciously, so that the client remains safe)
vuetify or another vue component library
fontawesome
nodemailer

# Positive requirements:
## CLIENT:
### GUI requirements
Must work for
- [ ] Tablet
- [ ] Widescreen
- [ ] Phone
Preferences:
- [ ] All on by default
- [ ] Preferences are saved and persist once selected
- [ ] Dark mode option
- [ ] Flashing Lights
- [ ] Music option
- [ ] Tutorial
Views
- [ ] Players listed in world lobby
- [ ] Players Display Win loss ratio in lobby

### Player requirements
- [ ] Must register on first connection
- [ ] Player has Win loss ratio
- [ ] After first win, Intoduced to guild
registration has
- [ ] Email
  - [ ] True user name
  - [ ] Private
  - [ ] Email sent to complete registration
- [ ] Display name (gamer tag) 
  - [ ] seen by all
- [ ] Password 
  - [ ] Check password is strong

### Guild Requirements
- [ ] Accesible after first win
Guilds at first access 
- [ ] an option to create a new guild
- [ ] join an existing guild that's accepting members 
- [ ] continue playing solo. 
Specs to view
- [ ] Guild names always display the win/loss ratio of the players, e.g UVU Warr10r$ 394/185. 
Properties
- [ ] Player can leave a guild anytime. 
- [ ] Player can join a guild anytime after the first win, even if the player previously chose to continue playing solo.    

## Server:
### Lookup
- [ ] Table Lookup for logic
### Server build
- [ ] Vue3
  - [ ] Vue routing (client routing)
  - [ ] Pinia (state management)
  - [ ] Vite (build)
  - [ ] Nuxt3
- [ ] Tailwind (try to do it entirely in Tailwind; RARE and MINIMAL overrides with CSS are allowed)
- [ ] Node/Express
- [ ] Netlify hosted

### Game Requirements
- [ ] 3rd user can join a game in progress as comentator
Gameplay - 
- [ ] Game is best of 7
- [ ] if Player disconnects, disconnected is counted as a loss
- [ ] if Player Disconnects, remaining has no change in stats
Player Actions
- [ ] Can choose Rock, Paper, Scisors, Lizard, or Spok
- [ ] Can send emoticons
- [ ] Can Send Text message
- [ ] Speech recording

### Performance
- [ ] Must be able to handle 1000 simultanious games
### Testing  
- [ ] Must Test 1000 Simultanious games
- [ ] HTML and CMD bot to do testing
- [ ] Bot should be able to play on other person's server 
- [ ] 50 bot commentators required as well


## Turn in
- [ ] Deliver a zip file
- [ ] Zip File must NOT HAVE NODE_MODULES 



# Negative requirements
## Server:
### Lookup
- [ ] No branching statements for winner logic
### Players
- [ ] Do not allow weak passwords



[Edit on StackBlitz ⚡️](https://stackblitz.com/edit/node-gk5ebl)
