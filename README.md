# product-backlog
Purpose: All new features, bugs, customer requests will be curated in this repo. We will use the issues created here to flesh out features, designs, and requirements. 

*What happens here, doesn't stay here*
- The issues reported in this repo will be worked on in other Hypothesis repos. 
- Issues created in #product-backlog will serve as parent cards that track all information about that request. 
- All Google docs, pr info, or issues created in other repos must be linked back to issues created in this repo. 
- We're implementing this system so that we can have complete transparency around our product developement process.

## Reporting Bugs

**P1: Emergency**

*Description:* It’s likely that the entire application is effectively down for a substantial % of users.  The defect affects key functions and there is no workaround.  Our core metrics may be substantially affected until this is resolved. Customers are probably angry or will be shortly.

*Response:* This bug should interrupt the work of however many folks are needed to troubleshoot and fix.  If it is after hours pagers are called. (Pizza is getting ordered!). Notify Nick, Lena, and Arti in the #support channel in Slack, and send them the link to the github issue and ticket. If a user is reporting this bug, asking us about it, tell them that we are aware, and are working to fix it. Once fixed, an immediate deployment is made, and users are notified. 

*Example:* The H client is down and users are unable to annotate.

**P2: Urgent**

*Description:* The defect affects core functions and a substantial % of users are affected— there is a workaround but it is not obvious or not trivial. Major customers or high profile users may be escalating.  Reflects poorly on Hypothesis.

*Response:* This bug is an urgent fix. It goes to the top of Up Next & is the next card picked up— but if its during work hours someone should probably be looking at it right away. Any fix is reviewed immediately and a specific deployment is made to address it. Create an issue in github, alert Arti, Nick and Lena (in support), so that we can prioritize the fix. 

*Example:* Direct links are failing.

**P3: Next sprint**

*Description:* The defect affects minor (though perhaps still important) functions, or affects more important functions but has a very easy / obvious workaround. It’s noticeable and anyone might encounter it in the normal course of events. This might also be used for bugs that block us releasing functionality currently in development.

*Response:* This bug should get addressed during the next sprint. Deploy at the next natural opportunity, ok to wait for other work to complete first. Create an issue in github, alert Arti and Lena (in support), so that we can prioritize the fix for the next sprint. 

*Example:* There is an error in the annotation process, that allows a user to annotate, but the annotations are showing up as orphans, and are not being anchored on the page. This results in a painful UX, but the user can still see the annotations they are making. PDF fingerprints in Safari are different. (https://github.com/hypothesis/h/issues/3471)

**P4: Three months**

*Description:* This defect is annoying. We ought to address rather than let sit.

*Response:* This bug should get addressed preferably before the next major chunk of work we tackle.

*Example:* A user has to highlight text instead of double clicking the text in order to annotate. There is a workaround but the user still has to perform an extra step to achieve the primary action. 

**P5: When convenient**

*Description:* It’s a bug. It may be present only on a single site, or in very specific situations.  Most users will never see it or never give it much thought if they do.  If we never fixed it it wouldn’t be the end of the world, but … we should anyway.

*Response:* It shouldn’t get in the way of other important work. Perhaps we group it with other work we’re doing in the same part of the system.

*Example:* Rename user fails silently if there’s a space at the end (https://github.com/hypothesis/h/issues/3627)

**Bug reports**
----
_Each report will include (will be in the issue template):_
- Priority Measurement (Assign a label)
- Severity Measurement (Assign a label)
- Problem User is reporting
- Steps to reproduce the issue
- Expected Behavior
- System Info (H client version, browser version)

## New Feature Request
Yay! New feature ideas are awesome! But before we start seriously thinking about them as a team, make sure you're providing as much detail in your card as possible. 

For Example: "I think a blue button would be cool" IS NOT A FEATURE REQUEST. 

Use the New Feature request form in the Issue Template to create a new feature request. Fill out all the fields, and you're golden. Thanks! 

