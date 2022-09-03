# Axus
New design Music bot for Discord 
module.exports = {
    app: {
        token: 'XXX',
        playing: 'by Aaron ❤️',
        global: true,
        guild: 'xxx'
    },

    opt: {
        DJ: {
            enabled: false,
            roleName: 'XXX',
            commands: []
        },
        maxVol: 100,
        leaveOnEnd: true,
        loopMessage: false,
        spotifyBridge: true,
        defaultvolume: 75,
        discordPlayer: {}
    }
};
Basic configuration

app/token, the token of the bot available on the Discord Developers section
app/playing, the activity of the bot
app/global, whether the commands will work on all servers or just one (if global they might take up to an hour to show up)
app/guild, the guild the slash command will be loaded to (this only applys if global is set to false)
DJ mode configuration

opt/DJ/enabled, whether the DJ mode should be activated or not
opt/DJ/roleName, the name of the DJ role to be used
opt/DJ/commands, the list of commands limited to members with the DJ role
Advanced configuration

opt/maxVol, the maximum volume that users can define
opt/leaveOnEnd, if the bot will leave on finishing the queue
opt/loopMessage, if the message that a music is played should be sent when it is looped
opt/spotifyBridge, takes spotify songs/playlists and searches it on youtube and plays it (highly recommended)
opt/defaultvolume, is the defaul volume the queue will start at
opt/discordPlayer, options used by discord-player
📑 Installation

To use the project correctly you will need some tools.

FFmpeg to process audio

Node JS (v16.6) for environment

Without forgetting of course the code editor ^^

Realized with ❤️ by AaronIG

Please do not withdraw the license and keep the credits on this project.

To have full access to the project and to be able to withdraw the credits a small donation is accepted.

📝 ToDo

 lyrics command

 Vote to skip command #187

 history commnad

 auto autocomplete (play, search, filters, ect)

 better button option's

 more config's for discord player
