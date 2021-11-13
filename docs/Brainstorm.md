# Mission Statement

I'm creating a social media platform governed and secured by blockchain technology to give content creators more control over the value of their content.

## Content Creation

Users will be able to post any kind of content, from long-form text, to punchlines, to memes, to videos, to music. Once the content is created, it is stored on the user's device. It is also sent to our servers to a queue service that waits a specified amount of time for any followers to log on and receive the new post. Posts at this stage are ephemeral, meaning they expire and will not take up hard drive space on servers. User's posts will remain on their phone until the user deletes them. Content posters may also choose how long their content should remain available to their followers.

## The Agora

The "Agora" is a feed of posts from the entire community that uses the app. To be featured on the Agora, a user must be invested in the platform through staking. Misbehavior results in those locked funds being evenly distributed to other stakeholders. There are 2 ways that users can interact with these posts besides consumption: They can promote it, or they can demote it. The high-level is that "promoting" makes the post visible to more users, while "demoting" does the opposite. The details of how it works are still to be determined.

If a non-creator user creates a post and it receives enough awards, the post will automatically be featured on the Agora.

When a post is featured in the Agora, the file will be stored on our server for a preset amount of time. "Time tokens" (explained below) can be used to extend that time.

## Monetization

Users have the option of staking some money in Agora in exchange for monetization rights. The exact tokenomics still need to be designed, but with those rights they will be able to create paid content which will be published on the "Agora", a single content feed shared by everyone around the world.

Another option for monetization will be a user-generated award system. Awards can be created at any time from the app and are 32x32 pixel image files that are also minted, fractional NFTs. Any user can create them and put them up for sale on any NFT marketplace, but users who have created their own NFTs may also spread them around by awarding other posts with them. These NFTs come with royalties built-in so that if the award is bought, sold, traded or awarded to another post, the creator of the award gets paid (see footnote 1).

## Post Expiration System

Everyone is given a bunch of free "time tokens" every day. Those tokens can be awarded to a post to keep it alive longer. But the longer a post is alive, the less time a token will be capable of adding to its timer.

The following information will be public on every profile:

Time Ratio - how much time they've given/how much time they've received (show actual numbers AND ratio)
Award Ratio - how many awards they've given/how many they've received (show actual numbers AND ratio)

## Governance

Individual users vote on which posts should be allowed on the platform by "promoting" and "demoting" posts.

Stakeholders can propose changes to the mechanics of the app. These changes will be posted to the Agora for a vote from the community. Voting systems will be determined later when I have a political science advisor to help.

## Caveats for Users

- All fees will be very visible with explanations of where that fee is to be used.
- When giving time tokens, as the time runs down, the token will have less effect on a post. This will also be made abundantly clear to the users.

## Future Plans and Ideas

- each post is an NFT so if user follows you, they have key to that NFT and can view whenever they want until it expires
- when post expires, keys are burned? (smart contract)
- since ethereum refunds when you destroy blocks, we can use that to pay to keep certain posts online forever
- Play around with the idea of basing the rate of decay of a post on the total percentage of the entire platform that wants more people to see it
	- e.g. if more than 50% of the platform clicked "promote", it earns a spot to live on the platform forever
	- maybe the percentage of promotions also goes into the calculation of how much of the ethereum refunds goes to keeping that post online
	- maybe we can also calculate the rate of decay based on the percentage of promotions vs demotions
	- maybe post only decays if under 50% threshold
	- maybe we have a special agora called the library of alexandria that holds only posts that are above the 50% threshold
	- maybe that's what Agora is?
	- either way, over time the collection would naturally gravitate towards posts that the most people want to be seen

# Known Issues

- capitalism lmao if someone manipulates a decent amount of people, they can fudge numbers
- also capitalism, you can even just manipulate a few people to share your awards for any number of non-related blessings.. "share these awards and tomorrow you'll find a billion dollars on the street!" or any variation thereof
- if the key to the NFT is burned when the timer runs out, we have to make sure we can still verify ownership in case video is used elsewhere

### Footnotes

1. Any user can get on at any time and create these NFTs, which may give rise to the concern that someone could flood the market with their NFT awards. However, this is okay. Likely, most people who receive them will never touch them again and they will be effectively "burned". I'm looking into what the effect would be if I allow users to just burn any awards they have in their wallet. (they would be sent to a wallet specifically created to never use, which means they're off the market.)