<h2>EE Slack Usage Guide</h2>
This guide outlines a few principles and guidelines intended to get the most shared benefit out of a communication tool that is also an evolving body of information.

The following principles were used when writing this slack usage guide:

*   Give everyone the bigger picture by making information and conversations public
    *   Widen people’s context
    *   Make channels public by default, it provides the greatest opportunity for others to learn from any discussion, and documents tribal knowledge.

*   Increase the signal to noise ratio of the information and conversations
    *   Narrow people’s focus
    *   Ensure people are reading information that is relevant and useful to them
    *   Efficiently use people’s time

*   Respect the amount of information anyone can tolerate reading
    *   Do not overwhelm people with a high volume of messages that they are expected to read
    *   Avoid communication burnout

*   Optimise for the whole of the global organisation rather than local optimisations for parts of the organisation

    *   Avoid creating a disjointed experience for people by focusing on overall simplicity rather than local simplicity


<h2 id="is-your-message-worth-bothering-someone-or-everyone-in-a-channel">Is your message worth bothering someone or everyone in a channel?</h2>

<h3 id="use-of-@channel-and-@here">Use of `@channel` and `@here`</h3>

By minimising `@here/@channel` use, people are less likely to mute or leave the channel due to being spammed with notifications. This then allows the notifications to be used to properly  and interrupt people as the sender intended. **Before using either, consider the number of members of the channel and if the majority of members of a channel would agree that their attention needed to be demanded to read the message**. 

`@channel` alerts all channel members regardless if they’re online or not, it should be used for incredibly high priority messages that need attention right now. It is intended to distract everyone in that channel from what they are doing right now. 

`@here` alerts people who are currently online in slack, and in that channel, it should be used for high priority messages that need attention right now. It is intended to demand attention from those online as soon as possible.

If you just want to send a message but people don't need to see it right now, just put it into the channel normally, as everyone should consume it when they next have a moment. 

Some examples of good use are:

    Channel Type: Office
    Channel Member Count: 50
    Message: “@here two tickets available for a concert tonight, if anyone wants them”
    
    Channel Type: Announcements
    Channel Member Count: 900    
    Message: “@channel everyone must complete timesheets by the end of the week”


Some examples of bad use:

    Channel Type: Community of practice    
    Channel Member Count: 200    
    Message: “@here is anyone available to do an interview in the next two weeks”
    
    Channel Type: Announcements    
    Channel Member Count: 900    
    Message: “@channel is google down for you”

<h3 id="using-threads">Using threads</h3>

One of the constant challenges we face with popular Slack channels (e.g. #announcements and #smallvictories) is keeping information **_relevant_** (so people don't leave / mute the channel) while maintaining a **_steady flow of information_** (so people are informed and included) and giving people an **_opportunity to respond/discuss_** (so it's not just a one-way street).

When in a large channel like these, prefer responding in a thread rather than replying directly in the channel. This keeps noise to a minimum, while allowing discussion to continue amongst those that are interested. We don’t want to stop congratulating our colleagues when they’ve done a good job (e.g. in response to a message in #smallvictories) - but that message is actually intended just for the few people mentioned in the message, not everyone in the channel. Replying in a thread ensures those people see it, but no one else is distracted by it.

In a more narrowly-focused channel (e.g. #aws), it’s often worth replying directly in the channel as most people are in that channel to observe the general conversation, even if they’re not a part of it. There are still cases where a thread is useful, but they tend to be used more sparingly.

**Tip:** A general rule of thumb when replying to a message in Slack is this:

_If your reply is only intended to be read by the original poster (or the people mentioned in the original post), you should use a thread. If your reply is valuable to everyone in the channel, reply in the channel._

_If you want to create a place for an expected conversation to continue and don’t want to create a separate, temporary channel (like #tmp-conversation) then consider starting a thread from your own post._

**Tip: **A custom :thread: emoji has been added to help guide people towards posting in a thread rather than in the channel. Sometimes you may feel it is better to react with an emoji than telling someone to use a thread. It’s quick and it avoids yet another message (you could use a thread though :slightly_smiling_face:).

**Tip**: One way to induce people to reply using threads is to post the highlight of your message first in the main channel, then create a thread on your own message and add in the details. When people see a thread, they are more likely to use it.

<h3 id="mentioning-by-name">Mentioning by Name</h3>

If you mention someone by their slack handle (e.g. percy or @percy), it highlights them in slack, notifies them (and prompts you to invite them to the channel if they’re not already present, or notify them of the channel). \


Naming is generally acceptable convention to avoid misspellings and add additional potentially interested people to the conversation.

_i.e. I know that Quincy really likes Michael Jackson’s music and there’s a conversation about this music between Vince and Nelly in the #random channel. You write “I love what you just shared and I think @Quincy would find this interesting too”. _

However, it is impolite to highlight someone if you’re only intending to speed up responses to your non-urgent questions. 

_i.e. if they’ve been responding to the conversation on slack, and then they take longer than you anticipated for their response, you use “hey @quincy! What did you think about what I said?”. → this is impolite. _

<h3 id="mentioning-by-name-when-they-are-not-in-the-channel">Mentioning by name when they are not in the channel</h3>

When you post a message that @ mentions someone who is not in the channel, you can choose to either "invite" them to the channel (which force joins them), or to send them a link (if the channel is public). Unless their input is required for the matter at hand you should you use the second option, and try to include enough content in the line so that the message they receive allows them to make an informed decision about whether they should join the channel or not.

<h3 id="use-of-private-messages">Use of Private Messages</h3>


Before using a private message, consider why it couldn't be public to the network as that has the benefits of allowing others to pick up (help, improve) on what is happening or learn from the conversation.

<h3 id="conversations-transitioning-off-slack">Conversations Transitioning off Slack</h3>


Sometimes a conversation will start on slack, but move off-channel to a face-to-face conversation. It is polite to either post "This conversation has gone face-to-face" so that others aren't confused by a slack conversation that just ends mid way through, or post a summary of the conversation back into slack for posterity.

<h3 id="share-a-message-instead-of-copying-its-content">Share a message instead of copying its content</h3>


It’s better to share links to a message than to duplicate the message itself. If you are trying to reach a wide audience (that spans multiple channels) then favour posting once in the busiest or most relevant channel and then sharing a link ([https://get.slack.help/hc/en-us/articles/203274767-Share-messages-in-Slack](https://get.slack.help/hc/en-us/articles/203274767-Share-messages-in-Slack)) to the post.

The alternative is to duplicate the content. I think the benefit of sharing is that it helps to focus all discussion in the place that the link was originally posted (people will need to click through the shared link if the first message is more than a few lines in order to see the whole message). For instance if you post something in #serverless but you think that it would be valuable to people in #product then post a _link_ in #product to the message in the #serverless channel. There are a number of benefits to doing this rather than doubling up on message posting:

1. Encourage as much discussion as possible in one place (instead of having some serverless zealots talking in one place and product people talking in another, you may see the two groups interact and generate a more lively, richer and more valuable discussion)

2. More subtly, highlight to groups that might not be aware that there is a channel called #serverless where people who might not know about it could learn more

3. Any changes to the original message will be reflected in the shared links.

<h2 id="channels">Channels</h2>


<h4 id="when-to-create-a-new-channel">When to create a new channel</h4>


Whenever you feel like sharing your passion/interest/hobby/ideas/whines and there isn't another channel for the same purpose. So do a search first, and if there’s nothing obvious, create one and follow the naming convention so others can find the channel easily.

<h4 id="when-to-archive-a-channel">When to archive a channel</h4>


You should archive a channel you created if there’s been no activity in the last 3 months.This helps keep the list of channels smaller, as well as helping users find conversations more easily.

Archived channels are searchable, and everyone has the ability to unarchive channels which add's the pre-archived channel members to continue the conversation.

There is a slackbot called [“Slack Gardener”](https://github.com/EqualExperts/slack-gardener) that will automatically prompt a channel if it becomes inactive for 3 months, and will archive it if no-one answers the prompt within a week.

<h4 id="naming-channels">Naming Channels</h4>

<h5 id="channels-generally-fall-into-some-broad-categories">Channels generally fall into some broad categories</h5>

We’ve come up with a few ordinal terms to represent broad categories we think everything can fall into, and some prefixes to denote each category (with the exception of one of those categories).  

These prefixes aren’t hard rules and must be followed with every channel name, but they do help discoverability of channels and help reinforce their intended use. 
 
This naming convention follows [Slack’s guidelines](https://get.slack.help/hc/en-us/articles/217626408-Create-guidelines-for-channel-names). 


<table>
  <tr>
   <td><strong>What is the channel about</strong>
   </td>
   <td><strong>Prefix in channel name</strong>
   </td>
   <td><strong>Examples</strong>
   </td>
  </tr>
  <tr>
   <td>An interest, a hobby, a topic, a community of practice 
Intended to be long-lived and can either be software or consultancy related; or of personal interest to some of us
   </td>
   <td>NONE
   </td>
   <td>#aws
<p>
#books
<p>
#kotlin 
<p>
#afol
<p> 
#conf-ee-rences
<p> 
#securit-ee
<p>  
#mobil-ee
<p> 
#operabilit-ee
   </td>
  </tr>
  <tr>
   <td>Office 

<p>
Typically named after the city, unless multiple offices in the city.
<p>
Usually created when BU’s are large enough that there will be ‘office chatter’ that all of a BU members don’t need to know e.g. people arriving at reception
   </td>
   <td>#office-
   </td>
   <td>#office-london
<p>
#office-manchester
<p>
#office-leeds
<p>
#office-lisbon
<p>
#office-pune
<p>
#office-nyc 
<p>
#office-sydney
<p>
#office-melbourne
   </td>
  </tr>
  <tr>
   <td>Cross-functional groups/Task force
<p>
Groups set up to achieve a specific task such as office move.  Generally not an interest-based channel (if you are organising a football game, keep it in the football channel).
   </td>
   <td>#task-
   </td>
   <td>#task-ldn-office-move
   </td>
  </tr>
  <tr>
   <td>Help based channels 
Where people can ask questions, look for advice; look for someone in person to connect to
   </td>
   <td>#ask-
   </td>
   <td>#ask-gsuite 
<p>
#ask-timesheets
<p>
#ask-1password
<p>
#ask-peopleteam 
<p>
#ask-finance
<p>
#ask-bul
<p> 
#ask-exec
   </td>
  </tr>
  <tr>
   <td>Advice process discussion channels 
Where people can discuss active advice processes, share updates on a particular topic, and gather opinions from across the business.
   </td>
   <td>#ap-
   </td>
   <td>#ap-cleanupslack 
<p>
#ap-dig-foundations
   </td>
  </tr>
  <tr>
   <td>Domain 
Discussion around domains of knowledge
   </td>
   <td>#domain
   </td>
   <td>#domain-fs-banking 
<p>
#domain-healthcare
   </td>
  </tr>
</table>


<h5 id="don’t-proliferate-channels-keep-channels-broad-and-go-more-specific-in-the-name-if-needed">Don’t proliferate channels; keep channels broad, and go more specific in the name if needed.</h5>


Remember, when our workspace becomes overloaded with heaps of channels,  the more difficult it is for effective sharing to happen. 

Keep channel topics broad, and if more specific interests develop within the channel, then create those channels. eg. start with #ee-marketing, and then if there’s a need for marketing training courses, then spin out the channel #ee-marketing-training

<h4 id="other-hygiene-factors">Other hygiene factors:</h4>


If your channel name is made up of one or more words, separate out the words with hyphens-, not underscores_

Make sure to set:



*   Channel purpose to short description of channel’s intended use
*   Channel topic to communicate more important current information 

These are particularly helpful when channel names aren’t able to convey the purpose effectively (likely due to acronyms and character limits in names).

Keep your channel name within company policy.

Invite people to channels by using `/invite @user` over sending a message to the channel `@user` and then inviting via the prompt that slack sends you. This means that the entire channel is **not** alerted to when a new user joins a channel.

<h2 id="profiles">Profiles</h2>


Have at least the following information supplied in your profile so that others can more easily find you outside of Slack:



*   Full Name - so people can find you
*   Display Name - how you’d like people to refer to you in slack
*   Profile Picture -  so people can identify you (it needs to be an accurate representation of you)
*   What you do
*   EE client - if applicable
*   Home Base - so people know where you’re usually located

If you want to supply personal data that is key to your online identity such as full date of birth; be aware that there are risks to this. 

There are other fields that we encourage people to fill out such as phone number, skype, twitter, github, but these are not required.

<h2 id="search">Search</h2>


Before asking a question in a channel, check to see if the question has already been answered. Type a word or phrase in the search box to start looking. If you can’t find what you’re looking for, try search modifiers to narrow your search even further.


<table>
  <tr>
   <td>Search modifiers
   </td>
   <td>Description
   </td>
  </tr>
  <tr>
   <td>in:[channel]
   </td>
   <td>Searches just the messages and files in a specific channel.
   </td>
  </tr>
  <tr>
   <td>to:me
   </td>
   <td>Searches all the direct messages that have been sent to you.
   </td>
  </tr>
  <tr>
   <td>from:@[displayname]/
<p>
from:me
   </td>
   <td>Searches messages from a specific person/ yourself
   </td>
  </tr>
  <tr>
   <td>before:[date]
   </td>
   <td>Searches messages or files before a specific date
   </td>
  </tr>
  <tr>
   <td>after:[date]
   </td>
   <td>Searches message or files after a specific date
   </td>
  </tr>
</table>


Examples:


<table>
  <tr>
   <td>Search phrase
   </td>
   <td>Description
   </td>
  </tr>
  <tr>
   <td>in:#office-london to:me after:May
   </td>
   <td>Messages sent to you, in the #office-london channel after May
   </td>
  </tr>
  <tr>
   <td>in:#office-london from:@Thomas before:December
   </td>
   <td>Messages from Thomas, in #office-london before December
   </td>
  </tr>
</table>


<h2 id="gif’s-and-emoji’s">Gif’s and Emoji’s</h2>

There are no rules about using emojis & displaying images & gifs, however given images can sometimes be inappropriate or distracting, especially on a client site, there are ways to minimise them. 

*   You can quickly hide all images in a channel using /collapse  and then /expand to display them again
*   In Preferences (click your avatar) > Messages and Media > Inline Media and Links, untick the boxes to hide all images until you're ready to see them. You will have to select the arrow to open each image separately.
