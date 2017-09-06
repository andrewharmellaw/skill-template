# Contributing
Hello! Thank you for wanting to contribute to this Skill. We love contributions. (Isn't Open Source great?)

Please note, all contributors must agree to abide by our [Code of Conduct](./CODE_OF_CONDUCT.md) - it keeps things civil and inclusive.  We want to make this a safe place for everyone to make awesome things.

The details of how to contribute to this quest follow.  

## Making Your Own Copy, Then Proposing We Accept Your Changes 
Because more than one person might want to contribute to this skill at the same time, and because we want to make sure all changes fit the aim, we have a slightly indirect process to follow when you want to make a change.  The way we ask that you do this is via a fork-and-a-pull request combination. It sounds a little complicated, but it's simple really.  (If you've used [github](https://github.com) before you can probably skip this section.)

First, click the "Fork" button (top right - you might want to CTRL-click to do this in a new window so you can keep this page open at the same time).  This will make your own personal copy of everything in this skill including this file, linked back to us, it's parent. (Note: to do this you'll need to be logged into your github account. If you don't have one, [sign up](https://github.com/join)! It's free, and easy to get going.)

Once you've forked, you'll probably want to make one or more edits (or even possibly move or delete things, or add some new files).  You can do all this in your web browser.  If you're editing a file which ends in ".md" then you need to know "Markdown".  It's [very easy to use](http://www.markdowntutorial.com/).

Once you've made your changes, you can let us know about them, and politely ask that we consider bringing them back in-house.  You do this by creating what is know as a "Pull Request" (as in "here are my proposed changes, would you like to pull them back into your original copy?") To do this, you don't "Save" and instead you "Commit". You can commit to the default ```master``` branch, it's fine.  Then you need to go to the "Pull Requests" tab and click the "New Pull Request" button. Github is clever, and it will see your recent change, and know that you forked from our original.  It will ask you for a comment (which we'll see so make it as helpful as you can) and then you can create the request via another, final green button.

We'll then see the pull request.  We might have a few comments. Please don't be offended if we ask you to make some further changes - we like to keep everything incredibly tidy over here.  It helps less-experienced people contriute too.  Please also note that we might not accept your changes at all.  We will give you the reason(s) for this.  (Remember, just because we don't want something, others might.  You can just use your copy as your new master copy, and start again from there.)

Once we're happy, we'll "merge" your pull request. That means we'll update our copy of the files with your proposed changes.  Awesome! You're now a contributor.  Thankyou very much!

N.b. you're not obliged to submit PRs.  Feel free to keep your changes to yourself of you like.  We only ask that you abide by the [terms of the licence](LICENSE.md).

## Editing Existing Skill Content
The simplest way to contribute is to edit the existing README.md files. This is the thing which when used in a Quest, ends up as a skill-page.  To make an edit, find the README.md file you want to update in your forked copy, and click the "edit" pencil in the top right.  Then follow the instructions above.

## An Important Note on Names, Namespaces, and Versions
If there is one aim for this project it is to make it easy for people to share their curated learning journeys in a way that is simple for others to use, contribute to, and adapt to their own needs.  Central to achiving this are the following trinity of concepts:

  * names
  * namespaces
  * versions

Why central?  Hold on, I'll get developer-technical for a moment.

Say your friend and you both have a Quest or Skill.  How can you tell if they are the same?  You could start by looking at their _names_.  Both are called "The Best Quest Ever".  That sounds like they are the same. But you remember that we've encouraged people to take their own copies of Quests and Skills and make them their own (called "Forking").  Has that happened?  To find out, you can look at the _namespace_ of the Quest or Skill.  That's made up of the two bits after the "github.com" in your browser address bar right now.


This is why we're using the two complex things git and NPM.  They help us manage all this version / namespace complexity, and let us get on with the real task of creating and maintaining all the Quests and Skills themselves.

Versions are very important to us.  Specifically we mean a number which uniquely identifies a specific version of your skill, and therefore differentiates it from 
