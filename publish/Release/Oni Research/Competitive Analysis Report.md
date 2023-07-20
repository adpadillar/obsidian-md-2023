## Background

The 2nd UX case study that Orely is doing is related to a meditation app. This competitive analysis report is a summarisation of the competitive analysis document that have been compiled for the research of this case study.

## Insights

### First impressions

The best first impression was from Headspace, as the app feels fresh and the onboarding feels great because you’re immediately given a breathing exercise to practice. After the breathing exercise, a screen comes up prompting you to subscribe. Users can subscribe in a more relaxed and open manner. This is a very subtle persuasion technique that borders on a dark pattern.

The most confusing first impression was from Insight Timer and Calm. Insight Timer was named like that because it wants to be a timer for meditation. Instead, the timer was hidden in the profile section and was nowhere near the front/home pages. There is a Stories feature that’s just confusing and anxiety-inducing. The Workspace feature is pretty oddly named.

Calm is really bad because the onboarding required 10+ screens to finish before even getting to the app itself. It’s also very hard-selling; these 10+ screens are quotes and membership/subscription offers.

#### Lessons

1. Create a fresh first impression by giving a breathing exercise to practice beforehand
2. Put the namesake feature of your app at the forefront; don’t hide it
3. Don’t sell too hard; avoid long onboarding, forced memberships and subscriptions, etc

### Features

#### Streaks

The streaks feature is an important, polemical one. Headspace seems to have had it before, but decided to add an option to turn it off after some debate. Their help page featured the aftermath of this situation; it provides a hastily-added link to a badly-designed article from Andy about the inclusion of the feature. It’s easy to see the controversy: while during meditation one is supposed to let go, it is also easy to almost accidentally create an attachment towards the practice of meditation if it’s not gently introduced. In any case, this feature should be either rethought, not provided by default, or there should be an option to turn it off.

| |Headspace|Insight Timer|Wysa|Medito|Calm|
|---|---|---|---|---|---|
|Streaks|✅ Can be turned off|❌ Can’t be turned off|N/A, doesn’t exist|❌ Can’t be turned off|🚧 Partial turning off|

#### Live group meditation

Some apps provide live group meditation settings, like Headspace and Insight Timers. These live group meditation settings are always available through the app, sometimes they have a coach and sometimes they don’t. The time zone varies. Insight Timer provides a number of the people who meditated with you when you meditate.

#### Content

Besides content on meditation, there are usually content that tries to provide calming benefits for the user, such as soundscapes and “focus music” and also yoga guidance content. The main selling point for a lot of apps seems to be the variability of content provided.

Sometimes there would also be expert guidances, or the “theory” behind the practices given in the app. These expert guidances feature people who are usually considered experts or even monks.

#### Content delivery

Wysa is unique in that it is a therapy or counseling app that also offers meditation content, but the content is delivered through a conversational AI. It is an interesting case study in conversational design and conversely a direct competitor to the app that we will be designing. The app’s content offerings seem to be the same as the other competitors; it’s just that the medium of delivery is different, it utilizes this conversational AI & UX. Through the feature of this chatbot, it is hoped that users will feel a sense of familiarity because they feel like they converse with someone else instead of moving through a set of interfaces and buttons.

Content is usually organized in playlists, which will be discussed in the user flow section of this report.

#### Daily check-in

The daily check-in feature is a staple of all the apps analyzed. This feature seems to be required of all the journaling/meditation apps analyzed.

#### Library

A content library seems to also be the default standard for every app tested. The IA varies from good to bad and that’s something to be discussed in another section of this report.

#### Lessons

1. Rethink streaks
2. Live group meditations are a good idea, when participated with consent
3. Ensure good IA instead of amount of content (make sure the Library in particular has good usability)
4. Think about conversational AI/UX
5. Ensure good accessibility for the daily check-in feature

### Accessibility

There are three types of accessibility features checked in this report:

1. Visual design
    1. Font color contrast
    2. Font sizes
2. Features & content delivery
    1. Features that promote anxiety
    2. Features that doesn’t help relieve anxiety
    3. Confusing content delivery options

#### Visual design

Nearly all of the applications analyzed have great color contrast, except for Calm, which features a virtually unreadable bottom navbar. The winning one here is Headspace which features pure black on pure white text. Font sizes are also usually pretty great and readable, except again for Calm.

| |Headspace|Insight Timer|Wysa|Medito|Calm|
|---|---|---|---|---|---|
|Great contrast|Excellent|Could be improved|Excellent|Excellent|Could be improved|
|Text sizes|Excellent|Excellent|Excellent|Excellent|A little bit too small|

#### Features and content delivery

Some features that promote anxiety or FOMO that is present in some of the apps analyzed include Stories (featured in Insight Timer). The streak, discussed in another part of this report, can also increase anxiety instead of diminishing it. The daily check-in feature of all of the apps also don’t feature deletion or modification of inserted data, which could promote anxiety. There is also no summarization for data entered through the check-in feature, which is a must for designing for anxiety.

Confusing content delivery options include the sheer number of content, promoting decision paralysis. Insight Timer is the worst at this, proudly announcing that they have hundreds of thousands of guided meditation content ready to be used by the user. It surely is a great point, but it’s not a selling point for people who need relief from anxiety as their primary reason for visiting or downloading the app.

| |Headspace|Insight Timer|Wysa|Medito|Calm|
|---|---|---|---|---|---|
|Anxiety-inducing features|Streak, which could be turned off|Stories; streak that can’t be turned off; daily check-in unsummarized and no deletion|Talking could be anxiety-inducing, if the conversation isn’t done well|None|Streak is only partially switch-offable|
|Daily check-in summarized?|❌ No|❌ No|✅ Yes, through conversation|N/A, no feature|❌ No|
|Daily check-in deletable?|❌ No|❌ No|✅ Yes, through the Journal feature|N/A, no feature|✅ Yes|
|Decision paralysis?|✅ No, thanks to good IA|❌ Yes|❌ Yes, plus no Search feature|❌ Yes, plus no Search feature|❌ Yes|

#### Lessons

1. Feature great contrast and text sizes
2. Check what features promote FOMO and anxiety-inducement, and stay away from those kinds of features even if they promote business interests
3. Make streak switch-offable
4. Don’t be too proud of the number of content in your app

## User flow

Two types of flows are analyzed in this report:

1. Onboarding
2. How to reach meditation content

### Onboarding

The best onboarding was with Wysa; it was extremely simple; they just introduced the Wysa mascot, asked for a nickname, a referral code, plus one reason you came into the app. This wasn’t skippable, but it feels like it doesn’t need skipping since it was so simple anyway. The app immediately gets you to the home page.

The second best was Headspace, which neatly balanced user needs and business needs by giving the user a prompt for a simple meditation session/breathing exercise. Then, when the user is relaxed, the app immediately switches into the subscription prompt. This prompt is given exactly at the time when the user is calm and very susceptible, prompting them to click buy immediately.

The worst was with Calm, which features a 10+ screen onboarding complete with unnecessary screens containing only photographs of accomplished people and their quotes (what they had through meditation). After that, the user is still prompted to subscribe; needless to say, it was such a huge cognitive load that is really hard to reconcile with the entire operations of the app. In one egregious case, the app asks if the user wants to go sleep right now, and then jumps immediately into the log in screen.

### Reaching meditation content

The easiest app to reach meditation content would be Medito, but that is because the meditation content is free and easy to reach nonetheless. The easiest experience for the paid or subscribed app would be Headspace. The typical flow for reaching meditation content would be:

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a20e6684-d4be-4225-a4a9-18c00f6b67e9/Untitled.png)

### Lessons

1. Make onboarding simple, only a few screens at best
2. Calm the users first, then ask for subscription, and even then make it skippable
3. Make it easy to reach content; remove the mood check-in prompt or at least make it skippable

## Navigation

All of the apps analyzed use a form of persistent navigation at least in the form of a bottom navbar. The simplest form of the bottom navbar would be Medito’s which feature only two options for the bottom navbar (going against [Material Design Guidelines’ recommendation](https://material.io/components/bottom-navigation#usage) for the bottom navbar). Headspace gives five options for the bottom navbar.

Most of the bottom navbar analyzed uses verbs instead of nouns to describe the content that they’re aiming at. The exception, again, would be Calm, which is not consistent in its usage of word types: two of them are nouns, one is a verb. Insight Timer is also weird in this regard: two of them are verbs, and two other are nouns.

Navigation [should be centered around objects and not tasks](https://uxmastery.com/object-focused-vs-task-focused/), therefore it would be more preferable to use nouns instead of verbs in the bottom navbar. Headspace features a tricky approach: the bottom navbar uses verbs, but when opened, those verbs act as nouns:

### Lessons

1. Use a hybrid approach: verbs in the bottom navbar makes the app seem more lively, but they should still be centered around an object-oriented model, tasks second
2. Don’t go against the Material Design Guidelines unless really necessary (use a minimum of 3 and maximum of 5 bottom navbar items)

## Branding

All of the analyzed apps’ branding are pretty consistent. All of their visual designs are usually smooth and never jagged (never any hard edges, including on illustrations). Also, illustrations and images are only sparingly used, except in Calm and Insight Timer which features images every which way.

The most interesting case would be Wysa, in which the user interface tries to fade back into the blackness and instead promotes the operation of the app through the chatbot interface itself. There aren’t any pictures or illustrations, just simple patterns in the buttons.

### Lessons

1. Use illustrations sparingly and don’t use any hard edges
2. Hide or fade the interface back if the user doesn’t require it
3. Use more playfulness:
    1. Use larger elements in order to appear more toylike and reduce anxiety
    2. Use softer colors (but watch out for contrast)

## Tone of voice

The tone of voice of these apps are usually consistent. They’re usually youthful, but not brash, and still tries to maintain professionalism. They also try not to be overly playful. Wysa’s is elegant and non-assuming. In particular, the conversations are held in a friendly manner and it doesn’t force you to interact with it in any way. Medito’s is interesting because it can feel reassuring at times.

### Lessons

1. See how Medito does reassurance through its tone of voice
2. Go with a calm and playful tone, don’t be overly professional

## Descriptiveness

All of the apps analyzed are pretty descriptive in how they describe content. None of them are lacking in this department. Insight Timer though can be too wordy, sometimes it’s even cut off into two halves in the UI.

### Lessons

1. Watch out for content being halved due to length


## Source

- https://orely.notion.site/Competitive-Analysis-Report-118767cb11464aea83626ef3b355b04c
