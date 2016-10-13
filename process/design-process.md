#Foundations Design Process

This is a proposal for the Foundations design process and is welcome to feedback so that it can be improved. This process is still in flux as we figure out the best effective and efficient method. 
This is inclusive of anyone in the company that has a request for a pattern.

##For Anyone

###To find/learn about an existing pattern:

- Check Ferrous and Bowie for awareness.
  - Note that the ferrous ‘styleguide’ is very much under development at the moment; it may not always be up to date and is not comprehensive. We welcome any feedback on how to make it and the bowie styleguide more helpful. There are also remnants of the old joan-rivers styleguide which document some styles that have not been cleaned up/updated.
- Check the list of issues on github or waffle and/or talk with the relevant party (regardless of whether the pattern is documented in one of the styleguides) to see if there is any work in flux or further ideas about this pattern. 
Relevant parties are Sean (GEM), Sabrina (P42), Kara &/or Rosina (Zephyr).

###To request a new pattern, or request an evolution to a pattern:

- Review the list of pattern issues on github or waffle.
  - If you do not have a github account you can create one and request access to the gust/ferrous repository (any dev can grant you access), or you can use the shared zephyr-dev account, the password for which is available via Meldium.
- Find or create an issue for the pattern you’d like to propose. 
- Add your comments to the issue. Your comments should indicate any specific use cases. However, it is also helpful to include any known visual bugs/usability issues with the existing pattern, suggested variants, relevant screenshots of Gust UX or UI (you can paste images), and any inspirational ideas or links.
  - The Foundations team will automatically be notified of new issues via slackbot.
- If there is specific urgency to address a pattern immediately, email Jun and make that clear in your comments on the issue.

###To report a bug:

- Find or create an issue on github or waffle for the bug you’ve found. Make sure to add comments with clear steps to reproduce the bug, and include the browser/version you were using when the bug was found.
- Tag the issue with the #bug tag.  


##For Foundations Council Members

###To begin discussions around a new pattern/design:

- Create an issue on github or waffle in order to share your ideas about the new pattern or design you’re introducing to a product. Tag the issue as a #discussion, meaning it’s still evolving in the individual products and is not yet ready to graduate to ferrous.
- Solicit ideas and feedback, as well as related designs/patterns in other products via posts in #foundations_team, individual conversations, and the weekly E2E.

###To introduce a pattern or design to ferrous (unify across products): 

- Once it is clear that it is useful to standardize a pattern across products, find the pattern issue on github or waffle in order to review the collected comments. Move the issue to the ‘design’ stage on waffle, or add the #design tag on github, and notify the team via #foundations_team.
- Gather all the representative use cases. This can be through slack and/or conversations - depending on the size/complexity of the pattern. If the pattern is substantial/complex, consider using a kick-off brainstorm during an E2E.
- Generate ideas for the pattern, considering usability and best practices. Represent the default state and common states, including descriptions for how the pattern should be used. Include common variants and animations. You needn’t be overly exhaustive of edge cases, rather just make a list of lower priority edge case requests or variants for future reference.
- Share your draft in the github issue comments.
  - Comments will be automatically shared with the #foundations_team channel via slackbot.
- Present the pattern draft at the next E2E in order to receive feedback and determine if this pattern should be added to Ferrous for cross-product consumption. 
- Iterate, based on feedback. Share in #foundations_team slack channel or via . If it seems more conversation is needed, then meet in person (either adhoc or E2E).
- Upon consensus, add final design to github issue. Include screenshot, PDF, and if there is a Sketch file, add it to the styleguide folder in dropbox and include the link. Move the issue to the ‘ready’ stage on waffle, or replace the #design tag with the #ready tag on github.
- If relevant, add pattern to Craft library for Sketch.

