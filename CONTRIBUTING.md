**PULL/MERGE REQUEST DETAILS**
HERE’S HOW WE VALIDATE CONTRIBUTOR PULL/MERGE REQUESTS (“PR/MRS”) FOR HACKTOBERFEST

[ OUT-OF-BOUNDS ]
**YOUR PR/MRS MUST BE WITHIN THE BOUNDS OF HACKTOBERFEST.**
Your PR/MRs must be created between October 1 and October 31 (in any time zone, UTC-12 thru UTC+14).

Your PR/MRs must be made to a public, unarchived repository.

[ EXCLUDED ]
**REPOS THAT GO AGAINST HACKTOBERFEST’S VALUES WILL BE EXCLUDED FROM QUALIFICATION AND PR/MRS MADE TO THOSE REPOS WON’T COUNT.**
Found a repository that goes against the values of Hacktoberfest? LET US KNOW AND WE’LL TAKE A LOOK.

[ SPAM ]
**YOUR PR/MRS MUST NOT BE SPAMMY.**
PR/MRs that are labeled with a label containing the word “spam” by maintainers will not be counted.

We use the Node.js 16 RegEx engine with /\bspam\b/i to look for spam labels.

PR/MRs that also have the “hacktoberfest-accepted” label cannot be marked as spammy via a label.

PR/MRs that have been merged and do not have a label containing the word “invalid” cannot be marked as spammy via a label.

PR/MRs that our system detects as spammy will also not be counted.

Any user with two or more spammy PR/MRs will be disqualified.

[ PARTICIPATING ]
**YOUR PR/MRS MUST BE IN A REPO TAGGED WITH THE “HACKTOBERFEST” TOPIC, OR HAVE THE “HACKTOBERFEST-ACCEPTED” LABEL.**
Hacktoberfest is now opt-in for maintainers, so only contribute to projects that indicate they’re looking for Hacktoberfest PR/MRs.

Once your PR/MR has passed this check, we won’t check this again (unless your PR/MR fails a check before this, such as it being marked as spammy).

[ INVALID ]
**YOUR PR/MRS MUST NOT BE LABELED AS “INVALID”.**
PR/MRs that have a label containing the word “invalid” won’t be counted, unless they also have the “hacktoberfest-accepted” label.

Specifically, we use the Node.js 16 RegEx engine with /\binvalid\b/i to look for invalid labels.

[ ACCEPTED ]
**YOUR PR/MRS MUST BE MERGED, HAVE THE “HACKTOBERFEST-ACCEPTED” LABEL, OR HAVE AN OVERALL APPROVING REVIEW.**
Your PR/MR must not be a draft to be considered accepted.

If your PR/MR is being accepted for Hacktoberfest via an overall approving review it must also not be closed.

**ONCE YOUR PR/MRS PASS ALL THE CHECKS ABOVE, IT WILL BE ACCEPTED FOR HACKTOBERFEST AFTER THE 7-DAY REVIEW PERIOD.**
We continually evaluate all of the checks except the [PARTICIPATING] check. If it fails any of these checks during this time, the 7-day timer will reset.

After the 7-day review period completes, your PR/MR will be automatically accepted for Hacktoberfest assuming it still passes all the checks. Once accepted for Hacktoberfest, we stop checking. :party:



**MEASURES TO REDUCE SPAM**
**SPAMMY PULL/MERGE REQUESTS WILL BE LABELED AS “SPAM.”**
Maintainers: label spammy requests “spam” and close them. PR/MRs labeled “spam” won’t count toward Hacktoberfest. Contributors with 2+ spammy PR/MRs are disqualified.

**PULL/MERGE REQUESTS MUST BE APPROVED BY A MAINTAINER.**
Maintainers accept PR/MRs by merging them, labeling them “hacktoberfest-accepted,” or giving them an overall approving review. Accepted PR/MRs enter a 7-day review window, during which approval can be revoked by the maintainer or by our team.

**BAD REPOSITORIES WILL BE EXCLUDED.**
PR/MRs should be useful to maintainers. Repos that encourage simplistic PR/MRs (like adding a name or profile to a list or arbitrarily curating content) will be excluded from Hacktoberfest. Remember: quantity is fun, quality is key.

Found a repository that you think doesn’t follow our values? 
REPORT IT TO US AND WE’LL TAKE A LOOK.

**AVOID SUBMITTING LOW-QUALITY PULL/MERGE REQUESTS.**
Hacktoberfest is about contributing meaningfully to open-source projects. Here are some examples of low-quality pull/merge requests that won’t count towards Hacktoberfest.

- Automated pull/merge requests: scripted opening pull requests to remove whitespace, fix typos or optimize images.
- Disruptive pull/merge requests: taking someone else’s branch/commits and making a pull request.
- Anything that a project maintainer flags as spam.
- Anything that looks like an attempt to duplicate your pull request count for October.

Multiple pull/merge requests for the same issue that are unnecessary -for example five PR/MRs to remove a stray whitespace is not.
