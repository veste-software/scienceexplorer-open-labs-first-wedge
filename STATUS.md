# ScienceExplorer Open Labs (first wedge)

**Stage:** killed · **Platform:** web · **Score:** 5/5 · **Spend:** $0.64

Topic search listing researchers in Germany with recent papers from existing data, each marked 'status unknown' until the researcher claims the profile and sets 'taking students'. Applicants send a structured intent form with a limit of 3 a week, and supervisors get a weekly digest. There is no free chat and no AI ranking of applicants. Segment: People seeking a PhD place in Germany, starting with computer science and biology. This is the first wedge of a larger bet, "ScienceExplorer Open Labs": A rate-limited way for PhD and postdoc applicants to find active supervisors by topic and reach those who have said they are taking people, built on ScienceExplorer's ranked researcher map. Build only the wedge, and keep the data model and the pages ready for the loop that makes it grow: Each supervisor who marks a lab open makes search more useful, which brings more serious applicants and a better inbox than e-mail, which brings more supervisors and paid positions.

**Why now:** standing need. Window: One University of Chicago professor reports about 20 mostly AI-written e-mails a day and says these are unlikely to get a reply (GradPilot, 31 October 2026). OpenAlex also made the researcher graph cheap, and the owner has already built on it.

## Needs you

Nothing right now.

## Recommendation

None yet. The Growth role gives one after launch.

## Metrics

No real numbers yet. Fill in `metrics.json` (Search Console, analytics, Stripe); agents never invent them.

## Target queries

- how to find a phd supervisor
- phd positions in germany
- how to find a phd supervisor in germany
- how to find postdoc positions in europe
- cold email professor for phd
- email to professor for phd supervision
- finding a phd supervisor in germany
- phd positions in germany for international students
- find phd advisor
- how to find postdoc positions

## Alternatives found

- EURAXESS (partial): Free and lists thousands of institution-posted offers, but the page shows no signal of whether a given supervisor is open.
- FindAPhD (partial): Charges per project (from GBP 110 per search results; the page refused my fetch), so a supervisor who is open but has no advertised project is not visible.
- SupervisorMatch (partial): Recommends professors from an applicant's CV, and its listing does not say professors opt in, so it can add to the inbox problem.
- PhD-Match (University of Melbourne) (partial): Covers one university only; seen in search results, not opened.

## History

- 2026-11-12 12:57 · scouted · found by manual
- 2026-11-12 12:57 · scouted · ranked first in the daily pool (aggregate 2.72 of 5 by 3 independent rankers, including a Big-bet bonus of 0.3); the studio builds the day's best candidate whatever its score, and the prototype is how it is judged
- 2026-11-12 12:59 · killed · rejected by the product lead: The only payer is a lab buying position posts, which labs already place free on EURAXESS, DAAD and university portals and pay for only on boards with an audience; open supervisors without a post have nothing to buy, and the search channel reaches applicants (who never pay), not labs.
