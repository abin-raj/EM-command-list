# EM-command-list

The following commands (including admin and bot owner) are available in EM :

## Core
<pre>
* info          Info on Easy Manager bot  
* load          Command which Loads a Module  
* reload        Command which Reloads a Module  
* restart       Restart the bot  
* shutdown      Shutdown the bot  
* traceback     To send traceback msg to owner  
* unload        Command which Unloads a Module  
* uptime        Shows how long bot has been awake  
</pre>
## Help
<pre>
* help          Shows help about the bot, a command, or a category  
</pre>
## Tourney
<pre>
* contact           Links to contact us incase you are interested to host tourneys using Easy Manager Bot  
* edit              Edit discord registration for tourney  
* feedback          Provide feedback for Easy Manager Bot  
* formregister      To register your team in the ongoing tournament  
* group             Common info for finding group for registered players  
* idp               Common Info for reg users  
* insta             Insta verification for tourney  
* mygroup           Find group number for a registered IGL  
* pointtable        Point Table Commands  
* premium           Premium Commands  
* print             For IGLs to get their registartion details in DM  
* quote             Ask quote for hosting tourneys using Easy Manager Bot  
* regforma          Shows current registration format set for tourney  
* register          Discord registration for tourney  
* regselec          Set reg options  
* round             Commands to handle multiple rounds  
* setroundstatus    Set the status for the ongoing round  
* settourneyinprogress  Change tournament status to Inprogress. THIS IS IRREVERSIBLE.  
* ss                SS commands  
* tag               To Update the tag members for a team. All tagged members with fer IDP, messages, etc.  
* tourney           Commands to register for Tournaments  
* tourneyset        Sets guild variables for the server  
* ugroup            Find group number for any registered IGL  
* uprint            To send the user details in DM  
</pre>
## GuildManager
<pre>
* guildmanager     Commands for managing guilds  
* leave            Leave the server  
</pre>
## Sample
<pre>
* globalsync       sync  
* ping             Check latency of the bot  
* sync             sync  
</pre>
## Utils
<pre>
* embed           Send an embed in the current channel.  
* say             Make the bot say something  
</pre>

## Subcommands available

### Round subcommands
<pre>
* add           Add round details  
* complete      To check round completion and update the user database for the next round  
* create        To create groups for the ongoing round  
* dmslot        To DM the slot list for a particular group number.  
* export        Export Group wise slot list for the on-goining round  
* info          Show info on the current round for the tournament  
* init          Initialise the round for the tournament  
* msg           To DM the team lead and tagged members  
* print         To show the group list for a particular group number.  
* promote       Round Promotion  
* publish       To publish the group list for a particular group number.  
* publishall    To publish the all the group lists.  
* status        Set the round state  
* swap          To swap teams in round list  
</pre>

### Tourney subcommands
<pre>
* complete      To clear server and user database once a tournament is completed  
* create        Create tourney  
* deleteallusertourney    Delete all members registartion data for a tourney  
* deletetag     To delete stored tags of a member incase of fake tags  
* deleteusertourney       Delete a members registartion data for a tourney  
* info          Shows the tournament information  
* init          To initialise a tournament in the discord server  
* ownerdeleteguildtourney  Delete a tourney  
* status        Shows the tournament information  
</pre>
### Tourneyset subcommands
<pre>
* count         Sets confirmed team count for bot  
* discregcount  Sets discord man count for tourney  
* regchannel    Sets channel id for bot to accept registartaion info  
* role          Sets the default role id to give to user upon registartion  
* round         Sets the current round number  
* teamchannel   Sets channel id for bot to log confirmed teams info  
</pre>
### SS subcommands
<pre>
* clear    Clear SS data of a member  
* view     View SS data of a member  
</pre>
### Point table subcommands
<pre>
* addgfx        Add PT GFX images into database under the specified name  
* addlogo       Upload logos for printing in pt file  
* alt           To test point table creation using sample data  
* create        To create pt image  
* image         List PT GFX images available for this server  
* load          Load pt for print or adding next data  
* make          To create pt image  
* removeimage   Remove PT GFX images name for a server  
* sample        To test point table creation using sample data  
* setimage      Set PT GFX images name for a server  
* text          Create a txt file for the point table  
</pre>
### Premium subcommands
<pre>
* addtourney    Add Premium for a server  
* check         Check if the server is premium or not  
* listserver    List Premium tourneys in a server  
* removetourney Remove Premium for a server  
</pre>
